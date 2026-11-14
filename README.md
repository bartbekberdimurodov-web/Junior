<H1 align="center">Junior</H1>

<a href="./README_RU.md">Readme на русском</a>

<img src="./app_JR/src/main/assets/JR.png" align="left" width="150" height="150" alt="Junior logo">

[![Android CI](https://github.com/Junior/Junior/workflows/Android%20CI/badge.svg)](https://github.com/Junior/Junior/actions)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/Junior/Junior)](https://github.com/Junior/Junior/actions)
[![Discord](https://img.shields.io/discord/1365346109131722753.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/VHdwQFsaGX)

* Junior is a launcher, based on [MojoLauncher](https://github.com/PojavLauncherTeam/PojavLauncher), that allows you to play Minecraft: Java Edition on your Android device!

* It can run almost every version of Minecraft, allowing you to use .jar only installers to install modloaders such as [Forge](https://files.minecraftforge.net/) and [Fabric](http://fabricmc.net/) and mods like [OptiFine](https://optifine.net).

## Navigation
- [Introduction](#introduction)
- [Getting Junior](#getting-Junior)
- [Building](#building) 
- [Current roadmap](#current-roadmap) 
- [License](#license) 
- [Contributing](#contributing) 
- [Credits & Third party components and their licenses](#credits--third-party-components-and-their-licenses-if-available)

## Introduction 
* Junior is a Minecraft: Java Edition launcher for Android based on [MojoLauncher](https://github.com/PojavLauncherTeam/PojavLauncher)
* This launcher can launch almost all available Minecraft versions ranging from rd-132211 to 26.x snapshots (including Combat Test versions). 
* Modding via Forge and Fabric are also supported. 

## Getting Junior

You can get Juniorvia four methods:

1. You can get the prebuilt app from the [releases section](http://github.com/Junior/Junior/releases).

2. You can get it from Google Play by clicking on this badge:
[![Google Play](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/apps/details?id=git.Junior.JuniorLauncher)

3. You can get early builds from [Github Actions](http://github.com/junior/junior/actions).

4. You can [build](#building) from source.
## Building   
* Build the launcher (it will automatically download all required components)
```
./gradlew :app_mojo:assembleDebug
```
If you are building on Windows:
* Replace `./gradlew` with `.\gradlew.bat`
* Make sure `mojoexec`, `sdl`, `glfw` are symlinked into `app_junior/src/main/jni/`

## Current roadmap
- [x] Instance system in favor of profiles
- [x] Out-of-the box 1.21.5 support
- [x] mrpack/CurseForge zip import
- [x] LTW: enable compute shader/image extensions
- [ ] LTW: resolve issues with Create
- [ ] LTW: switch to a color-renderable format for framebuffers
- [ ] Modpack/mod management tool
- [ ] MMC-compatible instance import
- [ ] Vintage Story support
- [ ] Implement common native library standard

## Known Issues
- Some physical mice may have very slow mouse speed
- On Holy GL4ES, large texture atlases may be distorted (resulting in stretched/blocky textures in modpacks)
- Probably more, that's why we have a bug tracker ;) 

## License
- Junior is licensed under [GNU LGPLv3](https://github.com/Junior/Junior/blob/v3_openjdk/LICENSE).

## Contributing
Contributions are welcome! We appreciate any type of contribution, not only code. For example, you can help the wiki shape up. You can help the [translation](https://Junior.ru/translator/translator.html) too!


Any code change to this repository should be submitted as a pull request. The description should explain what the code does and give steps to execute it.

## Third party components, licenses and sources (when applicable)
- [Junior](https://github.com/MojoLauncher/MojoLauncher): [GNU LGPLv3 License](https://github.com/MojoLauncher/MojoLauncher/blob/v3_openjdk/LICENSE)
- Android Support Libraries: [Apache License 2.0](https://android.googlesource.com/platform/prebuilts/maven_repo/android/+/master/NOTICE.txt).
- [Holy GL4ES](https://github.com/Junior/gl4es_extra_extra/): [MIT License](https://github.com/ptitSeb/gl4es/blob/master/LICENSE).
- [OpenJDK](https://github.com/MojoLauncher/openjdk-multiarch-jdk8u): [GNU GPLv2 License](https://openjdk.java.net/legal/gplv2+ce.html).
- [GLFW](https://github.com/Junior/glfw): [zlib license](https://github.com/Junior/glfw/blob/glfw34/LICENSE.md)
- [SDL](https://github.com/Junior/MojoSDL): [zlib license](https://github.com/Junior/MojoSDL/blob/main/LICENSE.txt)
- [LWJGL2-GLFW](https://github.com/Junior/lwjgl2-glfw): 3-Clause BSD license
- [LWJGL3](https://github.com/LWJGL/lwjgl3): [BSD-3 License](https://github.com/LWJGL/lwjgl3/blob/master/LICENSE.md).
- [mojoexec](https://github.com/Junior/mojoexec): [MIT License](https://github.com/Junior/mojoexec/blob/master/LICENSE)
- [Mesa 3D Graphics Library](https://gitlab.freedesktop.org/mesa/mesa): [MIT License](https://docs.mesa3d.org/license.html).
- [pro-grade](https://github.com/pro-grade/pro-grade) (Java sandboxing security manager): [Apache License 2.0](https://github.com/pro-grade/pro-grade/blob/master/LICENSE.txt).
- [Authlib-Injector](https://github.com/yushijinhun/authlib-injector) (Used for authorisation via ely.by): [AGPL-3.0](https://github.com/yushijinhun/authlib-injector/blob/develop/LICENSE).
- [alsoft](https://github.com/kcat/openal-soft/) (Audio output library): [GNU Library General Public License](https://github.com/kcat/openal-soft/blob/master/COPYING) and [Modified PFFFT](https://github.com/kcat/openal-soft/blob/master/LICENSE-pffft).
- [oboe](https://github.com/google/oboe): [Apache License 2.0](https://github.com/google/oboe/blob/main/LICENSE).
- Thanks to [Mineskin](https://mineskin.eu/) for providing Minecraft avatars.
