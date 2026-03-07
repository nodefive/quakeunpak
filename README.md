# Quake 1 PAK Extractor

A Python 3 script designed to extract contents from Quake 1 `.pak` archive files.

## Features
- Validates the `PACK` magic header to ensure file integrity.
- Parses the internal directory structure and automatically creates required destination folders.
- Extracts all embedded files directly to their correct relative paths.

## Usage
Run the script passing the target PAK file as an argument:
```bash
quakeunpak <filename.pak>
```
