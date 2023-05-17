# easykoi

`easykoi` is a SoundFont-based re-implementation of [`herakoi`](https://github.com/lucadimascolo/herakoi) — a motion-sensing sonification experiment. 

## Installation
The sound synthesis in `easykoi` makes use of a SoundFont2 specifications and requires an external synthesis driver, `fluidsynth`.
If you are running `easykoi` within a `conda` environment, you can install `fluidsynth` by running

```
conda install -c conda-forge fluidsynth
```

If you are on Windows, you can also try with the installer on the [`fluidsynth` release](https://github.com/FluidSynth/fluidsynth/releases) page.


Then, to install `easykoi`: 

```
git clone https://github.com/lucadimascolo/easykoi.git
cd easykoi
python -m pip install -e .
```
