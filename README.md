This is a tool that lets you use MacBook Pro Retina's highest and unsupported resolutions.
As an example, a Retina MacBook Pro 13" can be set to 3360×2100 maximum resolution, as
opposed to Apple's max supported 1680×1050. It is accessible from the menu bar.

![rdm-screenshot](screenshot.png)

You should prefer resolutions marked with ⚡️ (lightning), which indicates the resolution
is HiDPI or 2× or more dense in pixels.

For more practical results, add RDM.app to your Login Items in **System Preferences ➡ Users & Groups ➡ Login Items**.
This way RDM will run automatically on startup.

This version has integrated generator/editor of display override plist (see https://comsysto.github.io/Display-Override-PropertyList-File-Parser-and-Generator-with-HiDPI-Support-For-Scaled-Resolutions/), which allows to add custom scaled resolutions. System Integrity Protection should be disabled to edit the resolution list. To get a HiDPI resolution, you should specify 2x more pixels height and width and check HiDPI checkbox.

This is a fork of https://github.com/avibrazil/RDM.

Code for toggling display mirroring is taken from https://github.com/fcanas/mirror-displays.

Requires macOS 10.10 or higher for running, Xcode 10 for building. For older systems use the original version.

Downloads my release ➣ [RDM.zip](https://github.com/chris1111/RDM/releases/tag/V2.3.1)
