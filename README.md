# Dataset Description: Resilience Enhancement of Highway Systems Considering Multilayer Energy Supply Networks

This dataset is developed to support research on highway system resilience enhancement within transportation–power–hydrogen multilayer coupled networks. It provides fundamental network topology data and operational flow allocation data for transportation, power, and hydrogen systems. The dataset can support complex network centrality analysis, mixed traffic flow equilibrium (UE) computation, and resilience optimization based on the genetic algorithm–mixed-integer linear programming (GA–MILP) framework.

---

## Data Desensitization Statement

To protect critical infrastructure security and comply with relevant data disclosure regulations, all datasets have been desensitized. Geographic coordinates have been transformed into abstract topological node coordinates and do not contain any real geographic location information.

---

## Usage Guidelines

1. Read the topology data files of the transportation network, power network, and hydrogen network separately to construct the three-layer static physical network model;

2. Assign traffic flow and energy load data to the corresponding network nodes and edges, and calculate the flow-informed weighted betweenness centrality of nodes and edges under the initial system state;

3. Based on the calculated centrality indicators, generate random attack scenarios with different intensities (random removal of nodes/edges) or strategic attack scenarios (prioritized removal of high-centrality nodes/edges ranked according to the computed flow-informed weighted betweenness centrality) to simulate cascading failures in the multilayer network;

4. Import multidimensional resilience enhancement strategy parameters, including physical hardening, backup allocation, P2H interlayer coupling, and mobile hydrogen storage vehicle dispatch;

5. Solve the optimal resource allocation scheme with the objective of minimizing the overall system resilience loss.
