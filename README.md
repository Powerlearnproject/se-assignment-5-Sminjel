[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15369242&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   Getting VS Code on my Windows 11 machine was straightforward. I just went to their website, downloaded the installer, and ran it. The setup wizard guided me through the installation process step by step.

   Download the Visual Studio Code installer for Windows.
   Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute.
   By default, VS Code is installed under C:\Users\{Username}\AppData\Local\Programs\Microsoft VS Code.
   <https://code.visualstudio.com/docs/setup/windows>

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   After installing VS Code, I spent a bit of time customizing it:

   Settings: Font and Theme: Go to File > Preferences > Settings to select your favorite font and theme. To alter these settings, type "font" and "theme" into the search bar.
   Indentation: Modify the indentation and tab size to conform to your coding style. To change these settings, look for "tab size" and "indentation" in the options.
   To guarantee that your edits are automatically saved, turn on auto save. Look up "auto save" in the options and select your favorite.
   Line Numbers: To make navigating through your code easier, display the line numbers. Go into the settings and find "line numbers" to activate this option.
   Extensions: To improve your coding experience, install the necessary extensions for your programming language or framework.

   Add-ons:
   Bracket Pair Colorizer: This add-on makes navigating complicated code easier by highlighting bracket pairs that match in color.
   ESLint: If you work with JavaScript, you can use ESLint to find and correct issues in your code.
   Prettier: Prettier is an automatic code formatter that helps you keep a consistent style across your code.
   GitLens: GitLens makes it simpler to comprehend code authorship and history by offering insightful information about your Git repository straight within VS Code.
   Live Server: Live Server can start a development local server with a live reload feature for both dynamic and static sites in order to facilitate web development.
   <https://www.studocu.com/en-za/messages/question/7902801/after-installing-vs-code-what-initial-configurations-and-settings-should-be-adjusted-for-an-optimal>

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Main Components of VS Code User Interface

   The Activity Bar is the main component of the VS Code user interface. It is situated on the far left side of the VS Code window. It has icons for many views, including Source Control, Explorer, Search, and Extensions. Users can effortlessly transition between these many functionalities because to its rapid access.
   Side Bar: The Activity Bar and the Side Bar are adjacent to each other. It has several views, including Source Control, Explorer, Search, and Extensions. Access to extra features like extensions, Git integration, and debugging is also provided. Depending on their preferences, users can set the Side Bar to display or conceal particular views.
   Editor Group: When files and folders are opened for editing in the VS Code window, they are located in the Editor Group. It is made up of one or more editor panes, each of which shows a split view of several files or a single file. Users have the ability to switch between several files and alter the Editor Group's arrangement to suit their workflow.
   Status Bar: The VS Code window's Status Bar can be found at the bottom. It shows details about the file, editor, and project that are currently open. Additionally, it offers access to a number of features, including line endings, indentation settings, language mode selection, and Git status. It also displays faults and notifications and lets users adjust the color theme and select other settings.
   <https://www.studocu.com/en-za/messages/question/7903040/explain-the-main-components-of-the-vs-code-user-interface-identify-and-describe-the-purpose-of-the>

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   Whenever I needed to perform specific tasks like opening files or changing settings, I simply hit Ctrl+Shift+P and typed what I needed. It was like having a command center at my fingertips.
   <https://chatgpt.com/>

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Extensions' Function in VS Code
   The functionality of VS Code is improved with extensions, which offer more features, language support, themes, and other things. They let users alter the development environment to fit their own requirements.

   Locating, Installing, and Managing Extensions The procedures listed below allow users to locate, install, and manage extensions in Visual Studio Code:

   To locate Extensions, select the Extensions view icon located in the window's Activity Bar. Next, look for extensions by name or feature using the search bar.
   Installing Extensions: Select the "Install" option to add an extension to VS Code after it has been located.

   Auto Rename Tag: Renames matched XML and HTML tags automatically.
   Filenames in your code are autocompleted using Path Intellisense.

   These plugins offer features for code formatting, error checking, and effective workflow, which can greatly enhance the web development experience with VS Code.

   <https://www.studocu.com/en-za/messages/question/7903198/discuss-the-role-of-extensions-in-vs-code-how-can-users-find-install-and-manage-extensions>

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   You can open a terminal as follows:

   From the menu, use the Terminal > New Terminal or View > Terminal menu commands.
   From the Command Palette (Ctrl+Shift+P), use the View: Toggle Terminal command.
   In the Explorer, you can use the Open in Integrated Terminal context menu command to open a new terminal from a folder.
   To toggle the terminal panel, use the Ctrl+` keyboard shortcut.
   To create a new terminal, use the Ctrl+Shift+` keyboard shortcut.

   <https://code.visualstudio.com/docs/terminal/basics>

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

   Managing files and folders was a breeze:

   I created new files and folders right from the Explorer view.
   Double-clicking files opened them instantly, or I used Ctrl+P to search and jump between files quickly.

   <https://chatgpt.com/>

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Use the Settings editor to review and change VS Code settings. To open the Settings editor, navigate to File > Preferences > Settings. Alternately, open the Settings editor from the Command Palette (Ctrl+Shift+P) with Preferences: Open Settings or use the keyboard shortcut (Ctrl+,).

   <https://code.visualstudio.com/docs/getstarted/settings#:~:text=Use%20the%20Settings%20editor%20to,keyboard%20shortcut%20(Ctrl%2B%2C).>

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Setting up debugging was straightforward:

   I created a launch.json file to configure my debug environment.
   Pressing F5 started the debugger, where I could set breakpoints and watch variables to pinpoint issues in my code.

   <https://chatgpt.com/>

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

   Integrating Git into VS Code was seamless:

   I initialized my project as a Git repository right from the Source Control view.
   Making commits with meaningful messages and pushing changes to GitHub were just a few clicks away, keeping my code versioned and organized.

   <https://code.visualstudio.com/docs/sourcecontrol/intro-to-git#:~:text=Pick%20an%20existing%20or%20new,init%20on%20the%20command%2Dline.>

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

