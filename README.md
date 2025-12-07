# Bidirectional Quantum Teleportation 

[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs11082--022--03951--x-blue)](https://link.springer.com/article/10.1007/s11082-022-03951-x)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/)
[![Qiskit](https://img.shields.io/badge/Qiskit-0.37-6929C4)](https://qiskit.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains the source code and simulation data for the paper **"Bidirectional quantum teleportation of an arbitrary number of qubits over a noisy quantum system using 2n Bell states as quantum channel"**, published in *Optical and Quantum Electronics*.

We present a scalable protocol where Alice and Bob can simultaneously exchange an arbitrary number of unknown qubits. Unlike previous schemes that require complex resource states, our protocol utilizes a channel composed of **4n entangled Bell states** and relies on standard Bell-basis measurements.

### Key Features
* **Scalability:** Designed to teleport an arbitrary number (*n*) of qubits bidirectionally.
* **Resource Efficient:** Uses standard Bell states ($4n$ total) as the quantum channel.
* **Noise Analysis:** Includes comprehensive simulation of **Amplitude Damping** noise effects on fidelity.
* **Verification:** Validated on the IBM Quantum `qasm_simulator`.

## Getting Started
To install dependencies:
```bash
pip install -r requirements.txt

```

### Prerequisites
The code is built on **Qiskit** 

### Citation
url = {[https://link.springer.com/article/10.1007/s11082-022-03951-x](https://link.springer.com/article/10.1007/s11082-022-03951-x)}

