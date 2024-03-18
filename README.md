# Learning Task-relevant Representations via Rewards and Real Actions for Reinforcement Learning


This is the code of paper **Learning Task-relevant Representations via Rewards and Real Actions for Reinforcement Learning**.


## Requirements

Python 3.6.9
PyTorch 1.10
tqdm
dm_control 0.0.322773188
mujoco-py 2.0.2.13
distracting_control==1.0.0

```
pip install -r requirements.txt
```
<!-- `conda install -y tensorboard` -->


## Reproduce the Results

For example, run experiments on Cartpole Swingup with color distractions

``` bash
bash run.sh
```


## Citation

If you find this code useful, please consider citing the following paper.

## Remarks

```
@article{yang2022learning,
  title={Learning Task-relevant Representations for Generalization via Characteristic Functions of Reward Sequence Distributions},
  author={Yang, Rui and Wang, Jie and Geng, Zijie and Ye, Mingxuan and Ji, Shuiwang and Li, Bin and Wu, Feng},
  journal={arXiv preprint arXiv:2205.10218},
  year={2022}
}
```
