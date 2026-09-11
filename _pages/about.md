---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

I am a Master's student in Computer Technology at the University of Chinese Academy of Sciences and conduct research at the Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences. I am advised by **Xitong Gao**.

My research focuses on making large language models (LLMs) robust to adversarial misuse, securing LLM agents operating in untrusted environments, and improving the effectiveness and efficiency of agent systems.

<span class="anchor" id="research"></span>

# Research Experience

## LLM Jailbreak Defense - StreamGuard

Designed and implemented **StreamGuard**, a lightweight, plug-and-play decoding-time defense against jailbreak attacks. StreamGuard self-reviews partial generations and inserts safety prompts when unsafe content is detected, without fine-tuning. Across six model-attack settings, it achieved a mean attack success rate of **1.7%**, compared with **20.3%** for the strongest defense baseline and **60.3%** without defense.

## MCP Agent Security - A2M

Designed and implemented **A2M (Attraction to Manipulation)**, a two-stage black-box attack that optimizes tool metadata to increase selection likelihood and then refines return payloads using execution traces to manipulate downstream reasoning. On LiveMCPBench, A2M achieved a mean ASR of **74.4%** across information exfiltration, unauthorized environment modification, and reasoning derailment objectives, and increased token consumption by **32.4x** on a separate token-wasting objective. The optimized attacks also transferred effectively to unseen models.

## Efficient LLM Agents - Growing Harness

Designed and implemented **Growing Harness**, a failure-guided framework that starts from a strategy-free scaffold and incrementally grows into an executable agent harness through function-level execution traces and localized code edits. This shifts recurring control logic from LLM inference to reusable program code. Across six benchmark-model settings, it achieved a mean task success rate of **42.2%**, compared with **23.6%** for a ReAct-style Tool-Calling baseline, while reducing LLM calls by **76.0-91.8%** and inference cost by **74.4-98.6%**.

<span class="anchor" id="publications"></span>

# Publications

1. **StreamGuard: A Streaming-based Defense Against Jailbreaking Attacks in Large Language Models**  
   *Laizhen Li*, Xitong Gao, Xuan Wang, Juanjuan Zhao, and Kejiang Ye. **ICONIP 2025**. [Paper](https://doi.org/10.1007/978-981-95-4109-6_21)

2. **JADE: Jailbreak-Aware Dynamic Defense Enhancer for LLMs via Reinforcement Learning**  
   Peicheng Zhao, *Laizhen Li*, Xitong Gao, Juanjuan Zhao, and Kejiang Ye. **IEEE BigData 2025**. [Paper](https://doi.org/10.1109/BigData66926.2025.11400893)

3. **A2M: Trace-Optimized Agent Hijacking in the MCP Ecosystem**  
   *Laizhen Li*, Xuan Wang, Peicheng Zhao, Juanjuan Zhao, Kejiang Ye, Cheng-zhong Xu, and Xitong Gao. **AACL-IJCNLP 2026, accepted**.

# Manuscripts Under Review

1. **Grow the Harness, Not the Context: From Strategy-Free Scaffolds to Reusable Specialist Agents**  
   **AAAI 2027**, under review.

2. **Co-Evolving Poison and Defense Harnesses: Adversarial Arms Races for Indirect Prompt Injection in Tool-Integrated Agents**  
   **AAAI 2027**, under review.

# CV

For a complete list of education, research experience, publications, and skills, see my [CV](/files/Laizhen-Li-CV.pdf).
