Hi, I'm Ryan Bahadori. I build low-level tools and write them so they can be read: a C compiler, a terminal emulator, a tiling window manager. Most of what is here started as "the existing one is annoying to understand."

**Now:** [LumiComp](https://github.com/IzonIcy/LumiComp) v0.2.0, a C compiler in C that carries a subset of the language from source to readable textual IR and then to x86-64 assembly you can assemble and run. Lexer, preprocessor, parser, semantic analysis, code generator, stack-slot backend. Built with `make`, tested with `make verify`.

## Projects

| Project | What it is | Demo |
| --- | --- | --- |
| [LumiComp](https://github.com/IzonIcy/LumiComp) | C compiler in C, five-stage pipeline, readable IR, x86-64 assembly | [v0.2.0 release](https://github.com/IzonIcy/LumiComp/releases/tag/v0.2.0) |
| [LumiTerm](https://github.com/IzonIcy/LumiTerm) | GPU-rendered terminal emulator in Rust, real PTY, vt100 parsing | [v0.1.0 release](https://github.com/IzonIcy/LumiTerm/releases/tag/v0.1.0) |
| [Mist](https://github.com/IzonIcy/Mist) | Tiling window manager for macOS, Swift, no third-party deps | [v0.1.2 release](https://github.com/IzonIcy/Mist/releases/tag/v0.1.2) |
| [FabOps Sentinel](https://github.com/IzonIcy/fabops-sentinel) | Vision monitoring for 3D printers and CNC machines, with SMS alerts | [repo](https://github.com/IzonIcy/fabops-sentinel) |
| [Ai-Chef](https://github.com/IzonIcy/Ai-Chef) | Terminal cooking assistant that matches recipes to what is in your kitchen | [v1.2.0 release](https://github.com/IzonIcy/Ai-Chef/releases/tag/v1.2.0) |
| [Cloud Spend Planning Desk](https://github.com/IzonIcy/infrastructure-cost-visualizer) | Browser-based cloud cost estimator, three pricing models | [live](https://infrastructure-cost-visualizer.vercel.app) |
| [Unheard Voices](https://github.com/IzonIcy/UnHeard-Voices) | Canvas 2D timeline of 60 overlooked historical events | [live](https://un-heard-voices-8xof.vercel.app) |
| [Portfolio](https://github.com/IzonIcy/Portfolio) | Personal site, Astro 7 | [live](https://portfolio-ecru-rho-94.vercel.app/) |

## Upstream

Three pull requests merged into [athas](https://github.com/athasdev/athas), a Tauri code editor:

- [#765](https://github.com/athasdev/athas/pull/765) return the formatted file for file-output formatters
- [#739](https://github.com/athasdev/athas/pull/739) fix broken vim ex commands (`:w`, `:wq`, `:q!`, line jumps)
- [#733](https://github.com/athasdev/athas/pull/733) align stores with `createSelectors` and centralize row line-height

Ten more pull requests to [t3code](https://github.com/pingdotgg/t3code) went through review and were closed rather than merged.

Stack: C · Rust · Swift · TypeScript · Python · Astro

Email: ryanbahadori74@gmail.com

Open to internships. If it is interesting, I am in.
