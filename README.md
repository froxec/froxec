## About me 👋
## Brief
- 💡 Fields of interest: Machine Learning 🦾, Computer Science 🖥️, Control Systems and Autonomous Systems 🏎️ ✈️
- 📚 Education: Machine Learning (Msc) and Automation and Control Systems (BEng) at Gdańsk University of Technology

## Contact
e-mail: durawa.p.soft@gmail.com

## Skills 

#### ML Tools
<div class="MLSkills">
<img src="https://github.com/devicons/devicon/blob/master/icons/pytorch/pytorch-original.svg" alt=PyTorch, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg" alt=Tensorflow, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" alt=numpy, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" alt=pandas, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/r/r-original.svg" alt=pandas, width=30, height=30/> 
</div>

#### Programming Languages/Tools
<div class="ProgrammingLanguages">
<img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" alt=python, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/cplusplus/cplusplus-original.svg" alt=cpp, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/c/c-original.svg" alt=c, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/cmake/cmake-original.svg" alt=cmake, width=30, height=30/>
</div>

#### System Tools
<div class="ProgrammingLanguages">
<img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-original.svg" alt=docker, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" alt=linux, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/ros/ros-original.svg" alt=c, width=30, height=30/>
<img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original.svg" alt=git, width=30, height=30/>
</div>

## Projects

### Oversteer and understeer detection system for iRacing

This project implements OS/US detection system for iRacing simulator. The detection model is based on Adaptive Neuro Fuzzy Inference System (ANFIS)  [[2]](#2), [[3]](#3).
The idea to use ANFIS is based on work of Hirche and Ayalew [[1]](#1).

#### Data collection
- Data was collected on [Centripetal Circuit](https://www.iracing.com/tracks/centripetal-circuit/).
- Each test consisted of Sine with Dwell maneuver.
- Tests are were performed under different vehicle velocities, sine frequencies, dwell times, maximum steering angles.
- Dataset is balanced for left and right turns.
- Data collection procedure was derived from [[1]](#1).

#### Model
- Model was trained using the ANFIS-PyTorch framework implemented by J. Power [[3]](#3).
- Model for Mazda MX-5 is available.
- Mazda MX-5 model struggle when vehicle runs on kerbs.

#### References
- <a id="1">[1]</a> 
Hirche, B. and Ayalew, B.,
"A Fuzzy Inference System for Understeer/Oversteer Detection Towards Model-Free Stability Control"
SAE Int. J. Passeng. Cars - Mech. Syst. 9(2):2016, doi:10.4271/2016-01-1630.
- <a id="2">[2]</a>
Jang, Jyh-Shing.,
(1993). ANFIS Adaptive-Network-based Fuzzy Inference System.
Systems, Man and Cybernetics, IEEE Transactions on. 23. 665 - 685. 10.1109/21.256541. 
- <a id="3">[3]</a>
Power, J.
Implementation of ANFIS using the pyTorch framework
Source: https://github.com/jfpower/anfis-pytorch [Access: 29.04.2024]

<!--
**froxec/froxec** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
