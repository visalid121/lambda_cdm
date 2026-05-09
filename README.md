ΛCDM Optimizer: Physics-Inspired Metaheuristic for Constrained Optimization

This repository implements a novel optimization algorithm inspired by the ΛCDM cosmological model (Lambda Cold Dark Matter) and compares it against standard metaheuristics such as Particle Swarm Optimization (PSO) on a constrained engineering benchmark: the Pressure Vessel Design Problem.

🚀 Overview

The ΛCDMOptimizer is a hybrid population-based optimization algorithm that blends:

🌌 Gravitational interaction dynamics (mass–fitness attraction)
📉 Time-decaying gravity field (G(t))
🎯 Best-solution exploitation pressure
🌬️ Cosmological expansion term (Λ-driven divergence)
🔊 Controlled stochastic exploration (noise injection)

The goal is to achieve a balance between:

Exploration (diversity preservation)
Exploitation (convergence stability)
Constraint-aware search

🧠 Key Idea

The algorithm simulates a simplified universe:

Better solutions act like massive bodies attracting others
A decaying gravitational constant controls convergence speed
Late-stage Λ (lambda) expansion prevents premature collapse
Noise acts like quantum fluctuations maintaining diversity

📦 Features
Physics-inspired optimization framework
Built-in constraint handling (penalty method)
Diversity monitoring and anti-collapse mechanism
Benchmark-ready implementation
Comparison with PSO
Visualization of convergence and population diversity
🏗️ Problem Solved: Pressure Vessel Optimization

We use the classical engineering benchmark:

Objectives:

Minimize:

Material cost (f1)
Volume cost (f2)
Constraints:
Thickness constraints
Geometric feasibility
Minimum volume requirement

Penalty-based constraint handling is used to enforce feasibility.

⚙️ Algorithm: ΛCDMOptimizer
Core Update Rule:
Gravity Force (fitness-based attraction)
Best-agent exploitation pressure
Time-decaying gravitational constant
Velocity update (momentum + force)
Λ-driven expansion (cosmic divergence)
Random exploration noise
Boundary correction & NaN protection

📊 Outputs

During optimization, the algorithm tracks:

1. Convergence Curve
Tracks best fitness over iterations
Shows rapid early convergence followed by stabilization
2. Diversity Curve
Measures population spread
Ensures exploration does not collapse too early
📈 Results
Example Run (Pressure Vessel)
Best ΛCDM solution fitness: ~0.0907
PSO fitness: ~0.0950
Observations:
ΛCDM converges faster in early iterations
Maintains better diversity mid-run
Achieves slightly better final solution than PSO
