# Third-party credits

These acknowledgements describe EncodeLab's source-complete R79 private release candidate. The currently published documentation predates the first public software release; the corresponding version-matched source and notices materials are prepared for distribution with the approved binary. [Staged legal texts](THIRD_PARTY_NOTICES/INDEX.md) include historical records; see [source availability](SOURCE_AVAILABILITY.md) for the current release preparation status.

| Component | Audited version | Credit and licence evidence |
|---|---|---|
| [FFmpeg / FFprobe](https://ffmpeg.org/legal.html) | 8.1.1 | FFmpeg developers; GPL-2.0-or-later build, GPL enabled, nonfree/version3 not enabled |
| [x264](https://www.videolan.org/developers/x264.html) / [x265](https://www.videolan.org/developers/x265.html) | 0.165 r3222 / 4.3 | VideoLAN/x264 contributors; MulticoreWare/x265 contributors; GPL-2.0-or-later route |
| [Opus](https://opus-codec.org/) | 1.6.1 | Xiph.Org and contributors; BSD licence and patent grant |
| [dav1d](https://code.videolan.org/videolan/dav1d), [SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1), [libvpx](https://chromium.googlesource.com/webm/libvpx/) | 1.5.4 / 4.3.0 / 1.17.0 | Their respective authors; BSD-family terms, applicable patent grants |
| [LAME](https://lame.sourceforge.io/) / [mpg123](https://mpg123.org/) | 4.0 / 1.33.7 | LAME and mpg123 developers; LGPL-family terms |
| [oneVPL](https://github.com/intel/libvpl), [NV codec headers](https://github.com/FFmpeg/nv-codec-headers), [AMF headers](https://github.com/GPUOpen-LibrariesAndSDKs/AMF) | 2.17.0 / 13.0.19.0 / 1.5.3 | Intel, NVIDIA and AMD; respective header/dispatcher grants. GPU drivers are not bundled |
| [MKVToolNix](https://mkvtoolnix.download/) | mkvpropedit 103.0 (MSYS2 UCRT64 package 103.0-1) | Moritz Bunkus and contributors; GPLv2. Matching source packages, patches, linked dependencies and build receipts prepared |
| [Python](https://www.python.org/downloads/release/python-31210/) | CPython 3.12.10 | Python Software Foundation and earlier contributors; PSF/historical licence bundle |
| [PyInstaller](https://github.com/pyinstaller/pyinstaller/tree/v6.16.0) | 6.16.0 | PyInstaller team; GPL-2.0-or-later bootloader exception, Apache-2.0 runtime hooks |
| [Qt / PySide6 / shiboken6](https://doc.qt.io/qtforpython/) | 6.12.0 | The Qt Company and contributors; LGPLv3/GPL alternatives, per-module and embedded-component grants |
| [VapourSynth](https://github.com/vapoursynth/vapoursynth/tree/acabf605b2205b32d65859bb2736405719d2fafd) | R79 / API4 | Fredrik Mellbin and contributors; LGPL-2.1-or-later core. CPU runtime rebuilt from pinned source with corresponding patches and build recipe; official R79 binding/vspipe/vsscript retained |
| [QTGMC / havsfunc](https://github.com/HomeOfVapourSynthEvolution/havsfunc/commit/99db9ab4d343bcea5d1f37cb26f58a8c79600c04) | Explicitly Unlicensed upstream revision, with documented compatibility patch | HolyWu and credited QTGMC contributors including Vit and Didée; complete matching source and patch supplied. Historical r33 is not distributed |
| [adjust](https://github.com/dubhater/vapoursynth-adjust) | pinned revision | dubhater; WTFPL. The unused mvsfunc dependency was removed from the release candidate |
| [MVTools](https://github.com/dubhatervapoursynth/vapoursynth-mvtools) | 29 | Fizick, dubhater and contributors; conservative GPLv2 route because inherited headers are narrower than aggregate metadata |
| [znedi3](https://github.com/sekrit-twc/znedi3) | 3.3 including weights | sekrit-twc and original nnedi3 contributors; GPLv2 evidence, no verified later-version grant |
| [fmtconv](https://github.com/EleonoreMizo/fmtconv) | 31 | EleonoreMizo; WTFPL |
| [RemoveGrainVS](https://github.com/vapoursynth/vs-removegrain) / [MiscFilters](https://github.com/vapoursynth/vs-miscfilters-obsolete) | R1 / R2 | Fredrik Mellbin and contributors; WTFPL / LGPL-2.1-or-later source evidence |
| [NumPy](https://numpy.org/) / [OpenBLAS](https://github.com/OpenMathLib/OpenBLAS) | 2.2.6 / 0.3.29 | NumPy, OpenBLAS and LAPACK contributors; BSD and bundled-code terms |
| [typing_extensions](https://github.com/python/typing_extensions) | 4.16.0 | Python typing contributors; PSF-2.0 |

Further embedded/runtime acknowledgements: [OpenSSL](https://www.openssl.org/) 3.0.16 (Apache-2.0), [SQLite](https://sqlite.org/copyright.html) 3.49.1 (public-domain dedication), [libffi](https://github.com/libffi/libffi) (MIT), GCC runtime with its Runtime Library Exception, MinGW-w64, winpthreads, zimg, graphengine and vsxx. The Microsoft Visual C++ x64 Redistributable is a documented system prerequisite, not part of the portable ZIP. Qt also incorporates separately credited font, image, compression, regex, Unicode and software-OpenGL components. Matching source archives, build scripts and patches are prepared in the private source-materials package; the recovered legal texts retain their authors' notices.

Qt PDF, QML and WebEngine; Pillow; FFMS2; MVUtensils; mvsfunc; vsjetpack; akarin; resize2; R81/glslang; proprietary RTX enhancement SDKs/models are **not in this candidate**. Historical acknowledgements are not assertions that these packages are shipped now.

No affiliation, endorsement or permission beyond the applicable upstream terms is implied. The 57 identified original EncodeLab application/build files use GPL-2.0-or-later. No public binary download is offered here.

The application icon is original EncodeLab artwork created during development and retained from the earlier Studio project.
