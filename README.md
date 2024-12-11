# Uippao Meta Packages

This repository contains my custom meta packages for Arch Linux and other Arch-based systems. I've mainly intended this for personal use, but if you find these useful, feel free to do as you please with them. Just remember to use at your own risk, as they may contain a number of bugs and oversights. These packages bundle together software that I think is useful to install in a single meta package, even if they may not always make sense to anyone else. They are naturally tailored to my preferred configurations.

## Currently Available Meta Packages

- **`plasma-uippao-meta`**: A custom meta package for the KDE Plasma desktop environment, to get you up and running with a Plasma desktop quickly and efficiently. Contains software not related to the DE itself, but are my preferences for a usable desktop.

## Installation

### 1. Clone the repository (if you plan to install multiple packages)

If you want to install multiple meta packages from this repository, it's recommended to clone the entire repository:

```bash
git clone https://github.com/Uippao/uippao-meta-packages.git
cd uippao-meta-packages
```

Then, cd into the desired package folder and build it with makepkg:

```bash
cd plasma-uippao-meta
makepkg -si
```


### 2. Download and install a single package using curl

If you only need to install a single package, you can use curl to download the PKGBUILD file and install it directly:

```bash
curl -LO https://github.com/Uippao/uippao-meta-packages/raw/main/plasma-uippao-meta/PKGBUILD
cd plasma-uippao-meta
makepkg -si
```

Remember to replace `plasma-uippao-meta` with the name of the package you're installing!
