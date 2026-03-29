# Super Mario Bros Level 1 — PPO RL Agent

An AI-powered extension of the classic Super Mario Bros Level 1 recreation, featuring a PPO (Proximal Policy Optimization) reinforcement learning agent trained to play the game autonomously.

![screenshot](https://raw.github.com/justinmeister/Mario-Level-1/master/screenshot.png)

## 🎮 Original Project

This project is built on top of the excellent **Mario-Level-1** game recreation originally created by [**@caglar28**](https://github.com/caglar28). The original project faithfully recreates the first level of Super Mario Bros using Pygame, providing a solid foundation for RL experimentation.

**Original repository:** [caglar28/Mario-Level-1](https://github.com/caglar28/Mario-Level-1)

## 👥 Credits & Acknowledgments

| Contributor | Role |
|---|---|
| [**@caglar28**](https://github.com/caglar28) | 🎮 **Original creator** — designed and built the Mario Level 1 game recreation, game engine, physics, level design, and sprite system |
| [**@Nikabanzai**](https://github.com/Nikabanzai) | 🤖 **RL extension** — added PPO training pipeline, custom Gymnasium environment wrapper, and AI agent |

> Without @caglar28's carefully crafted game implementation, this RL project would not be possible. Full credit for the game itself belongs to them.

## 🤖 RL Agent

This fork adds:
- **Custom Gymnasium environment** (`mario_env.py`) wrapping the original game
- **PPO training pipeline** (`train.py`) using stable-baselines3
- **Pre-trained model** (`mario_ppo.zip`) that plays Level 1
- **Tensorboard logging** for training visualization

## Controls (Manual Play)

- Arrow keys — direction
- `a` — jump
- `s` — action (fireball, run)

## Dependencies

```bash
pip install -r requirements.txt
```

## Video Demo

http://www.youtube.com/watch?v=HBbzYKMfx5Y

## Disclaimer

This project is intended for non-commercial educational purposes.