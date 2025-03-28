<img align="left" width="100" height="100" src="doc/firestorm_256.png" alt="Logo of Firestorm viewer"/>

**[Firestorm](https://www.firestormviewer.org) is a free client for 3D virtual worlds such as Second Life and various OpenSim worlds where users can create, connect and chat with others from around the world.**

**THIS IS NOT AN OFFICIAL REPOSITORY**

[Real Firestorm Github](https://github.com/FirestormViewer/phoenix-firestorm)

## Differences from real Firestorm

- gestures starting with "/" are not echoed to local chat when typoed
- built-in gesture "/." toggles voice from avatar to camera position and back
- New RLV command: @gesture=/<gesture> will run a gesture through RLV, meaning scripts can now trigger gestures (if the trigger command starts with '/')

This is experimental and completely without support.
Use at your own risk.
I have no intention of pushing fixes back to main. If you want them there, feel free to steal and take credit for them. I'm happy here.

## Open Source

Firestorm is a third party viewer derived from the official [Second Life](https://github.com/secondlife/viewer) client. The client codebase has been open source since 2007 and is available under the LGPL license.

## Download

Pre-built versions of the viewer releases for Windows, Mac and Linux can be downloaded from the [official website](https://www.firestormviewer.org/choose-your-platform/).

## Build Instructions

Build instructions for each operating system can be found using the links below and in the official [wiki](https://wiki.firestormviewer.org).

- [Windows](doc/building_windows.md)
- [Mac](doc/building_macos.md)
- [Linux](doc/building_linux.md)

> [!NOTE]
> We do not provide support for compiling the viewer or issues resulting from using a self-compiled viewer. However, there is a self-compilers group within Second Life that can be joined to ask questions related to compiling the viewer: [Firestorm Self Compilers](https://tinyurl.com/firestorm-self-compilers)

## Contribute

Help make Firestorm better! You can get involved with improvements by filing bugs and suggesting enhancements via [JIRA](https://jira.firestormviewer.org) or [creating pull requests](doc/FS_PR_GUIDELINES.md).
