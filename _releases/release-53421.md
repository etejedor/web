---
layout: releases
version: 5.34/21
release_date: 2014-09-09
state:

toc: true
toc_sticky: true
sidebar:
  nav: "download"
---


## Release Notes
The release notes for this release can be found [here]({{ '/download/all_releases/root-version-v5-34-00-patch-release-notes#21' | relative_url }}).

## Source distributions

| Platform       | Files | Size |
|-----------|-------|-----|
| source | [root_v5.34.21.source.tar.gz](https://root.cern.ch/download/root_v5.34.21.source.tar.gz) |  72M |


## Binary distributions

| Platform       | Files | Size |
|-----------|-------|-----|
| Linux slc5 gcc4.3 | [root_v5.34.21.Linux-slc5-gcc4.3.tar.gz](https://root.cern.ch/download/root_v5.34.21.Linux-slc5-gcc4.3.tar.gz) |  64M |
| Linux slc5_amd64 gcc4.3 | [root_v5.34.21.Linux-slc5_amd64-gcc4.3.tar.gz](https://root.cern.ch/download/root_v5.34.21.Linux-slc5_amd64-gcc4.3.tar.gz) |  69M |
| Scientific Linux Cern 6_amd64 gcc4.4 | [root_v5.34.21.Linux-slc6_amd64-gcc4.4.tar.gz](https://root.cern.ch/download/root_v5.34.21.Linux-slc6_amd64-gcc4.4.tar.gz) |  69M |
| Scientific Linux Cern 6_amd64 gcc4.7 | [root_v5.34.21.Linux-slc6_amd64-gcc4.7.tar.gz](https://root.cern.ch/download/root_v5.34.21.Linux-slc6_amd64-gcc4.7.tar.gz) |  70M |
| Scientific Linux Cern 6_amd64 gcc4.8 | [root_v5.34.21.Linux-slc6_amd64-gcc4.8.tar.gz](https://root.cern.ch/download/root_v5.34.21.Linux-slc6_amd64-gcc4.8.tar.gz) |  71M |
| OsX 10.9 i386 | [root_v5.34.21.macosx64-10.9-i386.tar.gz](https://root.cern.ch/download/root_v5.34.21.macosx64-10.9-i386.tar.gz) |  55M |
| Windows Visual Studio 10 (dbg) | [root_v5.34.21.win32.vc10.debug.exe](https://root.cern.ch/download/root_v5.34.21.win32.vc10.debug.exe) |  93M |
| Windows Visual Studio 10 (dbg) | [root_v5.34.21.win32.vc10.debug.tar.gz](https://root.cern.ch/download/root_v5.34.21.win32.vc10.debug.tar.gz) | 138M |
| Windows Visual Studio 10 | [root_v5.34.21.win32.vc10.exe](https://root.cern.ch/download/root_v5.34.21.win32.vc10.exe) |  47M |
| Windows Visual Studio 10 | [root_v5.34.21.win32.vc10.tar.gz](https://root.cern.ch/download/root_v5.34.21.win32.vc10.tar.gz) |  61M |
| Windows Visual Studio 11 (dbg) | [root_v5.34.21.win32.vc11.debug.exe](https://root.cern.ch/download/root_v5.34.21.win32.vc11.debug.exe) |  99M |
| Windows Visual Studio 11 (dbg) | [root_v5.34.21.win32.vc11.debug.tar.gz](https://root.cern.ch/download/root_v5.34.21.win32.vc11.debug.tar.gz) | 149M |
| Windows Visual Studio 11 | [root_v5.34.21.win32.vc11.exe](https://root.cern.ch/download/root_v5.34.21.win32.vc11.exe) |  48M |
| Windows Visual Studio 11 | [root_v5.34.21.win32.vc11.tar.gz](https://root.cern.ch/download/root_v5.34.21.win32.vc11.tar.gz) |  62M |



## Installations in AFS and CVMFS
Standalone installations with minimal external dependencies are available at:
~~~
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/x86_64-slc5-gcc47-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/i686-slc5-gcc47-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/i686-slc6-gcc48-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/x86_64-slc6-gcc47-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/x86_64-slc6-gcc48-opt
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/i686-slc6-gcc47-opt
~~~

## AFS
Versions for many different platforms and compilers are available at:
/afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21

To use ROOT directly from AFS:
~~~
. /afs/cern.ch/sw/lcg/external/gcc/4.8/x86_64-slc6-gcc48-opt/setup.sh
. /afs/cern.ch/sw/lcg/app/releases/ROOT/5.34.21/x86_64-slc6-gcc48-opt/root/bin/thisroot.sh
~~~

## Direct Git repository access
The entire ROOT source can be obtained from our public Git repository:

~~~
git clone http://root.cern.ch/git/root.git
~~~
The release specific tag can be obtained using:
~~~
cd root
git tag -l
git checkout -b v5-34-21 v5-34-21
~~~