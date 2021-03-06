# How to install Mods on Mac:

## Prerequisites

Download and install [Mono Project](https://www.mono-project.com/download/stable/)

## Installation

From a terminal run:
1. `cp QmodManagerMac/* ~/"Library/Application Support/Steam/steamapps/common/Subnautica/Subnautica.app/Contents/Resources/Data/Managed"`
1. `cd ~/"Library/Application Support/Steam/steamapps/common/Subnautica/Subnautica.app/Contents/Resources/Data/Managed"`
1. `mono QModManager.exe` - Note: You may receive an error stating that the Presentation Framework is missing, don’t worry about this error because this is not a Windows OS that requires the Presentation Framework.
1. `mkdir ~/"Library/Application Support/Steam/steamapps/common/Subnautica/QMods"`

## Usage

Place all mods you wish to use in `~/"Library/Application Support/Steam/steamapps/common/Subnautica/QMods"`

## Testing

To test your installation, try the [Custom Load Screen](https://www.nexusmods.com/subnautica/) mod.

# Known issues:

1. Subnautica Map Mod DOES NOT WORK.  It requires DX11 or DX12 and mac only supports OpenGL.
1. If you have QMods previously installed, you must uninstall and install via the above instructions.

# Developers

These files were created by cloning the existing DLL files, editing them in VisualStudio, and changing the built in path directories to be Mac specific.
