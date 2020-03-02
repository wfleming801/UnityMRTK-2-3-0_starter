[BETA] -- still working through a few issues

# UnityMRTK-2-3-0_starter
a unity project(**2018.4.17f1**) configured with **MRTK 2.3.0** ready to fork for your own HoloLens development


The intent here is to provide a bit of ground work, to building HoloLens(HL) and Mixed Reality(MR) projects. There is substantial importing of assets and configuration to do before you can actually build and deploy such a project -- which is alleviated by this project. This may be of use to those getting started to have much of this initial setup already accomplished-- all within a forkable git repo. Hope here is to provide a quick common starting place for any new HL or MR project to get up and running, just that much faster.

My only work here is providing this repo of a configured project to be used as a starter template; the underlying tools and work is not mine but these are readily available online separately if desired (see links below). However, by meeting the mentioned assumptions, then forking this repo, you should be ready to "build-and-deploy". 

Please fork as desired to start-off your own projects.

## What is accomplished within this project:
 1. new unity project with text meta data settings for versioning, also TextMesh Pro installed/configured with the examples
 2. git project with gitignore settings appropriate for Unity, Visual Studio (and others)
 3. import of MRTK_2.3.0 assets packages (foundation, tools, extensions, examples)
 4. Unity build and player settings set for UWP platform and HoloLens in addition to MRTK recommended settings, 16-bit depth format
 XR setting
 5. MRTK is added to the initial scene, and that scene is already added to the build

## ASSUMPTIONS:
1. Unity **2018.4.17f1** installed or equivalent compatible version
2. Windows SDK installed (minimal 10.0.10240.0, preferred latest: **10.0.18362.0** )
3. Visual Studio **2019** installed
4. git installed (2.25.0.windows.1)

## STEPS to deploy
1. Meet ASSUMPTIONS
2. Fork this repo
3. Open This project in Unity
4. Edit | Project Settings... select Player, change "Product Name" to be your product
5. File | Build Settings... Build -- choose App/ folder
6. Open solution in Visual Studio 2019
7. Set Debug, X86, Device (Or emulator)
8. Run

### Unity -- initially using version: 2018.4.17f1
https://unity.com/

### Microsoft Windows 10 SDK
https://developer.microsoft.com/en-US/windows/downloads/windows-10-sdk/

### MRTK (Mixed Reality Toolkit) 
https://microsoft.github.io/MixedRealityToolkit-Unity/README.html

### git for Windows 10
https://git-scm.com/downloads

### git ignore settings obtained from Cameron Vetters' incredible tutorials
https://www.cameronvetter.com/2016/11/02/hololens-tutorial-source-control/

-- with modification to the gitignore to allow some files in Library. (see Library/README.md)




