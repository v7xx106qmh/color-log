# color-log

Level-aware coloured output for the standard logging module.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install color-log
```

## Usage

```python
from color_log import colorLog

result = colorLog("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
