---
permalink: /
title: ""
excerpt: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<header class="site-intro">
  <h1 class="site-intro__name">Laizhen Li (李来真)</h1>
  <p class="site-intro__address">
    Shenzhen Institute of Advanced Technology, Chinese Academy of Sciences<br>
    Shenzhen, Guangdong, China
  </p>
  <p class="site-intro__links">
    <a href="mailto:lilaizhencs@gmail.com">lilaizhencs@gmail.com</a>
    <span aria-hidden="true">·</span>
    <a href="https://github.com/Lilaizhen">GitHub</a>
    <span aria-hidden="true">·</span>
    <a href="/files/Laizhen-Li-CV.pdf">CV</a>
  </p>
</header>

# About Me

I am a master's student in Computer Technology at the University of Chinese Academy of Sciences. I conduct research at the Shenzhen Institutes of Advanced Technology, Chinese Academy of Sciences, under the supervision of **Xitong Gao**. I received my B.Eng. in Software Engineering from Henan University of Engineering in 2023.

I work on trustworthy and efficient AI, with a current focus on LLM safety, agent security, and agent efficiency.

<span class="anchor" id="selected-works"></span>

# Selected Works

## LLM Safety - StreamGuard

Designed and implemented **StreamGuard**, a lightweight, plug-and-play decoding-time defense against jailbreak attacks. StreamGuard self-reviews partial generations and inserts safety prompts when unsafe content is detected, without fine-tuning. Across six model-attack settings, it achieved a mean attack success rate of **1.7%**, compared with **20.3%** for the strongest defense baseline and **60.3%** without defense.

## Agent Security - A2M

Designed and implemented **A2M (Attraction to Manipulation)**, a two-stage black-box attack that optimizes tool metadata to increase selection likelihood and then refines return payloads using execution traces to manipulate downstream reasoning. On LiveMCPBench, A2M achieved a mean ASR of **74.4%** across information exfiltration, unauthorized environment modification, and reasoning derailment objectives, and increased token consumption by **32.4x** on a separate token-wasting objective. The optimized attacks also transferred effectively to unseen models.

## Agent Efficiency - Growing Harness

Designed and implemented **Growing Harness**, a failure-guided framework that starts from a strategy-free scaffold and incrementally grows into an executable agent harness through function-level execution traces and localized code edits. This shifts recurring control logic from LLM inference to reusable program code. Across six benchmark-model settings, it achieved a mean task success rate of **42.2%**, compared with **23.6%** for a ReAct-style Tool-Calling baseline, while reducing LLM calls by **76.0-91.8%** and inference cost by **74.4-98.6%**.

<span class="anchor" id="publications"></span>

# Publications

1. **StreamGuard: A Streaming-based Defense Against Jailbreaking Attacks in Large Language Models**  
   <u>Laizhen Li</u>, Xitong Gao, Xuan Wang, Juanjuan Zhao, and Kejiang Ye.<br>
   **ICONIP 2025**. [Paper](https://doi.org/10.1007/978-981-95-4109-6_21)

2. **JADE: Jailbreak-Aware Dynamic Defense Enhancer for LLMs via Reinforcement Learning**  
   Peicheng Zhao, <u>Laizhen Li</u>, Xitong Gao, Juanjuan Zhao, and Kejiang Ye.<br>
   **IEEE BigData 2025**. [Paper](https://doi.org/10.1109/BigData66926.2025.11400893)

3. **A2M: Trace-Optimized Agent Hijacking in the MCP Ecosystem**  
   <u>Laizhen Li</u>, Xuan Wang, Peicheng Zhao, Juanjuan Zhao, Kejiang Ye, Cheng-zhong Xu, and Xitong Gao.<br>
   **AACL-IJCNLP 2026 (main)**.

# Manuscripts Under Review

1. **Grow the Harness, Not the Context: From Strategy-Free Scaffolds to Reusable Specialist Agents**  
   **AAAI 2027**, under review.

2. **Co-Evolving Poison and Defense Harnesses: Adversarial Arms Races for Indirect Prompt Injection in Tool-Integrated Agents**  
   **AAAI 2027**, under review.
