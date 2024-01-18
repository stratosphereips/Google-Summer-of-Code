<p align="center">
<img src="https://user-images.githubusercontent.com/2458867/220867986-ce57cfbc-8fbb-4890-9ca6-22e9ca04b5e2.png" alt="Logo" width="200" class="center">
</p>



# Stratosphere Google Summer of Code 2023
This is the repository with all the information you need to know about the Google Summer of Code for Stratosphere Laboratory 2023

## About the Stratosphere Laboratory
Stratosphere conducts research at the intersection of machine learning, cybersecurity and helping others by developing free software tools. We are part of the Artificial Intelligence Center, Faculty of Electrical Engineering, Czech Technical University in Prague. Stratosphere is an official organization in the Google Summer of Code 2023.

## Google Summer of Code
The [Google Summer of Code](https://summerofcode.withgoogle.com/) is a global, online program focused on bringing new contributors into open source software development. GSoC Contributors work with an open source organization on a 12+ week programming project under the guidance of mentors.


# Projects you can contribute for Stratosphere
1. Slips (Stratosphere Linux IPS)
2. Attacker IP Threat Intelligence Framework (AIP)

# Communication
We strongly suggest that you go to our public Discord and talk to us there to start discussing your own ideas on what to work on and make us questions. Go here to [Discord](https://discord.gg/zu5HwMFy5C).

# Project Slips (Stratosphere Linux IPS)

### Description of Slips
Slips is a behavioral intrusion prevention system that uses machine learning to detect malicious behaviors in network traffic. Slips focus on targeted attacks, detection of command and control channels, and providing a good visualization for the analyst. It can analyze network traffic in real-time, network captures such as pcap files, and network flows produced by Suricata, Zeek/Bro, and Argus. Slips processes the input data, analyzes it, and highlights suspicious behavior that needs the analyst's attention.

Slips is full of features and crazy ideas, detection methods, databases, machine learning and many many more (including a P2P detection system!). So get to know the project, try it, and come up with your own ideas.

### Project Link: 
https://github.com/stratosphereips/StratosphereLinuxIPS


## 🧑🏽‍💻 Work Idea 1: Improvement of Slips web interface

This idea consist in taking the current web page of Slips and implement a set of medium to advanced features to make it better. 

#### Proposed lists of topics that could be included:

- Adapting the web interface to show all the information Slips has on each profile (connections, attacks, detections, etc.)
- Manage the complete configuration of slips from the web.
- Add graphs for continuous visualization of traffic
- Add explanations for alerts, evidence, and flows.

### Expected hours of work
175 (4hs per day for 12 weeks) 

### Expected length of the project 
10-22 weeks

### Difficulty
Medium
 
**Detail of the tasks description**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#improvement-of-slips-web-interface

**Mentor**: [Sebastian Garcia](https://github.com/eldraco)

**Technology**: JavaScript, JQuery, flask, Python

**Current status**: There is a working web interface

<img src="https://raw.githubusercontent.com/stratosphereips/Google-Summer-of-Code-2023/main/images/web_interface.png"  width="900" height="300">

---

## 🧑🏽‍💻 Slips idea 2: Better Installation

Slips has a hard time being installed in many systems given its dependencies to many tools and to TensorFlow framework. Help Slips being easier to install and use!

#### Proposed lists of topics that could be included:

- An easy way to install slips in many systems: Linux, Macos, Windows, Rpi, etc.
- Make packages for some Linux systems, Debian, Ubuntu, Fedora
- Make a brew package of slips


### Expected hours of work
175 (4hs per day for 12 weeks) 

### Expected length of the project 
10-22 weeks

### Difficulty
Medium

**Details of the tasks**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#better-installation

**Mentor**: [Alya Gomaa](https://github.com/AlyaGomaa)

**Current status**: Slips is working in docker, and can be installed locally using install.sh and conda/pip. 

**Technology**: python, package management, brew

---

### 🧑🏽‍💻 Slips idea 3: Improving Performance
Slips wants to do many detections in your network, but that requires CPU, memory and sometimes GPU for the machine learning. This idea is to help Slips improve its performance by consuming less CPU and memory for its detections. Goal: to make Slips be able to work continusly in a large network.

#### Proposed lists of topics that could be included:

- CPU usage profiling
- Memory usage profiling
- Provide statistics and graphs about which parts or modules of slips need optimizations
- Provide optimization ideas


### Expected hours of work
175 (4hs per day for 12 weeks) 

### Expected length of the project 
10-22 weeks

### Difficulty
Medium

**Detailed tasks**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#improve-performance

**Mentor**: [Alya Gomaa](https://github.com/AlyaGomaa)

**Current status**: basic previous work in this area

**Technology**: Python, profiling tools



## 🧑🏽‍💻 Slips idea 4: Machine Learning detections

#### Proposed lists of topics that could be included:

- Anomaly detection methods:

Detect anomalies in the amount of traffic send and received

Detect anomalies in the HTTP User Agents

Detect anomalies in the IP addresses each host connects TO and receives FROM

Detect anomalies in the countries if the destination IPs an IP connects to

Adapt the retraining module of AD for users to adapt modesl to their traffic

- Supervised detection methods:

Improve the detection of C&C channels using the stratoletters by retraining in new dataset

Detect DGA by using sequence models or transformers


#### Important
More importantly your prosposal should tell us not only how to run some ML library with an algorithm but to:
- evaluate and process the datasets
- know if you can design the required features
- evaluate the features
- create a correct training/evaluation/testing setup
- see the explanation of why it fails (XAI)
- design a concept drift solution (retraining, drift detection, etc) 
- understand that you will have many different training data and testing data
- develop a way to not use the algorithm if it performs badly


### Expected hours of work
175 (4hs per day for 12 weeks) 

### Expected length of the project 
10-22 weeks

### Difficulty
Hard

**Detailed tasks**: https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Ideas.md#machine-learning-detection

**Mentor**:   [Sebastian Garcia](https://github.com/eldraco)

**Current status**: Beta. Some things are working, but they need tuning, retraining etc.

**Technology**: Python, tensorflow, keras, sklearn

---

---
<br>
<br>


# Project Attacker IP Prioritization Framework (AIP)
## Description of AIP
AIP is a framework to design, create and evaluate the performance of Threat Intelligence lists. The current most used protection mechanism in our security community are threat intelligence feeds, but there is no clear understanding of which ones are best, why they are best, which ones do not work and how to evaluate them. More importantly, there was no framework to create new models that output TI feeds. AIP allows anyone to create their own lists and compare their performance with public lists. Stratosphere Laboratory has its own honeypots and we use the AIP framework to create new blocklists for the community every day.

### Project Link: https://github.com/stratosphereips/AIP

## 💻 AIP Idea 1: AIP Web User Interface (AIP-WebUI)
### Description
Create a web application to display and manage the information produced by the tool. People running AIP and generating lists will use the AIP-WebUI to publish their lists in a user-friendly way.

The main page will show a logo, a general project description, and a query form. The logo and the description of the project should be customizable. The query form will receive an IP and show the lists in which the IP appears. A checkbox will allow querying the IP in all the historical blocklists generated by AIP.

AIP Tool produces several types of blocklists, depending on different models. We will evaluate the proposals about the best way to show a summary of each list that will include at least the following:

* A description of the algorithm generating the list: Propose a method for AIP Tool to make this information available so AIP-WebUI can add new models and blocklists transparently.

* A plot with the metrics: AIP Tool provides a .csv file with metrics. The AIP-WebUI tool will consume it to create and show the graphs.

* Ten Top-ranked attackers (if applicable): Some models generate blocklists with a ranking. For those models, the AIP-WebUI application will show the top-ranked IPs. 

The number of different blocklists depends on the AIP Tool configuration. If new models become available, the AIP-WebUI should be flexible and add the new blocklists automatically. 

The application must include a REST/API endpoint to query if an IP is in a list.

**Extra points**: bulk query of IPs. 

**Extra points**: Include a Dark/Light theme switch.

### Note for wannabe contributors:

This Idea states some of the requirements for the AIP-WebUI and its integration with the AIP Tool. You may have other ideas we want to hear. Explain them clearly in your proposal and include a paragraph detailing how your idea will improve the project if followed. Also, include information about your assumptions for your idea to work. For example: "To load the top-ranked attackers properly, the blocklist must include a column named 'rank'".

Follow the guidelines described here to write the proposals: https://google.github.io/gsocguides/student/writing-a-proposal. Pay special attention to the "deliverables" section.

Submit your proposal drafts to the #aip channel in discord. We suggest a Google Docs read-only link for which a mentor will ask permissions to make comments with a personal email address.

**Mentor**: [Joaquin Bogado](https://github.com/jwackito/)

**Current status**: Beta Testing

**Technology**: Python, Flask

## Expected size
175 (4hs per day for 12 weeks) 

## Expected length of project 
10-22 weeks

## Difficulty
Medium


### What we expect from you
We expect you to get motivated by the projects and to get involved in how to make them better! You will have to work around 4hs per day (small projects) to 6hs per day (large project), during 12 weeks (22 weeks max if we agree). We can agree in your time off, and holidays and how to better work with us. 

To get approved in your work during the summer you will be required to present a report and Google will ask us an evaluation of your work. This will happen twice during the summer.

## Application template (for students)

For students applying to one of Stratosphere projects, you can fill out the below form and send it to us by email 

https://github.com/stratosphereips/Google-Summer-of-Code-2023/blob/main/Application_template.md


**For Slips** send your application to the following emails in Cc:

Alya Gomaa alyaggomaa@gmail.com

Sebastian Garcia sebastian.garcia@agents.fel.cvut.cz

Veronica Valeros veronica.valeros@aic.fel.cvut.cz 

stratosphere@aic.fel.cvut.cz

**For AIP** send your application to the following emails in Cc:

Joaquin bogadjoa@fel.cvut.cz

Sebastian Garcia sebastian.garcia@agents.fel.cvut.cz

Veronica Valeros veronica.valeros@aic.fel.cvut.cz 

stratosphere@aic.fel.cvut.cz

## Communication

It is very important that you keep communicating with us. Use our [Discord](https://discord.gg/zu5HwMFy5C) (slips channel) and [GitHub](https://github.com/stratosphereips/StratosphereLinuxIPS/) channels to contact us and to ask questions.

We will be in permanent contact, but we will have from 1 to 3 meetings per week to guide you on what to do.

