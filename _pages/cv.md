---
permalink: /
title: "About me"
toc: true
---



My name is Na Tang, an EPSRC Research Fellow in the Department of Electronic and Electrical Engineering at [the University of Sheffield](https://www.sheffield.ac.uk/), UK. My advisor is Professor [<font color="blue">Xiaoli Chu</font>](https://www.sheffield.ac.uk/eee/people/academic-staff/xiaoli-chu). I am leading an EPSRC-funded project that integrates underwater acoustic communications, backscatter communications, and piezoelectric materials. 
My research focuses on piezoelectric node modeling, trajectory and resource allocation optimization, and communication framework development for 5G and beyond networks, e.g., underwater backscatter, UAV, fog computing and 5G VoNR.
Additionally, I am interested in reconfigurable intelligent surfaces (RIS), wireless power transfer, and AI-based networking, aiming to advance environmental sustainability and health monitoring through theoretical research and prototype development.


I received a Ph.D. degree in Communication and Information Systems from [the University of Chinese Academy of Sciences (UCAS)](https://en.wikipedia.org/wiki/University_of_the_Chinese_Academy_of_Sciences), China, in March 2022, supervised by Professor Baoqing Li. I received a B.S. degree in Electronic Information Science and Technology from [Central South University (CSU)](https://en.wikipedia.org/wiki/Central_South_University), China, in June 2016. 


<span style="font-weight: bold; color: blue;"> I am looking for relevant job opportunities.</span>

<h2 id="projects"><i class="ion-ios-lightbulb"></i> Research</h2>

### Underwater Acoustic Backscatter Communications
Backscattering enables battery-less and perpetually operating Internet-of-Things (IoT) devices to sweep through ambient electromagnetic waves (in terrestrial networks) or acoustic waves (in underwater networks) rather than generate new waves.
The emerging underwater acoustic backscatter communication (UABC) has the potential to avoid the need for underwater nodes to actively emit acoustic signals, thus, reducing their energy consumption. However, there is a lack of a clear design, comprehensive modeling or analysis of UABC systems. 

This research studies a UABC system where a high-power transceiver transmits acoustic signals and a piezoelectric UABC node modulates and reflects the incident acoustic signals back to the transceiver. The main components of this research are listed as follows:
1. Developed a circuit model for UABC nodes to enable the mathematical analysis of their acoustic impedance across varying materials and operating frequencies from its physical design.
2. Designed the node load to maximize the nodes’ acoustic reflection coefficient based on the circuit model.
3. Developed a comprehensive communication analytical framework for UABC that supports the derivation of the bit error rate of UABC as a function of the piezoelectric material properties, operating frequencies of UABC nodes, transmission distances, ambient noise intensities, carrier wave frequencies, and wind speeds.

Our research bridges the fields of underwater acoustics, backscatter communications, and piezoelectric materials.

<!--
<table style="text-align:center" class="center">
<tr>
<td><img src="/assets/paper_img/UABC/UABC_systemmodel2.png" style="width:38vw"/></td>
</tr>
<tr>
<td><Figurenum>The architecture of a UABC system.</Figurenum></td>
</tr>
</table>


<table style="text-align:center" class="center">
<tr>
<td><img src="/assets/paper_img/UABC/UABC_circuitmodel.png" style="width:28vw"/></td>
</tr>
<tr>
<td><Figurenum> The equivalent circuit for a UABC node.</Figurenum></td>
</tr>
</table> 
-->
<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/UABC/UABC_systemmodel2.png" style="width:34vw"/></th>
<th>  <img src="/assets/paper_img/UABC/UABC_circuitmodel.png" style="width:24vw"/> </th>
</tr>
<tr>
<td><Figurenum>The architecture of a UABC system.</Figurenum></td>
<td><Figurenum>The equivalent circuit for a UABC node.</Figurenum></td>
</tr>
</table>

###  Joint Trajectory Design and Power Control for UAV-Enabled NOMA Networks
Unmanned aerial vehicles (UAVs)-assisted communications have emerged as essential complements to terrestrial networks, offering on-demand deployment, high mobility, and line-of-sight (LoS) dominant channels.

The focus of this research is to explore the interplay between UAVs and power-domain non-orthogonal multiple access (NOMA) in the following aspects:
1. Investigated the sum secrecy rate (or lifetime) maximization problems by jointly optimizing the 3D UAV trajectory (or hovering position), decoding order, and power allocation, while enhancing the spectrum efficiency of the whole system by exploring power-domain NOMA in conjunction with cognitive radio. 
2. By formulating, transforming and solving a non-convex mixed-integer programming problem, we propose a near-optimal power allocation strategy and UAV trajectory design based on the Lagrange duality, the constrained ellipsoid method,  the successive convex approximation technique and the penalty function method.
3. Based on the analytical and numerical results, practical insights are provided into how the interference threshold for protecting the primary receivers should be chosen to improve the sum secrecy rate (or lifetime).

<!--
1. Investigated the lifetime maximization for IoT devices by jointly optimizing the UAV hovering position, decoding order, and transmission power control. 
* Obtained the globally optimal solution to the joint optimization for small-scale scenarios based on the Lagrange duality and the constrained ellipsoid method.
*  Devised a low-complexity sub-optimal algorithm for large-scale scenarios based on the successive convex approximation technique and the penalty function method. 
* Based on the analytical and numerical results, practical insights are provided into how the cognitive IoT devices’ transmit power should be controlled to prolong their lifetime while keeping the interference to the primary network below the tolerance threshold.
-->

<table style="text-align:center" class="center">
<tr>
<td><img src="/assets/paper_img/UAV_NOMA/UAV_NOMA.jpg" style="width:25vw"/></td>
</tr>
<tr>
<td><Figurenum>The UAV-enabled NOMA communication system.</Figurenum></td>
</tr>
</table>


### Joint Maneuver and Beamwidth Optimization for UAV-Enabled Multicasting
This research investigates the interaction between a UAV’s directional antenna beamwidth and its 3D trajectory (or location) and their joint optimization for minimizing the mission completion time while guaranteeing coverage in a multicasting system. 
* Our algorithm design considers both a quasi-stationary UAV scenario and a mobile UAV scenario. 
* We present analytical and numerical results to reveal the performance gains (in both mission completion time and energy consumption) achievable by jointly optimizing the UAV’s position/trajectory, antenna direction and beamwidth.

<table style="text-align:center" class="center">
<tr>
<td><img src="/assets/paper_img/UAV_beamwidth/UAV_beamwidth.jpg" style="width:25vw"/></td>
</tr>
<tr>
<td><Figurenum>The UAV-enabled multicasting communication system.</Figurenum></td>
</tr>
</table>


###  Design and Realization of Chaotic Synchronization Based on DSP
Chaotic synchronization occurs when two or more systems align their state variables, either directly or according to a specific function, with the synchronization criterion being that the error between these variables approaches zero. Chaotic synchronization has attracted growing interest in secure communication, image encryption, and signal processing.

This research focuses on the numerical simulation and digital circuit implementation of integer-order and fractional-order chaotic system synchronization. My main contributions are listed as follows:

1. Solved the simplified Lorenz system and fractional simplified hyperchaotic Lorenz system using the Runge-Kutta algorithm
and Adomian algorithm and realized the synchronization of the above Lorenz systems in numerical simulations.
2. Realized simplified synchronization of a chaotic Lorenz system using the drive-response method and implemented a fractional simplified hyperchaotic Lorenz system using the function projective synchronization method on the TMS320F28335 digital signal process (DSP).

<table style="text-align:center" class="center">
<tr>
<th><img src="/assets/paper_img/DSP/DSP1.jpg" style="width:13vw"/></th>
<th>  <img src="/assets/paper_img/DSP/DSP2.jpg" style="width:18vw"/> </th>
</tr>
<tr>
<td><Figurenum>DSP-based experimental platform for chaotic system synchronization.</Figurenum></td>
<td><Figurenum>x1-x3 phase diagram of a chaotic attractor.</Figurenum></td>
</tr>
</table>


<h2 id="industry-experience"><i class="ion-ios-lightbulb"></i>Development Project </h2>
### Inter-RAT Blind Redirection for Voice and Data Services in 5G EMMB Base Station
Inter-radio access technology (Inter-RAT) blind redirection is a process where a user device switches between different radio access technologies, such as from LTE to New Radio, based solely on network instructions and without the need for measurement reports. This mechanism is crucial during the early stages of 5G deployment, where LTE and New Radio coexist, as it optimizes resource allocation and enhances user experience by ensuring seamless coverage.

Voice services, traditionally carried on dedicated channels in GSM, UMTS, or LTE networks, have transitioned to standard data channels with the introduction of Voice over LTE (VoLTE) and Voice over New Radio (VoNR). This shift enables the use of Inter-RAT blind redirection techniques for voice services. However, voice calls require lower network latency and higher stability than general data traffic. Thus, it is essential to differentiate between voice and data services during Inter-RAT blind redirection to maintain service quality.

My main duties include:
1.  Developed an algorithm using C that enables Inter-RAT blind redirection for differentiating voice and data services in the resource management module (RRM) of 5G eMMB base stations.
2.  Designed, executed and reported the test use cases for this new feature. 
3.  Collaborated on code reviews and updated feature specifications.

<h2 id="publications"><i class="ion-ios-book"></i> Publications</h2>
1. **Na Tang**, Yang Liu, Xiaoli Chu and Ian F. Akyildiz, “Design, modeling and analysis of underwater acoustic backscatter
communications,” Proc. IEEE Conf. Commun. (ICC), accepted, 2024.  
1. Yang Liu, **Na Tang**, Xiaoli Chu, Yang Yang, and Jun Wang, “LPCSE: Neural speech enhancement through linear predictive
coding,” Proc. IEEE Global Commun. Conf. (Globecom), Dec. 2022, pp. 5335-5341. [<font color="blue">[PDF]</font>](https://ieeexplore.ieee.org/abstract/document/10001278)
1. **Na Tang**, Hongying Tang, Baoqing Li, and Xiaobing Yuan, “Lifetime maximization for UAV-enabled cognitive-NOMA IoT
networks,” arXiv:2110.01133, 2021. [<font color="blue">[PDF]</font>](https://arxiv.org/pdf/2110.01133)
1. **Na Tang**, Hongying Tang, Baoqing Li, and Xiaobing Yuan, “Cognitive NOMA for UAV-enabled secure communications: Joint
3D trajectory design and power allocation,” IEEE Access, vol. 8, pp. 159965-159978, Sep. 2020. [<font color="blue">[PDF]</font>](https://ieeexplore.ieee.org/abstract/document/9184057)
1. **Na Tang**, Hongying Tang, Baoqing Li, and Xiaobing Yuan, “Joint maneuver and beamwidth optimization for UAV-enabled
multicasting,” IEEE Access, vol. 7, pp. 149503–149514, Oct. 2019. [<font color="blue">[PDF]</font>](https://ieeexplore.ieee.org/abstract/document/8866720)


<h2 id="skills"><i class="ion-ios-gear"></i> Skills</h2>

* Hands-on experience with RRM module development in 5G RAN and basic knowledge of 3GPP standards.
* Proficient in C/C++, and Matlab. Grade Two in National Computer Rank Examination.
* Skilled in theoretical and algorithmic aspects of convex optimization methods (e.g., ADMM, interior point method).
* Hands-on experience with circuit design, printed circuit board (PCB) design and manufacturing, and microcontroller
programming.
* Course: Machine Learning, Matrix Analysis, Stochastic Process, Digital Signal Processing, Fundamentals Wireless
Communication, Data Structures and Algorithms.


<h2 id="work-experience"><i class="ion-ios-filing"></i>Work Experience</h2>

* EPSRC research fellowship at The University of Sheffield (Dec. 2022 - Nov. 2024)

* Protocol Software Engineer at Datang Mobile Communication Equipment Co., Ltd (Aug. 2022 - Nov. 2022)


<h2 id="professional-activities"><i class="ion-ios-bookmarks"></i> Professional Activities</h2>

* TPC member of the IEEE Vehicular Technology Conference (VTC) Fall 2023 and 2024.
* TPC member of the IEEE International Symposium on Personal, Indoor and Mobile Radio Communications (PIMRC) 2024.
* TPC member of the International Conference on Computer Communications and Networks (ICCCN) 2024.
* Excellent Reviewer of the IEEE Transactions on Network Science and Engineering.
* Peer-reviewing papers for IEEE Transactions on Machine Learning in Communications and Networking, IEEE Internet of
Things Journal, IEEE Transactions on Network Science and Engineering, IEEE Open Journal of Vehicular Technology, IEEE International Conference on Communications (ICC), and IEEE Global Communications Conference (Globecom).



