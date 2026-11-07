# file_handler

## Overview

Save and load Python objects with the format detected from the file extension: JSON (`.json`), Pickle (`.pkl`), YAML (`.yml`, `.yaml`), and HDF5 (`.h5`, `.hdf5`).

## Components

| Component | Description |
|------|------|
| [handler.py](handler.py) | `FileHandler` (`save`, `load`) |
| [type.py](type.py) | `FileType` enum and extension-to-type mapping |
