# UAV_Navigation_DRL_AirSim

This project implements Deep Reinforcement Learning (DRL) for autonomous UAV (drone) navigation using Microsoft AirSim as the simulation environment.

The repository focuses on training and evaluating RL agents for navigation tasks in simulated environments, enabling research and experimentation in autonomous flight and robotics.

---

## Overview

The project combines:

- Microsoft AirSim (drone simulator)
- OpenAI Gym-compatible environments
- Deep Reinforcement Learning algorithms
- Stable-Baselines3 integration
- Custom training and evaluation scripts

The goal is to train a UAV agent to navigate safely and efficiently in simulated environments.

---

## Key Components

- `gym_env/` – Custom Gym environment for UAV navigation  
- `configs/` – Configuration files for training and evaluation  
- `scripts/` – Training and utility scripts  
- `tools/` – Supporting utilities  
- `resources/` – Additional assets and environment resources  
- `airsim_settings/` – AirSim configuration files  
- `stable-baselines3/` – RL framework integration  

---

## Requirements

- Python 3.8+
- Microsoft AirSim
- Unreal Engine (for AirSim environments)
- Stable-Baselines3
- Gym / Gymnasium
- NumPy
- PyTorch

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Setup

### 1. Install AirSim

Follow the official AirSim installation guide and set up an Unreal environment.

### 2. Configure AirSim

Copy the configuration from:

```
airsim_settings/
```

to your AirSim settings directory.

### 3. Install Python Dependencies

```bash
pip install -r requirements.txt
```

---

## Training

Start AirSim simulation first.

Then run training:

```bash
python scripts/train.py
```

Adjust configuration files in `configs/` to modify training parameters.

---

## Evaluation

Run evaluation scripts:

```bash
python scripts/evaluate.py
```

Evaluation logs are stored in:

```
logs_eval/
```

---

## Research Goals

- Autonomous UAV navigation
- Obstacle avoidance
- DRL policy learning in simulation
- Sim-to-real experimentation groundwork

---

## Notes

- Ensure AirSim is running before training or evaluation.
- Modify environment parameters in config files for different scenarios.
- Check logs for training metrics and debugging.

---
