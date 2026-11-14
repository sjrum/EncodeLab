# Source availability — preparation status

EncodeLab's verified R79-based release candidate has a **privately prepared, version-matched source and notices archive** for distribution with an authorised public portable release. The source package is **not yet published**, and the public GitHub repository currently hosts documentation only.

| Component | Prepared matching source/build materials |
|---|---|
| EncodeLab application | GPL-2.0-or-later declarations for the 57 identified original application/build files; public release source export prepared separately from private Git history and owner data |
| FFmpeg/FFprobe 8.1.1 and codecs | Matching source archives, licences, patches and recorded build configurations supplied in the private source/notices collection |
| Qt/PySide6/shiboken6 6.12.0 | Source correspondence and LGPL replacement information recorded; 25 native-library payloads and 24,245 source-file comparisons were verified |
| MKVToolNix 103.0 (MSYS2 UCRT64 103.0-1) | Exact source packages, static/runtime dependency sources, build recipes and patches collected for the distributed mkvpropedit binary |
| VapourSynth R79 | Source-pinned CPU core/filter build at `acabf605b2205b32d65859bb2736405719d2fafd`, including modified source/recipes; official R79 binding/vspipe/vsscript retained |
| QTGMC/havsfunc | Explicitly Unlicensed upstream revision `99db9ab4d343bcea5d1f37cb26f58a8c79600c04`, complete source and documented compatibility patch. Historical r33 and mvsfunc are not distributed |
| Other shipped dependencies | Version-matched licence/notices and source evidence collected in the release's corresponding-source materials |

The private source/notices archive contains 46 source archives and 1,114 files, including relevant patches and build instructions. The portable ZIP and this source package should be made available together with equal access, along with SHA-256 checksums, after explicit owner release approval.

The official Microsoft Visual C++ x64 Redistributable is a **prerequisite**, not an included app-local runtime. Clean-Windows installation has not been independently verified.

For redistribution obligations see [GNU GPLv2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html), [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html), [FFmpeg legal guidance](https://ffmpeg.org/legal.html) and [Qt licensing](https://doc.qt.io/qt-6/licensing.html). Public documentation is not itself a corresponding-source distribution.
