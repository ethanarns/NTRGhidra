# NTRGhidra
A Nintendo DS Loader for Ghidra

![NTRGhidra a Nintendo DS Loader for Ghidra](https://user-images.githubusercontent.com/16199912/56060896-12690380-5d36-11e9-802e-8c7e70cd481e.png)

# License
NTRGhidra is released under the ![Apache License 2.0](https://github.com/pedro-javierf/NTRGhidra/blob/master/LICENSE).

# Contributing & Support
* Fork and pull request to contribute, feel free to open issues suggesting feautures or reporting bugs. It is recommended to follow the issue templates.
* Support by starring the project.

# Features
See [here](https://github.com/pedro-javierf/NTRGhidra/projects/1)

# Installation
If you just want to install the loader into a existing Ghidra installation:

1. Download the .zip from releases OR build the project.
2. Put the .zip into the GHIDRA_INSTALL_DIR/Extensions/Ghidra folder
3. In the initial window (not the Code Browser), open the File menu, and select Install Extensions. Click the small 'plus' icon in the top right of the window, and select the extension zip file downloaded. This should add an entry into the extensions list. Make sure it is checked and click OK.
![Step 1](install1.png)
![Step 2](install2.PNG)
4. Restart Ghidra.

# Source and Build
Provided is an Eclipse project to debug and build the loader. You must have a Ghidra installation as well as the Ghidra Eclipse extension.

To export a build of the project in Eclipse select File > Export and then choose Ghidra > Ghidra Module Extension. You can then use a local Gradle installation or an online build.

# Acknowledgements
* Special thanks to [gbatek](https://problemkaputt.de/gbatek.htm) for ds technical info
* Thanks to Gericom for the original C# Header and ARM9 decompression code from EFE(Every File Explorer), as well as for testing.

# Others
For reference and tutorials about Ghidra loaders and how to write them, you may want to read:
* [Tutorial: Writing a Ghidra loader](https://pedro-javierf.github.io/devblog/tutorialwritingaghidraloader/)
* [Advanced Ghidra Loader: labels, overlays and Function ID](https://pedro-javierf.github.io/devblog/advancedghidraloader/)
