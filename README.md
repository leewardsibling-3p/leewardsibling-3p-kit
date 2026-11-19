# leewardsibling-3p-kit

Sort a folder of files into per-type subfolders.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m leewardsibling_3p_kit.cli --help
```

```python
from leewardsibling_3p_kit.core import Leewardsibling3pTool

tool = Leewardsibling3pTool()
print(tool)
```

## Layout

```
leewardsibling_3p_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 leewardsibling-3p
