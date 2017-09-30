## OpenRazer_GameOflife
### Run Game of Life on your favourite Razer Keyboard!

#### Requirements:

- python-notify2, available on AUR
- openrazer-meta, available on AUR
- Python 3.x
- NumPy library, available via pip

After setting all this up, if you didn't do already, run this command:

  sudo gpasswd -a <YOURUSERNAME> plugdev

and reboot your system in order to let the OpenRazer Driver to run properly.

> All this code is tested under Arch Linux, it should also work in other distros!


### Usage:

Run the game:

```python main.py```

Restore keyboard after usage:

```python main.py reset```

#### Related Projects, Infos and Links:

[My Python GameOfLife implementation]("https://github.com/marcioz98/pygameoflife")

[OpenRazer Website]("https://openrazer.github.io/")
