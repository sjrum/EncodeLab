# Source availability — EncodeLab 0.11.13

The [matching application source and third-party notices archive](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Source_and_Notices.zip) is publicly available alongside the [Windows x64 portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Windows_x64_Portable.zip).

This repository hosts documentation. The attached source/notices archive contains EncodeLab's actual GPL-2.0-or-later application source, dependency sources, licences, patches and build/replacement instructions. GitHub's automatic source ZIP/tarball of this documentation repository is **not** the application's corresponding source.

Ordinary users need only the portable ZIP and any missing system prerequisites to run EncodeLab. The separate source archive is supplied for source access and licensing compliance.

| Component | Included matching source/build materials |
|---|---|
| EncodeLab application | GPL-2.0-or-later declarations for the 57 identified original application/build files; actual application source and build scripts included separately from development history and user data |
| FFmpeg/FFprobe 8.1.1 and codecs | Matching source archives, licences, patches and recorded build configurations supplied in the matching source/notices archive |
| Qt/PySide6/shiboken6 6.12.0 | Source correspondence and LGPL replacement information recorded; 25 native-library payloads and 24,245 source-file comparisons were verified |
| MKVToolNix 103.0 (MSYS2 UCRT64 103.0-1) | Exact source packages, static/runtime dependency sources, build recipes and patches collected for the distributed mkvpropedit binary |
| VapourSynth R79 | Source-pinned CPU core/filter build at `acabf605b2205b32d65859bb2736405719d2fafd`, including modified source/recipes; official R79 binding/vspipe/vsscript retained |
| QTGMC/havsfunc | Explicitly Unlicensed upstream revision `99db9ab4d343bcea5d1f37cb26f58a8c79600c04`, complete source and documented compatibility patch. Historical r33 and mvsfunc are not distributed |
| Other shipped dependencies | Version-matched licence/notices and source evidence collected in the release's corresponding-source materials |

The source/notices archive contains **46 source archives and 1,114 files**, including relevant patches and build instructions. Both archives are publicly available together on the [0.11.13 Release](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13), with [SHA-256 checksums](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/SHA256SUMS.txt).

The official Microsoft Visual C++ x64 Redistributable is a **prerequisite**, not an included app-local runtime. Clean-Windows installation has not been independently verified.

For redistribution obligations see [GNU GPLv2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html), [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html), [FFmpeg legal guidance](https://ffmpeg.org/legal.html) and [Qt licensing](https://doc.qt.io/qt-6/licensing.html). Public documentation is not itself a corresponding-source distribution.
