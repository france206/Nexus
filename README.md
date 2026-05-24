# Nexus
# NEXUS: Modern Age (Geopolitical AI Simulator)

NEXUS: Modern Age is a next-generation, open-source geopolitical and macroeconomic simulator for Android. It breaks away from traditional strategy games driven by rigid, linear scripts by introducing a local-first multi-AI agent framework. The ecosystem combines a closed-loop macroeconomic engine with a hyper-fluid UI, allowing players to govern nations through real-time natural language processing.

## 🚀 Key Features
* **Conversational Cabinet:** Manage national policies, taxation, and international relations by chatting directly with your AI-powered Ministers. No bloated sub-menus, just tactical intent.
* **Privacy-First Edge AI:** All Large Language Model (LLM) inference is executed entirely offline on the user's device. No data leaves the device, eliminating cloud API dependencies and protecting user privacy.
* **Deep Modding & Open Architecture:** Built under the Apache 2.0 license to allow global communities, students, and indie developers to inject custom geopolitical scenarios, economic models, and regional data.

## 🛠️ Tech Stack
NEXUS is designed with a modular architecture focused on performance, minimizing battery consumption while running local inference:

* **Core Simulation Engine:** Written in **Rust** for lightning-fast execution of high-frequency macroeconomic matrix calculations.
* **Edge AI Runtime:** Optimized via **ONNX / Llama.cpp** to handle heavily quantized, efficient local models (e.g., Gemma 3 1b) using on-device NPUs and GPUs.
* **Android Application:** Developed natively in **Kotlin** and **Jetpack Compose** for a minimalist, high-refresh-rate cyberpunk/military UI.

## 📊 Macroeconomic Architecture
The simulation bypasses arbitrary increments. It relies on a closed-loop economic system where national balances respond to accurate macroeconomic laws.

Gross Domestic Product ($Y$) is computed dynamically every turn following the standard macro identity:
$Y = C + I + G + (X - M)$

Where:
* $C$ (Consumption): Tied to employment rates and household tax pressure.
* $I$ (Investment): Driven by Central Bank interest rates and country stability.
* $G$ (Government Spending): Budget allocated by the player (Healthcare, Infrastructure, Defense).
* $(X - M)$ (Net Exports): Real-time trade balance between simulated sovereign networks.

Public Debt ($D$) sustainability dynamically shifts bond yields ($r$) based on parliamentary consensus and market trust:
$$\Delta D_t = G_t - T_t + r \cdot D_{t-1}$$

## 🤖 Multi-Agent Local AI Framework
Every foreign state and internal ministry runs as an independent intelligent agent. By fine-tuning local open weights, the ecosystem simulates:
* **The Ministry of Finance:** Handles double-entry bookkeeping of the state, flags inflation risks, and outlines optimal fiscal maneuvers based on the player's goals.
* **Global Supply Chain Disruption:** AI-driven rival states evaluate embargoes, trade deals, and defensive pacts by analyzing real-time resource allocations (Semiconductors, Rare Earth Elements, Crude Oil).

## 📄 License
This project is licensed under the **Apache License 2.0**. You are free to use, modify, and distribute this software for personal, academic, or commercial purposes, provided the open-source nature of the core architecture remains intact.
