# 🤖 Reinforcement Learning Projects

This repository contains three different reinforcement learning projects, each demonstrating different algorithms and applications in artificial intelligence for business optimization.

## 📦 Project 1: Q-Learning for Warehouse Optimization

**File:** `Q-Learning for Warehouse Optimization/q_learning.py`

This project implements a Q-Learning algorithm to optimize warehouse flows and logistics routing. The AI system learns to find the shortest and most efficient routes between different locations in a warehouse environment.

**Key Features:**
- Classic Q-Learning implementation with gamma and alpha parameters
- Environment defined with 12 locations (A through L) 
- Reward matrix representing possible connections between locations
- Route optimization function that finds optimal paths between any two points
- Production-ready function for multi-stop routing (starting → intermediary → ending location)

**Use Case:** 🏭 Optimizing warehouse operations by finding the most efficient paths for workers or automated systems to move between different storage locations.

## 🌡️ Project 2: Deep Q-Network (DQN) for Server Temperature Control

**Files:** `Deep Q-Network (DQN) for Server Temperature Control/` directory containing:
- `dqn.py` - Deep Q-Network implementation with experience replay
- `environment.py` - Server room environment simulation
- `brain_dropout.py` / `brain_nodropout.py` - Neural network architectures
- `training_earlystopping.py` / `training_noearlystopping.py` - Training scripts
- `testing.py` - Model evaluation

This project uses Deep Q-Learning to optimize server room temperature control, minimizing energy consumption while maintaining optimal operating conditions.

**Key Features:**
- Deep Q-Network with experience replay for improved learning stability
- Environment simulation including atmospheric temperature, user load, and data transfer rates
- Neural network brain with configurable dropout layers
- Temperature control actions to maintain optimal server operating conditions
- Energy optimization comparing AI vs non-AI control systems
- Training with early stopping capabilities

**Use Case:** 🏢 Intelligent HVAC control for data centers and server rooms, reducing energy costs while ensuring optimal performance and equipment safety.

## 🚀 Getting Started

Each project can be run independently. Navigate to the respective folder and execute the main Python file:

```bash
# Project 1: Q-Learning
python "Q-Learning for Warehouse Optimization/q_learning.py"

# Project 2: DQN Training
python "Deep Q-Network (DQN) for Server Temperature Control/training_earlystopping.py"
```

## 💼 Applications

These projects demonstrate practical applications of reinforcement learning in business scenarios:
- **📦 Logistics and Supply Chain Optimization**
- **🌡️ Energy Management and Smart Building Control**
