# Table of Contents
[**1. Related Work Survey**](#related-work-survey)
---
> [**1.1. Introduction**](#introduction)
> ---
> * [**1.1.1. Scope of Document**](#scope-of-document)
> * [**1.1.2. Project Overview**](#project-overview)
> 
> [**1.2. Related Work Survey**](#related-work-survey)
> ---
> * [**1.2.1. Survey Introduction**](#survey-introduction)
> * [**1.2.2. Background Information**](#background-information)
> * [**1.2.3. Related Work Reviews**](#related-work-reviews)
> * [**1.2.4. Comparison To Proposed Work**](#comparison-to-proposed-work)

[**2. Project Planning**](#project-planning)
---
> [**2.2. Work Packets**](#work-packets)
> ---
> * [**2.2.1. WP-1 Project Management**](#work-packet-1-project-management)
>
> [**2.3. Project Schedule & Milestones**](#project-schedule--timeline)
> ---
> [**2.4. Conclusion**](#conclusion)
> ---
[**3. Appendix**](#appendix-1)
---
[**4. Citations**](#citations)
---
# Related Work Survey

## Introduction

### Scope of Document

### Project Overview

## Related Work Survey

### Survey Introduction

### Background Information

### Related Work Reviews

#### Related Work 1:

### Comparison To Proposed Work

# Project Planning

## Work Packets
### Work Packet 1: [Project Management](/A4b%20Project%20Planning%20Report/wp-1_ProjectManagement.md)

### Technical Content _(Block diagrams, Flowcharts, etc)_

### Links Between Sub-Works

### Team Member Assignments & Responsibilities

## Project Schedule & Timeline

### Deliverables & Milestones
> Milestone 1: **Literature Review & Technology Selection** milestone 1 is expected to be met by progress report 1. We are expecting to have a comprehensive literature review on [_SDN_](#software-defined-networking), [_Load Balancing_](#load-balancing) and telemetry technologies.
>
> Milestone 2: **System Architecture Design** we expect to have a detailed system architecture diagram outlining component interactions & data flow.
>
> Milestone 3: **Telemetry Data Collection & Processing** we expect to complete milestone 3 by progress reports 3 and 4. At this stage documentation for a prototype system to collect and process incoming network telemetry data from [_OVS_](#open-vswitch-ovs) instances using [_GoFlow2_]().
>
> Milestone 4: **Load Balancing Algorithm Development** by the 5th and final reports we expect to have finalized the documentation and begin the development of the prototype load balancing algorithm.
>
> Milestone 5: **Integration & Testing** at this stage in second semester of the project we are striving to integrate the prototype load balancer with the [_SDN_](#software-defined-networking) controller and [_OVS_](#open-vswitch-ovs) instances.
>
> Milestone 6: **Performace Evaluation** at this stage in the second semester we will evaluate the performance of the prototype load balancer using tools like [_Docker_](#docker-and-containers) containerization for deploying [_Mininet_](#mininet) instances to generate simulated network traffic.
>
> Milestone 7: **Refinement & Optimization** we will strive at this point to iteratively refine the prototype load balancer's algorithm and system architecture based on the performance evaluation results.
>
> Milestone 8: **Final Prototype Demonstration** At the end of the second semester we will strive to have a completed prototype that is ready to deploy and showcase.

## Conclusion

## Appendix
#### Software Defined Networking:
> Software defined networking is an approach to network management that enables dynamic and programmatically efficient network configuration to improve network performance. Software-Defined Nwtworking has emerged as a transformative paradigm in network management, decoupling the control plane from the data plane. This separation enables centralized management and control of network resources, facilitating greater flexibility, scalability, and programmability.

#### Load Balancing:
> Load Balancing is the technique of distributing network traffic to better optimize the load across multiple network devices

#### OpenFlow:
> OpenFlow is a standardized protocol for controlling network devices, enabling programmatic configuration and management.
> OpenFlow provides a foundation for SDN implementations and facilitates the collection of telemetry data.

#### Mininet:
> Mininet is a virtual network emulator that allows for the creation and testing of various network topologies and configurations.
> Mininet offers a flexible environment for developing and evaluating SDN applications and telemetry systems.

#### Go (Golang):
> The Go programming language is a modern, high-performance language designed for building scalable and efficient applications.
> The Go programming language offers strong concurrency features, garbage collection, and a simple syntax, making it suitable for network programming and telemetry systems.

#### Kafka:
> Kafka is a distributed streaming platform designed for handling real-time data ingestion and processing.
> Offers high throughput, low latency, and fault tolerance, making it suitable for handling large volumes of telemetry data.

#### Open vSwitch (OVS):
> Open vSwitch is a virtual switch that can be deployed on a variety of platforms, including physical servers, virtual machines, and containers.
> Open vSwitch provides a flexible and scalable solution for connecting virtual machines and containers to physical networks.
> Open vSwitch offers support for OpenFlow, making it a key component of many SDN environments.

#### Docker and Containers
> Docker provides a platform for packaging applications into containers, which can be easily deployed, managed, and scaled across different environments.
> Containers offer improved portability, isolation, and resource efficiency compared to traditional virtual machines.
> Our telemetry system can be packaged as a containerized application, making it easier to deploy and manage in cloud environments.


## Citations
1. Khriji, Sabrine et al. “Design and Implementation of a Cloud-Based Event-Driven Architecture for Real-Time Data Processing in Wireless Sensor Networks.” The Journal of supercomputing 78.3 (2022): 3374–3401. Web.

