RL control project 
==============
Humanoid Robot Simulation and Control

In a short [project](https://github.com/SalmaKazemiRashed/RL_control_project) I developed a complete framework for simulating, controlling, and analyzing a humanoid robot in PyBullet. What I have:

- Robot Model: A full humanoid URDF with articulated legs, enabling joint-level control and realistic physics-based motion.

- System Architecture: Low-level joint control is implemented via PID controllers, allowing precise actuation and real-time simulation of physical constraints.

- Data-Driven Motion Replay: Joint logs (CSV) can be mapped to the robot’s actuators to visualize and analyze motion in both 2D (matplotlib) and 3D (PyBullet), with GIF capture for documentation.

- Reinforcement Learning Integration: The framework is designed to interface with RL policies, enabling experimentation with adaptive control, policy evaluation, and sim-to-real studies.

- Simulation-to-Real Insights: By replaying and analyzing joint-level data, this repository helps quantify control performance, explore failure modes, and reduce the sim-to-real gap in humanoid robotics.

This project serves as a hands-on platform for understanding the interaction between learning-based models, low-level control, and physical constraints, providing a foundation for developing general-purpose, adaptive robotic systems.
