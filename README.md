<!--
  Hi, source-code inspector.

  Yes, there is HTML in this README.
  It was easier this way.
-->

<div align="center">

# Hi 👋, I'm Minh

### Software Engineer · Computer Science PhD Student · Systems Tinkerer

**Security · Distributed systems · Developer tools · Local AI**

Born and raised in Germany with Vietnamese roots. Currently doing my PhD in Canada.

**Available for part-time remote contracting · $70/hour**


</div>

<img
  align="right"
  width="220"
  hspace="0"
  src="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/rainbow-cat-round.gif"
  alt="Rainbow cat"
/>

I like building things, taking systems apart, and finding out why something behaves differently from what I expected. Sometimes that leads to a useful tool. Sometimes it just leads to another project.

For my PhD, I'm working on **distributed key management for storage systems**. A lot of that means writing prototypes, running benchmarks, and seeing what happens when the system is under load or parts of it fail.

In my free time I've been messing with **coding agents and their harnesses**. Lately I've been looking into skills: do they actually make agents better at particular tasks, or are we sometimes just adding more instructions and hoping for the best?

There's also my **homelab**, which runs on Proxmox and regularly gives me something new to tinker with. I tend to try a tool, run into one annoying limitation, and start wondering whether I should build my own. This may explain the number of unfinished projects.

<br clear="right" />

---

## 🔭 What I'm building (and what I've built)

<table>
<tr>
<td colspan="2" valign="top">

### 💸 Arc Payables

`agents` `Arc` `USDC` `Solidity` `Python`

An accounts-payable agent I built for the Tameion Agents Hackathon. It can recommend payments, but it can't approve its own spending. A budget contract on-chain makes that decision instead. I'd rather not let an agent talk its way around a spending limit.

<br>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 Distributed KMS

`distributed systems` `storage` `security` `performance`

Part of my PhD research. I'm comparing different ways to build key management services for distributed storage and testing how they behave.

Generating a key is usually the easy bit. Things get more interesting when requests pile up, a node disappears, or recovery doesn't go quite as planned.

<br>

</td>
<td width="50%" valign="top">

### 🛠️ Ground Control

`infrastructure` `control plane` `automation` `systems`

A commissioned prototype for managing different hypervisor platforms through one interface. It supports Proxmox and Xen Orchestra, with room for additional providers.

The prototype is complete and has been handed off to the requesting organization's R&D team. It's not an open-source project.

<br>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧠 Small-model coding agents

`local AI` `agents` `LLMs` `benchmarking`

I keep wondering how much of a coding agent's performance comes from the model itself and how much comes from everything around it.

I've been experimenting with smaller local models, tool use, context handling, and delegation. More recently, I've been trying to figure out which agent skills actually help and which ones just add noise.

<br>

</td>
<td width="50%" valign="top">

### 🐧 Reproducible systems

`NixOS` `Linux` `containers` `homelab`

My NixOS configuration stopped being *just* a configuration a while ago. It's now where I experiment with multi-machine setups and self-hosted services.

I like being able to rebuild a machine without having to remember every little thing I changed six months ago. Whether I always manage that is another question.

<br>

</td>
</tr>
</table>

---

## 🌱 Open source

I maintain **Specht**, and I also contribute fixes upstream when I run into problems. Sometimes the fix is tiny. Figuring out why it's needed usually isn't.

A few examples:

* **[TokenTracker](https://github.com/xiufengsun/TokenTracker)** — Worked on Linux/NixOS and WSL support, provider integrations, and token accounting.
  [Antigravity process + port detection](https://github.com/xiufengsun/TokenTracker/pull/579) · [Command Code limits](https://github.com/xiufengsun/TokenTracker/pull/594) · [Antigravity token accounting](https://github.com/xiufengsun/TokenTracker/pull/599) · [DeepSeek Harness v3](https://github.com/xiufengsun/TokenTracker/pull/614)

* **[Serpantinum](https://github.com/ilyamiro/serpantinum)** — Fixed some Wayland desktop behavior and display-manager issues.
  [SDDM compositor handling](https://github.com/ilyamiro/serpantinum/pull/282) · [Autohide tray behavior](https://github.com/ilyamiro/serpantinum/pull/249)

* **[Specht](https://github.com/minh-tg/specht)** — Vulnerability management tooling I'm working on. I want it to be useful to developers first, not just another place to dump scanner output. I'm exploring CLI and MCP support so coding agents can help make sense of findings and work through them. Still very much a work in progress.

---

## 📚 Publications

- **[You Can't Touch This: Detecting Typosquatting Packages for Enhanced Malware Prevention in Software Supply Chains](https://doi.org/10.1007/978-981-96-3531-3_8)** — NSS 2024, Best Paper Award (Springer)
- **[Comparing Client- & Server-Side AEAD Encryption in Software-Defined Storage Systems](https://doi.org/10.1109/pst65910.2025.11268846)** — PST 2025 (IEEE Xplore)

---

## ⚙️ Toolbox

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original.svg" height="32" alt="Go" title="Go" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" height="32" alt="Python" title="Python" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" height="32" alt="Linux" title="Linux" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nixos/nixos-original.svg" height="32" alt="NixOS" title="NixOS" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" height="32" alt="Docker" title="Docker" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" height="32" alt="PostgreSQL" title="PostgreSQL" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kubernetes/kubernetes-original.svg" height="32" alt="Kubernetes" title="Kubernetes" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" height="32" alt="Git" title="Git" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/csharp/csharp-original.svg" height="32" alt="C#" title="C#" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dotnetcore/dotnetcore-original.svg" height="32" alt=".NET" title=".NET" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" height="32" alt="TypeScript" title="TypeScript" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" height="32" alt="JavaScript" title="JavaScript" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vuejs/vuejs-original.svg" height="32" alt="Vue.js" title="Vue.js" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" height="32" alt="React" title="React" />
  <img width="7" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-plain-wordmark.svg" height="32" alt="AWS" title="AWS" />
</div>

<p align="center">
  Most days I write <strong>Go</strong> or <strong>Python</strong>. The rest depends on what I'm trying to make work.
</p>

---

## 📊 GitHub

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://gitcard-studio.creativecode.com.co/api/stats?username=minh-tg&theme=dark&locale=en"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://gitcard-studio.creativecode.com.co/api/stats?username=minh-tg&theme=light&locale=en"
    />
    <img
      src="https://gitcard-studio.creativecode.com.co/api/stats?username=minh-tg&theme=light&locale=en"
      alt="Minh's GitHub statistics"
    />
  </picture>
</div>

<br>

<div align="center">
  <img
    src="https://streak-stats.demolab.com?user=minh-tg&theme=dracula&hide_border=true&border_radius=5&mode=weekly"
    height="165"
    alt="GitHub streak"
  />
</div>

<br>

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/snake.svg"
    />
    <img
      src="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/snake.svg"
      alt="GitHub contribution snake"
    />
  </picture>
</div>

---

## 🤝 Connect

If you're working on something interesting, have a weird bug, or just want to compare notes, feel free to reach out.

<p align="center">
  <a href="https://www.linkedin.com/in/minh-tg/">
    <img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://orcid.org/0009-0006-3866-4621">
    <img src="https://img.shields.io/badge/ORCID-research-A6CE39?logo=orcid&logoColor=white" alt="ORCID" />
  </a>
  <img src="https://img.shields.io/badge/Discord-minh__tg-5865F2?logo=discord&logoColor=white" alt="Discord: minh_tg" />
</p>

---

<p align="center">
  <i>Probably working on another side project.</i>
</p>
