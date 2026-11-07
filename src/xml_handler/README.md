# xml_handler

## Overview

Parse XML files and read tag values from the root element or nested tag paths.

## Components

| Component | Description |
|------|------|
| [handler.py](handler.py) | `XMLHandler` implementation (`find`, `find_nested_tags`, `from_path`) |

## Examples

```python
import xml.etree.ElementTree as ET

from xml_handler import XMLHandler

tree = ET.parse("config/settings.xml")
handler = XMLHandler(xml=tree, source="config/settings.xml")
```
