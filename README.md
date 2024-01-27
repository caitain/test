<picture>
  <img alt="Lovense Viewer Logo" src="doc/login_viewer_logo.png">
</picture>

**[Lovense Viewer](https://www.lovense.com/game/lovense-viewer/) is a free client for 3D virtual worlds such as Second Life and various OpenSim worlds where users can create, connect and chat with others from around the world.** This repository contains the official source code for the Lovense viewer.

## Open Source

Lovense viewer is a third party viewer derived from the official [Second Life](https://github.com/secondlife/viewer) client. The client codebase has been open source since 2007 and is available under the LGPL license.

## Download

Pre-built versions of the viewer releases for Windows and Mac can be downloaded from the [official website](https://www.lovense.com/game/lovense-viewer/).

## Build Instructions

### Build Instructions For Windows
##### Prerequisites
- Python 3.0 or later
- Visual Studio 2022
- Cmake 3.0 or later

------------


###### Compilation steps
1.Install autobuild  
`pip install autobuild`  
2.Install llbase     
`pip install llbase`  
3.Use the command line to generate project files    
`autobuild configure -c RelWithDebInfoOS -A 64`  

### Build Instructions For Mac
##### Prerequisites
- Python 3.0 or later
- Xcode 15.0 or later
- Cmake 3.0 or later

------------


###### Compilation steps
1.Install autobuild  
`pip install autobuild`    
2.Use the command line to generate project files    
`autobuild configure -c RelWithDebInfoOS`  
Or Use build script  
`build-xcode.sh`

Please note that we do not provide support for compiling the viewer or issues resulting from using a self-compiled viewer. However, there is a self-compilers group within Second Life that can be joined to ask questions related to compiling the viewer: [Lovense Viewer Self Compilers](secondlife:///app/group/2014ce4c-5393-fb67-83ac-910db84c273c/about)

## Contribute

Help make Lovense Viewer better! You can get involved with improvements by filing bugs and suggesting enhancements via [Discord](https://discord.gg/lovense) or creating pull requests.
