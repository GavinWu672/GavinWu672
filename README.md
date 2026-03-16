# Gavin Wu
**Software Architecture / AI Governance**
Exploring how **architecture contracts** can control and stabilize AI-assisted software development.

---

## Core Idea

Modern AI coding tools can generate working code — but they consistently break **architecture boundaries**.

The missing layer isn't smarter AI — it's machine-readable architecture contracts that AI must operate within.

> Instead of relying only on human code review, architecture constraints become **enforceable rules** that govern what AI is allowed to do.

---

## Projects

### AI Governance Framework

A runtime framework that ensures AI coding tools respect software architecture constraints.

**Key capabilities**
- Architecture rules as machine-readable governance contracts
- Contract-driven development with domain plugin support
- Architecture drift detection
- Session lifecycle governance with audit trail

**Repo** → [ai-governance-framework](https://github.com/GavinWu672/ai-governance-framework)

---

### Architecture Contract Experiments

These repositories apply governance concepts to specific engineering domains, each acting as a domain plugin to the framework.

#### USB Hub Firmware Architecture Contract
ISR boundary and shadow RAM state constraints for embedded USB hub firmware systems.

**Repo** → [USB-Hub-Firmware-Architecture-Contract](https://github.com/GavinWu672/USB-Hub-Firmware-Architecture-Contract)

---

#### Kernel Driver Contract
IRQL boundary and WDK safety rules for Windows kernel-mode driver development.

**Repo** → [Kernel-Driver-Contract](https://github.com/GavinWu672/Kernel-Driver-Contract)

---

#### IC Verification Contract
Spec-driven signal maps and DUT boundary enforcement for IC validation pipelines.

**Repo** → [IC-Verification-Contract](https://github.com/GavinWu672/IC-Verification-Contract)

---

## Goal

To explore whether **architecture contracts** can become the missing layer between AI coding tools and real-world software systems — where domain knowledge is proprietary, errors are costly, and human review alone is insufficient.
