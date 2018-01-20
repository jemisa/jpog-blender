## jpog-blender

A toolset for blender allowing the import and export of Jurassic Park - Operation Genesis models, textures and animations.


### Installation
- Click the `Clone or Download` button at the right, then `Download ZIP`.
- Extract the ZIP you just downloaded and pack the _contents_ of the `jpog-blender-master` folder into a new ZIP file.
- To install with the addon installer in Blender, click `File` > `User Preferences` > `Add-ons` > `Install Add-ons from File` and select your new ZIP file.

### Before You Start
- Make sure you gain writing privileges for the JPOG folders.
- Make a backup of your JPOG files, if you haven't already done so.

### How To Use
#### Importing Models
- `File` > `Import` > `Toshi Model (.tmd)`. Import a TMD model from a JPOG-like folder structure, either directly from the game's folders or from a backup. The default settings should be fine. Refer to the tooltips of the import options for further information.
#### Exporting Models
- `File` > `Export` > `Toshi Model (.tmd)`. The default settings should be fine. To export new animations, turn on `Export Anims` and `Pad Anims`.
#### Resizing
- Warning: Needs animations to be exported for ideal results! It will do _something_ without new animations, but won't be perfect.
- Select the armature in object mode, scale it to the desired size and press `Apply Scale to Objects and Animations` in the tool shelf.

### Known Limitations
- Animations break other animals using the same TKL file.
- Bug: Support for models rigged to more than 28 bones is implemented, but does not work properly and results in blue flashing models.

### Credits
- Equinox of https://github.com/OpenJPOG for file format specification and support
- Andres James http://tresed.trescom.org/jpog/ for ConvertCCT source code and original file format specification
- JPOG was created by Blue Tongue Entertainment for Universal Interactive.
