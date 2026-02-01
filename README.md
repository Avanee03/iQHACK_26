# iQHACK_26
This repository contains my complete work for the MIT's annual quantum hackthon (Entanglement Distillation Challenge).

🔍 Problem Overview

The challenge is based on a quantum network graph, where each node represents a location and each edge represents a noisy quantum channel.

The task is to:

design LOCC-compliant entanglement distillation circuits

use a limited number of Bell pairs

and claim edges in the graph by achieving a fidelity above a given threshold.

Each edge has:

a difficulty rating (D1–D5)

a minimum fidelity threshold

constraints on allowed quantum operations (LOCC only)


🛠 Technologies Used

Python

Qiskit (QuantumCircuit, measurements, classical control)

NetworkX (for graph handling)

Matplotlib (graph visualization)

Jupyter Notebook

Custom client API provided by the hackathon
