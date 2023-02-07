# Google Summer of Code 2023
Repository with data and documents for Google Summer of Code 2023 proposal for the Stratosphere Laboratory

## About the Stratosphere Laboratory
Our group conducts research at the intersection of machine learning, cybersecurity and helping others. We are part of the Artificial Intelligence Center, Faculty of Electrical Engineering, Czech Technical University in Prague.

## Google Summer of Code
The [Google Summer of Code](https://summerofcode.withgoogle.com/) is a global, online program focused on bringing new contributors into open source software development. GSoC Contributors work with an open source organization on a 12+ week programming project under the guidance of mentors.



# Projects Proposal Ideas
*  [Stratosphere Linux IPS (Slips)](https://github.com/stratosphereips/Google-Summer-of-Code-2023#stratosphere-linux-ips)
*  [Attacker IP Threat Intelligence Framework (AIP)](https://github.com/stratosphereips/Google-Summer-of-Code-2023#attacker-ip-threat-intelligence-framework-aip)


# Project Slips (Stratosphere Linux IPS)

### Description of Slips
Slips is a behavioral intrusion prevention system that uses machine learning to detect malicious behaviors in network traffic. Slips focus on targeted attacks, detection of command and control channels, and providing a good visualization for the analyst. It can analyze network traffic in real-time, network captures such as pcap files, and network flows produced by Suricata, Zeek/Bro, and Argus. Slips processes the input data, analyzes it, and highlights suspicious behavior that needs the analyst's attention.

Slips is full of features and crazy ideas, detection methods, databases, machine learning and many many more (including a P2P detection system!). So get to know the project, try it, and come up with your own ideas.


### Project Link: 
https://github.com/stratosphereips/StratosphereLinuxIPS

### Expected size
175 (4hs per day for 12 weeks) 

### Expected length of project 
10-22 weeks

### Difficulty
Medium

### Idea 1: Improvement of Slips web interface

#### Proposed lists of topics that could be included:

- Showing all the info we have on each profile.
- Manage the configuration of slips from the web.
- Fix a few bugs.
 
**Detailed tasks**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#improvement-of-slips-web-interface

**Mentor**: [Sebastian Garcia](https://github.com/eldraco)

**Technology**: JavaScript, JQuery, flask, python


**Current status**: working web interface

<img src="https://raw.githubusercontent.com/stratosphereips/Google-Summer-of-Code-2023/main/images/web_interface.png"  width="900" height="300">

### Idea 2: Better Installation

Slips has a hard time being installed in many systems given its dependencies to many tools and to TensorFlow framework. Help Slips being easier to install and use!

#### Proposed lists of topics that could be included:

- An easy way to install slips
- Bonus: brew installation of slips

**Detailed tasks**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#better-installation

**Mentor**: [Alya Gomaa](https://github.com/AlyaGomaa)

**Current status**: Slips is working in docker, and can be installed locally using install.sh and conda/pip. 

**Technology**: python, package management, brew


### Idea 3: Improving Performance
Slips wants to do many detections in your network, but that requires CPU, memory and sometimes GPU for the machine learning. This idea is to help Slips improve its performance by consuming less CPU and memory for its detections.

#### Proposed lists of topics that could be included:

- CPU Profiling
- Memory Profiling
- Provide statistics and graphs about which parts or modules of slips need optimizations
- Provide optimization ideas

**Detailed tasks**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#improve-performance

**Mentor**: [Alya Gomaa](https://github.com/AlyaGomaa)

**Current status**: basic previous work in this area

**Technology**: python, profiling tools


---

# Attacker IP Threat Intelligence Framework (AIP)

### Description of AIP

### Project Link:  https://github.com/stratosphereips/AIP-Blacklist-Algorithm

### Expected size
175 (4hs per day for 12 weeks) 

### Expected length of project 
10-22 weeks

### Difficulty
Medium

### Idea 1:

#### Proposed lists of topics that could be included:

**Mentor**: [name](https://github.com/)

**Current status**: 

**Technology**: python, ...


### Idea 2:

#### Proposed lists of topics that could be included:

**Mentor**: [name](https://github.com/)

**Current status**: 

**Technology**: python, ...


### Idea 3:

#### Proposed lists of topics that could be included:

**Mentor**: [name](https://github.com/)

**Current status**: 

**Technology**: python, ...

--- 

## What we expect from you
We expect you to get motivated by the projects and to get involved in how to make them better! You will have to work from 4hs per day (small projects) to 6hs per day (large project), during 12 weeks (22 weeks max if we agree). We can agree in your time off, and holidays and how to better work with us. 

To get approved in your work during the summer you will be required to present a report and Google will ask us an evaluation of your work. This will happen twice during the summer.


## Communication

It is very important that you keep communicated with us. Use our [Discord](https://discord.gg/zu5HwMFy5C) (slips channel) and [GitHub](https://github.com/stratosphereips/StratosphereLinuxIPS/) channels to contact us and to ask questions.

We will be in permanent contact, but we will have from 1 to 3 meetings per week to guide you on what to do.

