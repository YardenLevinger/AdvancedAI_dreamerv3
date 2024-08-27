# AdvancedAI - Ex1

A reprocessing of [DreamerV3][paper], a scalable and general reinforcement
learning algorithm that masters a wide range of applications with fixed
hyperparameters.

For reading the original [README.md](https://github.com/YardenLevinger/AdvancedAI_dreamerv3/blob/main/original_README.md)

For accessing My reprocessing results: https://drive.google.com/drive/folders/1U2Kqf_41mbm4jKDVgQy-bScwhvT2i_6u?usp=drive_link

## Reprocessing

Reprocessing Commands:

```sh
python dreamerv3/main.py --logdir ./Logs/dmc_acrobot_swingup --configs dmc_vision_acr --task dmc_acrobot_swingup
```
```sh
python dreamerv3/main.py --logdir ./Logs/dmc_vision__dmc_walker_wak --configs dmc_vision --task dmc_walker_walk
```
```sh
python dreamerv3/main.py --logdir ./Logs/dmc_vision__dmc_cheetah_run --configs dmc_vision --task dmc_cheetah_run
```

## Open Reprocessing Results

1. install tensorboard through pip
2. run the command (example for dmc_vision__dmc_cheetah_run):
```sh
tensorboard --logdir=./Logs/dmc_vision__dmc_cheetah_run
```