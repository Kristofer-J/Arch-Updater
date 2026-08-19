# Arch-Updater

A simple Arch Linux updater with `--noconfirm` flags. It can update your system using **pacman**, **yay/AUR**, and **Flatpak**.

## Installation

1. Download the [`update-all`](https://github.com/Kristofer-J/Arch-Updater/blob/main/update-all) file from this repository.

2. Make the file executable:

```bash
chmod +x update-all
```

3. Move it to your local binary directory:

```bash
mv update-all ~/.local/bin/
```

4. You can now run the updater from anywhere in your terminal with:

```bash
update-all
```

### If `update-all` doesn't work immediately

Make sure the file is executable before running it:

```bash
chmod +x update-all
```

If you've already moved it to `~/.local/bin/`, you can run:

```bash
chmod +x ~/.local/bin/update-all
```

Then try:

```bash
update-all
```

If it still doesn't work, restart your terminal so your shell can pick up `~/.local/bin` correctly.


After that, simply run:

```bash
update-all
```

and let it handle your updates.

## Features

* Updates Arch packages with `pacman`
* Updates AUR packages with `yay`
* Updates Flatpak packages
* Uses `--noconfirm` to make the update process quick and straightforward

> **Note:** This project was made with the help of AI.
