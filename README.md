# dynamicvoxelization

This repository contains the files that need to be replaced in https://github.com/nutonomy/second.pytorch/ in order to train PointPillars using dynamic voxelization. The instructions on the README file of nutomy's repository should be followed before replacing these files.

## Instructions

After cloning the repository from nutomy, the files from this repository should replace the following files:

- preprocess.py should replace second.pytorch/second/data/preprocess.py
- point_cloud_ops.py should replace second.pytorch/second/core/point_cloud/point_cloud_ops.py
- train.py should replace second.pytorch/second/pytorch/train.py
- voxelnet.py should replace second.pytorch/second/pytorch/models/voxelnet.py
- pointpillars.py should replace second.pytorch/second/pytorch/models/pointpillars.py
