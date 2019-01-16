---
permalink: /
title: "About me"
toc: true
---

My name is Yang Liu, a final-year PhD candidate in Communication and Information System at Chinese Academy of Sciences(CAS). My advisor is professor [Yang Yang](http://sist.shanghaitech.edu.cn/sist_en/2018/1227/c3846a38413/page.htm). 
I received the Bachelor degree from Anhui University, China, in 2012, and Master degree from Beihang University, China, in 2016. 
My project involves mobile interaction, embedded system, wireless localization. Currently, my work focuses on novel mobile interaction technologies using wireless signals, especially acoustic signals. Recently, I have designed and developed an acoustic based localization and tracking prototype system using an android smartphone and some commercial speakers, which could provide fine-grained motion tracking in 2D and 3D space, and could detect small and slow movement (e.g. human breathing). I’m highly self-motivated, because I hope that the knowledge that I learned could help me to bring inventive ideas into real-world applications. 



<h2 id="projects"><i class="ion-ios-lightbulb"></i> Projects</h2>

### Fine-grained Acoustic based Ranging (ACM MM'18 demo)
In recent years,  motion tracking methods based on dedicated hardware devices (e.g., infrared devices and cameras) are used successfully in many commercial products, such the Vive of HTC, and the 360 VR camera of Microsoft. However, these methods are either expensive or have large computation overhead, and not good enough for tracking a user’s gesture or posture in our daily life.
Compared with the dedicated hardware devices, ubiquitous devices with reliable speakers and microphones can be developed to achieve cheap acoustic-based motion tracking, which is appropriate for low-power and low-cost IoT applications.
In this demonstration, we propose and implement an acoustic based ranging scheme, which can be developed on commercial mobile devices (e.g., smartphones) to provide fine-grained location and motion tracking for the devices.
Our key insight is that we can use the acoustic phase change at mobile devices to achieve accurate distance measurement, as shown in Fig. 1.
A prototype system of ranging is implemented on a standard Android smart phone, which could monitor human breathing, as shown in Fig. 2. Experiment results show that our method can achieve an impressive millimeter-level ranging accuracy, and can detect small and slow movements.


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
In order to address this challenging,  a new parameter called Multipath Effect Ratio (MER) is proposed to estimate and mitigate the effects of multipath fading on received signals at different frequencies.
MER is calculated from a "constellation" diagram, in which R<sub>β</sub> is orthogonal to R<sub>α</sub> , as shown in Fig.4.
Based on MER, PAMT is developed to track mobile device's motion by using multiple speakers.
A prototype system of motion tracking is implemented on a standard Android smart phone. 
Experiment results show the measurement errors are less than 2 mm and 4 mm in one-dimensional and two-dimensional scenarios, respectively.
An example to illustrate the migration of multipath fading effects is shown in Fig.3 and Fig.4. 

<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/IoT2019/Multipath_fading.png" width="600" /></th>
<th>  <img src="/assets/paper_img/IoT2019/MDV.gif" width="290" /> </th>
</tr>
<tr>
<td><Figurenum>Moving distance measured at different
frequencies</Figurenum></td>
<td><Figurenum>A new feature indicating multipath fading effects </Figurenum></td>
</tr>
</table>

As shown in Fig.3, a speaker continuously transmits acoustic signals at 18 KHz, 18.8 KHz and 19.6 KHz at the same time. Then, we move an Android smartphone away uniformly from the speaker at the distance of 1 meter.
The smartphone obtains the signals frame by frame, and each frame has 512 sampling points with 48 KHz sampling rate.
Fig. 4 shows the the constellation diagram of carrier signals near Frame A in Fig.3.
The phase at the outer ring can be measured more accurately than that near the center due to larger signal to noise ratio. Thus, the shape ring can be seen as a feature to indicate the impact of multipath fading.
From the Fig.4, we can seen that the signal at 18.8 KHz is more close to the outer ring than others, so that we can select the phase change at 18.8 KHz to estimate moving distance in Frame A, as shown in Fig. 3. We repeat the selection in each frame, and obtain the estimation of total moving distance.



A brief introduction of this project is shown in the video below.


<div class="video-container">
<iframe src="https://www.youtube.com/embed/GcR-4sVL_1o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>  


A complete demonstration can be found [HERE](https://youtu.be/GcR-4sVL_1o).

###  Low-Cost Real-Time Power Measurement and Abnormal Diagnosis
Engineers engaged in the development of battery power-supply device are facing huge pressure to reduce the consumption of power.
During the development, engineers are required to known the real-time power computation of Devices Under Test(DUT).
In this work, a low-cost and real-time power measurement platform called PTone is proposed to provide a more flexible way for the low-power device development than cumbersome equipment, as shown in Fig.5.
We compare PTone with Keysight 34465A, and results shows that PTone estimates power to within 0.37% of its correct value, as shown in Fig.6.
Compared with traditional measuring equipment, such as Keysight 34465A (>$1500 on Amazon), our system (<$20) use could be widely deployed.
Based on the real-time power consumption measured by the system, we propose a SVM based method to diagnose abnormal status of DUT.
Our key insight is that the real-time power consumption of low power device changes with the periodic system process, such as data collecting, simple signal processing, signal transmission, and sleep.
Then, unique features are extracted from the power consumption, and used as a fingerprint to diagnose the system's status.


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




<h2 id="skills"><i class="ion-ios-gear"></i> Skills</h2>



* Digital signal processing
  * Audio processing
  * Sonar, radar
  * Array signals processing
  * Signal processing for wireless communication
  * Spectral density estimation
* Embedded System development.
  * Android development
  * IoT devices using microcontrollers,such as STM32, MP430.
  * Linux-based system, such as Ubuntu, OpenWrt.
  * FPGA development
* Optimization theory, machine learning.


<h2 id="publications"><i class="ion-ios-book"></i> Publications</h2>

1. **Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, and Xuewu Dai, “RAMTEL: Robust Acoustic Motion Tracking using Extreme Learning Machine for Smart Cities”, IEEE Internet of Things Journal (IF 5.863, Under Review).
2.	**Yang Liu**, Wuxiong Zhang, Yang Yang, Weidong Fang, Fei Qin, Xuewu Dai, PAMT: Phase-based Acoustic Motion Tracking in Multipath Fading Environments. IEEE Conference on Computer Communications (INFOCOM’19) (acceptance rate: 19.7%).
3.	**Yang Liu**, Yang Yang, Weidong Fang, Wuxiong Zhang, Demo: Phase-based Acoustic Localization and Motion Tracking for Mobile Interaction. ACM multimedia conference (ACM MM’18).
4.	**Yang Liu**, Yubing Wang, Weiwei Gao, Wuxiong Zhang, Yang Yang. A Novel Low-Cost Real-Time Power Measurement Platform for LoWPAN IoT Devices. Mobile Information Systems. 2017. 1-14.
5.	Weidong Fang, Wuxiong Zhang, Yang Yang, **Yang Liu**, Wei Chen. A resilient trust management scheme for defending against reputation time-varying attacks based on BETA distribution. Science China Information Sciences, 2017, 60(4):040305.
  
<h2 id="work-experience"><i class="ion-ios-filing"></i> Work Experience</h2>

### Research at Shanghai Institute of Microsystem and Information Technology (SIMIT), Chinese Academy of Sciences (CAS), China (Sept. 2016- Present)

I have designed and developed an acoustic based localization and tracking prototype system using an android smartphone and commercial speakers. The system could provide fine-grained mobile interaction in 2D and 3D space with high sensitivity.

I have designed and developed a prototype system for detecting gas leakage based on the distinctive acoustic spectrum change caused by gas leakage, which will be deployed to some natural gas wells of Shanghai as a pilot project.

### Research at Shanghai Research Center for Wireless Communications, Shanghai, China (Oct. 2014- Sept. 2016)

I have designed and developed a prototype system for intelligent pillow to avoid snoring using an embedded system, which could adjust the height of the pillow automatically according to the snore it heard. 

By migrating and modifying the Linux kernel module (ath9k) of OpenWrt, I have developed OpenWrt based wireless router, which could get Channel State Information (CSI) of WiFi signal between commercial router and smartphones.

### Project Intern at Topelec Tech, Co. Ltd, Beijing,China (Feb. 2014- Aug. 2014)

I have finished studies and applications about network protocol in practical projects, such as uIP, Zigbee 2007/pro and 900M RFID.

### Teaching Assistant (Sept. 2013- Jan. 2014)
As a teaching assistant, I assisted our teacher to address students' questions and gave a course about digital circuit design experiment for undergraduates.

### Intern at EDA Laboratory of Beihang University, Beijing, China (June 2013- Sept. 2013)
Before the start of my graduate studies, Professor Jinming Dong gave me an opportunity to join the EDA laboratory. 

### Summer student at school’s innovation Laboratory of Anhui University (July 2009- Aug. 2009)
I had the opportunity to work at the school’s innovation lab for National Undergraduate Electronic Design Contest.


