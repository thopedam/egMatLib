# egMatLib - A Material Library for Houdini

A Material Library for Houdini Mantra, Redshift and Arnold

![Interface](https://github.com/eglaubauf/egMatLib/blob/main/img/MatLib.png)


### Features:

- Lightweight (Houdini-native) storing and loading of node networks
- Save Redshift Material Builders, Principled Shaders,  Mantra Materialbuilders and Arnold Materialbuilders
  - Inside this nodes all objects are supported
- Favorites
- Adding and removing of categories
- Searchable tags (use t: as a modifier ) and material-names
- Open database (.json)
- Material Preview
- open HDAs for Redshift and Mantra for custom preview-images
- Deletion of entries from the database (deletes also from disk)
- Edit multiple materials at the same time via the Details-Pane
- Easy adjustable custom preview and rendersize
- ACES 1.2 support (Redshift Native)
- Right Click Menus for adding materials quickly from the network pane
- Importing to current network location (pwd()/matnet)
- Double Click or right click for importing Materials into the scene
- Easy installation with packages (see below)


### Compatibility

 - Tested on 18.5.696 on Windows 10 and Ubuntu 20.04
 - Houdini Indie only
 - Tested with Redshift 3.0.57
 - Other builds might work
 - The repo will be updated regularly
 - Python 2 support
 - Python 3 support

### Installation
- Download or Clone this repository and unzip
- Copy the provided `MatLib.json` to your `houdini18.5/packages` folder
- Edit the line `/home/elmar/MatLib` to the location of your downloaded folder, e.g.: `G:/Git/MatLib`
- Start Houdini

### Usage
 - Open Pane (MatLib)
 - On first usage the pane will prompt you for a directory:
   - Choose a safe directory --> this is where all your data will be stored
   - You also can change this directory later from Library/Preferences
 - Use buttons for import/export from library
 - Right Click on Redshift Material Builder, Principled Shader or Material Builder to store a material
 - Double Click on a Material in MatLib-Pane to import
 - Use the table view to the right for edit of currently seleted material
 - Search Function also can search tags with t:*yoursearchstring*


### Additional
- You can move the directory by hand on disk if you need to
- Do not (!) edit the .json file by hand if not needed
  - you have been warned ;)


### Contact & License

- Found a bug? please open an issue or contact me directly via Twitter
- Twitter: @eglaubauf
- Feel free to support me via gumroad https://elmeier.gumroad.com/l/bsghA
