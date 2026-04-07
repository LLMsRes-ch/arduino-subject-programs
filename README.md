# Codes for the Paper: "Evaluating Large Language Models (LLMs) for Arduino Code Generation"

## Overview

Large Language Models (LLMs), also known as Generative AI, have revolutionized code generation by converting natural-language prompts into executable code. However, their capabilities in generating code for **resource-constrained devices** like **Arduino**, which are widely used in **Internet of Things (IoT)** and **embedded systems**, remain underexplored.

This repository contains a **set of 31 Arduino subject programs**, each provided with **two optimized reference solutions**, designed to evaluate the effectiveness of LLMs in generating correct, efficient, and high-quality Arduino code. These subject programs support empirical research on LLM performance in microcontroller-based programming environments.

---

## Subject Program Design

- 🧩 **Number of Programs**: 31 tasks, each with 2 optimized solutions
- 🧠 **Task Coverage**: Data types, control structures, functions, arrays, loops, sensors, and more  
- 📟 **Platform**: Arduino Uno Rev3  
- 🔍 **Optimization Focus**: Execution speed, memory usage, and code readability

Each program task was developed based on examples from the official Arduino documentation. Two solutions per task were created by the authors to reflect **developer variation** and different optimization strategies. Some solutions favor **memory efficiency**, while others prioritize **faster execution**.

---

## Purpose of the Study

These subject programs were used in a study that evaluated **six state-of-the-art LLMs** across five key dimensions:

1. ✅ **Functional Correctness**  
2. ⏱️ **Runtime Efficiency**  
3. 💾 **Memory & SRAM Usage**  
4. 🧑‍💻 **Code Complexity and Similarity**  
5. 🔁 **Multi-Round Error Correction**

### Key Findings:
- **ChatGPT-4** achieved the highest zero-shot functional correctness and produced code most similar to human-written code.
- **Gemini 2.0 Flash** generated faster code but with higher complexity and lower similarity.
- **DeepSeek-V3** showed strong memory efficiency.
- **Claude 3.5 Sonnet** struggled with prompt interpretation.
- Multi-round prompting improved output correctness across all models.
- .........

---

## Prompt Structure

Each program is paired with a **zero-shot prompt** following a consistent and model-friendly structure.

--- 

## Cite these works
1.	S. K. Jabrw and Q. I. Sarhan, “A Systematic Survey on Large Language Models for Code Generation”, ARO, vol. 13, no. 2, pp. 83–99, Aug. 2025. https://doi.org/10.14500/aro.12159 
Impact Factor: 2.1 (as of 2025).

2.	S. K. Jabrw and Q. I. Sarhan, “Evaluating Large Language Models (LLMs) for Arduino Code Generation”, ARO, vol. 14, no. 1, pp. 37–47, Jan. 2026.
https://doi.org/10.14500/aro.12344 
Impact Factor: 2.1 (as of 2025).
