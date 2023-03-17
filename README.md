# Dual-Adaptive ϵ-Greedy Exploration (DAE)
This is the official implementation of [Incremental Reinforcement Learning with Dual-Adaptive ε-Greedy Exploration] in pytorch.



Requirements
------------

- [atari-py](https://github.com/openai/atari-py)
- [OpenCV Python](https://pypi.python.org/pypi/opencv-python)
- [Plotly](https://plot.ly/)
- [PyTorch](http://pytorch.org/)

To install all dependencies with Anaconda run `conda env create -n DAE -f environment.yml python=3.7` and use `conda activate DAE` to activate the environment.

Available Atari games can be found in the [`atari-py` ROMs folder](https://github.com/openai/atari-py/tree/master/atari_py/atari_roms).

Acknowledgements
----------------
This work is based on the implementation of [Rainbow](https://github.com/Kaixhin/Rainbow) from [@Kaixhin](https://github.com/Kaixhin)
