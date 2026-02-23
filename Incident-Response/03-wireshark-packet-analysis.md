# Incident Analysis: Network Traffic Inspection
**Date:** 01/12/2025
**Case Status:** Completed
**Severity:** Low

## Executive Summary
I was tasked with analyzing a packet capture file using Wireshark to understand how network traffic is structured and how to identify key information inside packets, with the objective of working on examining packet details and applying display filters as part of the detection and analysis process.

## Technical Analysis (The 5 W's)
* **Who**: I acted as the analyst responsible for reviewing the network logs.
* **What:** I examined packet headers and payloads to identify protocols and communication patterns.
* **When:** I performed this review during a detection and analysis lab session.
* **Where:** The analysis took place in a virtual lab environment using a Windows Virtual Machine.
* **Why:** I conducted this analysis to build foundational skills in network traffic inspection and to support the detection and analysis phase of incident response.

## Technical Walkthrough
### How I analysed the Traffic
I started by opening the capture file and looking at the overall conversation list to examine packet headers and payload details. Then, I used display filters to narrow down specific types of traffic, such as HTTP and TCP. This was critical step because it allowed me to ignore background noise and focus on the data that actually mattered for the investigation.

### Key Skills I applied
* **Filtering:** I used specific commands to find exactly what I was looking for among thousands of packets.
* **Dissection:** I looked deep into the layers of the packets (checking IP addresses at the Network Layer and port numbers at the Transport Layer.
* **Payload Inspection:** I checked the actual data being sent to ensure the communication matched the protocol being used.

## Lessons Learned
I realized that in a real security incident, an Analyst is often overwhelmed with data. This scenario taught me that knowing how to quickly filter for the right information is just as important as knowing how to read the data itself.
