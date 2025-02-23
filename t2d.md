# T2D Human-AI robot teaming testbed

[PDF version](https://nimrobotics.github.io/hai-testbeds/docs/t2d.pdf)

![T2D environment](docs/t2d.png "Title")

The T2D Human-AI Robot Teaming testbed is a testbed for Human-AI Robot Teaming. The environment is designed in 3D with urban search and rescue in emergency environment. The robot can controlled with Wizard of Oz interface. ([source](https://dl.acm.org/doi/abs/10.1145/3610978.3640649)). The original tasked is aimed at three membered team (mission commander, robot navigator, safety officer) but can be played any number of agents.

This test environment only supports Windows out of the box. However, if needed it can be built for macOS and Linux.

## Installation

- No installation is required. The testbed is available for download from the [here](https://uwprod-my.sharepoint.com/:f:/g/personal/aakash2_wisc_edu/Evzo1Q_5RXlNsgCjv97ZiioBl3vu7bUQQs1nrRLx3dWdmQ?e=a9gB2Z) (Note: this link is only accessible with a UW-Madison email address).
- Prebuilt trials are availbe in `prebuilt` directory and can be run with double clicking `test3.exe` file withing a trial.
- Several trials are provided (each trial differs in the position of the victims).
- One agent will need to create the room by clicking `create` button and other agents can join the room by clicking `join` button (make sure the created and joined rooms have same names)
- There are two settings, the agent can be human (option 1) or robot (option 2). And the hazard level can be visible (Assistance ON) or invisible (Assistance OFF).
- The agent can be controlled with the keyboard (WASD keys or arrow keys).
- The game can be ended by closing the window (press windows key and right click on the window in the taskbar and click close window).
- Game logs are saved in the `LOGS` directory at the desktop.

## Usage

