# Autonomous-Vehicles-Framework-in-Hydra-RAN
Goal-Oriented Cognitive Communication for Autonomous Vehicles: A Hierarchical World-Model Framework in Hydra-RAN
Autonomous-Vehicles-Hydra-RAN/

This repository contains the implementation and simulation framework for the paper "Goal-Oriented Cognitive Communication for Autonomous Vehicles: A Hierarchical World-Model Framework in Hydra-RAN".

This work proposes a novel communication paradigm that embeds explicit goal-awareness and hierarchical world-model reasoning into the communication fabric of Hydra-RAN enhanced autonomous vehicles, achieving significant reductions in communication overhead and cognitive load.

Key Features & Contributions
Hierarchical World-Model Framework: Implements belief alignment across Hydra-RAN layers (Vehicle, SRU, H-DU, H-CU, H-RIC).

Goal-Oriented Communication: Formulates communication as an optimal information selection problem under explicit system-level goal constraints.

Layer-Adaptive Paradigms:

Event-triggered semantic updates at the Vehicle-SRU edge.

Goal-oriented communication and world-model compression at higher aggregation layers.

Hierarchical knowledge distillation for cognitive synchronization.

Unified Optimization: A mathematical framework coupling communication, inference, and control.

Extensive Simulation: Validated in an integrated environment using CARLA, SUMO, and OMNeT++, showing:

├── src/
│   ├── world_model/          # Belief state and hierarchical model classes
│   ├── communication/        # Layer-adaptive communication protocols
│   ├── perception/           # Multi-task perception and fusion models
│   ├── control_optimization/ # Unified optimization solvers
│   └── utils/                # Helper functions and metrics
├── configs/                  # Simulation parameters, network configs
├── scripts/                  # Launch scripts for CARLA-SUMO-OMNeT co-simulation
├── data/                     # (Placeholder) Links to required datasets
├── results/                  # Scripts to reproduce figures and tables from the paper
└── docs/                     # Additional documentation
