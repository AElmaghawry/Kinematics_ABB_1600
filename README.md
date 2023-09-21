# Empowering Aerospace Automation: Visual Servoing for Maintenance and Inspections of Airplane Engine Blades

**Supervisor(s) Name(s) and Department affiliation**
- Prof. Yahya Zweiri, Aerospace Engineering – Advanced Research & Innovation Center
- Dr. Yusra Abdulrahman, Aerospace Engineering – Advanced Research & Innovation Center
- Eng. Brain Moyo, Sanad Aerotech

**Abstract**

Visual servoing applications have assumed a pivotal role in research, particularly within the realm of aerospace maintenance and inspections. This innovative technique seamlessly merges computer vision and advanced control methods, equipping serial robots with enhanced accuracy for intricate tasks. In contrast to traditional fixed movement patterns, visual servoing empowers robots to make smarter decisions using real-time images. Collaborations among experts in computer vision, control systems, and aerospace engineering yield algorithms that enable robots to harness camera and sensor data. Consequently, serial robots achieve the capability to autonomously conduct maintenance and inspections with remarkable precision. In aerospace research, visual servoing finds application in automating critical tasks, exemplified by the examination of aero-engine blades. Serial robots integrated with this technology can proficiently scrutinize engine blades and promptly identify deviations from ideal measurements. Ongoing research focuses on refining algorithms to accommodate variations in blade shapes, diverse lighting conditions, and real-world scenarios. Another avenue of exploration centers on the collaboration between serial robots equipped with visual servoing and human technicians in aerospace tasks. This necessitates advancements in human-robot interaction, perceptual understanding, and meticulous motion planning to ensure harmony. It's worth noting that this project is part of a collaboration between the Advanced Research & Innovation Center (ARIC) and SANAD Aerotech. This collaborative effort is geared towards developing advanced vision-based capabilities for robots, with the aim of translating the potential of vision-based robots into practical applications that benefit industries. Through this collaboration, the project seeks to bring vision-based robots closer to real-world deployment, ultimately revolutionizing aerospace maintenance and inspections.

**Outcomes (list of expected outcomes for successful completion)**

- Functional Robotic System: Development of a functional robotic system capable of autonomously performing maintenance and inspection tasks using visual servoing techniques.
- Informed Industry Solutions: Dynamic collaboration with SANAD Aerotech experts will lead to the generation of a comprehensive set of recommendations and solutions tailored to real-world challenges. These solutions, ranging from testing protocols to evaluations, will align the project with industry-specific needs and contribute to refining aerospace maintenance and inspection practices.

**Number of students and background and/or pre-requisites required**

Four/five Engineering and Computer Science students. Required Skills:
- Programming in python or C++
- Strong Mathematical Background and knowledge in kinetics and kinematics
- Experience in mechanical design and fabrication / CAD design
- Experience in Computer Vision is highly preferred

**Resources Required**

All resources will be covered by ARIC and SANAD R&D. These resources include:
- Serial Robotic Manipulator
- Robotic Gripper
- High-resolution RGBD Cameras
- Laser Scanners
# Robotics and Visual Servoing Curriculum Checklist

## **Robotics Fundamentals**
Resources:
 [Robotics, Vision and Control](https://petercorke.com/rvc/home/)

 
- [ ] **Introduction to Robotics:**
  - Basics of robotics and its applications.
  - Types of robots, focusing on serial robot arms.
  - Mobility and DOF (Degrees of Freedom) of any arm robot.

- [ ] **Robot Kinematics:**
  - Forward and inverse kinematics of serial robot arms.
  - Denavit-Hartenberg parameters.
- [ ] **Understanding Frames and Transformations:**
  - Local vs. global coordinate frames.
  - Euler angles and their representation in robotics.
  - Quaternions and their advantages in orientation representation.
  - Transformation matrices for frame transformations.
  

## **Robotics Operating System -ROS-**
- [ ] **Understanding Linux with Robot Control (High Priority):**
  
 Resources:
 [Linux for Robotics](https://app.theconstructsim.com/courses/linux-for-robotics-40/),
 ,[ROS Basics in 5 Days (Python)](https://app.theconstructsim.com/courses/ros-basics-in-5-days-python-55/)
 ,[ROS for Beginners: Basics, Motion, and OpenCV](https://www.udemy.com/course/ros-essentials/?kw=ROS+for+beg&src=sac)
 ,[linux_installation](https://www.youtube.com/watch?v=-iSAyiicyQY) 
  - Familiarity with the Linux operating system.
  - Introduction to ROS (Robot Operating System).
  - ROS nodes, topics, and messages.
- [ ] **Robot Arm Control:**
  - Joint control methods (position, velocity, torque).
  - Trajectory planning for robot arm movements.

- [ ] **Pose Estimation:**
  - Methods for determining object pose in camera frame.
  - Homography transformations.
- [ ] **Path Planning:**
  - Collision-free path planning for robot arm.
  - Trajectory generation for pick and place tasks.
  - 
## **Vision**
- [ ] **Visual Servoing Fundamentals:**
  - Introduction to visual servoing and its significance.
  - Types of visual servoing (image-based, position-based, etc.).

- [ ] **Camera Systems:**
  - Camera types and specifications.
  - Camera calibration for accurate vision data.

- [ ] **Image Processing:**
  - Techniques for image enhancement.
  - Object detection and feature extraction.
  
- [ ] **Object Detection and Recognition:**
  - Implementing object detection algorithms.
  - Machine learning-based object recognition (if applicable).
- [ ] **Integration of Visual Servoing with Robot Arm:**
  - How to interface visual servoing with the robot's control system.
  - Ensuring synchronization between vision and robot control.

## **Design**
- [ ] **Gripper Design and Control:**
  - Gripper types and selection.
  - Control logic for opening and closing the gripper.

---

## **Version Control**
- [ ] **Version Control System (VCS):**
  - Understanding and using a Version Control System such as Git.
  - Managing code repositories for collaborative development.
  - Branching and merging strategies for code collaboration.

---

## **Optional**
- [ ] **Safety Measures:**
  - Ensuring the robot operates safely, especially in human-robot collaboration scenarios.
- [ ] **Error Handling and Recovery:**
  - Strategies for handling errors and exceptions.
  - Fail-safe mechanisms to prevent accidents.
- [ ] **Data Logging and Analysis:**
  - Implementing data logging for troubleshooting and analysis.
- [ ] **Scaling and Future Expansion:**
  - Considerations for scaling the system or adapting it for new tasks.
- [ ] **Regulatory Compliance:**
  - Compliance with safety and industry regulations.
- [ ] **Training and User Education:**
  - Training personnel on operating and maintaining the system.
