# aria2 - The ultra fast download utility
static autobuild for Windows and Linux (TODO: MAC OSX, Android) with patched features using Docker and GitHub workflow

## Current Release
* Aria2 version: 1.37.0 for Windows 7 and newer, and Linux

## Example Usage
aria2c -c -j5 -k256K -s64 -x64 -m20 --retry-wait=5 --lowest-speed-limit=20K --no-conf --ca-certificate=path/to/ca-bundle.crt --dir=path/to/save/ https://example.com/largefile

## References
* aria2: [https://github.com/aria2/aria2](https://github.com/aria2/aria2)
* aria2 Online Manual: [https://aria2.github.io/manual/en/html/](https://aria2.github.io/manual/en/html/)
* aria2-build-msys2: [https://github.com/myfreeer/aria2-build-msys2](https://github.com/myfreeer/aria2-build-msys2)
* upload-to-release: [https://github.com/JasonEtco/upload-to-release](https://github.com/JasonEtco/upload-to-release)
* Docker: [https://www.docker.com/](https://www.docker.com/)
