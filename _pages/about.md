---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 🔥 About me 

Welcome to my home page! 

My name is Zedong Zhang, a junior researcher focuses on Robotics and AI. I currently work as a part-time research assistant at the National University of Singapore. I am seeking opportunities to continue my study as a Ph.D. candidate. My specific research interests include Robotics and Control, Medical Robots, Surgical Robots, AI, Reinforcement Learning, Life-long Learning, Non-parametric Learning, Offline RL, Human-Robot Collaboration, etc.

As for my education background, I graduated from [Chongqing University](https://www.cqu.edu.cn/) (project 985) with a B.Eng degree in Mechanical Engineering. In year 4, I participated in an exchange programme to study at the [National University of Singapore (Suzhou) Research Institute](http://en.nusri.cn/), where I completed my Final-Year-Project advised by [Prof. Zhang Yunfeng](https://cde.nus.edu.sg/me/staff/zhang-yunfeng/). I received my M.Sc degree from the [National University of Singapore](https://nus.edu.sg) in June 2022.

My research experience includes working at the [Centre for Smart Medical Technology of NUS research institute](http://en.nusri.cn/research/areas/amd/) supervised by [Prof. Ren Hongliang](https://cde.nus.edu.sg/bme/staff/dr-ren-hongliang/), during which period of time I participated in a National Key R&D project on Gastrointestinal Surgical Robot. After that, I have been working at the [NUS Advanced Robotics Centre](https://arc.nus.edu.sg/) supervised by [Prof. Ang Jr Marcelo](https://cde.nus.edu.sg/me/staff/ang-jr-marcelo-h/), in the realms of AI and human-robot collaboration.

📖 Educations
=========

-   ---------------------------------------------------- -------------------------

> ### **National University of Singapore**   📅 **[Aug 2021 -- June 2022]**
>
>  Master of Science in **Mechanical Engineering**

---------------------------------------------------- -------------------------

- **Academic Grades:**    *GPA:* 4.83/5.0 (Top 3/147)   
  
- **Courses:**  Neural Networks, Machine Vision, Linear System, Engineering Materials in Medicine, Engineering Acoustics, etc.


-   ---------------------------------------------------- -------------------------

> ### **National University of Singapore (Suzhou) Research Institute**   📅 **[Sep 2020 -- June 2021]**
> 
>  yr-4 exchange study in **Mechanical Engineering**

---------------------------------------------------- -------------------------

- **Academic Grades:** *GPA:* 90.44/100 (Top 5/110)   
  
- **Courses:**  Robot Mechanics and Control, Modern Control System, Automation in Manufacturing, Numerical Methods in Engineering, etc.

-   ---------------------------------------------------- -------------------------

> ### **Chongqing University**   📅 **[Sep 2017 -- June 2020]**
>
>  Bachelor of Engineering in **Mechanical Engineering**

---------------------------------------------------- -------------------------

- **Academic Grades:** *GPA:* 84.5/100  
  
- **Courses:**  Classical Mechanics, Mechanical Design, Theory of Machines and Mechanisms, Mechanics of Materials, etc.



# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE/RSJ IROS 2022</div><img src='images/gesr.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## GESRsim: Gastrointestinal Endoscopic Surgical Robot Simulator

Huxin Gao, **Zedong Zhang** (co-first author), Liyang Lin, Changsheng Li, Xiao Xiao, Liang Qiu, Xiaoxiao Yang, Ruoyi Hao, Xiuli Zuo, Yanqing Li, Hongliang Ren 
  
#### Accepted by IEEE/RSJ IROS 2022
### <a href="_pages/GESRsim.pdf" download>PDF📃</a>

</div>
</div>

# 📝 Submitted Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/firl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## A Versatile Agent for Fast Learning From Human Instructors

Yiwen Chen, **Zedong Zhang** (co-first author), Haofeng Liu, Jiayi Tan, Chee-Meng Chew, Marcelo Ang
  
#### Submitted for AAAI 2023, under review
### [PDF📃](https://arxiv.org/pdf/2203.00251)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/g2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Modeling, Analysis and Control of a Gastrointestinal Endoscopic Surgical Robot with Tunable Stiffness

Huxin Gao, Ruoyi Hao, Changsheng Li, Xiao Xiao, Xiaoxiao Yang, Liang Qiu, **Zedong Zhang**, Xiuli Zuo, Yanqing Li, Hongliang Ren 
  
#### Under review  
### <a href="images/gesr_abstract.txt" download>Abstract📃</a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/bal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

## Economical Precise Manipulation and Auto Eye-Hand Coordination with Binocular Visual Reinforcement Learning

Yiwen Chen, Sheng Guo, **Zedong Zhang**, Lei Zhou, Xian Yao Ng, Marcelo Ang 
  
#### Under review 
### [PDF📃](https://arxiv.org/pdf/2205.05963)

</div>
</div>

⌨ Projects
========

###  **Key Technologies and Systems of Gastrointestinal Endoscopic Minimally Invasive Surgical Robot**        

> ***Gastrointestinal Endoscopic Surgery, Natural Orifice Transluminal Endoscopic Surgical Robot*** 
>
> **Dec 2021 - Feb 2022**

- Key research project of Ministry of Science and Technology of China under Grant 2018YFB1307700, advised by Prof. Ren Hongliang (NUS). 
- Participated in the design and development of the manipulators and actuation module of a novel gastrointestinal
surgical robot (GESR) system. Specifically, we designed several **cable-driven, 3.5mm-diameter robot manipulators**, which are flexible serial robots of 6 DoFs that can work inside an endoscopic platform. The salient innovation is the achievement of **tunable joint stiffness**.
- We developed a robot simulator for our GESR as a subproject. The simulator is based on **Coppeliasim**, which contains full CAD models and kinematics. Besides, we designed canonical surgical training scenes with the help of professional surgeons. We endowed the simulator with novel control strategies (**visual servoing, DRL**) to prove its potential as an algorithm development platform. It is also the first GESR simulator.


###  **Pre-trained Models in Human-Robot Collaboration**        

> ***Reinforcement Learning, Interactive Task Learning*** 
>
> **Aug 2021 - May 2022**

- Master's Final-Year-Project, advised by Prof. Ang Jr Marcelo (NUS).
- We designed an algorithm for intelligent agents that can achieve **few-shot learning from human instructors** (demonstrations). This work is based on the idea of policy reuse. We adopted a **hierarchical policy structure**, and promoted learning efficiency through observation minimization and reward-augmented imitation learning. In this way, we achieved one-shot learning on a multi-stage task in mini-grid environment, with a success rate of 94%.

***

###  **Binocular Visual Alignment using Reinforcement Learning**        

> ***Visual Servoing, Reinforcement Learning, Machine Vision***       
>
> **Jan 2022 - Sep 2021**

- We designed an algorithm for learning alignment manipulation tasks, e.g., screw insertion, using binocular vision. We refer to a lines alignment control law in binocular images to avoid the calculation of depth information. We validated our approach on a dual arm KINOVA MOVO robot and achieve a success rate over 90%.

***

###  **Approximate Nearest Neighbor Search in Q-learning**        

> ***Reinforcement Learning, Non-parametric Learning, Episodic Control***       
>
> **Apr 2022 - Present**

- We intend to promote the performance of non-parametric Learning, e.g., episodic control, by introducing novel ANN search method. Additionally, we employ contrastive learning algorithm for better embedding. Our method can separate working memory from long term memory, i.e., relax the need to update the full gamut of parameters every iteration.

***

###  **Machine Learning in Solving the Vehicle Routing Problem**        

> ***Machine Learning, Combinatorial Optimization, VRP***       
>
> **Sep 2020 - Apr 2021**

- Undergraduate Final-Year-Project,  advised by Prof. Zhang Yunfeng (NUS).
- Studied a novel approach in solving combinatorial optimization problem using deep reinforcement learning algorithm. The method is based on Pointer Networks and can achieve a performance commensurate with SOTA conventional methods.
***

🏆 Honors and Awards
======

- Award of Outstanding Student, NUS Research Institute, June 2021
- Certificate of Merit, EMdeIC Global 2021, Nov 2021

💻 Experiences
==========

-   ------------------------------------------------ -------------------------

> ### **RA at National University of Singapore** 
>
> > **May 2022 - Present**
>

- Advanced Robotics Centre, Collab-AI, supervised by Prof. Ang Marcelo.
- Participated in researches regarding human robot collaboration and reinforcement learning (see Project Sec.).

***

> ### **RA at National University of Singapore (Suzhou) Research Institute**  
>
> > **Dec 2020 -- July 2021**
- Centre for Smart Medical Technology, supervised by Prof. Ren Hongliang.
- Participated in national key research project on Gastrointestinal Endoscopic Surgical Robot (see Project sec.).

***

> > ***R & D Engineer at Robert Bosch GmbH***
>
> > **July 2019 -  Sep 2019**
- Bosch Thermal Technology, R & D Dept.
- Completed a benchmark project on novel products. Conducted evaluation for the performance including flue-gas analysis, determination of energy efficiency, noise measuring, low temperature resistance, etc.

***

> > ***R & D Engineer at Cooper Standard Automotive Inc.***
>
> > **July 2018 -  Sep 2018**
- R & D Dept, Fluid group.
- Analysis and design of vehicle pipeline system using CAD software.

***
----


