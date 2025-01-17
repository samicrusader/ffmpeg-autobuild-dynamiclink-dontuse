# GitHub doesn't allow forks to release via Actions.
# Use https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink

# FFmpeg Latest Autobuilds for Windows

![Build FFmpeg on push](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/workflows/Build%20FFmpeg%20on%20push/badge.svg)
![Build FFmpeg on pull request](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/workflows/Build%20FFmpeg%20on%20pull%20request/badge.svg)

[FFmpeg](https://ffmpeg.org/) latest nonfree git/snapshot/development/master/nightly builds with additional libraries/dependencies.

[Downloads](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/releases)

#### Schedule

Release builds: Weekly or Every time [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) updates or someone updates the repository.\
Pre-release builds: Every 9:00 AM GMT-5 daily except weekends.

#### Release Retention Policy
Release builds are kept for two years.\
Last 1 pre-release build are kept every time a release build are released.

ffmpeg, ffprobe, and ffplay binaries and libav .dlls are included (!!Audacity users!!: avformat-*.dll)

Nonfree builds with Fraunhofer FDK AAC (libfdk_aac) & DeckLink.

Powered by [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) script to cross compile for Windows on Linux.

Uses [GitHub Actions](https://github.com/features/actions) to automatically compile FFmpeg.

Uses [Dependabot](https://dependabot.com/) to automatically update submodules.

For latest bug fixes, new improvements, cutting edge, use git/snapshot/development/master/nightly builds.

For other builds of FFmpeg built by others, goto [animmouse's list of FFmpeg Binaries](https://www.animmouse.com/p/ffmpeg-binaries/).
