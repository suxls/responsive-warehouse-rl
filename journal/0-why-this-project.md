# 00 — Why this project

Date: 2026-04-26

## Decision
Build a latency-aware multi-agent RL warehouse simulator as my last
independent project before graduating.

## Why this, not something else
- I want to learn PyTorch + PPO/MAPPO end-to-end.
- I want to learn C++.
- Multi-agent coordination + simulation is directly relevant to the
  ML-systems / robotics roles I'm targeting.
- My last internship "https://osmosis.ai/blogs/responsive-software"

## Alternatives considered
- LLM post-training research repo: too overlapping with my last internship.
- Pure quant project (orderbook simulator + RL trader): rich, but the
  data is messier and the "robotics" angle disappears.
- Self-driving toy in CARLA: too compute-hungry for a solo project.

## Phase 0 retro
- [ ] uv project initialized
- [ ] ruff + mypy + pytest green
- [ ] pre-commit installed
- [ ] CI workflow committed
- [ ] First commit pushed to GitHub