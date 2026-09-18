# Multi-Agent Formation Control

This project implements formation control for 20 agents connected through a
connected Erdős–Rényi communication graph.

The agents start from random positions in R² and sequentially form the letters
of the name **TANUSH** using a Laplacian-based formation control strategy.

## Parameters

- Number of agents: N = 20
- Graph: Connected Erdős–Rényi graph
- Edge probability: p = 0.25
- Initial positions: Random positions in R²
- Name: TANUSH

## Formation Sequence

T → A → N → U → S → H

## Files

- `formation_control1(1).py` - Python implementation
- `TANUSH_formation_control(8).mp4` - Animation showing the formation sequence
- `communication_graph(1).png` - Generated communication graph
- `formation_T(1).png` - Target formation for T
- `formation_A(2).png` - Target formation for A
- `formation_N1(1).png` - Target formation for N
- `formation_U(1).png` - Target formation for U
- `formation_S(1).png` - Target formation for S
- `formation_H1(1).png` - Target formation for H

## How to Run

Install the required Python packages:

```bash
pip install numpy networkx matplotlib
