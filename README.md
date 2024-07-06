# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   a. 64-bit Windows 11: Visual Studio Code is only available for 64-bit operating systems. 
   b. 1.6 GHz or faster processor: A faster processor will provide better performance, especially when working with large files or complex projects.
   c. 1 GB of RAM (minimum), 4 GB recommended: More RAM allows you to run more programs simultaneously without performance issues.

   Download the installer:

   Visit the official Visual Studio Code download page [Download Visual Studio Code].
    ouble-click the installer file to launch the setup process.



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   a. Interface customization i.e theme, fonts etc.

   b. settings for efficiency i.e, auto save, keyboard shortcuts etc

   c. extensions for specific languages or tasks i.e, python, git etc.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   a. Activity Bar (far left):

   Provides quick access to different views in VS Code.
    Icons represent views like Explorer (file management), Search, Source Control (Git integration), Debugger,  and more.

   b. Side Bar (usually on the left):

   Houses different panels that provide additional functionality and context.
   The specific panels displayed depend on the currently active view (e.g., Explorer view shows your project files, Git view shows version control information).
   You can open/close panels using the tabs at the top of the Side Bar or by right-clicking within the Side Bar area.

   c. 3. Editor Group (center):

   The heart of VS Code, where you write and edit your code.
   You can open multiple files side-by-side in tabs for easy comparison and editing.
   Each tab represents an open file.

   d. Status Bar (bottom)



4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   - The Command Palette is a tool for quickly finding and running commands in VS Code.
    
    How to Access the Command Palette:

   -Keyboard Shortcut: The most common way to open the Command Palette is by pressing Ctrl+Shift+P (Windows/     Linux) or Cmd+Shift+P (macOS).

       Menu: You can also access it by going to the View > Command Palette menu option.

      -Using the Command Palette:

      -Once opened, the Command Palette displays a search bar where you can type in keywords or phrases.
       As you type, VS Code will suggest matching commands, settings, and actions.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

      -Extensions are essentially add-ons that provide additional features and functionalities specific to programming languages, frameworks, tools, and more. 

      -VS Code Marketplace: The built-in VS Code Marketplace provides a vast library of extensions.

       pen_spark



6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   -The integrated terminal in VS Code is a powerful feature that allows you to run command-line tools and scripts directly within your development environment. This eliminates the need to switch back and forth between VS Code and a separate terminal window, boosting your productivity.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently.

   -Explorer View: The Explorer view (usually on the left sidebar) displays your project's file and folder structure

   -File: Choose "New File" and give it a name.

   -Folder: Select "New Folder" and name it appropriately.



8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   a.Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
   b. Settings: The Settings menu (Ctrl+, or Cmd+,) allows you to customize various
  settings, including the theme, font size, and keybindings.

   c. Theme: To change the theme, go to File > Preferences > Color Theme and select your



9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   a.Ensure your program is ready.
   b. Install language extension

   Open launch.json:

Go to Run and Debug view (usually on the left sidebar) or open the Command Palette (Ctrl+Shift+P) and search for "launch.json".

Configure launch.json

Choose the correct configuration for your language and environment. For example, if you're using Node.js,

choose "Attach to Node.js Process" and enter the port number where your Node.js server is running



10.1. Initialize a Git Repository:
Open your project folder in VS Code.
Go to the Source Control view (usually on the left sidebar) or open the Command Palette (Ctrl+Shift+P).
Search for "Git: Initialize Repository" and select it.
This creates a new .git folder in your project directory, marking it as a Git repository.
2. Making Commits:
Stage changes: Make changes to your code files. In the Source Control view, you'll see unstaged changes indicated by a blue plus sign (+).
Click the "+" icon next to a file to stage it for the next commit.
Alternatively, you can stage all changes using the "+" icon at the top of the Source Control view.
Create a commit message: Click on the staged changes section (which might show the number of staged files). This opens a text box where you can write a descriptive commit message explaining your changes.
Commit changes: Click on the checkmark icon (or use the keyboard shortcut Ctrl+Enter) to commit your staged changes with the provided message.
3. Pushing Changes to GitHub (Remote Repository):
Prerequisites:

A GitHub account and a remote repository created for your project on GitHub.
Git configured with your username and email address (you can do this from the terminal or through VS Code settings).
Pushing to GitHub:

Go to the Source Control view. You should see the name of your remote branch (usually origin).
Click on the three dots (...) next to the branch name and select "Publish Branch".
This will open a dialog where you can choose the remote repository URL on GitHub and the branch where you want to push your changes.
Enter your GitHub credentials if prompted.
Click on "Publish" to push your local commits to the remote repository on GitHub.
Additional Tips:

VS Code Git Lens: Consider installing the "GitLens" extension for VS Code. It provides additional functionalities for visualizing Git history, code authorship, and blame.
Pulling Changes: You can also pull changes from the remote repository to your local project using the "Pull" command within the Source Control view. This is useful for incorporating changes made by collaborators.
By integrating Git with VS Code, you can effectively track changes, collaborate with others, and revert to previous versions of your codebase if needed. Remember, these are basic steps, and Git offers a wider range of functionalities that you can explore as you become more comfortable with version control.

Note. Gemini was used as reference to come up with some of the answers to these questions.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

