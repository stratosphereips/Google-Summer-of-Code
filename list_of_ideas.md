# Stratosphere List of Ideas GSoC

We are accepting proposals for two projects as part of the Google Summer of Code:

- **Slips**: a free software behavioral Python intrusion prevention system (IDS/IPS) that uses machine learning to detect malicious behaviors in the network traffic. [[GitHub](https://github.com/stratosphereips/StratosphereLinuxIPS)]
- **AI VPN**: A Free-Software AI-Powered Network Forensics Tool [[GitHub](https://github.com/stratosphereips/AIVPN)]


## Table of Contents

- [Slips #1 ML Detection](#slips-1-ml-detection)
- [Slips #2 Better Installation](#slips-2-better-installation)
- [Slips #3 Slips Global P2P Threat Intelligence](#slips-3-slips-global-p2p-threat-intelligence)
- [AI VPN #1 CLI Management Console with Textual](#ai-vpn-1-cli-management-console-with-textual)
- [AI VPN #2 Codebase Enhancement through Unit Testing](#ai-vpn-2-codebase-enhancement-through-unit-testing)
- [AI VPN #3 Improve the AI VPN report of results](#ai-vpn-3-improve-the-ai-vpn-report-of-results)
- [AI VPN #4 System Audit and Internal Report](#ai-vpn-4-system-audit-and-internal-report)

## Slips #1: ML Detection
![Static Badge](https://img.shields.io/badge/Mentor-Sebastian_Garcia-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Alya_Gomaa-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Difficult-blue?labelColor=purple&color=white)

**Gist**: Improve the ML algorithms in Slips by adding multi-modal anomaly detection. 

**Skills**: Machine learning experience, Python, communication, a basic understanding of networking data.

**Description**: It is necessary to plan and design an anomaly detection schema that would use DNS, TLS, HTTP, ASN, and the time of the requests. Then, it is necessary to combine them in a multi-modal system. This task requires good training/testing before deploying. Additionally, it should also allow the users to retrain with their own traffic (like now with the MLflow module).

**Expected outcomes**: We expect i) an anomaly detection module in Slips that can work well with many types of data merged, at least in the development branch, and ii) a blog sharing the new detection module and what it does for the community to learn about it. 


## Slips #2 Better Installation
![Static Badge](https://img.shields.io/badge/Mentor-Alya_Gomaa-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Sebastian_Garcia-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Difficult-blue?labelColor=purple&color=white)

**Gist**: Easier installation of Slips and support for updates for future versions

**Skills**: Snapcraft or Debian packaging, communication

**Description**: Slips has grown into a sizable project with many dependencies, including libraries and tools such as Zeek and tensorflow framework. Due to its complexity, it is currently not easy for users to install Slips. Currently, Slips is supported in Docker and can be installed locally using install.sh and conda/pip. This project involves analyzing Slips and determining the best way to publish it to a known package management system.

**Expected outcomes**: We expect i) to be able to install Slips using a single command (e.g., apt install slips or snap install slips) and ii) a plan for automatically updating future versions of Slips.

## Slips #3 Slips Global P2P Threat Intelligence
![Static Badge](https://img.shields.io/badge/Mentor-Alya_Gomaa-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Sebastian_Garcia-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Medium-blue?labelColor=purple&color=white)

**Gist**: Implementation of the global P2P threat intelligence sharing system.

**Skills**: Python, Communication.

**Description**: We already designed a complex global P2P system and trust model for Slips (see the sub-modules repositories Iris and Fides). This project involves first implementing the servers and infrastructure for the global P2P network in the world. Second, implementing both systems inside Slips so it can use the global P2P system for sharing TI. Iris is the Global P2P system. And Fides is the global trust model.

**Expected outcomes**: We expect i) the implementation in cloud servers of the DNS and P2P infrastructure for sharing TI and ii) the implementation of Fides and Iris inside Slips. 



## AI VPN #1 CLI Management Console with Textual
![Static Badge](https://img.shields.io/badge/Mentor-Veronica_Valeros-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Maria_Rigaki-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Easy-blue?labelColor=purple&color=white)

**Gist**: Design and implement a management CLI using Textual

**Skills**: Python, UI, Communication

**Description**: We want to design and implement a new management CLI that allows admins to check the status of the AI VPN: users provisioned, ongoing activity, be able to provision and expire profiles, etc. We want this CLI to be developed using [Textual](https://textual.textualize.io/). The data of the modules is stored in Redis, and there are already some functions implemented to retrieve that data.

**Expected outcomes**: We expect i) a functional CLI merged in GitHub covering some basic functionality and ii) a blog post describing the CLI and how people can use it.

## AI VPN #2 Codebase Enhancement through Unit Testing
![Static Badge](https://img.shields.io/badge/Mentor-Veronica_Valeros-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Maria_Rigaki-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Easy-blue?labelColor=purple&color=white)

**Gist**: Identify core functionality and add unit testing to make the codebase more robust

**Skills**: Python, Unit Testing, CI/CD

**Description**: The objective is to strengthen the AI VPN codebase, ensuring it is more robust and resilient. We want this to help enhance the CI/CD process to make the process of integrating community contributions better. This project consists of designing and prioritizing the implementation of comprehensive Unit Tests throughout the codebase, improving its test coverage.

**Expected outcomes**: We expect i) a plan in the form of issues with priorities to increase the coverage of unit tests based on priorities, ii) implementation of unit tests in the code, and iii) successful integration of the tests through the GitHub CI/CD we already have.

## AI VPN #3 Improve the AI VPN report of results
![Static Badge](https://img.shields.io/badge/Mentor-Veronica_Valeros-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Sebastian_Garcia-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Medium-blue?labelColor=purple&color=white)

**Gist**: Find a better way to communicate the results to the user

**Skills**: UI, bash, web design (would be nice), communication

**Description**: The current AI VPN report has a lot of room for improvement. We want to discuss, design, evaluate, and implement how to do this better. Specifically, we want to communicate the results better and show the value of the AI VPN framework. 

**Expected outcomes**: We expect i) a new report produced merged at least in the development branch, ii) a blog post explaining the new report and what information users should expect to be there after an analysis.

## AI VPN #4 System Audit and Internal Report
![Static Badge](https://img.shields.io/badge/Mentor-Veronica_Valeros-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Mentor-Maria_Rigaki-blue?labelColor=blue&color=white)
![Static Badge](https://img.shields.io/badge/Size-90_hours-blue?labelColor=brown&color=white)
![Static Badge](https://img.shields.io/badge/Difficulty-Easy-blue?labelColor=purple&color=white)

**Gist**: Design and implement an AI VPN audit and generate a report

**Skills**: Python, Communication, Redis, UI

**Description**: Most features of the AI VPN focus on the clients, however, the administrators of the AI VPN also need to know and report the usage of the tool. How much is it used? How much traffic? How many incidents? Etc. This task involves putting yourself in the role of the admin, developing a report generator that would gather all sorts of valuable metrics, and creating a report that can be read and shared by the admin with interested stakeholders.

**Expected outcomes**: We expect i) a new tool that is able to pull the metrics needed for the report, ii) a report (text, PDF, or other) that will show the findings, and iii) a blog post explaining to other AI VPN users administrators what information is now available on this report.
