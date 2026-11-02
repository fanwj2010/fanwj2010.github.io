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



<!-- ============================================ -->
<!-- PentestLLM -->
<!-- ============================================ -->

<h3>PentestLLM: LLM-Enabled Penetration Testing</h3>

<div class="research-project">

  <div class="research-description">
    <strong>Brief Summary:</strong>

    PentestLLM explores the application of Large Language Models (LLMs) to penetration testing, aiming to make security assessment more intelligent and automated. By leveraging LLM-based reasoning and tool integration, the framework investigates how AI can assist in understanding testing objectives, identifying potential attack paths, executing penetration-testing workflows, and interpreting security assessment results. This research aims to advance LLM-enabled penetration testing and reduce the complexity of security evaluation.
  </div>

  <figure class="research-figure">
    <img src="/images/PentestLLM.png"
         alt="PentestLLM: LLM-enabled penetration testing">
    <figcaption>
      Overview of the LLM-enabled penetration testing framework.
    </figcaption>
  </figure>

</div>


<!-- ============================================ -->
<!-- PeerLumen -->
<!-- ============================================ -->

<h3>PeerLumen: Bitcoin P2P Network Telescope Honeypot</h3>

<div class="research-project">

  <div class="research-description">
    <strong>Brief Summary:</strong>

    PeerLumen investigates a client-side honeypot telescope for monitoring and analyzing security threats in the Bitcoin peer-to-peer (P2P) network. By observing network connections and peer behaviors, the system aims to collect valuable threat intelligence and characterize malicious activities within the Bitcoin ecosystem. The research explores network-level monitoring across IPv4, IPv6, and Tor onion services, providing insights into emerging threats, suspicious connection patterns, and the security dynamics of decentralized P2P networks.
  </div>

  <figure class="research-figure">
    <img src="/images/PeerLumen.png"
         alt="PeerLumen: Bitcoin P2P network telescope honeypot">
    <figcaption>
      Overview of the Bitcoin P2P network telescope honeypot.
    </figcaption>
  </figure>

</div>


<!-- ============================================ -->
<!-- VulnLoop -->
<!-- ============================================ -->

<h3>VulnLoop: AI Agent-Driven Vulnerability Discovery and Repair</h3>

<div class="research-project">

  <div class="research-description">
    <strong>Brief Summary:</strong>

    VulnLoop explores an AI agent-driven approach to automated software vulnerability discovery and repair. By leveraging intelligent agents and LLM-based reasoning, the framework aims to identify potential software vulnerabilities, analyze their root causes, and generate appropriate code-level fixes. Through an iterative discovery, analysis, repair, and validation process, this research investigates how autonomous AI agents can improve software security and facilitate continuous vulnerability remediation.
  </div>

  <figure class="research-figure">
    <img src="/images/VulnLoop.png"
         alt="VulnLoop: AI agent-driven vulnerability discovery and repair">
    <figcaption>
      Overview of the AI agent-driven vulnerability discovery and repair framework.
    </figcaption>
  </figure>

</div>


<!-- ============================================ -->
<!-- LLM-CW -->
<!-- ============================================ -->

<h3>
  LLM-CW:
  <a href="https://edas.info/showPaper.php?m=1571359596"
     target="_blank"
     rel="noopener noreferrer">
    LLM-Driven Cyber Wargaming for Evolving Attack-Defense Dynamics and Strategy Adaptation
  </a>
</h3>

<div class="research-project">

  <div class="research-description">
    <strong>Brief Summary:</strong>

    LLM-CW investigates the application of Large Language Models (LLMs) to cyber wargaming, focusing on evolving attack-defense interactions and adaptive strategy development. The research explores how LLM-driven agents can simulate attacker and defender behaviors, reason about dynamic cyber scenarios, and adapt their strategies in response to evolving threats and defensive actions. By integrating intelligent decision-making into cyber wargaming, this work aims to advance autonomous adversarial simulation and strategic analysis for cybersecurity.
  </div>

  <figure class="research-figure">
    <img src="/images/LLM-CW.png"
         alt="LLM-driven cyber wargaming">
    <figcaption>
      Overview of LLM-driven cyber wargaming and adaptive attack-defense strategies.
    </figcaption>
  </figure>

</div>

