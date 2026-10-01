<!-- [xihanzu-NR] -->
<div align="center">

# Reyhan Akhtar Afriansyah (Hanz)
**Systems & Software Engineer · Compiler Tooling · Linux Infrastructure · Applied AI**

`SMK Ma'arif 1 Kroya, Indonesia` · `17 y.o.` · `Void Linux / Arch Linux (Daily)`

<br/>

[![GitHub Repositories](https://img.shields.io/badge/GitHub-hanxthvy-141413?style=flat-square&logo=github&logoColor=faf9f5)](https://github.com/hanxthvy)
[![Portfolio](https://img.shields.io/badge/Portfolio-hanz.dev-cc785c?style=flat-square&logo=safari&logoColor=white)](https://github.com/hanxthvy/portfolio)
[![Rust Compiler](https://img.shields.io/badge/Ecosystem-HydraScript-141413?style=flat-square&logo=rust&logoColor=cc785c)](https://github.com/hanxthvy/hydrascript)
[![License](https://img.shields.io/badge/License-MIT-gray?style=flat-square)](LICENSE)

</div>

---

### // ENGINEERING THESIS

> *I build computing systems from the silicon and server chassis up to language compilers and neural inference engines. I prefer native binaries over bloated runtimes, minimal self-contained dependencies over framework abstractions, and verified benchmarks over ungrounded claims.*

---

### // FLAGSHIP WORK: THE HYDRASCRIPT ECOSYSTEM

An end-to-end programming language toolchain designed to combine the expressive conciseness of Python with the performance of native JavaScript/React compilation and local LLM code generation.

```
┌─────────────────────────┐      ┌───────────────────────────┐      ┌─────────────────────────┐
│   HydraScript Source    │ ───► │  Rust Compiler (hydra)    │ ───► │   React (.jsx)          │
│   (.hyx / .hys files)   │      │  AST Tokenizer & Emitter  │      │   Node.js ESM (.mjs)    │
└─────────────────────────┘      └───────────────────────────┘      └─────────────────────────┘
             ▲                                                                   │
             │ Fine-tuned on 6,965 compiler-verified pairs                       │
┌─────────────────────────┐                                                      ▼
│   HydraScript LLM       │ ◄────────────────────────────────────────────────────┘
│   Qwen3-0.6B LoRA Q8_0  │ (Validates against `hydra --check` in continuous feedback loop)
└─────────────────────────┘
```

| Project | Role & Description | Tech Stack | Status |
| :--- | :--- | :--- | :--- |
| [**HydraScript**](https://github.com/hanxthvy/hydrascript) | Standalone native compiler transpiling Pythonic syntax (`.hyx` for UI components, `.hys` for server logic) directly into clean React and Node.js ES Modules in ~1ms without runtime overhead. | Rust, Lexer/Parser AST, OxC | Public Open-Source |
| [**HydraScript LLM**](https://github.com/hanxthvy/hydrascript-llm) | Specialized 0.6B parameter code LLM fine-tuned via LoRA specifically on 6,965 compiler-checked syntax samples across 38 curricular segments. Exported to GGUF Q8_0 for edge CPU inference via llama.cpp. | Qwen3, PyTorch, LoRA, llama.cpp, GGUF | Public Open-Source |
| [**Developer Portfolio**](https://github.com/hanxthvy/portfolio) | Production portfolio web application authored 100% in HydraScript (`.hyx` and `.hys`). Features custom CSS matrix spatial perspective, Alight Motion-derived wave exit splash screen, and dynamic zero-FOUC theme switching. | HydraScript, React 18, Tailwind, GSAP | Public Open-Source |

---

### // HYDRASCRIPT SYNTAX AT A GLANCE

HydraScript replaces JSX angle-bracket clutter and boilerplate JavaScript keywords with clean Pythonic block syntax.

```python
# [xihanzu-NR]
# Counter.hyx — Compiled to React component by `hydra` in < 2ms
from "react" import useState

component Counter(initial=0, label="Clicks"):
    count, set_count = useState(initial)

    div(className="p-6 rounded-[8px] border border-[#e6dfd8] bg-[#faf9f5]"):
        p(className="text-xs font-mono text-[#cc785c] uppercase"): label
        h3(className="text-3xl font-semibold text-[#141413] my-2"): count
        button(
            onClick=lambda: set_count(count + 1),
            className="px-4 py-2 bg-[#cc785c] text-white rounded-[6px] hover:bg-[#a9583e]"
        ): "Increment"
```

---

### // PHYSICAL INFRASTRUCTURE & HOMELAB

I host and operate my own physical infrastructure without reliance on commercial cloud platforms for development clusters.

* **Physical Compute**: 1U Enterprise Rack Server **HPE ProLiant DL360 Gen9** (Intel Xeon, ECC DDR4 RAM).
* **Virtualization Layer**: **Proxmox VE** hypervisor orchestrating LXC micro-containers and Debian/Ubuntu VMs.
* **Network Topology**: WireGuard mesh tunnel bridging residential CGNAT networks directly to public routing gateways with zero port forwarding required.
* **Container Orchestration**: Pterodactyl daemon (`wings`) container clusters, running isolated compiler workers and continuous dataset distillation pipelines.
* **Daily Workstation**: Void Linux (`runit` init system), Arch Linux, Neovim, Bash toolchains, tmux.

---

### // INDUSTRY EXPERIENCE & CREDENTIALS

* **PT Panasonic Manufacturing Indonesia** — *Industrial Internship (PKL)*
  * Department: Audio PCB Assembly Line & Manufacturing Quality Control.
  * Responsibilities: Component mounting, panel cutting, quality verification under strict factory standard operating procedures (SOP).
  * Outcome: **Grade A — Score 94.3 / 100** *(Credential ID: `561/AD-PERS/I/2026`)*.

* **Dicoding Indonesia Verified Certifications**:
  * [Belajar Back-End Pemula dengan JavaScript](https://www.dicoding.com/certificates/98XWO65KLXM3) *(Credential: `98XWO65KLXM3`)*
  * [Belajar Dasar AI (Artificial Intelligence)](https://www.dicoding.com/certificates/RVZKO4110ZD5) *(Credential: `RVZKO4110ZD5`)*

---

### // CORE TOOLBOX

```
Systems & Langs   : Rust, Python, JavaScript/Node.js, C/C++, Bash Shell
Infra & Server    : Proxmox VE, Linux Kernel, WireGuard VPN, Nginx, Docker, Pterodactyl, Systemd/Runit
AI & Distillation : PyTorch, Unsloth, llama.cpp (GGUF), LoRA Fine-Tuning, Dataset Distillation Pipelines
Frontend & UI     : HydraScript (.hyx), React 18, Tailwind CSS, GSAP, SVG Vector Animation
Hardware & IoT    : PCB Assembly & Rework, SMT Component Soldering, Arduino, Embedded Sensors
```

---

### // CONNECT & VERIFY

* **GitHub**: [@hanxthvy](https://github.com/hanxthvy)
* **Email**: [contact@hanz.dev](mailto:contact@hanz.dev)
* **Location**: Kroya, Cilacap, Central Java, Indonesia (UTC+7)

<div align="center">
<sub>Engineered with precision. All source code watermarked with <code>[xihanzu-NR]</code>.</sub>
</div>
