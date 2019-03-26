---
permalink: /
title: "About me"
toc: true
---

My name is Yang Liu, a final-year PhD candidate in Communication and Information System at University of Chinese Academy of Sciences (UCAS). My advisor is professor [<font color="blue">[Yang Yang]</font>](http://sist.shanghaitech.edu.cn/sist_en/2018/1227/c3846a38413/page.htm). 
I received the Bachelor degree from Anhui University, China, in 2012, and Master degree from Beihang University, China, in 2016. 
My project involves mobile sensing, embedded system, and wireless localization. Currently, my work focuses on novel mobile interaction technologies using wireless signals, especially acoustic signals.
I’m highly self-motivated, because I hope that what I learned could help me to bring new ideas into real-world applications. 

<h2 id="projects"><i class="ion-ios-lightbulb"></i> Projects</h2>

### Fine-grained Acoustic based Ranging (ACM MM'18 demo)
In this demonstration, we propose and implement a fine-grained ranging system on commercial mobile devices (e.g., smartphones).
Our key insight is that we can use the acoustic phase change to achieve accurate distance measurement, as shown in Fig. 1.
A prototype system of ranging is implemented on a standard Android smart phone, which could monitor human breathing, as shown in Fig. 2. 


<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/MM2018/phase-based-ranging.gif" width="500" /></th>
<th>  <img src="/assets/paper_img/MM2018/breathing.png" width="450" /> </th>
</tr>
<tr>
<td><Figurenum>Phase based ranging</Figurenum></td>
<td><Figurenum>Breath monitoring using acoustic signals</Figurenum></td>
</tr>
</table>

### PAMT: Phase-based Acoustic Motion Tracking in Multipath Fading Environments (INFOCOM'19)

We propose and implement a fine-grained and low cost acoustic mobile interaction method called PAMT,  which allows mobile users to interact with computer by using gesture interface in practical indoor environments.
In this project, we first propose a phase based acoustic ranging method, which could measure accurate moving distance of mobile devices based on the phase change of received signals.
However, in practical indoor environments, it's challenging to obtain accurate moving distance change based on the phase change due to the attenuation and reflection of acoustic signals.
In order to address this challenging, we proposed a method to estimate the impact of multipath fading in real-time, as shown in Fig.3. Further, we calculate actual moving distance by combining the moving distances measured at different frequencies, as shown in Fig.4. Experiment results show the measurement errors are less than 2 mm and 4 mm in one-dimensional and two-dimensional scenarios, respectively.


<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/IoT2019/MDV.gif" width="290" /></th>
<th>  <img src="/assets/paper_img/IoT2019/Multipath_fading.png" width="600" /> </th>
</tr>
<tr>
<td><Figurenum>A new feature indicating multipath fading in real-time</Figurenum></td>
<td><Figurenum> Moving distance measured at different
frequencies</Figurenum></td>
</tr>
</table>

A brief introduction of this project is shown in the video below or can be found [<font color="blue">[HERE]</font>](https://1drv.ms/v/s!AnKk_YbMz-w-eJUKCf7u5CKMRQk).

<div class="video-container">
<iframe src="https://www.youtube.com/embed/HTM1ShTAH2A" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  


A complete demonstration is shown in the video below or can be found 
[<font color="blue">[HERE]</font>](https://1drv.ms/v/s!AnKk_YbMz-w-d-nGrF4VN8KJ40U)

<div class="video-container">
<iframe src="https://www.youtube.com/embed/GcR-4sVL_1o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  

###  Low-Cost Real-Time Power Measurement and Abnormal Diagnosis
Engineers engaged in the development of battery power-supply device are facing huge pressure to reduce the consumption of power.
During the development, engineers are required to known the real-time power computation of Devices Under Test (DUT).
In this work, a low-cost and real-time power measurement platform called PTone is proposed to provide a more flexible way for the low-power device development than cumbersome equipment, as shown in Fig.5.
We compare PTone with Keysight 34465A, and results shows that PTone estimates power to within 0.37% of its correct value, as shown in Fig.6.
Compared with traditional measuring equipment, such as Keysight 34465A (>$1500 on Amazon), our system (<$20) use could be widely deployed.
Based on the real-time power consumption measured by the system, we propose a SVM based method to diagnose abnormal status of DUT.
Our key insight is that the real-time power consumption of low power device changes with the periodic system process, such as data collecting, simple signal processing, signal transmission, and sleep.

<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/PTone/hardware.png" width="360" /></th>
<th>  <img src="/assets/paper_img/PTone/wave.png" width="300" /> </th>
</tr>
<tr>
<td><Figurenum>Real-time power measurement system</Figurenum></td>
<td><Figurenum>Power consumption measured by our system and digital multimeter</Figurenum></td>
</tr>
</table>

<h2 id="publications"><i class="ion-ios-book"></i> Publications</h2>

1. **Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai. RAMTEL: Robust Acoustic Motion Tracking using Extreme Learning Machine for Smart Cities. *IEEE Internet of Things Journal* (IF: 5.863). [<font color="blue">[PDF]</font>](/_pdf/RAMTEL.pdf)
2.	**Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai. PAMT: Phase-based Acoustic Motion Tracking in Multipath Fading Environments. *IEEE Conference on Computer Communications* (INFOCOM’19, acceptance rate: 19.7%). [<font color="blue">[PDF]</font>](/_pdf/PAMT.pdf)
3. Weidong Fang, Wuxiong Zhang, Wei Chen, **Yang Liu**, and Chaogang Tang. TMSRS: Trust Management-based Secure Routing Scheme in Industrial Wireless Sensor Network with Fog Computing. *Wireless Networks*, 2019
4.	**Yang Liu**, Yang Yang, Weidong Fang, and Wuxiong Zhang. Demo: Phase-based Acoustic Localization and Motion Tracking for Mobile Interaction. *ACM multimedia conference* (ACM MM’18). [<font color="blue">[PDF]</font>](/_pdf/Demo2018.pdf)
5.	**Yang Liu**, Yubing Wang, Weiwei Gao, Wuxiong Zhang, and Yang Yang. A Novel Low-Cost Real-Time Power Measurement Platform for LoWPAN IoT Devices. *Mobile Information Systems*. 2017. 1-14. [<font color="blue">[PDF]</font>](/_pdf/PTone.pdf)
6.	Weidong Fang, Wuxiong Zhang, Yang Yang, **Yang Liu**, and Wei Chen. A resilient trust management scheme for defending against reputation time-varying attacks based on BETA distribution. *Science China Information Sciences*, 2017, 60(4):040305. [<font color="blue">[PDF]</font>](/_pdf/trust_management.pdf)



<h2 id="skills"><i class="ion-ios-gear"></i> Skills</h2>

* Digital signal processing
  * Audio processing
  * Sonar, radar
  * Array signal processing
  * Signal processing for wireless communication
  * Spectral density estimation
* Embedded system development.
  * Android application development
  * IoT software development.
  * Linux-based system development, such as Ubuntu, OpenWrt.
  * FPGA development
* Optimization theory, machine learning.





  
<h2 id="work-experience"><i class="ion-ios-filing"></i> Work Experience</h2>

* Research at Shanghai Institute of Microsystem and Information Technology (SIMIT), Chinese Academy of Sciences (CAS), China (Sept. 2016- Present)

* Research at Shanghai Research Center for Wireless Communications, Shanghai, China (Oct. 2014- Sept. 2016)

*  Project Intern at Topelec Tech, Co. Ltd, Beijing,China (Feb. 2014- Aug. 2014)

*  Teaching Assistant (Sept. 2013- Jan. 2014)

* Intern at EDA Laboratory of Beihang University, Beijing, China (June 2013- Sept. 2013)

*  Summer student at school’s innovation Laboratory of Anhui University (July 2009- Aug. 2009)

