# Learning Hand-Eye Coordination for Robotic Grasping with Deep Learning and Large-Scale Data Collection

## Contribtion 
1. Method for learning continuous visual servoing for robotic grasping from monocular cameras
2. Novel CNN architectrue for learning to predict the outcome of a grasp attempt
3. Large scale data collection framework for robitc grasps

## Method
1. Prediction network: 
    - Input: image, task space motion command,
    - Output: probability that executing command will produce a successful grasp

2. Servoing function:
    - Uses prediction network to continously control the robot to servo the gripper to a success grasp

## Experiment
- Compare performance with manual hand-eye calibration transformation open-loop method
- Continuous update using servoing function performs better
