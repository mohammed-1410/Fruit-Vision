Fruit Vision is an applied robotics and computer vision project designed for agricultural and industrial automation. The system combines real-time perception, robotic manipulation, and autonomous decision-making to detect, classify, and sort fruits using ROS2, MoveIt2, and OpenCV.
It demonstrates how AI and robotics can work together to improve efficiency in farming, smart harvesting, and automated sorting lines in factories.

Project Purpose

Fruit Vision was developed to solve real-world problems in the agricultural and industrial sectors:

• Automating fruit picking and sorting
• Reducing manual labor and human error
• Improving speed, safety, and consistency
• Enabling robots to understand and interact with environments in real time

The system shows how modern robotics can support smart agriculture and industrial production lines.

Key Capabilities
1. Real-Time Fruit Detection & Classification (OpenCV + Python)

• Detects strawberries and other fruits in real-time video
• Classifies fruits into ripe (red) and unripe (green)
• Uses color segmentation, contour analysis, and filtering
• Achieved ~95% accuracy in ripeness classification
• Designed to work both in simulation and real-world environments

2. Robotic Manipulation (UR3 / Franka Emika Panda + MoveIt2)

• Supports multiple robotic arms (UR3 or Franka)
• Generates collision-free trajectories
• Performs autonomous pick-and-place operations
• Uses inverse kinematics and smooth trajectory execution
• Fully integrated with MoveIt2 for motion planning

3. ROS2-Based Modular Architecture

The system is built on ROS2 using a node-based structure:

• vision_node – Extracts fruit position, color, and ripeness level
• planner_node – Computes trajectories and forwards action goals
• arm_controller – Executes the robotic movement for grasping and placing

This modular design ensures scalability and real-time performance.

Related Robotics Work (Part of the Capstone Portfolio)

In addition to Fruit Vision, the project portfolio includes:

Bolt Detection & Picking System (Franka Panda + YOLO + ROS2)

• YOLOv8 used for detecting bolts on a workspace
• Franka Panda robot automatically picks bolts in real time
• ROS2 for communication and image processing
• MoveIt2 for motion planning and execution
• Demonstrates industrial-level precision for factory automation

Strawberry Sorting Robot (OpenCV + ROS2)

• Detects and classifies ripe vs unripe strawberries
• Uses vision-based sorting logic
• Integrates with motion planning in MoveIt2
• Applies directly to agriculture and greenhouse automation

Tech Stack

• Programming: Python, C++
• Computer Vision: OpenCV
• Robotics Framework: ROS2 (Foxy)
• Motion Planning: MoveIt2
• Simulation Tools: Gazebo, RViz
• Hardware: UR3 robotic arm / Franka Emika Panda
• Build Tools: CMake, colcon
• Robot Models: URDF, Xacro

System Architecture (Conceptual)

Vision Module → Planning Module → Robotic Control Module
• Vision extracts fruit coordinates and ripeness
• Planner generates safe trajectories
• Controller executes movements through ROS2 control

This pipeline allows full autonomy from perception to action.

Project Outcomes

• Fully autonomous fruit detection and sorting
• Real-time robotic manipulation using AI
• Agriculture-friendly automation (greenhouses, farms, packaging lines)
• Industrial application for sorting, inspection, and quality control
• Robust simulation environment for research and development

Images & Media

https://github.com/mohammed-1410/Fruit-Vision/tree/main/Fruit%20Vision/images%20and%20media

LinkedIn Project Demos:
• Fruit Vision:
https://www.linkedin.com/posts/mohammad-hafez-a2943b299_robotics-ros2-moveit2-activity-7333782715755892736-6HjQ


Summary

Fruit Vision demonstrates your ability to combine:

• Computer Vision
• Robotics
• ROS2 Systems Engineering
• Motion Planning
• Real-Time Automation

It is a strong proof of your applied skills in AI + robotics for both agricultural and industrial automation.