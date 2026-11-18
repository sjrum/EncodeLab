# Release status

**[EncodeLab 0.11.15 — Hardware Compatibility & Usability Update](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.15) is publicly available.**

Focused release checks passed independent ZIP extraction, clean startup, nine-profile defaults and short CPU x265 two-pass, NVIDIA NVENC and Intel QSV Main10/Opus jobs with fresh MKV statistics. Existing focused 100%/125% GUI and simulated legacy-hardware evidence was retained. Actual results on one NVIDIA/Intel system do not certify every GPU or driver. This release uses an explicitly Unlicensed havsfunc revision, a pinned-source VapourSynth R79 CPU runtime and MKVToolNix 103. Matching source/build materials, patches and third-party notices are [published alongside the portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.15/EncodeLab_0.11.15_Source_and_Notices.zip).

The original EncodeLab application/build files use GPL-2.0-or-later; third-party components retain their own terms. The official Microsoft Visual C++ x64 Redistributable is a documented prerequisite. **A fresh-Windows installation has not been tested.**

Download the [Windows x64 portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.15/EncodeLab_0.11.15_Windows_x64_Portable.zip), [matching source/notices](https://github.com/sjrum/EncodeLab/releases/download/v0.11.15/EncodeLab_0.11.15_Source_and_Notices.zip) and [SHA-256 checksums](https://github.com/sjrum/EncodeLab/releases/download/v0.11.15/SHA256SUMS.txt). Ordinary users need only the portable ZIP and any missing system prerequisites; the source archive is for source access and licensing compliance.

Fast Copy / Remux supports full-file copying only, without Start/Duration trimming. Experimental quality calibration does not guarantee precise bitrate or output size. Hardware encoders require compatible hardware/drivers, and not every configuration has been independently tested. Optional MakeMKV integration requires a separate MakeMKV installation.

Hardware-aware controls clear unsupported choices and expose supported options without switching encoder families. Improved QSV checks distinguish 8-bit from 10-bit availability and use compatible fallback modes only after successful probes. Concise tooltips replace raw diagnostics; detailed records remain available locally. Fresh installs show nine preferred profiles, with other profiles available in Profile Manager. Existing visibility preferences remain intact. CPU two-pass names are consistent and CPU utilisation is located on Queue & History.

Privacy verification passed for the actual portable payload, frozen Python code, executable resources, matching source and public documentation. No owner userdata, capability records, queues or private test evidence is distributed. The executable and corresponding application modules were compared, and all 1,160 locked dependency files and 46 pinned dependency-source archives matched the previous release. The existing encoding engines, factory compression settings, Clean Output and queue compatibility are retained.

Some legacy Intel configurations requiring the old HEVC user-plugin loader may remain unsupported by the bundled FFmpeg. Hardware availability remains dependent on enabled devices, installed drivers/runtimes and selected options.

[EncodeLab 0.11.14](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.14) and [EncodeLab 0.11.13](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13) remain available unchanged.
