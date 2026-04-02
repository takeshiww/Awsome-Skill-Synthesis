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
- (*Arxiv'26*) *AutoSkill: Experience-Driven Lifelong Learning via Skill Self-Evolution*  [[📝 Paper](https://arxiv.org/pdf/2603.01145)] [[💻 Code](https://github.com/ECNU-ICALK/AutoSkill)]  
→ A training-free framework that distills skills from conversations.

- (*Arxiv'26*) *CUA-Skill: Develop Skills for Computer Using Agent*  [[📝 Paper](https://arxiv.org/pdf/2601.21123)] [[💻 Code](https://github.com/microsoft/cua_skill)]  
→ A systematic skill library for desktop computer use, encoding human knowledge as reusable, parameterized skills with dynamic retrieval and failure recovery.

- (*Arxiv'25*) *ALLOY: Generating Reusable Agent Workflows from User Demonstration*  [[📝 Paper](https://arxiv.org/pdf/2510.10049)]  
→ A PBD-inspired system that converts user demonstrations into reusable, editable, generalizable agent workflows for web tasks.

- (*Arxiv'25*) *LLM Agents Making Agent Tools*  [[📝 Paper](https://arxiv.org/pdf/2502.11705)] [[💻 Code](https://github.com/KatherLab/ToolMaker)]  
→ An agentic framework that autonomously converts scientific papers with code into LLM-compatible reusable tools.

- (*EACL Findings'26*) *Skill Discovery for Software Scripting Automation via Offline Simulations with LLMs*  [[📝 Paper](https://arxiv.org/pdf/2504.20406)]  
→ An offline simulation framework for discovering and verifying reusable scripting skills via GNN-based API synergy.


## 2. Skill Synthesis via Self-Distillation
- (*Arxiv'26*) *SKILLRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning*  [[📝 Paper](https://arxiv.org/pdf/2602.08234)] [[💻 Code](https://github.com/aiming-lab/SkillRL)]  
→ An RL framework that distills rollout trajectories into a hierarchical skill library and recursively evolves these skills during training.

- (*Arxiv'26*) *EvoSkill: Automated Skill Discovery for Multi-Agent Systems*  [[📝 Paper](https://arxiv.org/pdf/2603.02766)] [[💻 Code](https://github.com/sentient-agi/EvoSkill)]  
→ A framework that distills skills via failure analysis by text feedback.

- (*Arxiv'26*) *MetaClaw: Just Talk -- An Agent That Meta-Learns and Evolves in the Wild*  [[📝 Paper](https://arxiv.org/pdf/2603.17187)] [[💻 Code](https://github.com/aiming-lab/MetaClaw)]  
→ A continual learning framework that synthesizes skills from failure trajectories.

- (*Arxiv'25*) *SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills*  [[📝 Paper](https://arxiv.org/pdf/2504.07079)] [[💻 Code](https://github.com/OSU-NLP-Group/SkillWeaver)]  
→ A web agent framework that distills exploration and practice experiences into reusable APIs.

- (*Arxiv'25*) *SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience*  [[📝 Paper](https://arxiv.org/pdf/2508.04700)] [[💻 Code](https://github.com/SunzeY/SEAgent)]  
→ A self-evolving computer-use agent that learns reusable skills from trial-and-error trajectories in unfamiliar software.

- (*Arxiv'26*) *Memento-Skills: Let Agents Design Agents*  [[📝 Paper](https://arxiv.org/pdf/2603.18743)] [[💻 Code](https://github.com/Memento-Teams/Memento-Skills)]  
→ A deployment-time learning framework that rewrites and grows an external skill library from execution feedback and reflection.

- (*Arxiv'26*) *Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills*  [[📝 Paper](https://arxiv.org/pdf/2603.25158)]  
→ Distills broad agent execution experience into transferable, conflict-free declarative skill directories via hierarchical inductive consolidation.

- (*Arxiv'25*) *Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback*  [[📝 Paper](https://arxiv.org/pdf/2506.04287)]  
→ An exploration-first skill discovery framework where one agent explores environments to generate feasible skill datasets for training another.

- (*Arxiv'25*) *Inducing Programmatic Skills for Agentic Tasks*  [[📝 Paper](https://arxiv.org/pdf/2504.06821)]  
→ A framework where agents self-induce, verify, and reuse programmatic code-based skills on the fly for web navigation tasks.

- (*Arxiv'26*) *OSExpert: Computer-Use Agents Learning Professional Skills via Exploration*  [[📝 Paper](https://arxiv.org/pdf/2603.07978)]  
→ A DFS-based exploration algorithm that discovers unit functions and composes composite skills for computer-use agents.

- (*Arxiv'25*) *WALT: Web Agents that Learn Tools*  [[📝 Paper](https://arxiv.org/pdf/2510.01524)] [[💻 Code](https://github.com/SalesforceAIResearch/WALT)]  
→ A framework that reverse-engineers latent website functionality into reusable invocable tool APIs for web agents.

- (*Arxiv'26*) *ACuRL: Autonomous Continual Learning of Computer-Use Agents for Environment Adaptation*  [[📝 Paper](https://arxiv.org/pdf/2602.10356)] [[💻 Code](https://github.com/OSU-NLP-Group/ACuRL)]  
→ An autonomous curriculum RL framework enabling computer-use agents to continually adapt to new environments with zero human data.

- (*Arxiv'26*) *MACRO: Evolving Medical Imaging Agents via Experience-driven Self-skill Discovery*  [[📝 Paper](https://arxiv.org/pdf/2603.05860)]  
→ A medical imaging agent that discovers recurring multi-step tool sequences from execution experience and synthesizes them into reusable composite tools.

- (*Arxiv'25*) *Audited Skill-Graph Self-Improvement for Agentic LLMs via Verifiable Rewards, Experience Synthesis, and Continual Memory*  [[📝 Paper](https://arxiv.org/pdf/2512.23760)]  
→ A framework for auditable skill-graph self-improvement where capabilities are extracted from trajectories and promoted after passing contract checks.


## 3. Surveys & Systematization
- (*Arxiv'26*) *Agent Skills for Large Language Models: Architecture, Acquisition, Security, and the Path Forward*  [[📝 Paper](https://arxiv.org/pdf/2602.12430)] [[💻 Code](https://github.com/scienceaix/agentskills)]  
→ A comprehensive survey covering skill architecture, acquisition methods, deployment at scale, security, and governance for LLM agents.

- (*Arxiv'26*) *SoK: Agentic Skills -- Beyond Tool Use in LLM Agents*  [[📝 Paper](https://arxiv.org/pdf/2602.20867)]  
→ A systematization of knowledge mapping the full skill lifecycle with seven design patterns, a representation-by-scope taxonomy, and security analysis.
