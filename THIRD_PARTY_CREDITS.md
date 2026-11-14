# Third-party credits — working draft

These acknowledgements describe the actual audit candidate. They are not a certificate of licence compliance. Original legal texts are retained in [THIRD_PARTY_NOTICES](THIRD_PARTY_NOTICES/INDEX.md); unresolved source and grant obligations are recorded in [SOURCE_AVAILABILITY](SOURCE_AVAILABILITY.md).

| Component | Audited version | Credit and licence evidence |
|---|---|---|
| [FFmpeg / FFprobe](https://ffmpeg.org/legal.html) | 8.1.1 | FFmpeg developers; GPL-2.0-or-later build, GPL enabled, nonfree/version3 not enabled |
| [x264](https://www.videolan.org/developers/x264.html) / [x265](https://www.videolan.org/developers/x265.html) | 0.165 r3222 / 4.3 | VideoLAN/x264 contributors; MulticoreWare/x265 contributors; GPL-2.0-or-later route |
| [Opus](https://opus-codec.org/) | 1.6.1 | Xiph.Org and contributors; BSD licence and patent grant |
| [dav1d](https://code.videolan.org/videolan/dav1d), [SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1), [libvpx](https://chromium.googlesource.com/webm/libvpx/) | 1.5.4 / 4.3.0 / 1.17.0 | Their respective authors; BSD-family terms, applicable patent grants |
| [LAME](https://lame.sourceforge.io/) / [mpg123](https://mpg123.org/) | 4.0 / 1.33.7 | LAME and mpg123 developers; LGPL-family terms |
| [oneVPL](https://github.com/intel/libvpl), [NV codec headers](https://github.com/FFmpeg/nv-codec-headers), [AMF headers](https://github.com/GPUOpen-LibrariesAndSDKs/AMF) | 2.17.0 / 13.0.19.0 / 1.5.3 | Intel, NVIDIA and AMD; respective header/dispatcher grants. GPU drivers are not bundled |
| [MKVToolNix](https://codeberg.org/mbunkus/mkvtoolnix/src/tag/release-98.0) | mkvpropedit 98.0 | Moritz Bunkus and contributors; GPLv2. Includes separately licensed libraries/resources documented upstream |
| [Python](https://www.python.org/downloads/release/python-31210/) | CPython 3.12.10 | Python Software Foundation and earlier contributors; PSF/historical licence bundle |
| [PyInstaller](https://github.com/pyinstaller/pyinstaller/tree/v6.16.0) | 6.16.0 | PyInstaller team; GPL-2.0-or-later bootloader exception, Apache-2.0 runtime hooks |
| [Qt / PySide6 / shiboken6](https://doc.qt.io/qtforpython/) | 6.12.0 | The Qt Company and contributors; LGPLv3/GPL alternatives, per-module and embedded-component grants |
| [VapourSynth](https://github.com/vapoursynth/vapoursynth/tree/R81) | R81/API4 | Fredrik Mellbin and contributors; LGPL-2.1-or-later core, separate embedded-library grants |
| [QTGMC / havsfunc](https://github.com/HomeOfVapourSynthEvolution/havsfunc/tree/7a4f5c77e7cf74bef3337a0c86fd4c90ecc0e547) | classic r33 with recorded API compatibility patch | HolyWu and credited original authors including Vit and Didée; complete pinned-revision grant coverage remains under review |
| [mvsfunc](https://github.com/HomeOfVapourSynthEvolution/mvsfunc) / [adjust](https://github.com/dubhater/vapoursynth-adjust) | 11 / pinned revision | mawen1250 and contributors / dubhater; full mvsfunc grant unresolved, adjust WTFPL |
| [MVTools](https://github.com/dubhatervapoursynth/vapoursynth-mvtools) | 29 | Fizick, dubhater and contributors; conservative GPLv2 route because inherited headers are narrower than aggregate metadata |
| [znedi3](https://github.com/sekrit-twc/znedi3) | 3.3 including weights | sekrit-twc and original nnedi3 contributors; GPLv2 evidence, no verified later-version grant |
| [fmtconv](https://github.com/EleonoreMizo/fmtconv) | 31 | EleonoreMizo; WTFPL |
| [RemoveGrainVS](https://github.com/vapoursynth/vs-removegrain) / [MiscFilters](https://github.com/vapoursynth/vs-miscfilters-obsolete) | R1 / R2 | Fredrik Mellbin and contributors; WTFPL / LGPL-2.1-or-later source evidence |
| [NumPy](https://numpy.org/) / [OpenBLAS](https://github.com/OpenMathLib/OpenBLAS) | 2.2.6 / 0.3.29 | NumPy, OpenBLAS and LAPACK contributors; BSD and bundled-code terms |
| [typing_extensions](https://github.com/python/typing_extensions) | 4.16.0 | Python typing contributors; PSF-2.0 |

Further embedded/runtime acknowledgements: [OpenSSL](https://www.openssl.org/) 3.0.16 (Apache-2.0), [SQLite](https://sqlite.org/copyright.html) 3.49.1 (public-domain dedication), [libffi](https://github.com/libffi/libffi) (MIT), GCC runtime with its Runtime Library Exception, MinGW-w64, Microsoft Visual C++ redistributable runtimes, zimg, libp2p, graphengine, vsxx, and [glslang](https://github.com/KhronosGroup/glslang/tree/vulkan-sdk-1.4.357.0) 16.4.0. Qt also incorporates separately credited font, image, compression, regex, Unicode and software-OpenGL components. Exact source/build closure is still being assembled; the recovered legal texts retain their authors' notices.

Qt PDF, QML and WebEngine; Pillow; FFMS2; MVUtensils; vsjetpack; akarin; resize2; proprietary RTX enhancement SDKs/models are **not in this candidate**. Historical acknowledgements are not assertions that these packages are shipped now.

No affiliation, endorsement or permission beyond the applicable upstream terms is implied. No final application licence or public binary download is offered here.

The application icon reuses the established EncodeLab artwork from the earlier Studio project. Its private Git provenance is retained; public asset rights and the final application licence remain under review.
