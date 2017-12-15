# DQN-Atari-Enduro
Re-implementation of DQN [Deepmind] for Enduro-v0 (Atari)

**Reference**: Human-level control through deep reinforcement learning, Nature 518, 529–533 (26 February 2015) doi:10.1038/nature14236

## Requirements:

1. Keras-RL
```bash
pip install keras-rl
```
source: https://github.com/matthiasplappert/keras-rl

2. Tensorflow-gpu
```bash
conda create --name tensorflow python=3.5
```
```bash
activate tensorflow
pip install tensorflow-gpu
conda install jupyter
conda install scipy
```
Check: https://www.tensorflow.org/install/

3. OpenAi gym
```bash
pip install gym
```
Check: https://gym.openai.com/envs/

4. Install atari
```bash
pip install "gym[atari]"
```
* For Windows installation:
Check:https://github.com/j8lp/atari-py

5. pyglet 1.2.4
```bash
pip install https://pypi.python.org/packages/68/c3/300c6f92b21886b0fe42c13f3a39a06c6cb90c9fbb1b71da85fe59091a7d/pyglet-1.2.4-py3-none-any.whl#md5=08e6404a678f91b4eee85eb33b028d88
```
**Note:**
1. In Jupyter Notebook open Dqn_atari_Enduro.ipynb
2. Training is not necessary. Weights can directly be loaded from dqn_atari_Enduro.h5f

## Papers Followed:

1. [Playing Atari with Deep Reinforcement Learning](https://arxiv.org/abs/1312.5602)
2. [Human-level Control Through Deep Reinforcement Learning](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf)

##### Trained on: Intel® Xeon® Processor E5, 2.40 GHz, Nvidia Quadro K4200
##### Bhartendu, Machine Learning & Computing
[Mathworks File-exchange](https://in.mathworks.com/matlabcentral/profile/authors/10083740-bhartendu?&detail=fileexchange),
[LinkedIn](https://in.linkedin.com/in/bhartendu-thakur-56bb6285),
[Github](https://github.com/matrixBT)
