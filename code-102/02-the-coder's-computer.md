# Choosing a Text Editor

## What are four important features to look for in a text editor?**

 1. Code completion, speeds up coding by offering suggestions as you type, reducing typos and saving time.
 2. Syntax highlighting, transforms code into a color-coded landscape, instantly revealing errors and boosting readability.
 3. A nice variety of themes (to reduce eye strain and fatigue),  many developers favor dark themes with vibrant syntax highlighting for reduced eye strain, but there are many themes to explore.
 4. The ability to choose from a healthy selection of extensions available when you need them. Extensions will ensure that you have the ability to add functionality as you need it

## The Command Line

### What do the following commands do?

- **pwd**: Print Working Directory - ie. Where are we currently.

- **ls**: List the contents of a directory.
- **cd**: Change Directories - ie. move to another directory.
- **mkdir**: Make directory - ie. creates new directories
- **touch**: Creates new empty files or updates timestamps of existing files

### Can you explain what is happening in the following scenario if these commands and arguments are entered into the command line? (Arguments are extra instructions given to a command.)

- This command changes the current working directory to the "projects" directory. It's like "navigating" into that folder within the command line.

   ```cd projects```
- This command creates a new directory named "new-project" within the current working directory, which is now "projects". It's like making a new folder within that "projects" folder.

   ```mkdir new-project```
- This command creates a new empty file named "newfile.md" inside the "new-project" directory. It's like creating a blank Markdown file (.md extension) within that newly created folder.

   ```touch new-project/newfile.md```
- This command moves the current working directory back up one level, to the parent directory of "projects". It's like "stepping out" of the "projects" folder.

   ```cd ..```
- This command lists the contents of the "new-project" directory, even though the current working directory is now the parent directory. It's like "peeking" into the "new-project" folder to see what's inside.

  ```ls projects/new-project```

