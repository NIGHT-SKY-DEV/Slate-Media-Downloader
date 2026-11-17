# Third-Party Notices

Slate uses the following third-party software. Their copyright and license
notices are preserved here. Slate is not affiliated with, and does not claim
ownership of, any of these projects.

## yt-dlp

- Version distributed with Slate v1.0.0: 2026.10.26
- Project: https://github.com/yt-dlp/yt-dlp
- License: The Unlicense (public domain)
- Role: Media retrieval (invoked as a standalone executable)

yt-dlp is a feature-rich command-line audio/video downloader. Slate invokes
the yt-dlp executable as an external process.

The full Unlicense text is available at https://unlicense.org and is
included in the THIRD-PARTY-LICENSES.txt file shipped with the application.

## FFmpeg

- Version distributed with Slate v1.0.0: N-128959-g4dbee3b241-20261116 (BtbN build)
- Project: https://ffmpeg.org/
- License: Primarily LGPL v2.1 or later; certain optional components under GPL
- Legal: https://ffmpeg.org/legal.html
- Role: Media processing and muxing (invoked as a standalone executable)

FFmpeg is a complete, cross-platform solution to record, convert and stream
audio and video. The exact licensing of the FFmpeg build distributed with
Slate depends on the build configuration and the optional components included.
Consult the FFmpeg legal page for the complete license terms applicable to
the build you received.

## Other dependencies

Slate is built with Electron, React, TypeScript, Vite, and Express. These
are distributed under their respective open-source licenses; see their
project pages for details.

## Notes

- Slate uses standalone executables for both yt-dlp and FFmpeg.
- Third-party software is excluded from Slate's proprietary ownership claims.
- Each third-party component remains governed by its own applicable license.
- A copy of the third-party license notices is included in the application
  distribution as `THIRD-PARTY-LICENSES.txt` (see the resources folder of
  the extracted application).
