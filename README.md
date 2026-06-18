# 🦅 SkyCipher: Autonomous UAV System

> **Notice:** This repository serves as a technical showcase. To protect intellectual property, the core proprietary neural network weights, complete datasets, and full simulation environments are kept private.

## 🏆 Awards & Recognition
* **1st Place Winner** at the *"Future Skills Week: AI and Employability"* Hackathon (Hashemite University, May 2026). 

## 🚀 Overview
In modern tactical operations, a drone is only as good as its signal. Once signal jamming occurs, multi-million dollar drones turn into falling debris. **SkyCipher** was built to solve exactly this vulnerability.

We didn't just build a flight controller; we built an independent "brain." SkyCipher is a fully autonomous UAV system designed to survive, navigate, and complete complex missions even when completely cut off from ground control. 

## 🧠 The Grind: 3.2 Million Steps of Training
Building an autonomous brain from scratch takes immense computational and engineering effort. The core of SkyCipher is powered by advanced Deep Reinforcement Learning (RL) algorithms. 

Instead of hardcoding flight paths, we threw the AI into a custom-built, highly realistic physics simulation engine. The drone had to learn how to deal with gravity, wind resistance, and dynamic constraints. 

* **The Training Phase:** The model underwent grueling training for approximately **3.2 million steps**. It crashed, failed, and recalibrated thousands of times until it mastered autonomous flight and obstacle avoidance.
* **Massive Data Generation:** During these 3.2 million steps, the environment wasn't just a testing ground; it was a data factory. The system autonomously generated a massive proprietary dataset from scratch. This includes thousands of complex environmental images and highly detailed telemetry and flight data, meticulously organized into robust `CSV` files for further machine learning analysis.

## 💬 Command & Control (C2) Meets Automation
A tactical operator in the field doesn't have time to read complex charts or debug code. They need immediate answers. 

To solve this, we completely redesigned the user experience. We built a custom, interactive **Chatbot** integrated directly into the dashboard. Using **n8n** for seamless workflow automation, the chatbot receives simple text commands from the operator and translates them into complex backend executions. 

* Ask the bot for the drone's status, and `n8n` dynamically fetches real-time telemetry, updates the 3D Radar, and returns instant ML results. Command and control is now as simple as having a conversation.

## ⚙️ Core Technologies
* **Deep Reinforcement Learning:** The backbone of the drone's decision-making process.
* **Computer Vision (CV):** Equipped with real-time detection capabilities to identify targets and understand the terrain.
* **n8n Workflow Automation:** Powering the Chatbot and backend data routing for instant military intelligence.

---
*Built with passion, late nights, and millions of lines of generated data. SkyCipher proves that when the signal is lost, true intelligence begins.*
