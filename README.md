# Hi, I'm Yash Prakash 👋

**Robotics Engineer leading Verification and Validation at [Skip](https://skipwithjoy.com).** Based in San Francisco.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yash-prakash-979853172/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yprakash.cmu@gmail.com)
[![Website](https://img.shields.io/badge/Website-111111?style=for-the-badge&logo=githubpages&logoColor=white)](https://yash-prakash1.github.io)

I work as the connective tissue across hardware, machine learning, and field operations, turning physical tasks into data, structured evaluations, and shipped hardware. I build robot test and evaluation infrastructure from zero, automate it over real instrumentation, and run the experiments that drive design changes.

## What I do

* **Robot test and evaluation infrastructure.** At Skip I built the evaluation stack from nothing, including automated workcells and benchmarks such as actuator dynos, BMS validation, impact, drop, and environmental tests, now followed by contract manufacturers and suppliers across China, Taiwan, and Canada.
* **Hardware automation and hardware in the loop CI.** I architected a Python automation pipeline over servo drives, torque sensors, and Rigol DAQ and oscilloscopes via SCPI and VISA, cutting hands on time from 4 hours to 10 minutes per run, plus a CI gate that runs structured evaluations on real hardware for every pull request.
* **Reliability that ships.** I ran a 300k plus cycle actuator durability program on the MoGo exoskeleton, using root cause analysis to drive design changes that lifted actuator MTBF from about 15k to over 200k cycles.
* **Robot learning.** My CMU thesis trained a custom robot to cross terrain it had never seen, using reinforcement learning and onboard vision.

## Featured projects

### 🤖 [moving_mass_robot_RL](https://github.com/Yash-Prakash1/moving_mass_robot_RL)
My M.S. thesis at Carnegie Mellon, advised by Dr. Howie Choset and funded by DARPA. VeRT is a custom 5 DoF wheeled robot with a pneumatically actuated shifting internal mass. I trained it with a teacher and student reinforcement learning setup in Isaac Gym, a PPO teacher on privileged terrain data distilled into a vision based student, across 256 parallel environments with a progressive terrain curriculum, so it traverses uneven, unstructured terrain zero shot. It benchmarked as the fastest platform against MIT Cheetah 3, Boston Dynamics Spot and Atlas, and ANYmal, with 100 percent task success against PPO, A3C, and TD3 baselines. The repository includes the thesis paper.

### 🔌 [connector](https://github.com/Yash-Prakash1/connector)
An AI powered CLI that connects engineers to lab instruments. It diagnoses connection issues, fixes permissions, installs dependencies, and generates working Python code, all from the terminal. It is built around a three tier device model, an auto discovering device registry, and pluggable Anthropic, OpenAI, and Google providers. This grew directly out of the instrumentation automation work I do over SCPI and VISA.

### 🚗 [cmu-16664-self-driving](https://github.com/Yash-Prakash1/cmu-16664-self-driving)
A convolutional neural network that classifies images from a self driving car dataset, built for 16-664 Self Driving Cars at Carnegie Mellon.

## Tech I work with

**Robot learning:** PPO, DAgger, teacher and student RL, sim to real, domain randomization, Isaac Gym and Isaac Sim, policy distillation

**Software:** Python, PyTorch, OpenCV, ROS, Weights & Biases, GitHub Actions, Docker, Linux

**Test and validation:** hardware in the loop, CI gating, fixture and benchmark design, structured evaluations, MTBF, root cause analysis, EVT

**Hardware:** actuators, encoders, IMUs, force and torque sensors, PCBs, CAN, BMS, LiDAR, depth cameras

**Instrumentation:** Rigol oscilloscopes and DAQ, Kollmorgen servo drives, Futek torque sensors, SCPI and VISA

## Experience

* **Skip Innovations**, Robotics Engineer leading Verification and Validation. April 2025 to present, San Francisco.
* **Orangewood Labs**, Robotics Integration and Field Engineer. June 2024 to April 2025, San Francisco.
* **Carnegie Mellon University, Biorobotics Lab**, Graduate Researcher advised by Dr. Howie Choset. August 2022 to May 2024, Pittsburgh.
* **Orangewood Labs**, Mechanical Engineer. July 2021 to July 2022, Delhi.

## Education

* **M.S. Mechanical Engineering, Robotics concentration**, Carnegie Mellon University, 2024. GPA 3.85 out of 4.0
* **B.Tech Production Engineering**, NIT Tiruchirappalli, 2021

## Get in touch

* LinkedIn, [yash-prakash-979853172](https://www.linkedin.com/in/yash-prakash-979853172/)
* Email, [yprakash.cmu@gmail.com](mailto:yprakash.cmu@gmail.com)
* Website, [yash-prakash1.github.io](https://yash-prakash1.github.io)
