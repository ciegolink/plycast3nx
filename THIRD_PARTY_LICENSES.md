# Third-party licenses

PlyCast 3NX is proprietary software by CiegoLink GmbH. It includes or uses the following open-source components. Each component remains under its own license; the full license texts are included in the installation's `licenses` folder.

| Component | License | Project |
|---|---|---|
| CasparCG Server | GPL-3.0 | [github.com/CasparCG/server](https://github.com/CasparCG/server) |
| FFmpeg / FFprobe | GPL-3.0-or-later | [ffmpeg.org](https://ffmpeg.org) · Build source: [FFMPEG_SOURCE_URL](FFMPEG_SOURCE_URL) |
| CodeMirror 6 | MIT | [codemirror.net](https://codemirror.net) |
| hls.js | Apache-2.0 | [github.com/video-dev/hls.js](https://github.com/video-dev/hls.js) |
| Python | PSF-2.0 | [python.org](https://www.python.org) |
| FastAPI | MIT | [github.com/fastapi/fastapi](https://github.com/fastapi/fastapi) |
| Starlette | BSD-3-Clause | [github.com/encode/starlette](https://github.com/encode/starlette) |
| Uvicorn | BSD-3-Clause | [github.com/encode/uvicorn](https://github.com/encode/uvicorn) |
| Pydantic | MIT | [github.com/pydantic/pydantic](https://github.com/pydantic/pydantic) |
| AsyncSSH | EPL-2.0 or GPL-2.0-or-later (used under EPL-2.0) | [github.com/ronf/asyncssh](https://github.com/ronf/asyncssh) |
| cryptography | Apache-2.0 or BSD-3-Clause | [github.com/pyca/cryptography](https://github.com/pyca/cryptography) |
| pystray | LGPL-3.0 | [github.com/moses-palmer/pystray](https://github.com/moses-palmer/pystray) |
| Pillow | MIT-CMU (HPND) | [github.com/python-pillow/Pillow](https://github.com/python-pillow/Pillow) |
| PyInstaller | GPL-2.0 with bootloader exception | [github.com/pyinstaller/pyinstaller](https://github.com/pyinstaller/pyinstaller) |

## Notes

- **CasparCG Server** and **FFmpeg** are separate programs distributed alongside PlyCast. PlyCast controls them via network protocol (AMCP) and command line; they are not linked into PlyCast. Their source code is available at the links above.
- **pystray** is included as a separate, replaceable Python module in the installation folder.
- **PyInstaller** is only used to package the application; its bootloader exception permits distribution under any license.
