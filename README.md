# gw-net-vuln

**Gromov–Wasserstein based Edge Vulnerability Analysis in Transport Networks**

This repository provides Python code to evaluate the structural vulnerability of transport networks
using **Gromov–Wasserstein (GW) distances**.  
By removing edges one at a time and recomputing distance distributions, the framework quantifies how much
the **global geometry of the network** changes — offering a resilience measure that complements
traditional metrics such as **edge betweenness centrality** or **ΔMSP (change in maximum shortest path)**.

---

## Features
- Compute **all-pairs shortest path** distance matrix.
- Perform **edge removal experiments** with GW distance.
- Output per-edge metrics: `GW distance`, `ΔMSP`, and `Edge Betweenness`.
- Compare metrics via scatter plots and correlations.
- Identify **top critical edges** in the network.

---

## Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/iman_ie/gw-net-vuln.git
cd gw-net-vuln
pip install -r requirements.txt
