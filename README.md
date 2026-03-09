# Control Strategy Comparison for an Intelligent Mobile Mechanism

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ROS 2](https://img.shields.io/badge/ROS2-Humble-22314E)
![Gazebo](https://img.shields.io/badge/Gazebo-11.14.0-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-2.7.0-red)
![OpenCV](https://img.shields.io/badge/OpenCV-4.12.0-green)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04.5-E95420)



This repository contains the source code, trained models, maps, and experimental data associated with the article **"Control Strategy Comparison for an Intelligent Mobile Mechanism"**. It was organized to support understanding of the experimental pipeline and reproduction of the simulation-based results reported in the paper.

## Repository structure

- `01_RL_training/`  
  Selected trained reinforcement learning models, including actor and critic files when applicable.

- `02_Controllers/`  
  Controller implementations and model-loading architecture used in the experiments.

- `03_Gazebo_ros2/`  
  ROS 2 and Gazebo interface files required to reproduce the simulation environment.

## Citation

If you use this repository, please cite both the software archive and the associated article.

## Zenodo archive

The archived version of this repository is available on Zenodo:

Souza Junior, F. R. de . (2026). Line-Following Control with PID and Deep Reinforcement Learning in Simulation (follower_meder). Zenodo. https://doi.org/10.5281/zenodo.18925646

For standardized citation metadata, see the `CITATION.cff` file in the root of this repository.






