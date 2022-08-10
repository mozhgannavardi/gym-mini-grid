# Minimalistic Gridworld Environment (MiniGrid)

## Create a virtual environment:

```
conda create -n minigrid python=3.8
conda activate minigrid
pip install -r req-env.txt
cd gym-minigrid
pip3 install -e .
git clone https://github.com/lcswillems/rl-starter-files
cd rl-starter-files
git clone https://github.com/lcswillems/torch-ac.git
cd torch-ac
pip3 install -e .
cd ..
python3 -m scripts.train --algo ppo --env MiniGrid-GoToDoor-8x8-v0 --model GoToDoor --text --save-interval 10 --frames 2000000

```
