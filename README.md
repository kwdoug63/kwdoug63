# Kenneth Wayne Douglas, MD

**Founder & CEO, Sober Agentic Infrastructure, Inc.** · *Operational Sobriety for the Agentic Era.*
**Founder & Creator, VAREK** · *AI Pipeline Programming Language.*

### About

I'm Ken — physician turned founder, based in Dallas-Fort Worth.

Founder & CEO of **Sober Agentic Infrastructure, Inc.** ([soberagents.ai](https://soberagents.ai)), building verification infrastructure for agentic AI. Creator of VAREK.

Medicine doesn't deploy systems that are "usually right" — it requires verification before action. I'm applying that standard to AI agents.

**Currently building:** deterministic runtime verification · compile-time pipeline safety · pre-execution policy decisions

**Background:** clinical medicine → AI safety infrastructure

---

## VAREK — AI Pipeline Programming Language

[varek-lang.org](https://varek-lang.org) · [github.com/kwdoug63/varek](https://github.com/kwdoug63/varek) · MIT License

VAREK is an open source programming language designed from the ground up for AI/ML pipeline engineering. It replaces the Python + YAML + JSON Schema + Bash fragmentation that plagues production AI systems with a single typed, compiled language where pipelines are first-class citizens — and verifies what the agents built on those pipelines are allowed to do.

* Statically typed — Hindley-Milner inference extended with tensor shape tracking
* LLVM-compiled — 10–40x faster than CPython for compute-heavy pipeline workloads
* Pipeline declarations — type-checked at compile time, not discovered at runtime
* Full interop — `import python::numpy`, `import python::torch` — no rewrites required
* v1.0 language baseline — 659 tests passing · 7-module standard library · 261 functions · package manager
* v1.5 Warden runtime — kernel-level interception via seccomp-unotify · sub-microsecond policy decisions · three-state ALLOW / DENY / UNKNOWN return with symmetric suppression
* v1.6 plan verification — the entire planned action graph is verified before execution begins · an unsafe plan is refused before the agent's first action · composes with the per-action runtime as a second deterministic layer

Deterministic AI safety in depth: verified at compile time in the language, across the whole plan before execution, and per action at the kernel.

---

## The Current Venture: Sober Agentic Infrastructure

[soberagents.ai](https://soberagents.ai)

We build model-agnostic, neuro-symbolic guardrails that sit between AI agents and critical infrastructure.

- **Deterministic Safety:** An SMT decision procedure mathematically blocks unsafe actions before they execute.
- **Plan Verification:** A simulation layer that validates agent plans before execution.
- **Liability Mitigation:** Closing the "Trust Gap" that prevents Fortune 500s from deploying autonomous agents at scale.

---

## The Founder Narrative: Forged in High-Stakes Environments

My approach to AI safety is not theoretical; it is forged in environments where failure is not an option:

- **Medical Precision:** Doctor of Medicine (MD), USC Keck School of Medicine. I understand systemic failure and the necessity of "clinical" guardrails in autonomous systems.
- **Language Design:** Built VAREK from first principles — lexer, parser, type system, LLVM backend, standard library, package manager. 659 tests. 13,006 lines. One year.
- **Hardware Innovation:** Lead Author of **US Patent 12,037,144 B1** (*Space Railway*). I build systems that rely on the laws of physics and logic, not probability.
- **Software Innovation:** Lead Author of a three-patent portfolio forming a vertical kernel-to-formal-methods stack for agentic AI safety:
  - **US Provisional 64/006,104** · Filed Mar 15, 2026 — *Deterministic Safety Guardrails and Outcome Verification for Agentic Systems*
  - **US Provisional 64/059,592** · Filed May 7, 2026 — *Kernel-Level Interception Architecture for Autonomous Agent Containment*
  - **US Provisional 64/062,549** · Filed May 11, 2026 — *Compositional Pre-Execution Verification of Agent Action Plans*

  I build systems that rely on the laws of math and logic, not probabilistic guesswork.

---

## Technical Stack & Infrastructure

- **VAREK:** Python (reference implementation) · LLVM IR via libLLVM-20 · Hindley-Milner type system
- **Sober Agentic Core:** Python 3.11+ · Rust (Logic Kernel) · FastAPI · Docker
- **Formal Methods:** SMT decision procedures · First-Order Logic (FOL) predicates · Symbolic Verification
- **Predictive Math:** NumPy/SciPy for latent-space bounding and action-validation

---

## Connect & Collaborate

- **VAREK:** [varek-lang.org](https://varek-lang.org)
- **Sober Agentic:** [soberagents.ai](https://soberagents.ai)
- **LinkedIn:** [linkedin.com/in/kwdoug63](https://linkedin.com/in/kwdoug63)
- **Email:** kenneth.douglas@soberagents.ai

---

> *"We don't need smarter models; we need soberer infrastructure."*
