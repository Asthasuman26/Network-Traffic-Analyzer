# Network Traffic Analyzer
## Project Overview

This project is a comprehensive Network Traffic Analysis and Security Monitoring Toolkit developed in Python. The objective of this task was to design and implement a system capable of analyzing both firewall logs and packet capture (PCAP) files to identify suspicious activity, detect potential threats, and generate structured security reports.

The solution demonstrates practical skills in log parsing, data analysis, threat detection logic, reporting automation, and user interface development.

## Objective of the Task

The core objective of this assignment was to:

Parse and analyze structured and semi-structured network data

Detect anomalous or malicious network behavior

Generate meaningful security insights

Provide automated reporting in user-friendly formats

Build both command-line and GUI-based interaction modes

The project simulates real-world cybersecurity workflows used in Security Operations Centers (SOCs) and network monitoring environments.

## Firewall Log Analysis

The firewall analysis component focuses on extracting and interpreting security-relevant information from firewall logs (such as FortiGate and Palo Alto formats).

## Key Work Completed:

Parsed raw firewall log entries

Normalized timestamps and extracted critical fields such as:

Source and destination IP addresses

Ports

Protocols

Actions (allowed/blocked)

Identified patterns indicating suspicious behavior, including:

Port scanning attempts

Brute-force login patterns

Repeated blocked access attempts

Unusual access to sensitive ports

Generated structured summary reports

Created visualizations to highlight top attackers and traffic trends

Enabled optional geolocation-based enrichment for IP analysis

This module demonstrates understanding of log correlation, anomaly detection logic, and data transformation techniques.

## PCAP Traffic Analysis

The PCAP analysis module processes packet capture files to inspect actual network traffic flows.

## Key Work Completed:

Converted packet capture data into structured analyzable format

Extracted packet-level information including:

IP addresses

Ports

Protocol types

Packet sizes

Communication timestamps

Designed detection logic for:

Port scanning behavior

Beaconing activity (periodic communication patterns)

Large data transfers (possible data exfiltration)

Suspicious payload patterns

Automated generation of Excel summaries and HTML reports

Created visual dashboards to simplify interpretation of results

This part of the project reflects applied knowledge in network forensics, protocol analysis, and behavioral anomaly detection.

## Reporting and Visualization

A major focus of the assignment was not just detecting threats, but presenting findings clearly.

The system automatically generates:

Structured Excel summaries

HTML-based reports

Visual charts for traffic distribution and threat patterns

Alert summaries highlighting potential security incidents

This ensures that technical findings are converted into actionable intelligence.

## User Interaction Design

To improve usability, the project includes:

Command-line interface for direct execution and automation

Graphical user interface for easier interaction and file selection

This demonstrates attention to usability and accessibility in cybersecurity tooling.


## Conclusion

The Network Traffic Analyzer project showcases the ability to build an end-to-end security analysis tool that processes raw network data and converts it into meaningful insights. It reflects real-world cybersecurity practices, combining automation, analysis, visualization, and reporting into a cohesive system.
