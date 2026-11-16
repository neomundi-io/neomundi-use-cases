<div align="center">

<sub><b>English</b> · <a href="README_FR.md">Français</a></sub>

# AI use cases. Real questions. Documented evidence.

**Understand what your AI systems do, examine what happened and decide with traceable measurements.**

**INSTALL → TRACE → MEASURE → VERIFY → ACT**

[**LIVE DEMO**](https://neomundi.io/demo/) · [**Deploy NeoMundi**](https://neomundi.io/contact-us/) · [Product architecture](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

</div>

---

## Start with the business problem

The following applications show **distinct roles for measurement, evidence and downstream decisions**. Pilot work is not a commercial customer reference; results are limited to the published conditions.

### 1. How do you audit an AI agent's actions?

**Business challenge:** A business-facing agent makes commitments or reports actions. How can you compare its statements with recorded operations?

- **AI Business / Express Test Purchase — controlled reference:** Three controlled agent test-purchase runs, including clean and deliberately defective receipt evidence. **E2**; synthetic conditions, no insurance or underwriting outcome. [Review the controlled evidence](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity).
- **Sergei Ponomarev / AI Business — ongoing study:** Independent runtime measurements support the separate promise/dialogue/journal comparison. The November series runs **6 Nov–5 Dec 2026**; **E0**, with results and model identities not yet publicly released. [View the public protocol](https://github.com/sergeiperm81-ux/ai-test-purchase).

**Why it matters:** Trace observations separately from the authority that decides whether an agent did what it claimed.

### 2. How do you control agent execution without confusing measurement and permission?

**Business challenge:** A system needs observations to inform policy, but measurements must not become unauthorized execution decisions.

- **OASSE / FAM / Gatekeeper:** Controlled campaigns of **1,000 and 60 requests**, separating measurement, deterministic policy and downstream handling. **E3** within this scope. Historical ALLOW/FLAG are measurement classifications, *not* execution permissions. [View the study](https://github.com/neomundi-io/use-case-oasse-runtime-governance).
- **ManChine / RGE-01, REB-01, RiCo-01:** Public architecture for pre-action admissibility, execution boundaries and continuity. **E1**; complete machine-to-machine validation is pending. [View the architecture](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility).

**Why it matters:** Keep the measurement, policy and operational authorities explicit and separate.

### 3. How do you reconstruct and verify evidence after an AI interaction?

**Business challenge:** A disputed answer or audit requires inspectable records rather than an unverifiable account of the interaction.

- **FactNotebook:** Five instrumented **PubMedQA** cases were reconstructed by the partner from runtime exports. **E3** within this scope; the reconstruction engine is not public and medical truth is not established. [NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [Partner reconstruction](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001).
- **Mark Mocnaj / Project Petunia × Judicator (OGS):** Five **synthetic** governance-object interoperability payloads and payload-bound receipts; internal deterministic replay reproduced the five classifications. **E2**; no external action was authorized and no real NeoMundi production measurement is included. [Public interoperability study](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot).

**Why it matters:** Test what evidence can actually support, with integrity and source boundaries clearly documented.

### 4. How do you assess whether an AI assistant improved?

**Business challenge:** A RAG assistant is corrected. How do you compare observable outcomes under a defined test protocol?

- **Kabbalah App / RAG Test Bench:** **60 instrumented generations per round**; the partner-reported alerts changed from **45/60 to 1/60** after a correction. **E3** for the bounded field test. The harness, scoring maps and raw data remain private. [Public evidence summary](evidence/kabbalah-app-rag/README.md).

**Why it matters:** Document observable changes instead of relying on impressions.

---

## Technical depth, without clutter

- [Complete technical catalogue — 12 pilot entries, status, evidence levels and independent reviews](CATALOG.md)
- [Measurement API](https://github.com/neomundi-io/neomundi-runtime-measurement) · [Station](https://github.com/neomundi-io/neomundi-station-public) · [Evidence verification](https://github.com/neomundi-io/neomundi-evidence-gateway)
- [NeoMundi product architecture](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

The cases above are **bounded demonstrations and research pilots**, not certifications, universal reliability findings or proof of regulatory compliance. Review each linked protocol for its exact coverage and limits.

## Your organisation, your use case

**[Explore the live demo](https://neomundi.io/demo/)** · **[Discuss a NeoMundi deployment](https://neomundi.io/contact-us/)**
