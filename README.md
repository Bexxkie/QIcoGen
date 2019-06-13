# QIcoGen                                                                                 

Version: 2.0

Initial Release: 2019-may-01

Author: BrianKG (AKA BEXXKIE)


Description:
Convert images to icons and apply them to a folder 

Example:
To create an icon for folder 'a'
Place an image inside folder 'a'
Drag and drop the image file from folder 'a' onto QIconGen.py
The script will generate an icon from the image and generate a desktop.ini file inside folder 'a'
The folder will now have the icon generated applied.

To use thumbnails the windows cache must be forcibly updated
Place the file forceUpdate.bat into the root directory folder 'a' is located in and run it.
The directory should look like this  Root/ a | forceUpdate.bat
forceUpdate.bat will update anything within the same directory
