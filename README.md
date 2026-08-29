# Emerson Busson

Senior Full Stack & Systems Software Engineer.

I build production web applications and high-performance systems tooling: from fast, accessible interfaces in React/Next.js to low-level systems in Rust (Linux kernel block drivers/WSL2) and distributed backend services in Go.

[LinkedIn](https://linkedin.com/in/emersonbusson) ·
[Email](mailto:emersonbusson@gmail.com) ·
[WhatsApp](https://wa.me/5585997926694)

## What I work with

- **Frontend & Product UI:** React, Next.js, TypeScript, state management (TanStack Query/Zustand), StyleX, forms and design systems
- **Quality & Testing:** accessibility (WCAG), responsive UI, Playwright, Vitest, contract testing and visual regression
- **Backend & Cloud:** Go, Node.js, PostgreSQL, Redis, REST APIs, typed contracts, authentication and workspace routing
- **Systems & Platform:** Rust, Linux Kernel (`ublk`, `zram`), WSL2 daemons, Docker, and self-hosted CI runners (`civmctl`)

## Selected work

- **[Google Gemini CLI](https://github.com/google-gemini/gemini-cli/pull/26955)** — upstream merged contribution optimizing runtime performance, bounding live UI output buffers (`LIVE_OUTPUT_MAX_CHARS`), and throttling shell telemetry in Google's official AI agent CLI.
- **[RamShared](https://github.com/emersonbusson/ramshared)** — a Rust systems project utilizing the Linux `ublk` driver to turn idle NVIDIA VRAM into an elastic memory tier (8.53 GB/s throughput in FIO); author of the formal kernel proposal in [microsoft/WSL#41054](https://github.com/microsoft/WSL/issues/41054).
- **[GuardWSL](https://github.com/emersonbusson/guardwsl)** — a Rust safety daemon that prevents physical disk/RAM exhaustion on WSL2 hosts via transactional allowlist cleanup and heavy-build serialization.
- **[civm](https://github.com/emersonbusson/civm)** — open-source tooling (`civmctl`) to provision, operate, and self-heal self-hosted GitHub Actions runners with strict `ubuntu-latest` parity.
- **Advoq** — a multi-tenant legal SaaS covering intake, CRM, case work, documents, and day-to-day operations with typed API contracts in Next.js, React, and TypeScript.

<details>
<summary>Português</summary>

## Sobre

Sou engenheiro de software sênior full stack e de sistemas. Desenvolvo aplicações web completas e ferramentas de infraestrutura/sistemas de alta performance: da concepção de UIs rápidas e acessíveis em React/Next.js a engenharia de baixo nível em Rust (drivers de kernel Linux/WSL2) e microsserviços em Go.

## Tecnologias

- **Frontend & UI de Produto:** React, Next.js, TypeScript, gerenciamento de estado (TanStack Query/Zustand), StyleX, formulários e design systems
- **Qualidade & Testes:** acessibilidade (WCAG), responsividade, Playwright, Vitest, testes de contrato e regressão visual
- **Backend & Cloud:** Go, Node.js, PostgreSQL, Redis, APIs RESTful, contratos tipados, autenticação e roteamento por workspace
- **Sistemas & Plataforma:** Rust, Linux Kernel (`ublk`, `zram`), daemons para WSL2, Docker e automação de runners de CI (`civmctl`)

## Trabalhos selecionados

- **[Google Gemini CLI](https://github.com/google-gemini/gemini-cli/pull/26955)** — contribuição upstream oficial otimizando performance de runtime, contenção de buffers de UI (`LIVE_OUTPUT_MAX_CHARS`) e telemetria de streaming no CLI de IA da Google.
- **[RamShared](https://github.com/emersonbusson/ramshared)** — projeto de sistemas em Rust que utiliza o driver `ublk` para transformar VRAM NVIDIA ociosa em uma camada elástica de memória (8.53 GB/s no FIO); autor da proposta formal de kernel em [microsoft/WSL#41054](https://github.com/microsoft/WSL/issues/41054).
- **[GuardWSL](https://github.com/emersonbusson/guardwsl)** — daemon em Rust que monitora a pressão física de disco/RAM no WSL2, executa limpeza transacional com allowlist estrita e serializa compilações pesadas.
- **[civm](https://github.com/emersonbusson/civm)** — ferramenta open-source (`civmctl`) em Go para provisionamento, ciclo de vida e watchdog de runners self-hosted do GitHub Actions no Ubuntu 24.04.
- **Advoq** — SaaS jurídico multi-tenant para atendimento, CRM, processos, documentos e operações do dia a dia com contratos tipados em Next.js, React e TypeScript.

</details>

