[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292409&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   Open your web browser and go to the Visual Studio Code website(https://code.visualstudio.com/).
   ![alt text](<visual studio code install.png>)
   Click on the Download for Windows button.
   ![alt text](<visual studio download.png>)
   Once the download is complete, open the downloaded file (VSCodeSetup.exe).
   ![alt text](<vscode setup.png>)  
   Follow the prompts in the setup wizard and accept the license agreement and choose the installation location.
   ![alt text](<visul studio download 2.png>)
   Choose additional tasks such as creating a desktop icon, adding VS Code to the PATH and enabling options for opening files with VS Code.
   Click Install. After installation, click Finish to launch VS Code.
   ![alt text](<visual studion finish.png>)


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   Initial Configurations and Settings
   Choose a Theme by going to File > Preferences > Color Theme and select a theme that suits you.
   ![alt text](<visual studio theme.png>)
   Search for Font Size and set your desired size.
   ![alt text](<visual studio start.png>)
   Install requireed extensions which help in maintaining a good development environment. These settings and extensons will help in mainatainig a good coding and development environment.
   Click on the Extensions icon in the Activity Bar Install extensions such as:
   Python (Python Development)
   Live Server (Local Development Server for HTML/JS/CSS)
   ![alt text](<vscode extensions.png>)


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Activity Bar- Located on the far-left side, this lets you switch between views like Explorer, Search, Source Control, Run and Debug, and Extensions.
   Side Bar- Just to the right of the activity bar it shows the content related to the selected view from the Activity Bar, such as the file explorer.
   Editor Group-This is the central area where you write and edit your files. You can open multiple files and split the editor to view files side by side.
   Status Bar- Located at the bottom, it shows information about the current file, like line number, cursor position, and errors/warnings.
   ![alt text](<user interface.PNG>)

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
   The Command Palette is where all Commands are found. It allows users to quickly execute commands by typing their names rather than navigating through menus.
   Accessing the Command Palette- Press Ctrl+Shift+P to open the Command Palette.
   Examples of common tasks include ;
   Open a file- Type > Open File.![alt text](<open file.png>)
   Change theme-  Type > Color Theme.
   Run a task- Type > Run Task.
   ![alt text](<command pallette.png>)


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Extensions in VS Code play the role of enhancing and customizing the development environment. They add new features, tools, and functionalities that cater to various programming languages, frameworks, and workflows.
   Click the Extensions icon in the Activity Bar or press Ctrl+Shift+X.
   Use the search bar to find extensions.
   ![alt text](extension.png)
   Click the Install button on the desired extension after running a search.
   View installed extensions, disable, enable, or uninstall them from the extensions view. This viewing and changing is the managing of extensions.
   ![alt text](installed.png)
   Essential Extensions for Web Development
   IntelliSense (Pylance) for code completion and type checking.
   Code linting using pylint.
   Jupyter Notebook support for interactive data science and machine learning work.
   Debugger for Chrome: Debug JavaScript code in Chrome.
   ![alt text](debug.png)
   

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   Click on the View menu at the top of the screen and select Terminal.
   ![alt text](terminal.png)
   Click the plus (+) icon in the terminal panel to open a new terminal session.
   Use the drop-down menu in the terminal panel to switch between multiple terminal sessions.
   Click the split terminal icon next to the plus (+) icon to split the terminal window into multiple panes (each pane runs differently).
   ![alt text](splitting.png)
   Click the trash can icon next to the terminal session to close it or you can also type exit to close the terminal.
   ![alt text](<exiting terminal.png>)
   Advantages of the Integrated Terminal include;
   Provides an Integrated Workflow execute commands without leaving VS Code while when using an external terminal you have to switch between VS Code and the external terminal, which can disrupt your workflow and reduce productivity.
   You can run multiple terminal sessions side by side in different windows while using an external terminal multiple windows can be unmanageable, especially if you have several terminal sessions and VS Code windows open simultaneously.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   Creating Files and Folders - Right-click in the Explorer view and select New File or New Folder.
   ![alt text](<vs create.png>)
   Opening Files - Double-click a file in the Explorer view or use File > Open File.
   ![alt text](opening.png)
   Navigating Files - Use Ctrl+P to quickly open a file by typing its name.
   The editor has a navigation bar above its contents called Breadcrumbs. It shows the current location and allows you to quickly navigate between folders, files, and symbols.
   ![alt text](navigation.png)
   ![alt text](breadcrumbs2.png)



8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   Go to settings
   Go to File > Preferences > Settings.
   ![alt text](<settings s.png>)
   Changing the Theme
   Search for Color Theme and select a preferred theme.
   ![alt text](<changing theme.png>)
   Adjusting Font Size
   Search for Font Size and set your desired size.
   ![alt text](font.png)
   Customizing Keybindings
   Go to File > Preferences > Keyboard Shortcuts to customize keybindings
   ![alt text](<key binding.png>)
   ![alt text](key.png)

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Open a file containing the code you want to debug.
   Set breakpoints by clicking in the gutter next to the line numbers. Breakpoints are essential tools in debugging that allow you to pause the execution of your program at specific lines of code. This lets you inspect the state of your application at those points, making it easier to identify and fix issues. 
   To Debug;
   Go to the Run and Debug view in the Activity Bar.
   ![alt text](<vs run.png>)
   Click Run and Debug or press F5 to start debugging.
   ![alt text](<vs debug 2.png>)
   ![alt text](<vs debug.png>)
   ![alt text](debugging.png)

   Key Debugging Features available are;
   Breakpoints - This pauses execution at specific lines to allow for inspection of the code.
   Watch expressions - lets you track specific variables or expressions.
   Call Stack - This displays the sequence of function calls that led to the current breakpoint or error.
   Variables- this allows for inspection and modification of variables at runtime there are various variables;
   Local Variables- Shows variables defined in the current function.
   Global Variables - Shows variables defined at the global scope.
   Watched Variables - Allows you to monitor specific variables or expressions by adding them to the Watch pane.
   Debug configurations define how to start and attach the debugger to your application there are ; Launch Configurations - they configure how to launch your application, specifying details like the program to run, arguments, environment variables, and more.
   Attach Configurations - this attaches the debugger to a running process, specifying the connection details.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
    Integrating Git with VS Code
   Initialize a Repository 
   Open the folder containing your project.
   ![alt text](repo.png)
   Go to the Source Control view in the Activity Bar and click Initialize Repository.
   ![alt text](inititalize.png)
   Making Commits
   Stage changes by clicking the + icon next to the files.
   Enter a commit message and click the checkmark icon to commit.
   ![alt text](commit.png)
   Pushing Changes to GitHub
   Click the (...) icon in the Source Control view and select Push.
   Follow the prompts to authenticate with GitHub and push your changes.
   Open your github account and you will see the repository that has been commited and pushed.
   ![alt text](resume.png)

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

