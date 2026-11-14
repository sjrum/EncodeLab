# Source availability — preparation status

No public binary or application-source release is offered yet. Links below identify upstream evidence; they are **not** a completed corresponding-source offer and do not replace a distributor's licence obligations.

| Covered component | Material verified locally | Before binary distribution |
|---|---|---|
| FFmpeg/FFprobe 8.1.1 | Exact main source archive, build recipe/configuration; dynamic codec package identities | Assemble matching codec/runtime source, patches, scripts and build inputs; offer a complete source kit with the binary |
| x264/x265 and other copyleft codec libraries | Package revisions and binary matches; x265 source; relevant licences | Match exact package revisions and build patches, preserve GCC exceptions and LGPL replacement/relinking requirements |
| Qt/PySide6/shiboken6 6.12.0 | Exact wheel metadata, Qt source attribution records and legal texts | Match wheel build sources/configuration, embedded libraries and Mesa/LLVM revision; document replacement of LGPL libraries and any applicable installation/relinking information |
| MKVToolNix 98.0 | Exact official source tarball and bundled notices | Complete Windows/static-library build closure and corresponding-source delivery |
| VapourSynth R81 and classic plugins | Exact wheels, source distributions, source headers, local compatibility patch | Pin zimg/libp2p and native build inputs; resolve the specific in-process licence combination; retain complete covered source and build instructions |
| Classic havsfunc/QTGMC r33 and mvsfunc11 | Exact revisions and historical grant research | Establish applicable grants for the complete shipped files; later licences must not simply be assumed retroactive |
| CPython/NumPy/other permissive components | Official artifact identities and major notice bundles | Finish static-component attribution mapping; comply with individual notices and redistribution terms |

Preferred delivery is a versioned, hash-addressed corresponding-source archive alongside any authorised binary download, with exact patches/build instructions and required notices. Do not rely solely on a moving upstream branch or a generic homepage. A written source offer has separate obligations and is not being issued by this draft.

Relevant authoritative guidance: [GNU GPLv2](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html), [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html), [FFmpeg legal guidance](https://ffmpeg.org/legal.html), [Qt licensing](https://doc.qt.io/qt-6/licensing.html).

EncodeLab's own source licence and a curated source export remain pending owner review. No private repository history, user data, test logs or application source is included in this documentation-only stage.
