<p align="center">
	<img src="logo.png" width="376" height="128" alt="Winlator Logo" />  
</p>

# WinlatorMali

Winlator is an Android application that lets you to run Windows (x86_64) applications with Wine and Box86/Box64.

Winlator By [BrunoSX](https://youtube.com/@brunodev85?si=RU9xw_ES_AEkE-Om)
 Box64,86 By [PtitSeb](https://youtube.com/@ptitseb123?si=P8xGe23ngzEXA0X1)
 Modded By [Me](https://youtube.com/@emuone24?si=je0MMb68WyyJdnSa)

# Warning ⚠️ 

Turnip,DXVK And Other Things That Are Not Related To Non Snapdragon Devices Are Removed In This Fork

# Installation

1. Download and install the APK from [GitHub Releases](https://github.com/Fcharan/WinlatorMali/releases)
2. Launch the app and wait for the installation process to finish

# Useful Tips

- If you are experiencing performance issues, try changing the Box64 preset to `Performance` in Container Settings -> Advanced Tab.
- For applications that use .NET Framework, try installing `Wine Mono` found in Start Menu -> System Tools.
- If some older games don't open, try adding the environment variable `MESA_EXTENSION_MAX_YEAR=2003` in Container Settings -> Environment Variables.
- Try running the games using the shortcut on the Winlator home screen, there you can define individual settings for each game.
- To speed up the installers, try changing the Box64 preset to `Intermediate` in Container Settings -> Advanced Tab.
- To improve stability in games that uses Unity Engine, try changing the Box64 preset to `Stability` or in the shortcut settings add the exec argument `-force-gfx-direct`.

# Credits and Third-party apps
- Ubuntu RootFs ([Focal Fossa](https://releases.ubuntu.com/focal))
- Wine ([winehq.org](https://www.winehq.org/))
- Box86/Box64 by [ptitseb](https://github.com/ptitSeb)
- PRoot ([proot-me.github.io](https://proot-me.github.io))
- Mesa (Turnip/Zink/VirGL) ([mesa3d.org](https://www.mesa3d.org))
- DXVK ([github.com/doitsujin/dxvk](https://github.com/doitsujin/dxvk))
- VKD3D ([gitlab.winehq.org/wine/vkd3d](https://gitlab.winehq.org/wine/vkd3d))
- D8VK ([github.com/AlpyneDreams/d8vk](https://github.com/AlpyneDreams/d8vk))
- CNC DDraw ([github.com/FunkyFr3sh/cnc-ddraw](https://github.com/FunkyFr3sh/cnc-ddraw))

Many thanks to [ptitSeb](https://github.com/ptitSeb) (Box86/Box64), [Danylo](https://blogs.igalia.com/dpiliaiev/tags/mesa/) (Turnip), [alexvorxx](https://github.com/alexvorxx) (Mods/Tips) and others.<br>
Thank you to all the people who believe in this project.
