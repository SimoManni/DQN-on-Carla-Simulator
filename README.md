# DQN-on-Carla-Simulator
This repository contains the implementation of a simple DQN agent to drive a car in the Carla simulation environement. 

<div align="center">
  <img src="https://github.com/user-attachments/assets/f9188dd5-467b-432d-a835-74d9edc0898b" alt="CARLA" width="400"/>
</div>


- ### CARLA
CARLA (Car Learning to Act) is an open-source simulator designed for autonomous driving research, offering a high-fidelity, customizable virtual world. It provides detailed urban and rural environments, realistic vehicle dynamics, and various sensors such as cameras and LiDAR, allowing researchers to test and validate autonomous vehicle algorithms in a simulated real-world setting. Additionally, CARLA allows users to create their own custom worlds for tailored testing and experimentation, enhancing the versatility and applicability of the simulation.

- ### RL
In this project, I implemented a simple reinforcement learning (RL) agent designed to avoid lane violations and collisions using sensors from the CARLA environment. The agent processes images from an RGB camera mounted on the car through a convolutional neural network (CNN) to determine the optimal driving actions.

## Results
In the video we can see the visualization of the Carla environement and the car being driven by the RL agent. 

Although this project is still in progress and serves as a proof of concept, it has helped in gaining familiarity with the CARLA environment and exploring its capabilities. The current results are suboptimal, indicating that the agent needs further training and improvements in state representation and image processing to extract relevant information. Nonetheless, the project highlights the significant potential of the CARLA simulator for developing and testing autonomous driving algorithms.




