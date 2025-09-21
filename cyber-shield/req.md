# Cyber Shield Project - System Requirements
The following instructions outline the (simulated) gathered requirements for the project. All instructions are summarized.

> [!NOTE]
> The instructions are as given, no further stakeholder interviews were conducted.

## General
Cyber Shield is a cyber security platform solution that can handle the detection and investigation of cyber threats. It broadly consists of three main components:
1. An engine for threat detection and forensics 
2. A central unit for processing the signals that were picked-up - The Cyber Automation Process (CAP)
3. A UI to display results to analysts that act upon them


## Detection & Forensics Engine
This component handles 4 main capabilities: (1) file analysis on user machines, (2) command and control to analyse IP traffic, (3) an end point agent that monitors events on user machines, and (4) network forensics for traffic indexing.


## CAP - Cyber Automation Process
The CAP acts as the brain of the platform, centralizing all analytics and results gathering from the engines. The CAP then issues signals to the investigation portal, if an action seems suspicious.


## Investigation Portal
This UI allows analysts to act upon all events registered by the platform. It also contains report generation capabilities.


## Other Requirements
This section contains general requirements like SLA uptimes or expected volumes per customer category (segregated by company size).