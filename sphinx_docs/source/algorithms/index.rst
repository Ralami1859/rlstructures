Provided Algorithms
===================


We provide multiple RL algorithms as examples.
1) A2C with General Advantage Estimator
2) PPO with discrete actions
3) Duelling Q-Learning
4) SAC for continuous actions

The algorithms can be used as examples to implement your own algorithms. Each algorithm is parameterized by a `YAML` file that contains the hyper-parameters (based on the `hydra` framework, allowing to launch on cluster).

Typical execution is : `python main.py -cd script_directory -cn config.yaml`

Note that all algorithms produced a tensorboard and a CSV output.\
