Resolved Issue:

> [Can't get VSCode/Python debugger to find my project modules](https://stackoverflow.com/questions/53290328/cant-get-vscode-python-debugger-to-find-my-project-modules) ``` Add it to the launch.json file "env": { "PYTHONPATH": "${workspaceRoot}"}``` [Shows 'File Not Found' error when 'Run and Debug' in VSCode. Works normally via cmd.](https://www.reddit.com/r/learnpython/comments/uo1bfq/shows_file_not_found_error_when_run_and_debug_in/)```"cwd": "${fileDirname}"```
