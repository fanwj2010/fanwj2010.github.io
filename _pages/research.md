---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## LLM-Powered Adaptive Honeypot

### HoneyLLMd: A Large Language Model-Powered Adaptive Honeypot System

<style>
.research-project {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 25px;
  align-items: center;
  margin: 20px 0 45px 0;
}

.research-description {
  text-align: justify;
  line-height: 1.7;
}

.research-figure {
  margin: 0;
  text-align: center;
}

.research-figure img {
  width: 100%;
  height: auto;
  border-radius: 6px;
}

.research-figure figcaption {
  font-size: 0.85em;
  color: #777;
  margin-top: 8px;
}

@media screen and (max-width: 768px) {
  .research-project {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="research-project">

  <div class="research-description">

    <strong>Brief Summary:</strong>

    Honeypots lure attackers by emulating vulnerabilities, yet balancing deep attacker engagement with resource security remains challenging. We propose an adaptive honeypot system powered by a Large Language Model (LLM). Unlike traditional decoys, the proposed system generates authentic, shell-like responses without exposing a real operating system, facilitating convincing request–response interactions that capture valuable attacker behavioral data. To enhance defensive capabilities, we employ a Hierarchical Probabilistic Automaton (HPA) to model attack transitions and dynamically adapt honeypot strategies. Experimental results demonstrate that our LLM-driven approach achieves superior attacker engagement and data collection while maintaining significantly lower security risks than conventional methods.

  </div>

  <figure class="research-figure">
    <img src="/images/HoneyLLMd.png"
         alt="LLM-powered adaptive honeypot architecture">
    <figcaption>
      Overview of the LLM-powered adaptive honeypot system.
    </figcaption>
  </figure>

</div>
