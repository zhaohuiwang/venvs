## Path
VSCode > Ctrl+Shift+P to open the command palette > Python:Select Interpreter > Enter interpreter path ...
```Bash
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/pytorch/.venv/bin/python
/Users/zhaohuiwang/dev/venvs/uv-venvs/pytorch/.venv/bin/python
```
## To activate this virtual environment from a project directory 
```Bash
source ../venvs/uv-venvs/pytorch/.venv/bin/activate

```

## Package adding log
```Bash
uv init pytorch-projects
cd pytorch-projects

uv add torch torchvision matplotlib seaborn
uv add fastapi[standard]
uv add requests rich


```
