### Goals
This repo is organized with some shared virtual environments (venv) across projects. 
Instead of creating individual `.venv` directory (some with size > 5 Gigabyte) inside of each project directory, I organized some venvs in this shared directory to reduce the memory usage. The path is listed in the README.md file inside the each venv directory.  

List of venvs and their path
```Bash
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/baysian/.venv/bin/python
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/finance/.venv/bin/python
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/gpflow_tf/.venv/bin/python
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/pysparkvenv/.venv/bin/python
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/pytorch/.venv/bin/python
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/sandbox/.venv/bin/python
``` 

To activate the selected venv, cd to the project directory the 

```Bash
source ../venvs/uv-venvs/baysian/.venv/bin/activate
source ../venvs/uv-venvs/finance/.venv/bin/activate
source ../venvs/uv-venvs/gpflow_tf/.venv/bin/activate
source ../venvs/uv-venvs/pysparkvenv/.venv/bin/activate
source ../venvs/uv-venvs/pytorch/.venv/bin/activate
source ../venvs/uv-venvs/sandbox/.venv/bin/activate
``` 

Note: My working directory is `/mnt/e/zhaohuiwang/dev/<project-name>` on my WSL system. I follow these steps to select a interpreter,<p>
VSCode > Ctrl+Shift+P to open the command palette > Python:Select Interpreter > Enter interpreter path ..
