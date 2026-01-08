# Mobile GUI Agent Survey Resources

This repository provides a comprehensive collection and classification of research papers related to **Mobile GUI Agents**. It is designed to support researchers and developers in understanding the current landscape, key architectures, and evaluation benchmarks in the field of autonomous mobile device interaction.

## 📋 Table of Contents
- [1. Survey Papers](#1-survey-papers)
- [2. Architectures & Models](#2-architectures--models)
  - [2.1 Perception & Grounding](#21-perception--grounding)
  - [2.2 Reasoning & Planning](#22-reasoning--planning)
  - [2.3 Learning Methods](#23-learning-methods)
- [3. Benchmarks & Datasets](#3-benchmarks--datasets)
- [4. Applications & Testing](#4-applications--testing)
- [5. Future Directions](#5-future-directions)

---

## 1. Survey Papers
These papers provide a high-level overview of the field, categorizing existing work and identifying open challenges.

| Paper Title | Year | Key Focus |
| :--- | :--- | :--- |
| [GUI Agents: A Survey](https://arxiv.org/abs/2412.13501) | 2024 | Comprehensive taxonomy of benchmarks, metrics, and architectures. |
| [LLM-Powered GUI Agents in Phone Automation](https://arxiv.org/abs/2504.19838) | 2025 | Evolution from script-based to intelligent adaptive systems. |
| [Large Language Model-Brained GUI Agents: A Survey](https://arxiv.org/abs/2411.18279) | 2024 | Historical evolution and core components of LLM-based agents. |

---

## 2. Architectures & Models

### 2.1 Perception & Grounding
Focuses on how agents "see" and "understand" the mobile interface, ranging from vision-only to hybrid approaches.

- **Mobile-Agent** (2024): A vision-only perception-based agent that operates without XML/metadata.
- **SeeClick** (2024): Harnesses GUI grounding for advanced visual agents using screenshots.
- **GUI-Actor** (2025): Introduces coordinate-free visual grounding with an attention-based action head.
- **CogAgent** (2023): A high-resolution visual language model specifically optimized for GUI understanding.

### 2.2 Reasoning & Planning
Focuses on the decision-making process, including error correction and long-term planning.

- **GUI-Reflection** (2025): Enhances agents with self-reflection and error correction behaviors.
- **BacktrackAgent** (2025): Implements error detection and backtracking mechanisms for robust execution.
- **XBOUND** (2025): Explores capability boundaries through trajectory tree exploration.

### 2.3 Learning Methods
Focuses on how agents are trained, including Supervised Fine-Tuning (SFT) and Reinforcement Learning (RL).

- **AgentCPM-GUI** (2025): Utilizes Reinforcement Fine-Tuning (GRPO) for on-device mobile agents.
- **UI-R1** (2025): Enhances action prediction through specialized reinforcement learning.
- **LearnAct** (2025): A few-shot framework using unified demonstration benchmarks.
- **MobileDreamer** (2026): An efficient sketch world model-based lookahead framework for mobile GUI agents.
- **Mobile-Agent-RAG** (2025): A hierarchical multi-agent framework that empowers agents with contextual knowledge via RAG.
- **MAI-UI** (2025): Alibaba's family of GUI agents designed for practical, real-world mobile capabilities.

---

## 3. Benchmarks & Datasets
Standardized environments and data for evaluating agent performance.

| Benchmark | Description |
| :--- | :--- |
| **AITW** | Android In-The-Wild: A large-scale dataset of human interactions. |
| **AndroidWorld** | A fully functional Android environment for agent evaluation. |
| **CAGUI** | A comprehensive Chinese GUI benchmark for mobile apps. |
| **AMEX** | Android Multi-annotation Expo Dataset for generalist agents. |
| **ProBench** | A mobile benchmark with 200+ challenging tasks across bilingual scenarios. |

---

## 4. Applications & Testing
Specific use cases such as automated testing and security evaluation.

- **DroidAgent** (2023): Intent-driven mobile GUI testing using autonomous LLM agents.
- **MobileSafetyBench** (2025): Evaluating the safety of autonomous agents in mobile device control.
- **AUITestAgent** (2025): Automatic requirements-oriented GUI function testing.

---

## 5. Future Directions
- **On-Device Efficiency**: Developing lightweight models (e.g., AgentCPM-GUI) for real-time local execution.
- **Multimodal Fusion**: Better integration of visual, textual, and structural (XML) information.
- **Long-Horizon Planning**: Improving the ability to handle complex, multi-step tasks without drifting.
- **Safety & Privacy**: Ensuring agents operate securely within sensitive user environments.

---
*This repository is automatically maintained for research purposes.*
