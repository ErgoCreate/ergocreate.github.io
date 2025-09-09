---

layout: post

title:  "Getting started"

categories: [Tutorials]

---

## Installation

>*SimpleKivy has only been tested on* ***Windows*** *and on Python >= 3.10. Support this project if you are interested on Linux and MacOS implementations.*
{: .prompt-info }

### Kivy
You need to install the `2.3` version of `Kivy`. Installation instructions can be found [here](https://kivy.org/doc/stable/gettingstarted/installation.html).

### SimpleKivy
You can install the latest development version with:
``` bash
pip install git+https://github.com/ErgoCreate/SimpleKivy.git
``` 

>**This project is in the early stages of development and is expected to change in the future. Use it at your own risk.**
{: .prompt-warning }

### Optional modules
#### New features support
##### Image
- New `copy/paste/save` functionalities introduced in **SimpleKivy** that require the following modules to work:
``` bash
pip install pyperclipimg, requests, pillow
``` 

- New ***svg source*** support introduced in **SimpleKivy** that requires the following modules to work:
``` bash
pip install CairoSVG
``` 

##### Camera
- A new and improved `Camera` widget has been introduced in **SimpleKivy** that requires the following modules to work:
``` bash
pip install opencv-python
``` 

### Next steps
Now that you have everything ready, you can: 
- [Check the documentation.](/documentation)
