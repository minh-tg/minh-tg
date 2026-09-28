<!--
  Hi, source-code inspector 👋

  Yes, there is HTML in this README.
  No, I don't regret it.
-->

<div align="center">

# Hi 👋, I'm Minh

### Software Engineer · Computer Science PhD Student · Systems Tinkerer

**Distributed systems · Storage · Security · Infrastructure · Local AI**

Born and raised in Germany with Vietnamese roots, currently doing my PhD in Canada.

</div>

<img
  align="right"
  width="220"
  hspace="0"
  src="https://raw.githubusercontent.com/minh-tg/minh-tg/readme-assets/rainbow-cat-round.gif"
  alt="Rainbow cat"
/>

I like building things, messing around with systems, and whatever I'm digging into at the moment. Right now that's mostly **agent harnesses, security tooling, and small local models**.

My PhD work is around **distributed storage and key management**, especially what happens when systems get busy, nodes disappear, or failover has to work outside the happy path.

Outside of that, I spend a lot of time with **NixOS, self-hosting, developer tools, infrastructure**, and side projects that have a habit of becoming slightly larger than intended.

A fairly common sequence of events:

> Find a tool → try it → hit one annoying limitation → try a few alternatives → build something instead.

<br clear="right" />

---

## 🔭 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### 🔐 Distributed KMS

`distributed systems` `storage` `security` `performance`

A large part of my PhD work revolves around distributed KMS designs for storage systems, with a focus on **request handling, scaling, and failure behavior**.

The interesting part usually starts when the happy path stops being happy.

<br>

</td>
<td width="50%" valign="top">

### 🛠️ Ground Control

`infrastructure` `control plane` `automation` `systems`

A control plane for **heterogeneous infrastructure**.

Machines, services, and environments are rarely as uniform as we'd like them to be. Ground Control currently supports **Proxmox and Xen Orchestra** through one interface, with the architecture set up so more providers can be added without redesigning the whole thing.

<br>

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧠 Small-model coding agents

`local AI` `agents` `LLMs` `benchmarking`

I'm interested in how far you can push a small local model when more of the work is handled by the **harness and tooling around it**.

I've been testing tool policies, delegation, context handling, and failure modes — less "which model feels better?" and more "what actually changed, and can I measure it?"

<br>

</td>
<td width="50%" valign="top">

### 🐧 Reproducible systems

`NixOS` `Linux` `containers` `homelab`

My NixOS config stopped being just a config a while ago.

It's now where I experiment with **reproducibility, Wayland, containers, self-hosting, multi-machine setups**, and whatever else I've decided would probably be nicer if it were declarative.

<br>

</td>
</tr>
</table>

---

## 🌱 Open source

I usually contribute upstream when fixing something makes more sense than maintaining a workaround.

Some recent examples:

* **[TokenTracker](https://github.com/xiufengsun/TokenTracker)** - Linux/NixOS and WSL support, provider integrations, parser work, and making token accounting less wrong.  
  [Antigravity process + port detection](https://github.com/xiufengsun/TokenTracker/pull/579) · [Command Code limits](https://github.com/xiufengsun/TokenTracker/pull/594) · [Antigravity token accounting](https://github.com/xiufengsun/TokenTracker/pull/599) · [DeepSeek Harness v3](https://github.com/xiufengsun/TokenTracker/pull/614)

* **[Serpantinum](https://github.com/ilyamiro/serpantinum)** - fixes around Wayland desktop behavior and display-manager integration.  
  [SDDM compositor handling](https://github.com/ilyamiro/serpantinum/pull/282) · [autohide tray behavior](https://github.com/ilyamiro/serpantinum/pull/249)

* **[Specht](https://github.com/minh-tg/specht)** - security tooling, vulnerability management, and fixes that occasionally require learning far more about a subsystem than expected.

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
  Most of my day-to-day coding is in <strong>Go</strong> and <strong>Python</strong>. The rest depends on whatever I'm working on.
</p>

Most of what I build ends up somewhere around **backend services, research prototypes, developer tools, automation, benchmarks, dashboards**, and small tools for problems I got tired of working around.

<!-- TODO

---

## ✍️ Recently wrote

BLOG-POST-LIST:START
BLOG-POST-LIST:END

-->

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

Always happy to connect, whether it's about distributed systems, open source, research, local AI, or some weird tool you've been tinkering with.

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
  <i>Stay curious. Keep tinkering.</i>
</p>
