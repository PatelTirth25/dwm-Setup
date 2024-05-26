# My Custom DWM Setup

This repository contains my customized versions of DWM (Dynamic Window Manager), dmenu, st (simple terminal), and dwmblocks. Additionally, it includes scripts required for dwmblocks, which are located in the `bin` folder.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation

### Clone the Repository

First, clone the repository:

    git clone https://github.com/PatelTirth25/dwm-Setup.git
    cd dwm-Setup

### Build and Install DWM

Navigate to the dwm directory and install:

    cd dwm
    sudo make clean install

### Build and Install dmenu

Navigate to the dmenu directory and install:

    cd ../dmenu
    sudo make clean install



### Build and Install st

Navigate to the st directory and install:

    cd ../st
    sudo make clean install


### Build and Install dwmblocks


Navigate to the dwmblocks directory and install:


    cd ../dwmblocks
    sudo make clean install

### Scripts for dwmblocks

The required scripts for dwmblocks are located in the bin folder. Make sure they are executable:

    cd ../bin
    chmod +x *

## Usage

- To start using DWM, you need to have a display manager or configure your .xinitrc to start DWM. Here’s an example of how to start DWM using .xinitrc:

    ```bash
    exec dwm

- To start dwmblocks, ensure the scripts in the bin folder are executable and properly configured to your needs. Then, add the following to your DWM startup script or .xinitrc:

    ```bash
    dwmblocks &

## Credits
- [suckless](https://suckless.org)
- [dwmblocks](https://github.com/torrinfail/dwmblocks)
