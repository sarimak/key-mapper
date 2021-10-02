<p align="center"><img src="data/key-mapper.svg" width=100/></p>

<h1 align="center">Key Mapper</h1>

<p align="center">
  An easy to use tool to change the mapping of your input device buttons.<br/>
  Supports mice, keyboards, gamepads, X11, Wayland, combined buttons and programmable macros.<br/>
  Allows mapping non-keyboard events (click, joystick, wheel) to keys of keyboard devices.
</p>

<p align="center"><a href="readme/usage.md">Usage</a> - <a href="readme/macros.md">Macros</a> - <a href="#installation">Installation</a> - <a href="readme/development.md">Development</a> - <a href="#screenshots">Screenshots</a> - <a href="readme/development.md">Examples</a></p>

<p align="center"><img src="readme/pylint.svg"/> <img src="readme/coverage.svg"/></p>

## Installation

##### Manjaro/Arch

```bash
pacaur -S key-mapper-git
```

##### Ubuntu/Debian

Get a .deb file from the [release page](https://github.com/sezanzeb/key-mapper/releases)
or install the latest changes via:

```bash
sudo apt install git python3-setuptools gettext
git clone https://github.com/sezanzeb/key-mapper.git
cd key-mapper && ./scripts/build.sh
sudo apt install ./dist/key-mapper-1.1.0.deb
```

key-mapper is now part of [Debian Testing](https://packages.debian.org/testing/key-mapper)

##### pip

```bash
sudo pip install git+https://github.com/sezanzeb/key-mapper.git
sudo systemctl enable key-mapper
sudo systemctl restart key-mapper
```

If it doesn't seem to install, you can also try `sudo python3 setup.py install`

## Screenshots

<p align="center">
  <img src="readme/screenshot.png"/>
</p>

<p align="center">
  <img src="readme/screenshot_2.png"/>
</p>
