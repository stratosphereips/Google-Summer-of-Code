# Google Summer of Code 2023
Repository with data and documents for Google Summer of Code 2023 proposal for the Stratosphere Laboratory

# About the Stratosphere Laboratory
Our group conducts research at the intersection of machine learning, cybersecurity and helping others. We are part of the Artificial Intelligence Center, Faculty of Electrical Engineering, Czech Technical University in Prague.

--What is the GSoC and links--

-- About that you should get in contact in Discord and discuss new possible ideas. The ideas we put here are an indication only --


# Projects Proposal Ideas
*  [Stratosphere Linux IPS (Slips)](https://github.com/stratosphereips/Google-Summer-of-Code-2023#stratosphere-linux-ips)
*  [Attacker IP Threat Intelligence Framework (AIP)](https://github.com/stratosphereips/Google-Summer-of-Code-2023#attacker-ip-threat-intelligence-framework-aip)
*  [Project 3]()
*  [Project 3]()


# Stratosphere Linux IPS

### Description of Slips
Slips is a behavioral intrusion prevention system that uses machine learning to detect malicious behaviors in network traffic. Slips focus on targeted attacks, detection of command and control channels, and providing a good visualization for the analyst. It can analyze network traffic in real-time, network captures such as pcap files, and network flows produced by Suricata, Zeek/Bro, and Argus. Slips processes the input data, analyzes it, and highlights suspicious behavior that needs the analyst's attention.


### Project Link: https://github.com/stratosphereips/StratosphereLinuxIPS

### Expected size
175 (4hs per day for 12 weeks) 

### Expected length of project 
10-22 weeks

### Difficulty
Medium

### Idea 1: Improvement of Slips web interface

#### Proposed lists of topics that could be included:
- Better display of timewindow numbers,  start time, and end time
- Show a list of Blocked Profiles in one place
- Show the history of threat levels and confidence of each profile
- If an IPv4 profile has an available IPv6 we should show it. and vice versa
- Show the current threat level of each profile 
- Show the user agent of each profile 
- Show the MAC of each profile
- Live (Asynchronous) updating of the web view. (meaning that without refreshing the page, new info should be displayed)
- Show Slips logo somewhere
- Show Progress bar 
- Show list of loaded modules and disabled modules
- Show current model status (are we in training or testing mode?)
- Show the current gateway’s IP and MAC, and mark the gateway profile as ‘Gateway’
- Have a whitelist tab to show what IPs/domains/orgs are currently whitelisted
- Manage the configuration of slips from the web

**Mentor**: [Sebastian Garcia](https://github.com/eldraco)

**Technology**: javascript, jquery, flask, python


**Current status**: working web interface

<img src="https://raw.githubusercontent.com/stratosphereips/Google-Summer-of-Code-2023/main/images/web_interface.png"  width="900" height="300">

### Idea 2: Better Installation

#### Proposed lists of topics that could be included:

- An easy way to install slips, Any of the following:
  - using apt
  - snap
  - dpkg
  
- Bonus: brew installation of slips (if the student has a macOS)  

**Mentor**: [Alya Gomaa](https://github.com/AlyaGomaa)

**Current status**: Slips is working in docker, and can be installed locally using install.sh and conda/pip. 

**Technology**: python, package management, brew



### Idea 3: Improving Performance


#### Proposed lists of topics that could be included:


- CPU Profiling; Using python profilers: for example profile and cProfile modules or others
- Memory Profiling; Using memray, Memory Profiler module or others that may do
- Provide statistics and graphs about which parts or modules of slips need optimizations
- Provide optimization ideas; what can be done differently? Why and How?


**Mentor**: [Alya Gomaa](https://github.com/AlyaGomaa)

**Current status**: basic previous work in this area

**Technology**: python, profiling tools


---

# Attacker IP Threat Intelligence Framework (AIP)

### Description of AIP

### Project Link: 

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

## Communication
The following Mmethods will be used for all projects:

Talk about communication mediums: discord? slack etc? how often are meetings? video calls or coice calls?

Reports: how often? reports about blockers/progress etc

Communications will be done over discord/slack, weekly/daily reports are going to be required, 

