# teleoperation-on-l4-autonomous-cars# 

## Table of Contents
1. [Introduction](#introduction)
2. [Abstract](#abstract)
3. [Architecture and Modes of Operation](#architecture-and-modes-of-operation)
4. [Companies Involved](#companies-involved)
5. [Challenges and Solutions](#challenges-and-solutions)
    - [Latency Issues](#latency-issues)
    - [Embodiment Issues](#embodiment-issues)
    - [Workload Issues](#workload-issues)
    - [Remote Interaction with Humans](#remote-interaction-with-humans)
6. [Real-Time Analysis of Disengaged Data](#real-time-analysis-of-disengaged-data)
7. [Discussion on Optimal Solutions](#discussion-on-optimal-solutions)
8. [Conclusion](#conclusion)
9. [References](#references)

## Introduction
Teleoperation is the process of controlling autonomous vehicles remotely. It involves a human operator, often located at a distance, having direct control over all aspects of the vehicle's operation, such as driving. The operator's inputs are transmitted to the vehicle, and feedback may be relayed back to the operator.

## Abstract
Remote operation has gained attention as a means to bridge the gap to fully autonomous mobility. It provides human assistance remotely when automated driving systems encounter unclear circumstances and require feedback from a remote operator. Additionally, remote operation enables drivers to operate vehicles from safer and more comfortable locations.

## Architecture and Modes of Operation
Remote operating systems are categorized based on the level of human involvement:
- **Remote driving**: The vehicle is fully under remote control.
- **Remote assistance**: The operator provides event-driven assistance while the vehicle is still responsible for the driving task.
- **Remote monitoring**: The operator remotely monitors the driving task.

## Companies Involved
### Designated Driver
A company based in Portland, Oregon, offering RORV-as-a-Service for cars with and without DA capabilities.
### Ottopia
A software firm providing RORV-as-a-Service mobility, currently in the round funding stage.
### Fernride
A spin-off company from the Teleoperations Research Lab at the Technical University of Munich, offering RORV systems in remote driving mode.

## Challenges and Solutions
### Latency Issues
#### Latency Threshold
Any delay in signals beyond 50 milliseconds negatively impacts the Remote Operator's ability to quickly understand and respond to critical situations.
#### Real-time Requirement
Autonomous Vehicles must send data in real-time to ensure immediate decision-making. However, issues such as limited 4G coverage in rural areas pose obstacles to seamless communication.

### Embodiment Issues
#### Lack of Physical Sensation
Remote operators lack the physical sensations of vehicle movement and steering feedback, leading to potential situational awareness gaps.
#### Detached Perception and Risk
The absence of embodiment may result in remote operators treating the driving experience like a game, reducing their awareness of real-life consequences and risk.

### Workload Issues
#### Cognitive Overload Risk
Each piece of information adds processing demands, raising concerns about cognitive overload for remote operators.
#### Balancing Workload
Low workload situations may lead to decreased vigilance, highlighting the need for a balanced workload to prevent operational issues.

### Remote Interaction with Humans
#### Passenger Confusion Resolution
Remote operators tackle challenges in clarifying AV actions to passengers, preventing confusion or unintended consequences.

## Real-Time Analysis of Disengaged Data
Among 2676 manufacturers in the United States, there were 364 different reasons for disengagements. The top reasons included map discrepancies, test driver interventions, and issues with software components.

## Discussion on Optimal Solutions
### Latency Solutions
Discuss the Successive Reference-Pose Tracking (SRPT) model, which involves predictive modeling to mitigate latency issues.
### Embodiment Solutions
Suggest enhancements for remote operator situational awareness using sensory feedback and visualization techniques.

## Conclusion
The analysis has examined teleoperation, its modes of operation, companies involved, and challenges faced by remote operators. Various solutions have been proposed to address latency, embodiment, workload, and interaction issues.

## References
1. UNECE. (2020). Human factors challenges of remote support and control: A position paper from HF-IRADS.
2. Ericsson. (2017). Remote operation of vehicles with 5G.
