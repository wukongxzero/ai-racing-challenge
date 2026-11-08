# AI Racing Challenge

ROB-GY 6323 (Reinforcement Learning & Optimal Control) team project, Fall 2026.
2D racing sim comparing Pure Pursuit, MPC, and PPO controllers, plus a human player.

## Layout

| Folder | Owner | Contents |
|---|---|---|
| `sim/` | Member 1 | vehicle model, physics step (runs without Pygame) |
| `tracks/` | Member 1 | track definitions |
| `controllers/pure_pursuit/` | Member 4 | Pure Pursuit baseline |
| `controllers/mpc/` | Member 2 | MPC (CasADi + IPOPT) |
| `controllers/ppo/` | Member 3 | Gymnasium env wrapper, reward, PPO training |
| `game/` | Member 4 | Pygame front end, race modes |
| `eval/` | Member 4 | metrics, comparison plots |
| `docs/` | all | proposal, reports |

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
