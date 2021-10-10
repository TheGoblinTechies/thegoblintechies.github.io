---
layout: post
---

This is a post for getting started on Nvidia's new simulation environment, Isaac Sim.

Follow this link to [**install and set up Isaac Sim**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/requirements.html).

A quick example on using UR10 for simple object picking: [**An example on UR10**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/sample_ur10.html)

To run python scripts directly, see [**Run Python Scripts**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/python_environment.html)

Python Scripts are supported mostly by [**Omniverse Kit**](https://docs.omniverse.nvidia.com/prod_kit/prod_kit/overview.html#what-is-kit)

[**Python Utility Snippets**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/python_snippets.html)

[**Robot and Environment**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/assets.html#robots)

[**A Reinforcement Learning Sample for Jetbot**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/sample_training_rl.html). Here you need to preprocess the components and create a folder as told before running python scripts.

[**Synthestic Data**](https://docs.omniverse.nvidia.com/app_isaacsim/app_isaacsim/sample_syntheticdata.html)

An example to use python scripts, open Terminal at **~/.local/share/ov/pkg/isaac_sim-2021.1.1/python_samples** and start **python simple/load_stage.py --usd_path /Environments/Jetracer/Tracks/track_solid_line.usd** to load a usd file. And similiarly, **python simple/load_stage.py --usd_path /Robots/UR10/ur10_short_suction.usd** to load your UR10 model.