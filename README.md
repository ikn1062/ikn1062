# Hello, I'm Ishaan Narain! 👋

## About Me
My name is Ishaan and I am a student at Northwestern University (NU) pursuing an accelerated MS in Computer Science, having just graduated with a BS in Mechanical Engineering in June 2022. I was born and raised in Hong Kong, and attended King George V School.

I am currently working on research projects with the Robotics Department in Inverse Reinforcement learning for Swarm Robotics, Applied Mathematics Department in Analyzing Video Data, and am beginning to work on Core Operating Systems Projects in Parallelism. Previously, I have also acted as a Software Engineering Intern at Tesla with the Electrical Systems team working on developing testing frameworks and debugging firmware issues in Python / C++, as well as a Technical Program Manager Intern at Tesla scaling manufacturing lines with the Battery Team. I have also previously worked as a Data Science / MLOps Researcher with the [DELOS](https://www.mccormick.northwestern.edu/research/deep-learning/projects/delos/) team and a Machine Learning Engineering Intern at [InfernoGuard](https://www.infernoguardusa.com) (NU Garage Startup).

I am currently looking for full-time opportunities in Software Engineering, Quant, and Robotics starting in Summer/Fall 2023.

### Contact Information:
Email: ishaannarain2022@u.northwestern.edu

LinkedIn: https://www.linkedin.com/in/ishaan-k-narain/

## Projects
Below, I have listed some of the projects I have worked on as part of my time at Northwestern University. These projects include some of the work as part of my coursework, personal projects, and research projects.


### Current Projects

- Ergodic Metric and Controller Library for Dynamic System
  - Created reinforcement learning library with model predictive control for autonomous robotics inspired by ergodic metric research
  - Deployed algorithm on 3-Omnid robot swarm, implementing dynamics, trajectory optimization in Python / C++.
  - Derived mathematics for iLQR control via gradient descent by solving Riccati equations from derivative of ergodic objective
  - Engineered interactive 3D learning-from-demonstration cart-pole simulation using Linux Robot-OS 2, CMake, and Python NumPy
  - Some of my initial work in this field can be found here: [Active Learning and Control](https://github.com/ikn1062/active-learning-and-control)

- [Zoom (and Live) Video Speaker Data Analysis](https://github.com/ikn1062/video_analysis)
  - Developed Zoom and Live (OWL) video data collection and analysis app, leveraging OpenCV, Mediapipe, and face recognition Python Libraries
  - Utilized 30 face-mesh tracking points to analyze speaker facial cues to predict the speaker when masks are worn
  - Reduced processing time by 82% using multithreading and multiprocessing functions, executing code in NU Linux computing cluster
  - Utilized: Python (OpenCV, Mediapipe, Face recognition (dlib), pytesseract, Scikit-learn), Bash, Linux

- [DeepQ Financial Trading Decisions](https://github.com/ikn1062/trading-system-deep-q-learning)
  -  Implemented deep Q-learning research paper outperforming S&P growth by 18% using Python NumPy, Pandas, and TensorFlow to predict buy, sell, and hold action strategy and number of shares to trade
  -  Increased profit by 30% through pretraining neural network by transfer learning from stocks with varied correlation to index
  -  Automated closing-day stock data pipeline by web scraping index data with Beautiful Soup and retrieval from Yahoo Finance API

### Previous Projects

- [DELOS - Deep Learning Model Serving System](https://www.mccormick.northwestern.edu/research/deep-learning/projects/delos/)
  - Implemtented neural network retraining module with 100% unit stress testing for deep-model serving by applying ML research 
  - Decreased training time by 24% by dynamically re-optimizing weights using online Multi-Arm Bandit memory replay algorithm
  - Developed stateless full-stack app to improve monitoring of over 20 ML KPIs, leveraging TensorFlow, Mongo, and Kubernetes
  - Some of my work in the application process is linked [here](https://github.com/ikn1062/nu-cdl-delos)

- [Sensing Navigation and ML in Robotics](https://github.com/ikn1062/turtlebot-slam/)
  - Created robotics library for Extended Kalman Filtered simultaneous localization and mapping using ROS2 and Armadillo in C++17
  - Integrated DDS publish-subscribe network protocols to facilitate communication between sensors and robot actuators
  - Automated packaging, documentation, and testing of 20,000-line C++ library using CMake, Doxygen, and Catch2 Framework
  - A simulation demonstration video of SLAM is linked [here](https://youtu.be/QlarJMluz2w)

- [Haptic Virtual Reality Wand](https://www.mccormick.northwestern.edu/news/articles/2022/06/design-studio-students-show-off-high-performance-robots/)
  - Designed and built wearable haptic robot to simulate weight of objects from VR up to 10N by combining torques from 3 motors
  - Derived kinematic model to estimate arm positions and calculate torque using data from Kalman-filtered sensors and Unity VR
  - Programmed control loop, robot geometry, and serial communication to run in 0.001 seconds per loop with embedded C++
  - •	Created and manufactured electrical board integrating 38 devices including motors, encoders, and 1500W power supply
  - [Haptic Robot for simulating the weight of objects in VR](https://github.com/ikn1062/vr-wand-robot)

- [Venmo Request Scheduler](https://github.com/mikeluvin/venmo-scheduler) (NU WildHacks 2022 Winner)
  -  Launched full-stack Venmo recurring payments scheduler web app on team of 4 in 24 hours, winning NU22 Hackathon prize
  -  Created 20 unique API endpoints and logic on Flask server for back-end and front-end integration, recurring payments, and messaging process
  -  anually overrode class methods from Python Venmo API wrapper to repurpose for app login and 2-factor OTP authentication

- [Northwestern University Solar Car Team - Previous Project Manager and Lead Mechanical Engineer](https://nusolar.org)
  - Managed team of 40 to design, manufacture, and assemble road-legal carbon-fiber solar vehicle to compete at Formula Sun Grand Prix
  - Engineered new suspension and monocoque chassis, increasing total power-to-weight ratio by 13% by using mechanical calculations and Matlab Simulink
  -  Led team to design and build new powertrain of car integrating battery pack, battery management system, solar array, and motor, improving solar power generated by 8%, power to weight ratio by 13%, and accomplishing an indefinite range of vehicle at 30mph
  -  Coordinated with University administration, faculty, and sponsors to secure funding and material resources over $60,000 of value
  -  Generated 40-page report detailing and analyzing the performance of vehicle systems proving compliance with 300 racing regulations
  - Refined driver and vehicle control communications by integrating 8 vehicle components using CAN protocol in embedded C++ 

### Northwestern University Courses
- [Introduction to AI](https://github.com/ikn1062/CS348-intro-to-ai)
- [Knowledge Representation and Reasoning](https://github.com/ikn1062/CS371_KR-R)
- [Modern Robotics](https://github.com/ikn1062/ME449-Modern-Robotics)
- [C++ Game Projects](https://github.com/ikn1062/CS212-cpp-game-projects)
- [Data Privacy Browser Extension](https://github.com/aryanjainnu/dataprivacy)
- [Machine Learning](https://github.com/ikn1062/CS349-machine-learning)

## Technical Skills

### What I'm Familiar With:
Languages:
- Python 3, C++ (C++14, C++17), C, Racket, Matlab, Bash, Mathematica, ASM (64-bit Intel x86)

Libraries:
- Python 3 Libraries: Numpy, Pandas, MatPlotLib, OpenCV, SymPy, TensorFlow, Requests, Sockets, Scikit-Learn, Asyncio, Fast API, Tkinter
- Python Frameworks:  Flask, Django
- C++ Libraries:      Eigen

Tools:
- Docker, Kubernetes, GDB, Vim, Linux, Multithreading, Multiprocessing, RESTful

Databases:
- PostgreSQL (Relational Databases), MongoDB, MySQL


