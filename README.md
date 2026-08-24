<!--lint disable double-link-->

<div align="center">
	<div>
		<img width="500" src="media/logo.svg" alt="Awesome AppImage">
	</div>
	<a href="https://awesome.re">
		<!img src="https://awesome.re/badge-flat2.svg" alt="Awesome">
	</a>
	<p>
		<sub>Lovingly crafted AppImage tools and resources. Follow me on <a href="https://twitter.com/probonopd">Twitter</a>.</sub>
	</p>
	<br>
</div>

# Awesome AppImage with stars

[AppImage](https://appimage.org) is a community-based format to distribute applications to various mainstream Linux distributions without the need for a centralized store. One app = one file! This list contains tools to work with AppImages, such as to create AppImages for applications and to integrate AppImages into the system easily. As the vibrant community around AppImage is growing, so is this list.

## Contents

* [AppImage discovery](#appimage-discovery)
  * [App catalogs](#app-catalogs)
  * [App stores](#app-stores)
  * [App centers](#app-centers)
  * [App scrapers](#app-scrapers)
* [AppImage consumption tools](#appimage-consumption-tools)
  * [Desktop integration](#desktop-integration)
  * [Updaters](#updaters)
  * [Sandboxes](#sandboxes)
  * [Package managers](#package-managers)
  * [Linux distributions](#linux-distributions)
* [AppImage developer tools](#appimage-developer-tools)
  * [Low-level tools](#low-level-tools)
  * [Build systems](#build-systems)
  * [Deployment tools for compiled applications](#deployment-tools-for-compiled-applications)
  * [Deployment tools for Python applications](#deployment-tools-for-python-applications)
  * [Deployment tools for Electron applications](#deployment-tools-for-electron-applications)
  * [Deployment tools for Windows applications](#deployment-tools-for-windows-applications)
  * [Deployment tools for Java applications](#deployment-tools-for-java-applications)
  * [Deployment tools for .NET Core (Mono) applications](#deployment-tools-for-net-core-mono-applications)
  * [Deployment tools for Flash applications](#deployment-tools-for-flash-applications)
  * [Deployment tools for Rust applications](#deployment-tools-for-rust-applications)
  * [Tools to convert from other package formats](#tools-to-convert-from-other-package-formats)
  * [Metadata tools](#metadata-tools)
  * [QC tools](#qc-tools)
  * [Continuous integration](#continuous-integration)
  * [Libraries](#libraries)
  * [Templates](#templates)
* [Resources](#resources)
  * [Specs](#specs)
  * [Documentation](#documentation)
  * [Tutorials](#tutorials)
  * [Articles](#articles)
  * [Videos](#videos)
  * [Books](#books)
  * [Blogs](#blogs)
  * [Courses](#courses)
  * [Community](#community)
  * [Miscellaneous](#miscellaneous)
  * [Related](#related)
  * [Other awesome lists](#other-awesome-lists)
  * [Expired links](#expired-links)

## AppImage discovery

### App catalogs

* [AppImage.GitHub.io](https://appimage.github.io/) - Catalog of AppImages that passed an automated test, links to upstream download pages.

### App stores

* [AppImageHub.com](https://www.appimagehub.com/) - Downloadable AppImages, powered by [Opendesktop.org](https://www.opendesktop.org/).
* [pling.com](https://www.pling.com/) - Open store where creators can publish their libre products and creative content including AppImages.
* [Manjaro Software Discover](https://software.manjaro.org/appimages) - Web-based app store that contains applications in multiple formats, including AppImage.

### App centers

* [AppImagePool](https://github.com/prateekmedia/appimagepool) ⭐ 722 | 🐛 28 | 🌐 Dart | 📅 2026-03-12 - Simple, modern AppImageHub Client, powered by flutter.
* [NX Software Center](https://github.com/Nitrux/nx-software-center) ⚠️ Archived - Portable Software Center for portable AppImage applications.

### App scrapers

* [AppImageRadar](https://github.com/AppImage/AppImageRadar) ⚠️ Archived - Search for AppImage-related activity on GitHub using Travis CI.
* [appimages.scraper](https://github.com/azubieta/appimages.scraper) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2018-10-25 - Search for AppImage releases over the web.

## AppImage consumption tools

### Desktop integration

* [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) ⭐ 8,252 | 🐛 205 | 🌐 C++ | 📅 2026-03-09 - Integrates into users' systems and establishes a single `~/Applications` directory, assisting the user to move AppImages into there, with support for updating and removing AppImages through apps launcher.
* [Gear lever](https://github.com/mijorus/gearlever/) ⭐ 2,129 | 🐛 203 | 🌐 Python | 📅 2026-07-22 - Integrates AppImages into the Gnome desktop by drag-and-drop onto the Gear lever application.
* [go-appimaged](https://github.com/probonopd/go-appimage/tree/master/src/appimaged) ⭐ 1,166 | 🐛 134 | 🌐 Go | 📅 2026-06-07 - Optional daemon that integrates AppImages into the system (experimental).
* [appimaged](https://github.com/AppImage/appimaged) ⚠️ Archived - Optional daemon that integrates AppImages into the system (deprecated).
* [XApp Thumbnailers](https://github.com/linuxmint/xapp-thumbnailers) ⭐ 57 | 🐛 5 | 🌐 Python | 📅 2026-06-16 - Thumbnailers for GTK Desktop Environments, including one for the AppImage file format. Makes Gtk based file managers like Caja (MATE), Nautilus (GNOME), Nemo (Cinnamon), PCManFM (LXDE), and Thunar (Xfce) show application icons on AppImages.
* [LinuxPA](https://github.com/CalebQ42/LinuxPA) ⭐ 40 | 🐛 2 | 🌐 Go | 📅 2025-01-11 - PortableApps.com type launcher for Linux with AppImage support.
* [AppImage Desktop Maker](https://github.com/Alexsussa/AIDM) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2023-06-24 - Creates menu entries for AppImages without the need for a daemon.
* [Thumbnailer for AppImages](https://github.com/mttbernardini/appimage-thumbnailer) ⭐ 11 | 🐛 3 | 🌐 CMake | 📅 2021-05-10 - Generates icons for AppImages that are shown in file managers of GNOME and KDE compatible desktop environments.
* [AppImage To Gnome](https://github.com/DejfCold/ATG) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2021-08-31 - Monitors and (de)installs AppImages from the Gnome desktop.
* [gnome\_appimage\_installer](https://github.com/knork-fork/gnome_appimage_installer) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2022-09-13 - Somewhat a misnomer (AppImages don't need to be "installed"), creates a desktop file that follows the freedesktop.org spec for your AppImage files; written in bash.
* [Getting Started Managing Software with AppImage on Ubuntu](https://adamtheautomator.com/appimage-ubuntu/) - Verbosely explains how to manage AppImages without the need for further software.
* [appimagehelper](https://gitlab.com/posktomten/appimagehelper) - Program for creating, deleting, controlling and organizing shortcuts to AppImage.

### Updaters

* [AppImageUpdate](https://github.com/AppImage/AppImageUpdate) ⭐ 728 | 🐛 79 | 🌐 C++ | 📅 2025-10-18 - Official grapical application to update AppImages; command-line tool to update AppImages.
* [AppImageUpdater](https://github.com/antony-jr/AppImageUpdater) ⭐ 46 | 🐛 1 | 🌐 C++ | 📅 2021-04-02 - Simple updater for humans written in C++ and Qt.
* [appimage-update](https://github.com/AppImageCrafters/appimage-update) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2020-07-27 - AppImage Update implementation written in Go.
* [appimage-updater](https://pypi.org/project/appimage-updater/) - AppImage Update implementation written in Python, distributed on PyPi.

### Sandboxes

* [Firejail](https://github.com/netblue30/firejail) ⭐ 7,603 | 🐛 523 | 🌐 C | 📅 2026-08-22 - Optional sandbox with support for AppImage built in.
* [AppImage Sandboxing Project](https://github.com/mgord9518/aisap) ⭐ 64 | 🐛 2 | 🌐 Zig | 📅 2024-12-02 - Golang library to help sandbox AppImages with bwrap.

### Package managers

**Note:** The AppImage format is explicitly designed *not to need any package managers* or similar tools. Everything can be done in the file manager (and an optional daemon for system integration).

* [bauh](https://github.com/vinifmor/bauh) ⭐ 1,399 | 🐛 107 | 🌐 Python | 📅 2024-10-13 - Graphical user interface for managing Linux applications supporting AppImage, Arch (repositories/AUR), Flatpak, Snap and native Web applications.
* [Zap](https://github.com/srevinsaju/zap) ⭐ 597 | 🐛 51 | 🌐 Go | 📅 2024-06-14 - AppImage package manager. Downloads the AppImage if it does not exist. If it already exists, updates it with AppImageUpdate. Integrates AppImage into the system.
* [AppMan](https://github.com/ivan-hc/AppMan) ⭐ 342 | 🐛 0 | 🌐 Shell | 📅 2026-08-23 - AppImage Manager that works like APT or Pacman.
* [appimage-manager](https://github.com/AppImageCrafters/appimage-manager) ⭐ 118 | 🐛 8 | 🌐 Go | 📅 2023-10-24 - Command-line tool for managing AppImages allowing to search, install, remove and update applications.
* [Bread](https://github.com/pegvin/bread) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2024-04-05 - Download, update, remove, and run AppImages from GitHub on the command line, and integrate apps into the desktop.
* [ayy](https://github.com/lawl/ayy) ⭐ 20 | 🐛 3 | 🌐 Go | 📅 2022-05-04 - Package manager for AppImage. Single, static, dependency free binary. Written in Go.
* [AIPM](https://github.com/michaeldelago/aipm) ⚠️ Archived - A Package Manager for AppImages.
* [leap](https://github.com/lnxcz/leap) ⭐ 14 | 🐛 2 | 🌐 Rust | 📅 2024-01-19 - Fast and simple AppImage manager. Written in Rust.
* [homebrew-appimage](https://github.com/athrunsun/homebrew-appimage) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2022-02-05 - Linuxbrew AppImage Formulae.
* [RookiePM](https://github.com/18fadly-anthony/rookie) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2022-04-07 - Package manager for AppImages and Shell Scripts.
* [jewelrystore](https://rubygems.org/gems/jewelrystore) - Command line AppImage store made in ruby.

### Linux distributions

Although the AppImage format was carefully designed not to need any special support from Linux distributions, there are some that offer varying degrees of AppImage friendliness out of the box.

* [Deepin](https://www.deepin.org/en/) - When you double-click an AppImage or any other executable file that lacks execute permissions, a user-friendly dialog explains the situation and asks for your permission to set the execute permission and execute the executable.
* [Nitrux](https://nxos.org/) - Promotes the use of AppImage as the main format for getting applications, has a built in app center featuring AppImages.
* [Linux Mint](https://linuxmint.com/) - Has an [AppImage thumbnailer](https://github.com/linuxmint/xapp-thumbnailers) ⭐ 57 | 🐛 5 | 🌐 Python | 📅 2026-06-16 to show application icons on AppImage files.
* [Zenwalk GNU Linux](http://www.zenwalk.org/) - Is "AppImage ready" and distributes some applications in AppImage format.

## AppImage developer tools

### Low-level tools

* [appimagetool](https://github.com/AppImage/AppImageKit/releases/tag/continuous) ⭐ 9,414 | 🐛 237 | 📅 2026-07-26 - Converts AppDirs into AppImages.
* [nix-bundle](https://github.com/matthewbauer/nix-bundle) ⭐ 858 | 🐛 58 | 🌐 Nix | 📅 2025-09-01 - Converts Nix derivations into AppImages.

### Build systems

* [appimage-builder](https://github.com/AppImageCrafters/appimage-builder) ⭐ 383 | 🐛 94 | 🌐 Python | 📅 2026-05-05 - Recipe based AppImage creation tool working from source.
* [appimagecraft](https://github.com/TheAssassin/appimagecraft) ⭐ 53 | 🐛 10 | 🌐 Python | 📅 2026-08-19 - Recipe based AppImage creation tool working from source.
* [rules\_appimage](https://github.com/lalten/rules_appimage) ⭐ 39 | 🐛 17 | 🌐 Starlark | 📅 2026-08-22 - Bazel rules to package any lang\_binary target as AppImage.
* [AppImage.cmake](https://github.com/Ravbug/AppImage.cmake) ⭐ 26 | 🐛 0 | 🌐 CMake | 📅 2021-07-25 - CMake script which facilitates generating AppImage executables for Linux.
* [KDE Craft](https://invent.kde.org/packaging/craft) - Build system used by KDE that can produce AppImages and other formats.
* [appimage-tooling](https://gitlab.com/sgclarkkde/appimage-tooling) - Ruby tooling to generate Appimages.

### Deployment tools for compiled applications

* [linuxdeployqt](https://github.com/probonopd/linuxdeployqt) ⭐ 2,468 | 🐛 212 | 🌐 C++ | 📅 2025-10-21 - Deploys dependencies into AppDirs and creates AppImages; for Qt and other compiled applications.
* [go-appimagetool](https://github.com/probonopd/go-appimage/tree/master/src/appimagetool) ⭐ 1,166 | 🐛 134 | 🌐 Go | 📅 2026-06-07 - Tool that deploys dependencies into AppDirs, and converts AppDirs into AppImages (experimental).
* [linuxdeploy](https://github.com/linuxdeploy/linuxdeploy) ⭐ 815 | 🐛 102 | 🌐 C++ | 📅 2026-08-01 - AppDir creation and maintenance tool using plugins.
* [XojoToAppImage](https://github.com/AlwaysOfflineSoftware/XojoToAppImage) ⭐ 5 | 🐛 0 | 🌐 Xojo | 📅 2025-03-10 - Graphical tool for packaging compiled Xojo Linux programs into AppImages.

### Deployment tools for Python applications

* [python-appimage](https://github.com/niess/python-appimage) ⭐ 223 | 🐛 17 | 🌐 Python | 📅 2026-08-02 - Ready to use AppImage distributions of Python (can be modified to include your application).
* [linuxdeploy-plugin-conda](https://github.com/linuxdeploy/linuxdeploy-plugin-conda) ⭐ 31 | 🐛 19 | 🌐 Shell | 📅 2024-09-07 - Bundle Python into an AppDir using a source distribution, Conda, and linuxdeploy.
* [PyAppImage](https://github.com/srevinsaju/pyappimage) ⭐ 29 | 🐛 2 | 🌐 Python | 📅 2021-10-08 - Ultimately simple python-to-appimage bundler.
* [linuxdeploy-plugin-python](https://github.com/niess/linuxdeploy-plugin-python) ⭐ 27 | 🐛 5 | 🌐 Shell | 📅 2024-05-23 - Bundle Python into an AppDir using a source distribution and linuxdeploy.
* [Briefcase](https://briefcase.readthedocs.io/) - Convert Python project into a standalone native application, e.g., using AppImage.
* [pycharm-appimage-support](https://gitlab.com/chezmurray/pycharm-appimage-support) - Deploy Python project as an AppImage directly from the PyCharm IDE.

### Deployment tools for Electron applications

* [electron-builder](https://github.com/electron-userland/electron-builder) ⭐ 14,648 | 🐛 82 | 🌐 TypeScript | 📅 2026-08-23 - Supports AppImage as an output format.
* [Appnativefy](https://github.com/sarweshparajuli/appnativefy) ⭐ 159 | 🐛 18 | 🌐 JavaScript | 📅 2023-02-03 - Create AppImage with embedded Electron browser from any website.
* [electron-forge-maker-appimage](https://github.com/saleae/electron-forge-maker-appimage) ⚠️ Archived - Electron Forge builder for AppImage.

### Deployment tools for Windows applications

* [AppImage For WINE](https://github.com/Hackerl/Wine_Appimage) ⭐ 478 | 🐛 12 | 🌐 Shell | 📅 2021-04-19 - WINE-based AppImages and LD\_PRELOAD based patches to launch WINE from AppImages.
* [wine32-deploy](https://github.com/sudo-give-me-coffee/wine32-deploy) ⭐ 62 | 🐛 8 | 🌐 Shell | 📅 2021-02-11 - Creates AppImages for 32-bit Windows applications that can run on 64-bit Linux systems without multilib installed.
* [ferion11/Wine\_Appimage](https://github.com/ferion11/Wine_Appimage) ⚠️ Archived - AppImage for WINE 32bits from PlayOnLinux, an run on no-multilib systems.
* [GameImage](https://gitlab.com/formigoni/gameimage) - Is a way to package up games with either Wine or an Emulator into a portable AppImage that could be useful for the Steam Deck.

### Deployment tools for Java applications

* [nbPackager](https://github.com/trixon/nbPackager) ⭐ 10 | 🐛 1 | 🌐 Java | 📅 2026-07-26 - Packages NetBeans Platform Application with a JRE for AppImage, Linux, macOS and Windows.

### Deployment tools for .NET Core (Mono) applications

* [PupNet Deploy](https://github.com/kuiperzone/PupNet-Deploy) ⭐ 259 | 🐛 5 | 🌐 C# | 📅 2026-04-12 - Cross-platform deployment utility which publishes your .NET project and packages it as a ready-to-ship installation file in a single step.
* [DotnetPackaging](https://github.com/SuperJMN/DotnetPackaging) ⭐ 131 | 🐛 4 | 🌐 C# | 📅 2026-05-17 - Tool to distribute .NET applications in the AppImage format.
* [.NET Core AppImage example](https://github.com/ppy/osu-deploy/blob/697a49e9602502a2b7a899c0dff5383f6512d5d2/Program.cs#L207-L243) ⭐ 55 | 🐛 2 | 🌐 C# | 📅 2026-06-08 - Example of how to deploy .NET Core (Mono) applications as an AppImage using `dotnet publish -f netcoreapp3.1 -r linux-x64` from within a `.cs` program.
* [Publish-AppImage for .NET](https://github.com/kuiperzone/Publish-AppImage) ⭐ 34 | 🐛 1 | 🌐 Shell | 📅 2023-03-24 - Publish AppImages for .NET applications.

### Deployment tools for Flash applications

* [flash-to-appimage](https://github.com/CredibleOpossum/flash-to-appimage) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2021-08-31 - Script to package a Flash game (`.swf`) into an AppImage.

### Deployment tools for Rust applications

* [Cargo AppImage](https://github.com/StratusFearMe21/cargo-appimage) ⭐ 79 | 🐛 10 | 🌐 Rust | 📅 2025-08-09 - Cargo program that allows you to convert your Rust programs into AppImages.

### Tools to convert from other package formats

* [pkg2appimage](https://github.com/AppImage/pkg2appimage) ⭐ 793 | 🐛 184 | 🌐 Shell | 📅 2025-07-21 - Converts from deb, zip, tar.gz and other formats to AppImage using YAML recipes.
* [arch2appimage](https://github.com/hanzala123/arch2appimage) ⚠️ Archived - Python script to convert any Arch Linux package (official/AUR) to an AppImage.
* [AppImaGen](https://github.com/ivan-hc/AppImaGen) ⭐ 40 | 🐛 0 | 🌐 Shell | 📅 2025-07-15 - Generates an AppImage from Debian or from a PPA of your choice for the previous (unfortunately not the oldest as recommended) and still supported Ubuntu LTS.
* [make-portable](https://github.com/sudo-give-me-coffee/make-portable) ⭐ 38 | 🐛 3 | 🌐 C | 📅 2025-02-10 - Deploys installed application to AppDir, uses strace to fetch all file system calls and copies all accessed files in to AppDir including glibc.
* [flatpak2appdir](https://github.com/sudo-give-me-coffee/flatpak2appdir) ⭐ 32 | 🐛 7 | 🌐 Shell | 📅 2020-05-11 - Turn Flatpak into AppDir which in turn can be turned into AppImage.
* [appimage-bash](https://github.com/valicm/appimage-bash) ⭐ 19 | 🐛 2 | 🌐 Shell | 📅 2025-01-16 - GitHub Action for creating AppImage releases from binaries inside `.tar.gz` archives.
* [Package-to-appimage](https://github.com/CausaPrincipalis71/package-to-appimage) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2022-11-02 - Tool for converting `.deb` and `.rpm` packages into AppImage format by using Docker.
* [Elements](https://github.com/s-zeid/elements) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2020-06-21 - Tool to generate single-file, runc-based AppImages using a minimal (\~3 MB compressed) Alpine Linux rootfs.
* [GMAppImager](https://github.com/samuelvenable/GMAppImager) ⭐ 2 | 🐛 0 | 🌐 Game Maker Language | 📅 2026-06-13 - Graphically Converts GameMaker Studio 2 games to AppImage bundles.
* [appimage2pkg](https://gitlab.com/nixtux-packaging/appimage2pkg) - Repack AppImage and make rpm/deb which does not require FUSE.
* [AppImage cobbler](https://gitlab.com/brinkervii/appimage-cobbler) - Python application that takes strace.log and turns it into a directory suited for an AppImage.

### Metadata tools

* [AppStream MetaInfo Creator](https://www.freedesktop.org/software/appstream/metainfocreator/#/) - More elaborate generator for AppStream MetaInfo files by the author of the AppStream metainfo format.

### QC tools

* [appimagelint](https://github.com/TheAssassin/appimagelint) ⭐ 57 | 🐛 16 | 🌐 Python | 📅 2026-06-23 - Tool to check AppImages for compatibility, best practices etc.
* [appimage-testsuite](https://github.com/aferrero2707/appimage-testsuite) ⭐ 20 | 🐛 3 | 🌐 Shell | 📅 2020-08-05 - AppImage testing environment based on Docker containers for various Linux distributions.

### Continuous integration

* [appimage.yml](https://github.com/iotang/Project_LemonLime/blob/master/.github/workflows/appimage.yml) ⭐ 704 | 🐛 81 | 🌐 C++ | 📅 2026-07-22 - Bigger, more complex example of how to build and upload AppImages using GitHub Actions.
* [GitHub Actions example](https://github.com/probonopd/Zoom.AppImage/blob/master/.github/workflows/main.yml) ⭐ 54 | 🐛 6 | 📅 2025-01-07 - Example of how to upload AppImages built using GitHub Actions to GitHub Releases.
* [build-appimage-action](https://github.com/AppImageCrafters/build-appimage-action) ⭐ 36 | 🐛 10 | 📅 2023-09-13 - GitHub Action for producing AppImages using appimage-builder.
* [jniltinho/packages](https://github.com/jniltinho/packages) ⭐ 7 | 🐛 1 | 🌐 Shell | 📅 2020-05-18 - Drone.io example for producing AppImages using go-appimagetool.
* [Link to the latest build artifact on GitLab CI](https://gitlab.com/linuxappimage/element-desktop/-/jobs/artifacts/master/raw/Element.AppImage?job=run-build) - Example of how to directly link to the latest build artifact on GitLab CI (can be tricky).

### Libraries

* [libappimage](https://github.com/AppImage/libappimage) ⭐ 57 | 🐛 60 | 🌐 C++ | 📅 2025-10-31 - Implements functionality for dealing with AppImage files, written in C++ using Boost.
* [QAppImageUpdate](https://github.com/antony-jr/QAppImageUpdate) ⭐ 28 | 🐛 1 | 🌐 C++ | 📅 2021-10-20 - Qt5 library and plugin for updating AppImages, can be embedded into applications.
* [libzsync-go](https://github.com/AppImageCrafters/libzsync-go) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2022-05-26 - Zsync implementation written in Go that can be used to update AppImages.
* [AppImageServices](https://github.com/azubieta/AppImageServices) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2019-10-07 - D-Bus services providing a high-level interface over the AppImage manipulation libraries for file managers, software centers and other tools.
* [appenv](https://github.com/TheMarlboroMan/appenv) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2026-06-12 - Small C++ library telling where the app data resides and where the user data is by using `readlink("/proc/self/exe")`), thus allowing C++ applications to become relocatable in the filesystem.

### Templates

* [qt-qml-project-template-with-ci](https://github.com/219-design/qt-qml-project-template-with-ci) ⭐ 66 | 🐛 1 | 🌐 QML | 📅 2026-05-11 - Template for a Qt/QML application with batteries included: GitHub CI, automated GUI testing, automatic code-format checks and more. Compiles for Linux (AppImage), Mac, and Android.
* [mini-qml](https://github.com/patrickelectric/mini-qml) ⭐ 46 | 🐛 4 | 🌐 QML | 📅 2020-08-08 - Minimal Qml application template with deployment for Linux (AppImage), Windows, macOS and WebAssembly.
* [Briefcase Linux AppImage Template](https://github.com/beeware/briefcase-linux-appimage-template) ⭐ 23 | 🐛 3 | 🌐 Dockerfile | 📅 2026-07-08 - Cookiecutter template for building Python apps that will run under Linux, packaged as an AppImage.
* [wxWidgetsTemplate](https://github.com/Ravbug/wxWidgetsTemplate) ⭐ 15 | 🐛 0 | 🌐 C++ | 📅 2021-03-23 - Cross-platform application template for wxWidgets C++, with pre-set files and IDE projects, supporting AppImage.
* [qt-hello-world](https://github.com/AppImageCrafters/qt-hello-world) ⭐ 2 | 🐛 0 | 🌐 QML | 📅 2023-09-07 - Qt Hello World project for AppImage creation using appimage-builder.
* [Qt Desktop Template](https://github.com/stemoretti/qt-desktop-template) ⭐ 0 | 🐛 0 | 🌐 C++ | 📅 2023-07-25 - Template for creating Qt Widgets desktop applications with AppImage generation using linuxdeployqt.

## Resources

### Specs

* [AppImageSpec](https://github.com/AppImage/AppImageSpec) ⭐ 93 | 🐛 30 | 📅 2026-04-03 - Official specification for the AppImage format.
* [Desktop Entry Specification](https://specifications.freedesktop.org/desktop-entry-spec/latest/) - Specification for the matadata used inside AppImages.

### Documentation

* [docs.appimage.org](https://docs.appimage.org/) - Official AppImage documentation.
* [appimage-builder.readthedocs.io](https://appimage-builder.readthedocs.io/) - Documentation of appimage-builder, includes tutorials, examples, and more.

### Tutorials

* [Produce an AppImage that bundles everything with go-appimage](https://www.youtube.com/watch?v=XTGn_JqmDu0) - How to make an AppImage that bundles *all* required libraries so that it should run not only on newer, but also on *older* systems than the build system.

### Articles

* [The Background Story of AppImage](https://itsfoss.com/appimage-interview/) - Interview with the creator of AppImage, explaining the key ideas and motivations behind the concept.
* [Flatpak, Snap and AppImage](https://distrowatch.com/weekly.php?issue=20160704#opinion) - Jesse Smith on DistroWatch about AppImage, Flatpak and Snap.
* [Don't Install, Just Copy with klik](https://dot.kde.org/2005/09/16/dont-install-just-copy-klik) - Article from 2005 that gives perspective on how AppImage started, relevant only for historical reasons now.

### Videos

* [AppImage: Portable applications for Linux](https://www.youtube.com/watch?v=nzZ6Ikc7juw) - Official AppImage introduction video by its founder.
* [Comparing Linux Package Formats - Deb, Flatpak, AppImage, etc.](https://www.youtube.com/watch?v=7fPShv-8Z_4) - By Bryan Lunduke.
* [AppImage: Universal Linux Apps, Overview and Thoughts](https://www.youtube.com/watch?v=tMqES2pNxYY) - By Jeremy "Jay" LaCroix, LearnLinuxTV.
* [AppImage system integration on Ubuntu using go-appimaged](https://www.youtube.com/watch?v=L00UjifUEfE) - New appimaged daemon from the go-appimage implementation.
* [Integrate and Manage AppImages with AppImageLauncher](https://www.youtube.com/watch?v=D2WA2zdLvVk) - By Eric Adams.

### Books

* [Mastering Qt 5](https://www.amazon.de/Mastering-Qt-stunning-cross-platform-applications-ebook/dp/B07DH9YK9Q/) - Contains a section on how to package and deploy Qt applications for Linux using linuxdeployqt.

### Blogs

* [Planet AppImage](https://appimage.gitlab.io/planet/) - Blog Aggregator covering all things AppImage.
* [TheAssassin Blog](https://assassinate-you.net/tags/appimage/) - Blog covering AppImage related topics by TheAssassin.
* [AppImage Crafters Blog](https://appimagecrafters.github.io/) - Blog about AppImage creation an usage by azubieta.

### Courses

### Community

* [#AppImage channel on libera.chat](https://web.libera.chat/#AppImage) - Chat where AppImage developers and users hang out, be prepared to stay in the channel for days if you don't get answers immediately.
* [discourse.appimage.org](https://discourse.appimage.org/) - Official AppImage forum for users and application developers.
* [Stack Overflow](https://stackoverflow.com/tags/AppImage) - Questions tagged `[appimage]` on Stack Overflow.
* [r/AppImage/](https://www.reddit.com/r/AppImage/) - AppImage subreddit.

### Miscellaneous

* [AppImage wiki](https://github.com/AppImage/AppImageKit/wiki) ⭐ 9,414 | 🐛 237 | 📅 2026-07-26 - Official AppImage wiki.
* [appdwarf](https://github.com/Phantop/appdwarf) ⭐ 33 | 🐛 0 | 🌐 Shell | 📅 2025-08-08 - A tool to convert an AppDir or an existing AppImage file, either as a local file or from a URL, into a highly compressed portable image using dwarfs.
* [AppImageZip](https://github.com/sagebind/appimagezip) ⚠️ Archived - Experimental pure Rust implementation of the AppImage runtime that uses Zip as the backing file system image.
* [help-wanted](https://github.com/search?q=user%3Aappimage+label%3Ahelp-wanted+state%3Aopen\&type=Issues) - AppImage issues that the AppImage team would like your help with. A great way to get started contributing to the project.

### Related

* [Similar projects](https://github.com/AppImage/AppImageKit/wiki/Similar-projects) ⭐ 9,414 | 🐛 237 | 📅 2026-07-26 - Comparison to other packaging systems.

### Other awesome lists

* [awesome-linuxdeploy](https://github.com/linuxdeploy/awesome-linuxdeploy) ⭐ 57 | 🐛 0 | 📅 2024-10-22 - Awesome list on linuxdeploy.
* [All Awesome Lists](https://github.com/topics/awesome) - All the Awesome lists on GitHub.

### Expired links

* [AppImage-Integrator](https://github.com/w-j-r/AppImage-Integrator) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2022-12-10 - A simple program to integrate AppImages into the Linux desktop written in Qt6.
* [App Outlet](https://app-outlet.github.io/) - Universal app store that works with AppImages, Flatpaks and Snaps.
* [appimage2desktop](https://github.com/me1ting/appimage2desktop) - Creates a desktop file and an icon in the system for an AppImage, nothing else.
* [Get AppImage](https://g.sreve/get-appimage/) - Collection of all AppImages in one website. Great search functionality.
* [AppStream Generator](https://output.jsbin.com/qoqukof) - Very simple generator for AppStream MetaInfo files which application authors can use to add metadata (like descriptions, screenshots, links) to their AppImage.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
