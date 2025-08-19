# crueter's CI stuff

This is an organization for storing CI, CMake, scripting, and other cool stuff made by crueter and others in a common place.

Repositories in this organization generally focus on libraries, e.g. SDL2 or OpenSSL, rather than applications. Other CMake utilities and scripts are included as well.

## CI

Supported platforms (if applicable):
- Linux/amd64
- Windows/amd64, Windows/arm64
- Android/aarch64
- FreeBSD/amd64
- Solaris/amd64

UNIX platforms will support aarch64 sometime in the near future, and macOS support may come eventually

### Repositories

- [OpenSSL](https://github.com/crueter-ci/OpenSSL) - OpenSSL 3+
- [SDL2](https://github.com/crueter-ci/SDL2) (currently private) - SDL2
- [FFmpeg](https://github.com/crueter-ci/FFmpeg) (currently private) - FFmpeg 7+

## CMake

Assorted CMake utilities and guides.

### Repositories

- [CPMUtil.cmake](https://github.com/crueter-ci/CPMUtil) (currently private) - wrapper around [CPM](https://github.com/CPM-cmake/CPM.cmake) focusing on reducing boilerplate and increasing flexibility

## Scripting

Assorted shell script (POSIX) utilities, setup scripts, and more

### Repositories

- [Forgejo Runner Scripts](https://github.com/crueter-ci/forgejo-runner) - Scripts and utilities for setting up Arch-based Forgejo runners for Linux and Android
