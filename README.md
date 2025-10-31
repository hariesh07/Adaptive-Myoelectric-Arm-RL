
# Adaptive Myoelectric Hand Control Using Reinforcement Learning

This repository contains the manuscript and implementation for an innovative control system for myoelectric prosthetic arms that leverages **Reinforcement Learning (RL)** for dynamic, continuous user adaptation.

## Project Overview

The core challenge in myoelectric prosthetics is the lack of adaptability to a user's unique physiology and signal changes over time. This work addresses that by proposing a **two-stage learning paradigm** to ensure precise and intuitive control.

## Methodology & Key Features

The system is built on a two-stage learning process using an **Actor-Critic** RL model:

1.  **Supervised Pre-training (Foundation):** The Actor-Critic model is first trained on a general EMG dataset to establish a foundational signal-to-action mapping.
2.  **Continuous Adaptive Refinement (Personalization):** Post-deployment, the *same* model is continuously refined in **real-time** using the individual user's Electromyography (EMG) data. This allows for personalized adjustments without requiring a full retraining cycle.

## Performance

The dynamic adaptation mechanism proves highly effective, demonstrating an improvement in action prediction accuracy of **up to 89% after adaptation** compared to the initial model. This validates the system's ability to effectively learn and match user-specific muscle patterns.

