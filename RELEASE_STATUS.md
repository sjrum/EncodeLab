# Release status

**[EncodeLab 0.11.13 — Initial Public Release](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13) is publicly available.**

Focused testing covered QTGMC Fast/Balanced/High Quality, CPU encoding, queue/error preservation, MKVToolNix statistics and stream/chapter retention, extracted-ZIP startup and privacy checks. This release uses an explicitly Unlicensed havsfunc revision, a pinned-source VapourSynth R79 CPU runtime and MKVToolNix 103. Matching source/build materials, patches and third-party notices are [published alongside the portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Source_and_Notices.zip).

The 57 identified original EncodeLab application/build files use GPL-2.0-or-later; third-party components retain their own terms. The official Microsoft Visual C++ x64 Redistributable is a documented prerequisite. **A fresh-Windows installation has not been tested.**

Download the [Windows x64 portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Windows_x64_Portable.zip), [matching source/notices](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Source_and_Notices.zip) and [SHA-256 checksums](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/SHA256SUMS.txt). Ordinary users need only the portable ZIP and any missing system prerequisites; the source archive is for source access and licensing compliance.

Fast Copy / Remux supports full-file copying only, without Start/Duration trimming. Experimental quality calibration does not guarantee precise bitrate or output size. Hardware encoders require compatible hardware/drivers, and not every configuration has been independently tested. Optional MakeMKV integration requires a separate MakeMKV installation.
