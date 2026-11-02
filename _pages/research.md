---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## LLM-Powered Adaptive Honeypot

### HoneyLLMd: A Large Language Model-Powered Adaptive Honeypot System

<figure style="margin: 20px 0; text-align: center;">
  <img src="/images/HoneyLLMd.png"
       alt="Architecture and workflow of the LLM-powered adaptive honeypot system"
       style="width: 100%; max-width: 850px; height: auto; border-radius: 6px;">
  <figcaption style="font-size: 0.9em; color: #666; margin-top: 8px;">
    Overview of the LLM-powered adaptive honeypot architecture.
  </figcaption>
</figure>

**Brief Summary:**

Honeypots lure attackers by emulating vulnerabilities, yet balancing deep attacker engagement with resource security remains challenging. We propose an adaptive honeypot system powered by a Large Language Model (LLM). Unlike traditional decoys, the proposed system generates authentic, shell-like responses without exposing a real operating system, facilitating convincing request–response interactions that capture valuable attacker behavioral data. To enhance defensive capabilities, we employ a Hierarchical Probabilistic Automaton (HPA) to model attack transitions and dynamically adapt honeypot strategies. Experimental results demonstrate that our LLM-driven approach achieves superior attacker engagement and data collection while maintaining significantly lower security risks than conventional methods.

**Key Contributions:**

- **LLM-Powered Shell Emulation:** Generates realistic, context-aware shell responses without exposing a real operating system.
- **Adaptive Attack Modeling:** Employs a Hierarchical Probabilistic Automaton (HPA) to model attacker behaviors and transitions.
- **Dynamic Honeypot Adaptation:** Adjusts deception strategies based on observed attack patterns.
- **Enhanced Threat Intelligence:** Improves attacker engagement and behavioral data collection while minimizing security risks.
