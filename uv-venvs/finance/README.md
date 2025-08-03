
Specify a stable version of python in the `pyproject.toml`. 
Avoid 3.13.x for production unless you need its new features, as it may have early bugs (released October 2024).
Use `>=3.12.5,<3.13` for Python 3.12.5 or newer within the 3.12 series (recommended for stability) or use `==3.12.*` to allow any 3.12.x version.
```
requires-python = ">=3.12.5,<3.13"
```
If a newer version, like `3.13.x` was applied already: 1. update the `pyproject.toml` 2. remove the `.python-version` dir 3. run `uv sync`
when running Python 3.12.9, I got this error
ModuleNotFoundError: No module named 'zlib'
Switching back to 3.13

## Path
VSCode > Ctrl+Shift+P to open the command palette > Python:Select Interpreter > Enter interpreter path ...
```Bash
/mnt/e/zhaohuiwang/dev/venvs/uv-venvs/finance/.venv/bin/python
/Users/zhaohuiwang/dev/venvs/uv-venvs/finance/.venv/bin/python
```
## To activate this virtual environment from a project directory 
```Bash
source ../venvs/uv-venvs/finance/.venv/bin/activate
source /mnt/e/zhaohuiwang/dev/venvs/uv-venvs/finance/.venv/bin/activate
source /Users/zhaohuiwang/dev/venvs/uv-venvs/finance/.venv/bin/activate
```

## Package adding log
```Bash

```
