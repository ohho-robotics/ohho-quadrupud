# OhhO Quadruped 🐕

The reference architecture for running the OhhO OS on quadruped robots (e.g., Unitree Go2, Spot). Features Reinforcement Learning (Isaac Lab) locomotion integrated with OpenVLA for high-level semantic navigation.

This repository is part of the **[OhhO Robotics Platform](https://github.com/ohho-robotics)**. It acts as the meta-workspace for onboarding this specific form factor into the OhhO ecosystem.

## 🚀 Quick Start (Simulation)
You can test the AI models and control stack for this robot in the OhhO Digital Twin without physical hardware.

```bash
git clone https://github.com/ohho-robotics/OhhO-Quadruped.git
cd OhhO-Quadruped
vcs import src < ohho.repos
docker compose up -d
```

## 🧩 OhhO Integration
This hardware profile natively supports:
- **OhhO Fleet**: Live telemetry and multi-agent coordination.
- **OhhO Connect**: ROSBridge / WebRTC low-latency streaming.
- **OhhO Mind**: VLA-based spatial intelligence.
