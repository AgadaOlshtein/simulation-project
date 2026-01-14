# Simulation Project – Water Park

## Water Park Description

This project focuses on modeling and simulating the operation of a water park that includes multiple facilities and services.
Visitors arrive at the park, enter through a reception area, and proceed to different attractions according to predefined movement rules.
Each facility operates with queues and service times, which affect both visitor experience and overall system performance.

The system is modeled as a service system with visitor flows, limited resources, and stochastic processes.

---

## Project Workflow

### 1. Modeling the Current State (As-Is)

In this stage, the current state of the water park was modeled by defining:
- Visitor types
- Visitor arrival process
- Structure of queues and facilities
- Visitor flow logic within the system
- Available resources at each facility

This model represents the existing operation of the park without any modifications or improvements.

---

### 2. Statistical Analysis of Samples and Distributions

Observation data collected for service times and arrival processes were analyzed statistically.
This stage included:
- Sample analysis
- Fitting probability distributions to the observed data
- Performing goodness-of-fit tests (e.g., Kolmogorov–Smirnov test)

The goal of this stage was to select appropriate probability distributions to represent the stochastic processes in the simulation model.

---

### 3. Modeling and Programming Using Discrete-Event Simulation

The simulation was implemented using discrete-event simulation.
The following events were defined:
- Arrival events
- Service start events
- Service completion events
- Queue and resource management

The implementation captures the system logic and tracks its state over time.

---

### 4. Simulation of the Current State

After completing the modeling and programming stages, the simulation was executed for the current state of the system.
During the simulation runs, performance measures were collected, including:
- Average waiting times
- Queue lengths
- Facility utilization levels
- System performance over multiple days

These results served as a baseline for comparison with alternative scenarios.

---

### 5. Evaluation of Alternatives

In this stage, alternative scenarios to the current state were examined, such as:
- Changes in the number of resources
- Modifications to service policies
- Adjustments to arrival or service parameters

The performance of these alternatives was compared to the current state in order to evaluate potential improvements in system efficiency and visitor experience.

---
