<div align="center">

![Fractal Ecosystem Architecture](assets/22.png)

# F R A C T A L
**C O M P U T E &nbsp; O R C H E S T R A T I O N S**
<br><br>
**Decentralized Edge Compute Harvesting, Sub-Byte INT4 Federated Learning, and Split LLM Inference.**

[![Organization](https://img.shields.io/badge/Organization-Fractal_Compute_Orchestrations-black?style=for-the-badge)](https://github.com/Fractal-Compute-Orchestrations)
[![License](https://img.shields.io/badge/License-Proprietary_Non--Commercial_v3.1-black?style=for-the-badge)](../LICENSE)
[![Open In Colab](https://img.shields.io/badge/Colab-Quickstart_Demo-black?style=for-the-badge&logo=googlecolab)](https://colab.research.google.com/github/Fractal-Compute-Orchestrations/FractalCore/blob/main/examples/colab_quickstart.ipynb)
[![Design Case Study](https://img.shields.io/badge/Design_Case_Study-Behance-black?style=for-the-badge&logo=behance)](https://www.behance.net/gallery/221459335/Fractal)

<br>

[FractalWorkspace](https://github.com/Fractal-Compute-Orchestrations/FractalWorkspace) | [FractalCore](https://github.com/Fractal-Compute-Orchestrations/FractalCore) | [FractalAndroid](https://github.com/Fractal-Compute-Orchestrations/FractalAndroid)

---
</div>

## Ecosystem Overview

**Fractal Compute Orchestrations** builds privacy-preserving edge intelligence software across heterogeneous consumer mobile devices.

1. **Outlier-Resilient Micro-Block INT4 Compression (`fractal_quant`)**: 64-element block quantization (`FRQ4`/`FRQD`) with error-feedback residuals delivering **7.1x** wire reduction (`4,196 MB -> 590 MB` on TinyLlama-1.1B) at **0.9878** layer cosine similarity.
2. **Hardened Coordinator & Byzantine Aggregation (`fractal_server`)**: Canonical tenant storage isolation, constant-time bearer auth, and FedAvg/Median/Krum/FedProx aggregators.
3. **Thermal-Gated Android Compute Client (`FractalAndroid`)**: Kotlin wire-compatible `Int4BlockCodec`, `OperationControl` thermal gating (`<= 40.0 C` and `THERMAL_STATUS_SEVERE` checks), and `FractalPaths` storage isolation.

## Core Repositories

| Repository | Designation | Stack |
| :--- | :--- | :--- |
| **[`FractalWorkspace`](https://github.com/Fractal-Compute-Orchestrations/FractalWorkspace)** | Umbrella Specs & Benchmarks | Git Submodules, Pareto Frontier Evaluations, Contracts |
| **[`FractalCore`](https://github.com/Fractal-Compute-Orchestrations/FractalCore)** | Python SDK, CLI & Server (`v1.0.0`) | Python 3.10+, PyTorch, Flask, `fractal` CLI, `pytest` CI |
| **[`FractalAndroid`](https://github.com/Fractal-Compute-Orchestrations/FractalAndroid)** | Mobile Edge Runtime | Kotlin, Android SDK 24+, TFLite, Gradle Unit Tests |

<div align="center">
  <img src="assets/12.png" width="100%" alt="Fractal Compute Orchestrations">
</div>

FRACTAL is governed and owned by **Fractal Compute Orchestrations** under the FRACTAL Proprietary Source-Available & Non-Commercial Restrictive License v3.1 (see `LICENSE`).
