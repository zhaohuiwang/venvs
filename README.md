### Goals
This repo is organized with some shared virtual environments (venv) across projects. 
Instead of creating individual `.venv` directory (some with size > 5 Gigabyte) inside of each project directory, I organized some venvs in this shared directory to reduce the memory usage. The path is listed in the README.md file inside the each venv directory.  For example, the path to the pytorch venv is 
```Bash
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/pytorch/.venv/bin/python
``` 
Note: My working directory is `/mnt/e/zhaohuiwang/dev/` on my WSL system. I follow these steps to select `pytorch` interpreter,
VSCode > Ctrl+Shift+P to open the command palette > Python:Select Interpreter > Enter interpreter path ..
