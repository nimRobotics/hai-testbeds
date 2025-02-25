# CREW Human-AI Teaming testbed

[PDF version](https://nimrobotics.github.io/hai-testbeds/docs/crew.pdf)

![CREW environment](docs/crew.png "Title")

CREW is a platform designed to facilitate Human-AI teaming research, engage collaborations from multiple scientific disciplines, with a strong emphasis on human involvement. It includes pre-built tasks for cognitive studies and Human-AI teaming with expandable potentials from our modular design. Following conventional cognitive neuroscience research, CREW also supports multimodal human physiological signal recording for behavior analysis. ([source](https://generalroboticslab.github.io/crew-docs/index.html)).

This platform supports Windows, macOS, and Linux. However, macOS prebuilt game environments does not work and will need to be rebuilt.

## Installation

Compreshensive installation guide can be found [https://generalroboticslab.github.io/crew-docs/getting_started/install.html](https://generalroboticslab.github.io/crew-docs/getting_started/install.html), make sure to follow them closely. Please reach out to Aakash if you face any issues.

Once everything is installed, we can run the game with following steps:

1. Lauch [docker desktop](https://www.docker.com/products/docker-desktop)
2. Navigate to `crew-dojo/Nakama/` and run `bash run.sh`. This should run the nakama server and it is viewable at [http://127.0.0.1:7351](http://127.0.0.1:7351) The default username is `admin`. Default password is `password`.
3. Activate the conda environment with `conda activate crew`. If you face any issues make sure to add the path to the conda environment to your `~/.bash_profile` with `echo export PATH="/Users/nimrobotics/.local/bin:$PATH" >> ~/.bash_profile` and then run `source ~/.bash_profile`
4. Navigate to `crew-dojo/Builds` and a game of your choice, double click to run OR `open Unity.app` from the terminal.
5. To change game parameters, you can run `open Unity.app --args -DisableFirstCamera -DisableAccumuCamera` or `open Unity.app --args -DojoRecording -DojoRecordingFile YOURFILEPATH`. See [here](https://generalroboticslab.github.io/crew-docs/dojo/components/games/nvn_hide_and_seek.html) for a list of all possible parameters.