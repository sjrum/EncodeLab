# Release status

**[EncodeLab 0.11.17 — QTGMC Cadence & Encoding Reliability Fix](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.17) is publicly available.**

Download the [Windows x64 portable ZIP](https://github.com/sjrum/EncodeLab/releases/download/v0.11.17/EncodeLab_0.11.17_Windows_x64_Portable.zip), [matching source/notices](https://github.com/sjrum/EncodeLab/releases/download/v0.11.17/EncodeLab_0.11.17_Source_and_Notices.zip) and [SHA-256 checksums](https://github.com/sjrum/EncodeLab/releases/download/v0.11.17/SHA256SUMS.txt).

## What is fixed
- Corrected QTGMC handling of legitimate MPEG-2 repeat-field cadence and field-phase transitions.
- Added a cached decoded-field cadence audit before expensive QTGMC encoding. Only explicitly signalled, verified field timelines are expanded; no arbitrary frames or audio samples are invented.
- Preserved exact audited field offsets for partial selections, avoiding whole-field rounding at duration boundaries. The zero-offset full-film processing path is unchanged.
- Strengthened encoding-pass completion checks: worker receipts, consumer frame counts and matching two-pass frame hashes are required. FFmpeg exit code 0 alone cannot make an incomplete pass successful.

## Validation
A complete two-pass production encode processed 500,221 frames in each pass, with identical delivered-frame hashes and duration 02:19:05.354. Full output decoding, sampled audio synchronisation and chapter checks passed. Targeted PAL/NTSC, TFF/BFF, clean/progressive, early-termination, queue-continuation, cancellation and completed-media-preservation checks passed. Short NVIDIA/Intel QTGMC checks and portable startup checks passed; no new AMD hardware validation is claimed. The completed production encode was retained as evidence, not repeated for this release.

## Preserved behaviour
Existing encoder quality settings, CPU two-pass, native FFmpeg audio/stream handling, Clean Output, denoising, hardware decoding, profiles, queues and completed-media protection remain unchanged. This is a scoped QTGMC source-adapter correction, not restoration of retired generic timestamp/DTS/PCM repair algorithms. Dependencies are unchanged from 0.11.16.

## Known limitations
- Arbitrary VFR, missing timestamps, unexplained gaps and changing picture geometry remain unsupported in the affected QTGMC path and are rejected before costly encoding. Repeat-field expansion is restricted to verified 8-bit NTSC MPEG-2/TFF. Clean TFF/BFF processing remains supported.
- Interactive previews use the existing bounded adapter and may refuse a mixed-cadence location; an older preview-error status can remain visible after a successful preview.
- A pre-existing 66.7 ms opening-audio omission observed under native zero-seek conditions remains for separate investigation. No unrelated audio fix or universal audio-alignment claim is made.
- Existing hardware/driver, MP4 stream-compatibility and other 0.11.16 limitations still apply. Clean-Windows installation has not been independently verified. The Microsoft Visual C++ x64 Redistributable may be required.

## Continuing release constraints

Software decoding remains the default; Auto currently uses software. Explicit hardware decoding is verified on a bounded four-frame source sample, limited to supported progressive H.264/HEVC 4:2:0 sources up to 4K using NVIDIA D3D11VA or Intel QSV. It downloads frames for CPU filters and excludes deinterlacing/QTGMC and full-video analysis. No AMD decoding or zero-copy claim. Hardware support depends on device/driver/runtime/options; probes cannot certify all sources or configurations. Some legacy Intel HEVC user-plugin configurations remain unsupported.

MP4 needs explicit acknowledgement before incompatible-track omissions or SRT conversion. Choose MKV for ASS/PGS, attachments, chapter UIDs/languages or exact nanosecond chapter timing. Audio/player compatibility varies. Sources requiring AMF's existing unknown-colour MKV correction are blocked for MP4. Denoising can remove desirable grain/detail; no universal quality or bitrate-saving promise is made.

The [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vc14/vc_redist.x64.exe) may be required. Optional [MakeMKV](https://www.makemkv.com/) is installed separately. Fast Copy / Remux remains full-file only; experimental calibration cannot guarantee exact size.

Privacy checks cover actual portable/source payloads, decompressed Python, executable resources and documentation. No owner settings, media, queues or private validation records are included. Matching source is in the attached Source_and_Notices archive, not GitHub's automatic documentation-source download. Existing GPL-2.0-or-later application declarations and dependency-specific licences, notices and source/build materials remain. No dependency upgrade or new licence-clearance claim is made.

Previous releases [0.11.16](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.16), [0.11.15](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.15), [0.11.14](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.14) and [0.11.13](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13) remain available unchanged.
