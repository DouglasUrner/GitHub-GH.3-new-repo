# GH.3: Making The Initial Commit To A New GitHub Repository

After accepting this assignment (you did or you wouldn't be here), you will have a new repository on GitHub. This repository will also be linked to [GitHub Classroom][classroom] where I can see it.

[classroom]: #

Here is the overview of what you are going to do:

1. **Clone** your assignment repository from GitHub to your local computer.
1. Copy your Pong project into the cloned repository.
1. **Commit** your changes.
1. **Push** your changes to GitHub.

Here is what to do:

1. On your computer, launch **GitHub Desktop**.
1. In GitHub Desktop you will see a list of the files that have been added to the repository.

1. You don't actually need all of the project files to rebuild the game. Git uses a file called **.gitignore** to specify which files will actually be tracked. When you accepted the assignment, you got a **.gitignore**.
1. Change directories to the folder that holds your Unity projects:
   ```bash
   cd /path/to/the/folder/holding/your/Pong/project
   ```
   Probably something like:
   ```bash
   cd /GameDesign2/Unity
   ```
   Or if you folder names include spaces:
   ```bash
   cd "/Game Design/Unit Projects"
   ```
1. Confirm that you are in the right place:
   ```bash
   ls
   ```
   In the result you should see your Pong folder.
