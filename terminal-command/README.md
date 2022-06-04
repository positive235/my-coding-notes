# Terminal (Command)

1. [Launching VS Code from command line](#launching-vs-code-from-command-line)
2. [Create multiple files](#create-multiple-files)

### Launching VS Code from command line

- [Reference:launching from command line](https://code.visualstudio.com/docs/editor/command-line#_launching-from-command-line)

- You can launch VS Code from the command line to quickly open a file, folder, or project. Typically, you open VS Code within the context of a folder. To do this, from an open terminal or command prompt, navigate to your project folder and type `code .`

- Note: Users on macOS must first run a command (Shell Command: Install 'code' command in PATH) to add VS Code executable to the `PATH` environment variable. Read the [macOS setup guide](https://code.visualstudio.com/docs/setup/mac) for help.

- Example
```
mkdir myProject
touch index.html style.css app.js
code .
```

### Create multiple files

```
touch index.html style.css app.js
```
