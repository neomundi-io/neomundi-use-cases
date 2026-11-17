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

**Jump to a business problem:** [Agent audit](#01--ai-agent-audit) · [Execution control](#02--agent-execution-control) · [Evidence & audit](#03--evidence--audit) · [RAG quality](#04--rag-quality)

---

## 01 — AI AGENT AUDIT

### How do you audit an AI agent's actions?

> **Business challenge**  
> A business-facing agent makes commitments or reports actions. How can you compare its statements with recorded operations?

| Documented application | Evidence and scope | Source |
| --- | --- | --- |
| **AI Business / Express Test Purchase** · **E2 — Controlled** | Three controlled agent test-purchase runs, including clean and deliberately defective receipt evidence. **Synthetic conditions**; no insurance or underwriting outcome. | [Controlled evidence](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) |
| **Sergei Ponomarev / AI Business** · **E0 — Ongoing** | Independent runtime measurements support the separate promise/dialogue/journal comparison. Series: **6 Nov–5 Dec 2026**. Results and model identities **not yet publicly released**. | [Public protocol](https://github.com/sergeiperm81-ux/ai-test-purchase) |

**Business value →** Trace observations separately from the authority that decides whether an agent did what it claimed.

---

## 02 — AGENT EXECUTION CONTROL

### How do you control agent execution without confusing measurement and permission?

> **Business challenge**  
> A system needs observations to inform policy, but measurements must not become unauthorized execution decisions.

| Documented application | Evidence and scope | Source |
| --- | --- | --- |
| **OASSE / FAM / Gatekeeper** · **E3 — Bounded** | Controlled campaigns of **1,000 and 60 requests**, separating measurement, deterministic policy and downstream handling. Historical **ALLOW/FLAG** values are measurement classifications, **not execution permissions**. | [Study](https://github.com/neomundi-io/use-case-oasse-runtime-governance) |
| **ManChine / RGE-01, REB-01, RiCo-01** · **E1 — Documented** | Public architecture for pre-action admissibility, execution boundaries and continuity; **complete machine-to-machine validation is pending**. | [Architecture](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility) |

**Business value →** Keep the measurement, policy and operational authorities explicit and separate.

---

## 03 — EVIDENCE & AUDIT

### How do you reconstruct and verify evidence after an AI interaction?

> **Business challenge**  
> A disputed answer or audit requires inspectable records rather than an unverifiable account of the interaction.

| Documented application | Evidence and scope | Source |
| --- | --- | --- |
| **FactNotebook** · **E3 — Bounded** | Five instrumented **PubMedQA** cases were reconstructed by the partner from runtime exports. **Reconstruction engine not public**; no medical truth established. | [NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [Partner reconstruction](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001) |
| **Mark Mocnaj / Project Petunia × Judicator (OGS)** · **E2 — Synthetic** | Five synthetic governance-object interoperability payloads and payload-bound receipts; internal deterministic replay reproduced all five classifications. **No external action authorized; no real NeoMundi production measurement**. | [Interoperability study](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot) |

**Business value →** Test what evidence can actually support, with integrity and source boundaries clearly documented.

---

## 04 — RAG QUALITY

### How do you assess whether an AI assistant improved?

> **Business challenge**  
> A RAG assistant is corrected. How do you compare observable outcomes under a defined test protocol?

| Documented application | Evidence and scope | Source |
| --- | --- | --- |
| **Kabbalah App / RAG Test Bench** · **E3 — Bounded** | **60 instrumented generations per round**; partner-reported alerts changed from **45/60 to 1/60** after a correction. **Harness, scoring maps and raw data remain private**. | [Public evidence summary](evidence/kabbalah-app-rag/README.md) |

**Business value →** Document observable changes instead of relying on impressions.

---

## Technical depth, without clutter

- [Complete technical catalogue — 12 pilot entries, status, evidence levels and independent reviews](CATALOG.md)
- [Measurement API](https://github.com/neomundi-io/neomundi-runtime-measurement) · [Station](https://github.com/neomundi-io/neomundi-station-public) · [Evidence gateway interface](https://github.com/neomundi-io/neomundi-evidence-gateway)
- [NeoMundi product architecture](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

The cases above are **bounded demonstrations and research pilots**, not certifications, universal reliability findings or proof of regulatory compliance. Review each linked protocol for its exact coverage and limits.

## Independent Evidence Reviews — legacy links

The independent technical reviews have moved to the [technical catalogue](CATALOG.md#independent-evidence-reviews). The links below preserve older README anchors shared by email.

- <a id="mark-mocnaj--project-petunia--judicator-ogs"></a>[Mark Mocnaj — Project Petunia × Judicator (OGS)](CATALOG.md#mark-mocnaj--project-petunia--judicator-ogs)
- <a id="dennis-christie--asin-hhc--cp8"></a>[Dennis Christie — ASIN-HHC / CP8](CATALOG.md#dennis-christie--asin-hhc--cp8)
- <a id="olusanya-timothy--conformance-corpus-and-cli-verification-contract"></a>[Olusanya Timothy — Conformance corpus and CLI verification contract](CATALOG.md#olusanya-timothy--conformance-corpus-and-cli-verification-contract)

---

## Your organisation, your use case

**[Explore the live demo](https://neomundi.io/demo/)** · **[Discuss a NeoMundi deployment](https://neomundi.io/contact-us/)**
