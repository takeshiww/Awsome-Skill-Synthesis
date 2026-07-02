<h1 align="center">
  <strong>Awesome-Skill-Synthesis</strong>
</h1>

<div align="center">

  [![Awesome](https://awesome.re/badge.svg?logo=stylelint)](https://awesome.re)

<p align="center">
 A curated collection of resources (e.g., papers, datasets, frameworks) on skill synthesis for advancing agentic intelligence.
</p>

<h3 align="center">
  <strong>🤖 Stay tuned — the repo is under active development! 🤖<br>⭐ Star this repo if you find it helpful! ⭐</strong>
</h3>

</div>

## 1. Skill Synthesis from External Knowledge
- (*TMLR'24*) *Voyager: An Open-Ended Embodied Agent with Large Language Models*  [[📝 Paper](https://arxiv.org/pdf/2504.20406)] [[💻 Code](https://github.com/MineDojo/Voyager)]  
→ A pioneering embodied lifelong-learning agent that builds an ever-growing executable code skill library from exploration and environment feedback.

- (*Arxiv'26*) *AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution*  [[📝 Paper](https://arxiv.org/pdf/2603.01145)] [[💻 Code](https://github.com/ECNU-ICALK/AutoSkill)]  
→ A training-free framework that distills skills from conversations.

- (*Arxiv'26*) *Automating Skill Acquisition from Open Source Repositories*  [[📝 Paper](https://arxiv.org/pdf/2603.11808)]  
→ A framework for extracting reusable skills from open source code repositories with multi-dimensional quality assessment.

- (*Arxiv'26*) *CUA-Skill: Develop Skills for Computer Using Agent*  [[📝 Paper](https://arxiv.org/pdf/2601.21123)] [[💻 Code](https://github.com/microsoft/cua_skill)]  
→ A systematically curated skill library for building computer-use agents.

- (*Arxiv'25*) *ALLOY: Generating Reusable Agent Workflows from User Demonstration*  [[📝 Paper](https://arxiv.org/pdf/2510.10049)]  
→ A system that converts user demonstrations into reusable, editable, generalizable agent workflows for web tasks.

- (*Arxiv'25*) *LLM Agents Making Agent Tools*  [[📝 Paper](https://arxiv.org/pdf/2502.11705)] [[💻 Code](https://github.com/KatherLab/ToolMaker)]  
→ An agentic framework that autonomously converts scientific papers with code into LLM-compatible reusable tools.

- (*EACL Findings'26*) *Skill Discovery for Software Scripting Automation via Offline Simulations with LLMs*  [[📝 Paper](https://arxiv.org/pdf/2504.20406)]  
→ An offline simulation framework for discovering and verifying reusable scripting skills via GNN-based API synergy.


## 2. Skill Synthesis from Experience
Methods that derive, refine, or maintain reusable skills from agent-environment experience, including trajectories, failures, feedback, and deployment histories.

### 2.1 General Embodied and Interactive Agent Tasks
- (*Arxiv'26*) *SKILLRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning*  [[📝 Paper](https://arxiv.org/pdf/2602.08234)] [[💻 Code](https://github.com/aiming-lab/SkillRL)]  
→ An RL framework that distills rollout trajectories into a hierarchical skill library and recursively evolves these skills during training.

- (*Arxiv'25*) *Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback*  [[📝 Paper](https://arxiv.org/pdf/2506.04287)]  
→ An exploration-first skill discovery framework where one agent explores environments to generate feasible skill datasets for training another.

- (*Arxiv'26*) *SkillX: Automatically Constructing Skill Knowledge Bases for Agents*  [[📝 Paper](https://arxiv.org/abs/2604.04804)] [[💻 Code](https://github.com/zjunlp/SkillX)]  
→ Automatically constructs a plug-and-play hierarchical skill knowledge base through multi-level skill design, iterative refinement, and exploratory expansion.

- (*Arxiv'26*) *Skill1: Unified Evolution of Skill-Augmented Agents via Reinforcement Learning* [[📝 Paper](https://arxiv.org/pdf/2605.06130)]  
→ A reinforcement learning framework that jointly evolves skill selection, skill utilization, and skill distillation from agent trajectories.

### 2.2 Web Navigation and Browser Automation
- (*Arxiv'25*) *SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills*  [[📝 Paper](https://arxiv.org/pdf/2504.07079)] [[💻 Code](https://github.com/OSU-NLP-Group/SkillWeaver)]  
→ A web agent framework that distills exploration and practice experiences into reusable APIs.

- (*Arxiv'25*) *Inducing Programmatic Skills for Agentic Tasks*  [[📝 Paper](https://arxiv.org/pdf/2504.06821)]  
→ A framework where agents self-induce, verify, and reuse programmatic code-based skills on the fly for web navigation tasks.

### 2.3 Computer-Use Agents and GUI / Software Operation
- (*Arxiv'26*) *OSExpert: Computer-Use Agents Learning Professional Skills via Exploration*  [[📝 Paper](https://arxiv.org/pdf/2603.07978)]  
→ A DFS-based exploration algorithm that discovers unit functions and composes composite skills for computer-use agents.

### 2.4 Coding, Office, Data, and Knowledge-Intensive Tool-Use Tasks
- (*Arxiv'26*) *EvoSkill: Automated Skill Discovery for Multi-Agent Systems*  [[📝 Paper](https://arxiv.org/pdf/2603.02766)] [[💻 Code](https://github.com/sentient-agi/EvoSkill)]  
→ A framework that distills skills via failure analysis by text feedback.

- (*Arxiv'26*) *Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills*  [[📝 Paper](https://arxiv.org/pdf/2603.25158)]  
→ Distills broad agent execution experience into transferable, conflict-free declarative skill directories via hierarchical inductive consolidation.

- (*Arxiv'26*) *SkillSmith: Co-Evolving Skills and Tools for Self-Improving Agent Systems* [[📝 Paper](https://arxiv.org/pdf/2606.01314)]  
→ A self-improving agent framework that co-evolves reusable skills and tools from execution traces, while retaining anti-pattern memory to avoid repeated failures.

### 2.5 Continual and Deployed Agent Self-Evolution
- (*Arxiv'26*) *MetaClaw: Just Talk -- An Agent That Meta-Learns and Evolves in the Wild*  [[📝 Paper](https://arxiv.org/pdf/2603.17187)] [[💻 Code](https://github.com/aiming-lab/MetaClaw)]  
→ A continual learning framework that synthesizes skills from failure trajectories and asynchronously updates the policy model (via LoRA) using the evolving skill library.

- (*Arxiv'26*) *Memento-Skills: Let Agents Design Agents*  [[📝 Paper](https://arxiv.org/pdf/2603.18743)] [[💻 Code](https://github.com/Memento-Teams/Memento-Skills)]  
→ A deployment-time learning framework that rewrites and grows an external skill library from execution feedback and reflection.

- (*Arxiv'25*) *Audited Skill-Graph Self-Improvement for Agentic LLMs via Verifiable Rewards, Experience Synthesis, and Continual Memory*  [[📝 Paper](https://arxiv.org/pdf/2512.23760)]  
→ A framework for auditable skill-graph self-improvement where capabilities are extracted from trajectories and promoted after passing contract checks.

### 2.6 Domain-Specific Expert Agents
- (*Arxiv'26*) *MACRO: Evolving Medical Imaging Agents via Experience-driven Self-skill Discovery*  [[📝 Paper](https://arxiv.org/pdf/2603.05860)]  
→ A medical imaging agent that discovers recurring multi-step tool sequences from execution experience and synthesizes them into reusable composite tools.

- (*Arxiv'26*) *Experience Makes Skillful: Enabling Generalizable Medical Agent Reasoning via Self-Evolving Skill Memory* [[📝 Paper](https://arxiv.org/pdf/2606.09365)]  
→ A self-evolving medical-agent framework that converts clinical interaction trajectories into reusable skill memory for continual reasoning improvement.

### 2.7 Robotics and Embodied Control
- (*Arxiv'26*) *ASPIRE: Agentic Skills Discovery for Robotics* [[📝 Paper](https://arxiv.org/pdf/2607.00272)]  
→ A continual robotics framework that synthesizes reusable robot skills from multimodal execution traces, failure diagnosis, and validated program repairs.


<!--- (*Arxiv'25*) *SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience*  [[📝 Paper](https://arxiv.org/pdf/2508.04700)] [[💻 Code](https://github.com/SunzeY/SEAgent)]  
→ A self-evolving computer-use agent that learns reusable skills from trial-and-error trajectories in unfamiliar software. -->

<!--- (*Arxiv'25*) *WALT: Web Agents that Learn Tools*  [[📝 Paper](https://arxiv.org/pdf/2510.01524)] [[💻 Code](https://github.com/SalesforceAIResearch/WALT)]  
→ A framework that reverse-engineers latent website functionality into reusable invocable tool APIs for web agents. -->

<!--- (*Arxiv'26*) *ACuRL: Autonomous Continual Learning of Computer-Use Agents for Environment Adaptation*  [[📝 Paper](https://arxiv.org/pdf/2602.10356)] [[💻 Code](https://github.com/OSU-NLP-Group/ACuRL)]  
→ An autonomous curriculum RL framework enabling computer-use agents to continually adapt to new environments with zero human data.  -->

## 3. Test-Time Skill Synthesis
- (*Arxiv'26*) *SkillGen: Verified Inference-Time Agent Skill Synthesis* [[📝 Paper](https://arxiv.org/pdf/2605.10999)] [[💻 Code](https://github.com/yccm/SkillGen)]  
→ A verified inference-time skill synthesis framework that derives an auditable skill from successful and failed agent trajectories through contrastive induction, iterative refinement, and paired performance verification.

- (*Arxiv'26*) *Skills on the Fly: Test-Time Adaptive Skill Synthesis for LLM Agents* [[📝 Paper](https://arxiv.org/pdf/2605.16986)]  
→ A test-time adaptive skill synthesis method that retrieves relevant training trajectories and compresses them online into temporary, task-specific textual skills without parameter updates.


## 4. Surveys & Systematization
- (*Arxiv'26*) *Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward*  [[📝 Paper](https://arxiv.org/pdf/2602.12430)] [[💻 Code](https://github.com/scienceaix/agentskills)]  
→ A comprehensive survey covering skill architecture, acquisition methods, deployment at scale, security, and governance for LLM agents.

- (*Arxiv'26*) *SoK: Agentic Skills -- Beyond Tool Use in LLM Agents*  [[📝 Paper](https://arxiv.org/pdf/2602.20867)]  
→ A systematization of knowledge mapping the full skill lifecycle with seven design patterns, a representation-by-scope taxonomy, and security analysis.
