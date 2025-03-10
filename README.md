<img width="281" alt="available" src="https://user-images.githubusercontent.com/59709552/121570145-96d76f80-c9ef-11eb-8e09-76e0983f7af8.png">

# AppearOnline
![version](https://img.shields.io/pypi/v/AppearOnline)
![status](https://img.shields.io/pypi/status/appearonline?label=Development%20Status)
![maintained](https://img.shields.io/maintenance/yes/2021)
![GitHub last commit](https://img.shields.io/github/last-commit/gansel51/appear-online)
![maintainer](https://img.shields.io/badge/Maintainer-gansel51-informational)
![license](https://img.shields.io/pypi/l/appearonline)

The [AppearOnline](https://pypi.org/project/appearonline/) project is intended to be run when you step away from your computer. From going to the bathroom to running errands, there are many reason why people may step away from their computer but don't want their computer to turn off or show that they are away. AppearOnline simulates mouse movement and keyboard usage to keep your computer appearing active! Users of Microsoft Teams will appear available while this program is running.

## Installation

### PyPi

Installation is available via PyPI using `pip install appearonline`.

### GitHub

Installation is available 2 ways via GitHub releases or by cloning the project using the command `git clone https://github.com/gansel51/appear-online.git`.

## Supported Operating Systems

The PyPI installation of this package is currently only supporting MacOS and WindowsOS. Adding support for Linux systems remains a top priority for the package maintainers. However, Windows and Linux users can install this project from GitHub.

## Requirements

Users that install from PyPI via `pip install appearonline` will have the dependent libraries downloaded automatically.

Users that dowload this package via GitHub should install the requirements by installing their operating system's `requirements.txt` file. This can be done via the command `pip install -r mac-requirements.txt`. Supported operating systems are MacOS, Windows, and Linux.

### MacOS Security and Privacy Settings

MacOS users may initially be prompted to allow accesibility access to their IDE or terminal. For this project to work, accessibility must be granted. To do so, go to System Preferences -> Security & Privacy -> Accessibility and add the IDE or terminal you are using to run the program. This will only need to be done once per application used.

## Use

If installed from PyPi, use the command `appearonline --runtime X` where `X` is the number of minutes for the program to run. This parameter is optional, and will default to 60 minutes if not specified.

If installed from GitHub, use the command `python __main__.py --runtime X` where `X` is the number of minutes for the program to run. As above, this parameter is optional and will default to 60 minutes when not specified.

To quit the package before the runtime has expired, use the keyboard interrupt `ctrl + c`.

Like this project? [Show your support!](https://www.buymeacoffee.com/gansel51)
## License

This project is made available under the MIT license. No warranty is provided for users of this product, nor are the authors liable for any issues arising from the use of this project. See the license for more information and fair usage information.
