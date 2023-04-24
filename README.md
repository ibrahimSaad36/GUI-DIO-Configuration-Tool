# AVR Configuration Tool Using Python 3.8.10 and PySide2
This tool is used to generate hader files which contain the configuration of pins (Output: high or low, Input: pull up, high impedance)

## Features:
* User friendly and easy to use design.
* By default all configuration of all pins is output low.
* Easily choose the path of file using a file chooser.
* You can save your configuration to an XML file so you can load it easily later.
* Checking if this XML file is modified by another source not the program, and in which line the modification is done.
* Date modified and author are added to the generated file, author is provided from os library to know the current logged in user

## Next Updates:
* Text field for each pin will be added so user can cofigure the pin name.
* The user will be able to add a description about the file in the generated file.
* The user will be able to modify deafult configuration for all pins using one click.
* The UI design will be edited to be responsive and not only a fixed size window.
* The XML file mode will be changed to read only mode after changing configurations by GUI, so any one else will be not able tochange the structure of the file.

## Requirements to Use This Program:
* First insall Python (Version: 3.8.10), and note that using another version may cause some ERRORS,
        [use this link to download the required version](https://www.python.org/downloads/release/python-3810/)
* Install PySide2, run these commands in cmd:

        python -m pip install --upgrade pip
        pip install PySide2
    
* Then you can simply use this program and ENJOY!

## Output
* There is sample output attached to this repo (Sample Output: sample XML file and sample of generated header file)
* In image below sample of default configuration loaded at the start of the program:

    ![default-config](https://user-images.githubusercontent.com/118214245/213980551-cd304600-9999-4769-92cc-85202ad725a9.png)

### Very Important Notes:
* This program was a practice on tooling course handeled by **Eng. Omar Soliman** in **9 Month Diploma - ES Track held by ITI** so, I want to thank him so much.
* This program is developed using free tools such as PySide2, Qt Designer and Python programming language so thanks to all of free and open source tools which make our life easier.
