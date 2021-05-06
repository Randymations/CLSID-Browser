# CLSID-Browser
A simple program to browse functional CLSIDs within Windows

## Functions
- Allows the user to access (some normally inaccessible) Windows menus through CLSIDs
- Has functionality for creating batch files to access the CLSIDs directly

## Use
The exe can be downloaded and run as-is. Optionally, if you'd prefer to compile it yourself, the Python module [Pyinstaller](https://www.pyinstaller.org/) was used with the command `pyinstaller -F -i "icon/file/path" "CLSID Browser.py"`. An icon file can be found [here](https://github.com/Randymations/CLSID-Browser/blob/main/icon/CLSID.ico) and a general tutorial can be found [here](https://www.youtube.com/watch?v=lOIJIk_maO4).

## Notes
- Program contains a hard-coded list of CLSIDs
- A complete list of CLSIDs on your system can be found under `HKEY_CLASSES_ROOT\CLSID` within the registry
- List was adapted from [this article](https://www.tenforums.com/tutorials/3123-clsid-key-guid-shortcuts-list-windows-10-a.html)
- Not all CLSIDs were tested and not all work
- I personally find option 91 particularly useful
