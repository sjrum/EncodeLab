# Release status

**[EncodeLab 0.11.16 — Focused Features & Responsiveness Update](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.16) is publicly available.**

This release adds HQDN3D/FFTDNOIZ CPU denoising methods and presets, direct MKV/MP4 container selection with content-change acknowledgement, conservative optional hardware decoding, improved effective hardware-setting reconciliation, a responsive startup screen and the revised Encoder Options layout. Fixed-bitrate typing no longer rebuilds unrelated hidden controls on every digit. Enter, focus loss and Add to Queue commit pending rate values.

Download the [Windows x64 portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.16/EncodeLab_0.11.16_Windows_x64_Portable.zip), [matching source/notices](https://github.com/sjrum/EncodeLab/releases/download/v0.11.16/EncodeLab_0.11.16_Source_and_Notices.zip) and [SHA-256 checksums](https://github.com/sjrum/EncodeLab/releases/download/v0.11.16/SHA256SUMS.txt). Ordinary users need only the portable ZIP and any missing system prerequisites. GitHub's automatic source archives contain documentation, not the matching application source.

Focused release checks passed versioned startup, queued bitrate capture, 22 targeted feature tests and two short packaged Main10 jobs: CPU two-pass/AAC MP4 with FFTDNOIZ and converted text subtitles; QTGMC/Opus MKV with HQDN3D, chapters, BT.709 metadata and fresh MKV statistics. Both archives were extracted and every file matched. Existing 100%/125% editing tests, short NVIDIA/Intel checks, simulated AMD/legacy-GPU cases and fault-injected output-preservation evidence were reused where code was unchanged. No new physical AMD/legacy-GPU test is claimed.

Privacy verification covered actual payloads, frozen Python code, executable resources, source and documentation. No owner userdata, capability records, queues or private evidence is distributed. Frozen application modules match supplied source. All 1,160 locked dependency files and 46 source archives match the previous public release. Original application/build files use GPL-2.0-or-later; dependencies retain their own terms and existing notices/build-source records. This includes the explicitly Unlicensed havsfunc revision, pinned-source VapourSynth R79 CPU runtime and MKVToolNix 103.

Software decoding remains the default; Auto currently uses software. Explicit hardware decoding is verified on a bounded four-frame source sample, limited to supported progressive H.264/HEVC 4:2:0 sources up to 4K using NVIDIA D3D11VA or Intel QSV. It downloads frames for CPU filters and excludes deinterlacing/QTGMC and full-video analysis. No AMD decoding or zero-copy claim. Hardware support depends on device/driver/runtime/options; probes cannot certify all sources or configurations. Some legacy Intel HEVC user-plugin configurations remain unsupported.

MP4 needs explicit acknowledgement before incompatible-track omissions or SRT conversion. Choose MKV for ASS/PGS, attachments, chapter UIDs/languages or exact nanosecond chapter timing. Audio/player compatibility varies. Sources requiring AMF's existing unknown-colour MKV correction are blocked for MP4. Denoising can remove desirable grain/detail; no universal quality or bitrate-saving promise is made.

Direct FFmpeg processing, CPU two-pass, existing encoder quality settings, MKV Clean Output, queue continuation and completed-media preservation remain. No retired custom timestamp/audio repair was reintroduced. Fast Copy / Remux is full-file only; experimental calibration cannot guarantee exact size. Some profile/page transitions retain layout latency.

The [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vc14/vc_redist.x64.exe) may be required. **Clean-Windows installation has not been independently verified.** Optional [MakeMKV](https://www.makemkv.com/) must be installed separately.

[EncodeLab 0.11.15](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.15), [0.11.14](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.14) and [0.11.13](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13) remain available unchanged.
