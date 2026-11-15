# EncodeLab — Special Thanks & Acknowledgements

EncodeLab builds on years of generous work by open-source developers. Thank you to the people who make dependable media tools, codecs and video processing available to everyone.

### Media and codecs

[FFmpeg / FFprobe](https://ffmpeg.org/) · [x264](https://www.videolan.org/developers/x264.html) · [x265](https://www.videolan.org/developers/x265.html) · [Opus](https://opus-codec.org/) · [MKVToolNix](https://mkvtoolnix.download/)

### Video processing

[VapourSynth](https://www.vapoursynth.com/) · [QTGMC / havsfunc authors](https://github.com/HomeOfVapourSynthEvolution/havsfunc) · [MVTools](https://github.com/dubhatervapoursynth/vapoursynth-mvtools) · [znedi3](https://github.com/sekrit-twc/znedi3) · [fmtconv](https://github.com/EleonoreMizo/fmtconv)

### Application foundations

[Python](https://www.python.org/) · [Qt / PySide6](https://doc.qt.io/qtforpython/) · [NumPy](https://numpy.org/) and their contributors.

We also thank [FFMS2](https://github.com/FFMS/ffms2) for its contribution to the wider video ecosystem; it is not bundled in this release. These credits do not imply affiliation or endorsement. [Full acknowledgements and component terms](THIRD_PARTY_CREDITS.md) recognise the wider dependency stack.

## Introducing EncodeLab

EncodeLab is a portable Windows x64 video-transcoding application. It brings CPU and GPU encoding, picture processing, stream management and a persistent queue into one interface.

## Features

- CPU x264/x265, including genuine video two-pass encoding.
- NVIDIA NVENC, Intel QSV and AMD AMF, subject to compatible hardware and drivers.
- Experimental full-video and opening-range calibrated quality selection, with CPU/OpenCL analysis options. Analysis selects a quality value; the ordinary encoder pipeline then performs the final encode. It cannot guarantee an exact bitrate or file size.
- QTGMC Fast, Balanced and High Quality, plus standard deinterlacing; crop, aspect-ratio handling and bounded/custom resolutions.
- Audio, subtitle, chapter and additional-stream selection; Fast Copy / Remux (full files only; no Start/Duration trimming).
- Optional **Open Disc / MakeMKV integration** for selecting and extracting supported disc titles and tracks. [MakeMKV](https://www.makemkv.com/) is installed separately and is not included in the portable package.
- Batch queue and history, completed-media protection and direct FFmpeg processing.
- Clean Output metadata handling and newly measured MKV track statistics through MKVToolNix.

## Screenshots

![Encode page](screenshots/encode.jpg)

## How to Use

1. Open media, or drop a supported source onto a general background area.
2. Choose a profile, picture settings and the tracks to keep. Specialised track-import regions retain their separate purpose.
3. Choose a new destination and add the job to the queue.
4. Start the queue and review the completed result.

The portable distribution is a complete extracted folder: keep its executable, `_internal` and `vendor` folders together. It needs a writable user location and compatible Windows x64 hardware. Hardware encoding requires the corresponding installed GPU driver. The Microsoft Visual C++ x64 Redistributable is a documented prerequisite where the matching runtime is not already installed. Clean-Windows operation has not yet been verified.

## Development Status

**EncodeLab 0.11.13 is the initial public Windows x64 release.** See [release notes](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13) for features, requirements and known limitations. Downloads are available below.

## Licensing and Third-Party Information

EncodeLab's original application code is licensed under **GPL-2.0-or-later**, as indicated by its source licensing notices.

EncodeLab builds upon numerous open-source projects, each retaining its respective licence and copyright.

Full [credits](THIRD_PARTY_CREDITS.md), [third-party licences](THIRD_PARTY_NOTICES/INDEX.md), [source availability](SOURCE_AVAILABILITY.md) and [release information](RELEASE_STATUS.md) are provided for transparency.

## Downloads

- **[EncodeLab 0.11.13 Windows x64 Portable](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Windows_x64_Portable.zip)** — 144.04 MiB
- [Matching application source and third-party notices](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/EncodeLab_0.11.13_Source_and_Notices.zip) — 691.06 MiB
- [SHA-256 checksums](https://github.com/sjrum/EncodeLab/releases/download/v0.11.13/SHA256SUMS.txt)
- [Full GitHub Release notes](https://github.com/sjrum/EncodeLab/releases/tag/v0.11.13)

Ordinary users only need the portable ZIP and any missing system prerequisites to run EncodeLab. Extract the complete folder before launching `EncodeLab.exe`. Install the official [Microsoft Visual C++ x64 Redistributable](https://aka.ms/vc14/vc_redist.x64.exe) if needed; hardware encoders require compatible installed GPU drivers.

The source/notices ZIP is provided separately for source access and licensing compliance; it is not needed merely to run the application. GitHub's automatic source archive of this documentation repository is not the application's corresponding source. Clean-Windows installation has not yet been independently verified.
