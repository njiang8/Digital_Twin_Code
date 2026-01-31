# Digital_Twin_Code

This repository provides the **code base and project index** supporting the paper:

> **Populating Urban Digital Twins with Humans:  
> A Framework Utilizing Artificial Agents**

The goal of this project is to develop a **modular, reproducible agent-based modeling (ABM) framework** for populating urban digital twins with artificial human agents, enabling the simulation of mobility, interaction, evacuation, opinion dynamics, and epidemiological processes in spatially explicit urban environments.

---

## Core Methodological Foundation

### Geographically Explicit Synthetic Population

Several models in this repository rely on a geographically explicit synthetic population framework to initialize realistic human agents:

- **Synthetic Population Generation Framework**  
  https://github.com/njiang8/geo-synthetic-pop-usa  

This framework provides:
- Census-consistent synthetic individuals
- Spatially explicit population distributions
- A scalable foundation for urban-scale digital twin simulations

---

## Project Overview

This repository serves as an **index of interconnected agent-based modeling projects**, each representing a functional module of an urban digital twin populated with artificial humans.

---

## Included Projects

### 1. Buffalo Traffic Dynamics Simulation  
**Repository**:  
https://github.com/JacoZhang-23/Traffic_Dynamics  

**Description**:  
An agent-based traffic and commuting model simulating daily mobility patterns and congestion dynamics in Buffalo, NY.  
The model integrates real road networks and commuter origin data to capture spatially grounded transportation behavior.

**Role in Digital Twin**:
- Urban mobility module  
- Commuting behavior and congestion formation

**Key Features**:
- Road-network-based agent navigation (NetworkX)
- Congestion effects from road capacity constraints
- GIS-based simulation and visualization (Mesa-Geo)

---

### 2. Multi-Round LLM for Opinion Dynamics  
**Repository**:  
https://github.com/JacoZhang-23/Multi-Round-LLM-for-Opinion-Dynamics  

**Description**:  
An agent-based opinion dynamics framework where agents interact through **multi-round large language model (LLM) dialogues**, allowing beliefs and opinions to evolve through natural language interaction.

**Role in Digital Twin**:
- Social interaction and belief evolution module  
- Information diffusion and polarization analysis

**Key Features**:
- LLM-powered artificial agents
- Multi-round conversational interaction
- Opinion convergence and divergence dynamics

---

### 3. Building Evacuation Simulation Framework  
**Repository**:  
https://github.com/JacoZhang-23/Building_Evacuation  

**Description**:  
An agent-based evacuation model simulating human movement in a multi-floor building under emergency conditions, incorporating congestion effects and spatial constraints.

**Role in Digital Twin**:
- Emergency response and evacuation module  
- Indoor human movement dynamics

**Key Features**:
- Two-floor raster-based building environment
- Elevation- and congestion-aware agent movement
- 3D evacuation animation and population time-series outputs

---

### 4. Multi-Disease SEIR Agent-Based Model  
**Repository**:  
https://github.com/njiang8/seir-multi  

**Description**:  
A multi-disease SEIR agent-based epidemiological model designed to simulate the spread and interaction of multiple infectious diseases within a shared population.

**Role in Digital Twin**:
- Public health and epidemiological module  
- Disease spread and intervention evaluation

**Key Features**:
- Multiple pathogens in a single population
- Disease interaction mechanisms
- Policy and intervention simulation

---

## Related Agent-Based Models

This project is closely related to ABM implementations developed in prior work:

- **Commute Model**  
  https://github.com/njiang8/erie-commute  

- **Vaccination Model**  
  https://github.com/fuzhen-yin/vaccination_model_erie_nys  

---

## Research Scope

Together, these projects demonstrate how artificial human agents can be embedded into urban digital twins to study:

- Urban mobility and congestion
- Social interaction and opinion formation
- Emergency evacuation behavior
- Epidemiological spread and policy response

Common methodological elements include:
- Agent heterogeneity
- Spatially explicit environments
- Network-based interactions
- Scenario and policy evaluation

---

## Usage

Each sub-project contains its own documentation, dependencies, and execution instructions.  
Please refer to the individual repositories for detailed usage information.

---

## License

This code collection is intended for **academic and research purposes**.  
Please cite the corresponding paper when using or extending this framework.
