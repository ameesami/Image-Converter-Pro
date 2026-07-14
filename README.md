# Image-Converter-Pro
A professional PySide6 desktop image converter for Windows, Linux and macOS.
We are now at 🚀 v0.1.0 Foundation

## Features

- Convert AVIF, HEIC/HEIF, WebP, JPG, PNG, TIFF, BMP, GIF and ICO
- Explorer-style folder tree and file list
- Image preview and metadata panel
- Batch conversion with optional subfolder scanning
- Preserve folder structure, metadata and timestamps
- Keep or remove originals
- Configurable output format and quality
- Live status bar with folder, image count, size, converted count and errors
- Cross-platform PyInstaller build scripts
- Report Issue link and About dialog

## Requirements

- Python 3.11 or newer

## Installation

```bash
python -m venv .venv
```

Windows:

```bat
.venv\Scripts\activate
pip install -r requirements.txt
python main.py
```

Linux/macOS:

```bash
source .venv/bin/activate
pip install -r requirements.txt
python main.py
```

## Building

Windows:

```bat
build\build_windows.bat
```

Linux:

```bash
chmod +x build/build_linux.sh
build/build_linux.sh
```

macOS:

```bash
chmod +x build/build_macos.sh
build/build_macos.sh
```

PyInstaller builds must be created on the target operating system.

## License

MIT License.

© SpaceBridge.de
