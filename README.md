# VL.Devices.StreamDeck
A package for using [Elgato StreamDeck](https://www.elgato.com/us/en/p/stream-deck-mk2-black) button display in VL.

## Using the library
In order to use this library with VL you have to install the nuget that is available via nuget.org. For information on how to use nugets with VL, see [Managing Nugets](https://thegraybook.vvvv.org/reference/libraries/dependencies.html#manage-nugets) in the VL documentation. As described there you go to the commandline and then type:

    nuget install VL.Devices.StreamDeck

Once the VL.Devices.StreamDeck nuget is installed and referenced in your VL document you'll see the category *StreamDeck* under *Devices* in the nodebrowser. 

Demo is available via the Help Browser! For now, this is tested only with the Classic StreamDeck (5x3 Buttons). If does (not) work with other devices, please let me know.

## Credits
Library is based on the nice [StreamDeckSharp](https://github.com/OpenMacroBoard/StreamDeckSharp) project, version 3.2.0. 

## License
MIT