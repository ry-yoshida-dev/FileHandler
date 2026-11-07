# txt_writer

## Overview

Append or overwrite text files with buffered flushing and context-manager support.

## Components

| Component | Description |
|------|------|
| [writer.py](writer.py) | `TxtWriter` implementation (`write`, `close`) |

## Examples

```python
from txt_writer import TxtWriter

writer = TxtWriter(output_path="tmp.txt")
writer.write(txt="Hello, world!", is_new_line=False)
writer.write(txt="Hello, world!", is_new_line=True)
writer.close()
```
