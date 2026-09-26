# Template project for Godot
This is the template I use for all of my projects. Currently, the latest-stable this repo is for is Godot 4.7.2.

This template has directions to project settings in it, as well as directions to my preferred editor settings. Feel free to pick and choose :)

Below the editor settings, I'll tell you which programs I have installed and what resources I use to get assets if I don't create them myself. 

I focus on being able to work on my (Apple Silicon) MacBook, my Windows machine and my Linux machine so cross-compatible programs are very important to me.


## Editor settings
All the settings I changed are listed. There aren't that many editor settings I changed, but I feel like they are quite important to change.

On the top right, enable advanced settings.
- Interface
  - Editor
    - Editor Language -> [en] English
- Asset Store
- Network
  - Connection
    - Network Mode -> Online
- Docks
- FileSystem
  - File Dialog
    - Show Hidden Files -> On
- Text Editor
  - Behavior
    - Files
      - Trim Trailing Whitespace on Save -> On
      - Autosave Intervall Secs -> 300
- Editors
- Export
- Run
- Debugger
- Version Control
- Input
- Project Manager

## Project settings
Also enable Advanced Settings here.

The settings under Debug/GDScript may cause you to not be able to use code examples that do not use static typing. But in production, static typing is **highly** recommended for various reasons. Be that code maintainability, debugging or performance. Read more in the Godot wiki (https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/static_typing.html).

I recommend looking through the settings yourself as well.
- Application
  - Config
  - Run
    - Max FPS: 60 (change this to 0 if you debug performance. Otherwise, I am limiting my FPS for battery usage reasons)
  - Boot Splash
- Accessibility
- Display
- Animation
- Audio
- Physics
- Debug
  - GDScript
    - Untyped Declaration: Error
    - Unsafe Property Access: Error
    - Unsafe Method Access: Error
    - Unsafe Cast: Warm
    - Unsafe Call Argument: Error
- Compression
- Rendering
  - Lights and Shadows
    - Use Physical Light Units: On
- Internationalization
- GUI
- Input Devices
- Navigation
- Network
- Threading
- XR
- Memory
- Editor
- Layer Names
- FileSystem

## Programs to install
I prefer using `brew` for installing programs on macOS. On Linux, I use CachyOS which, for me, is the perfect compromise between the flexibility of Arch and ease of use. I should probably use something more stable, like Debian, Mint, Ubuntu or Fedora, but I have not been burned yet. On Windows, I install programs normally, via a downloaded .exe. I am aware of winget and chocolatey.

git (https://git-scm.com/install/) and git-lfs (https://git-lfs.com)

A GUI client of your choosing, for me, at the moment, that is SourceGit (https://github.com/sourcegit-scm/sourcegit)

The Godot engine (https://godotengine.org/download)

Trenchbroom (https://trenchbroom.github.io) (for use in Godot, you also need the plugin func\_godot (https://github.com/func-godot/func_godot_plugin) in order to be able to use the .map files in your project)

Blender (https://www.blender.org/download/)

Krita (https://krita.org/de/download/)

Gimp (https://www.gimp.org/downloads/)

LMMS (https://lmms.io/download) I use the alpha version 1.3.0-alpha2 since that version came out September 6th 2026 and has Apple Silicon support. The last stable version is from July 4th 2020 (!). I do not yet have experience with LMMS, but I am willing to try it out.

Ardour (https://community.ardour.org/download) It's a DAW. FOSS and cross platform. Good enough for me.

I am not sure whether to use LMMS or Ardour or both at this point, I don't know which I need as Audio is my biggest weakness, to be honest. Just listed them because I may use them and liked the look of them.

Audacity (https://www.audacityteam.org/download/) (Without MuseHub)

OBS-Studio (https://obsproject.com/download)

Davinci Resolve (https://www.blackmagicdesign.com/products/davinciresolve) - Only non FOSS Software I really use. But it's cross platform and a one time purchase, so I am kinda okay with that.


## Resources to use
https://freesound.org/  - Sound effects. Just make sure to not break the licensing term of the sounds you download.

https://kenney.nl/ - Assets, Tools, Starter Kits. Quite a lot of them CC0. Feel free to check on the website and make sure to consider donating. Not affiliated at all, just really really love the resources provided.
