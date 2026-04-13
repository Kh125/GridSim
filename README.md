# GridSim - Distributed Systems Simulation

## Overview  
This project explores the GridSim toolkit for modeling and simulating distributed and grid computing environments. It focuses on analyzing resource management, task scheduling, and system performance under different workloads.

The system simulates real-world grid scenarios, including resource sharing, network communication, and job execution across distributed nodes.

## Background  
GridSim is a Java-based simulation toolkit designed for modeling distributed resource management and scheduling in grid computing. It supports simulation of heterogeneous resources, network behavior, and parallel workloads.

As described in the project report :contentReference[oaicite:0]{index=0}, the toolkit enables deterministic modeling of distributed systems, making it suitable for evaluating scheduling strategies and system performance.

## Features  
- Resource modeling (CPU, storage, network)  
- Network simulation (latency, bandwidth, communication)  
- Task and job scheduling simulation  
- Workload generation for testing scenarios  
- Fault tolerance and failure simulation  
- Performance analysis of distributed systems  

## Simulation Scenarios  

### Scenario 1: Basic Data Grid Setup  
- Initialized simulation environment  
- Created grid resources and users  
- Established network connections  
- Evaluated data management and replication  

### Scenario 2: File Management and Replication  
- Simulated file creation, transfer, and replication  
- Tested deletion and consistency handling  
- Evaluated system behavior under dynamic data operations  

### Scenario 3: Networked Grid Execution  
- Configured routers and network topology  
- Submitted distributed tasks (Gridlets)  
- Measured execution and response handling across nodes  

(Examples and outputs of these simulations are shown in the test results section of the report, pages 9–15 :contentReference[oaicite:1]{index=1}.)

## Tech Stack  
- Language: Java  
- Framework/Library: GridSim  

## Purpose  
The objective of this project is to evaluate the performance, scalability, and behavior of distributed systems using simulation techniques. It helps in understanding how scheduling algorithms and resource allocation impact overall system efficiency.
