<div align="center">

<sub><b>English</b> · <a href="README_FR.md">Français</a></sub>

# AI use cases. Real questions. Documented evidence.

**Know what your AI does. Prove what happened. Less guesswork. More evidence.**

**INSTALL → TRACE → MEASURE → VERIFY → ACT**

[**LIVE DEMO**](https://neomundi.io/demo/) · [**Deploy NeoMundi**](https://neomundi.io/contact-us/) · [Product architecture](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

</div>

---

## Explore 7 AI needs — choose a live demo

**One measurement primitive. Multiple applications. Multiple infrastructures.**

Start with the problem your team needs to solve. Each link opens a published NeoMundi demonstration; the detailed cases below distinguish **illustrative demos** from **documented pilot evidence**.

| Your small need | What you want to know | Explore |
| --- | --- | --- |
| **01 · AI agent audit** | Did an agent do what it claimed? | [Live demo 5 — agent actions](https://neomundi.io/demo-5/) |
| **02 · Agent execution control** | What can observations tell a downstream gatekeeper? | [Live demo 4 — agent in action](https://neomundi.io/demo-4/) |
| **03 · Evidence & audit** | Can someone else inspect what happened? | [Live demo — evidence journey](https://neomundi.io/demo/) |
| **04 · RAG quality** | What changes when an assistant is evaluated? | [Live demo 6 — RAG assistant](https://neomundi.io/demo-6/) |
| **05 · Healthcare AI** | What can be examined in a sensitive AI scenario? | [Live demo 3 — healthcare](https://neomundi.io/demo-3/) |
| **06 · Model comparison** | How can you compare AI model responses? | [Live demo 2 — model comparison](https://neomundi.io/demo-2/) |
| **07 · Conflicting answers** | What happens when two answers disagree? | [Live demo 7 — opposite answers](https://neomundi.io/demo-7/) |

**Explore a need → inspect the demonstration → open the underlying documentation.** Live demos are product illustrations, not additional pilot results.

---

## Documented use cases — problems, evidence, demos

The cases below keep **measurement**, **evidence** and **downstream decisions** distinct. Pilot work is not a commercial customer reference; published evidence has the scope stated in each source.

## 01 — AI AGENT AUDIT

### How do you audit an AI agent's actions?

> **Business challenge**  
> A business-facing agent makes commitments or reports actions. How can you compare its statements with recorded operations?

| Documented application | Evidence and scope | Source |
| --- | --- | --- |
| **AI Business / Express Test Purchase** · **E2 — Controlled** | Three controlled agent test-purchase runs, including clean and deliberately defective receipt evidence. **Synthetic conditions**; no insurance or underwriting outcome. | [Controlled evidence](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) |
| **Sergei Ponomarev / AI Business** · **E0 — Ongoing** | Independent runtime measurements support the separate promise/dialogue/journal comparison. Series: **6 Nov–5 Dec 2026**. Results and model identities **not yet publicly released**. | [Public protocol](https://github.com/sergeiperm81-ux/ai-test-purchase) |

**Business value →** Trace observations separately from the authority that decides whether an agent did what it claimed.

**[Explore live demo 5 — proving what an AI agent did](https://neomundi.io/demo-5/)** · Product demonstration; pilot proof remains in the sources above.

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

**[Explore live demo 4 — measuring an agent in action](https://neomundi.io/demo-4/)** · A demonstration of an agent workflow, not a verification of every downstream action.

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

**[Explore the NeoMundi evidence demonstration](https://neomundi.io/demo/)** · The published pilot links above remain the evidence references.

---

## 04 — RAG QUALITY

### How do you assess whether an AI assistant improved?

> **Business challenge**  
> A RAG assistant is corrected. How do you compare observable outcomes under a defined test protocol?

| Documented application | Evidence and scope | Source |
| --- | --- | --- |
| **Kabbalah App / RAG Test Bench** · **E3 — Bounded** | **60 instrumented generations per round**; partner-reported alerts changed from **45/60 to 1/60** after a correction. **Harness, scoring maps and raw data remain private**. | [Public evidence summary](evidence/kabbalah-app-rag/README.md) |

**Business value →** Document observable changes instead of relying on impressions.

**[Explore live demo 6 — measuring a RAG assistant](https://neomundi.io/demo-6/)** · Illustrative product demonstration, separate from the Kabbalah App results.

---

## 05 — HEALTHCARE AI

### How can you examine AI behaviour in a sensitive domain?

**Small need →** Review an AI response with explicit measurement and evidence context instead of relying on an unsupported quality claim.

**NeoMundi approach →** Instrument the interaction, inspect behavioural signals and preserve the technical record for review.

**[Explore live demo 3 — measuring healthcare AI](https://neomundi.io/demo-3/)** · NeoMundi product demonstration.

**Related documented evidence →** [FactNotebook / PubMedQA pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa). This is a separate pilot, not a claim about the demo or medical accuracy.

---

## 06 — MODEL COMPARISON

### Which differences can you document between AI model responses?

**Small need →** Compare responses while keeping the measurement conditions visible.

**NeoMundi approach →** Record observations, inspect the available signals and make the comparison context explicit.

**[Explore live demo 2 — AI model comparison](https://neomundi.io/demo-2/)** · NeoMundi product demonstration, not a published comparative benchmark.

---

## 07 — CONFLICTING ANSWERS

### What do you do when two AI answers disagree?

**Small need →** Examine contradictory outputs without treating a score as proof of factual truth.

**NeoMundi approach →** Present the observations and the available measurement evidence so a reviewer can inspect the conflict.

**[Explore live demo 7 — two opposite answers, one verdict](https://neomundi.io/demo-7/)** · Illustrative product scenario; any verdict displayed belongs to the demonstrated context.

---

## Explore more — technical depth and independent reviews

| Resource | Explore |
| --- | --- |
| **Complete pilot catalogue** | [12 documented entries, evidence levels and technical references](CATALOG.md) |
| **Measurement / Station / Evidence** | [Measurement API](https://github.com/neomundi-io/neomundi-runtime-measurement) · [Station](https://github.com/neomundi-io/neomundi-station-public) · [Evidence gateway](https://github.com/neomundi-io/neomundi-evidence-gateway) |
| **Architecture** | [NeoMundi product architecture](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md) |
| **Independent reviews** | [Technical catalogue — reviews](CATALOG.md#independent-evidence-reviews) |
| **All live demos** | [NeoMundi demo hub](https://neomundi.io/demo/) |

**Legacy review anchors** (kept for existing external links):

- <a id="mark-mocnaj--project-petunia--judicator-ogs"></a>[Mark Mocnaj — Project Petunia × Judicator (OGS)](CATALOG.md#mark-mocnaj--project-petunia--judicator-ogs)
- <a id="dennis-christie--asin-hhc--cp8"></a>[Dennis Christie — ASIN-HHC / CP8](CATALOG.md#dennis-christie--asin-hhc--cp8)
- <a id="pradeep-kumar--independent-evidence-review"></a>[Pradeep Kumar — AI Systems Architect & STANAIC Fellow](CATALOG.md#pradeep-kumar--ai-systems-architect--stanaic-fellow)
- <a id="olusanya-timothy--conformance-corpus-and-cli-verification-contract"></a>[Olusanya Timothy — Conformance corpus and CLI verification contract](CATALOG.md#olusanya-timothy--conformance-corpus-and-cli-verification-contract)

The documented cases are **bounded demonstrations and research pilots**, not certifications or proof of regulatory compliance. The live demos illustrate product workflows; review each source for its conditions.

---

## Your organisation, your use case

**[Explore the live demos](https://neomundi.io/demo/)** · **[Discuss a NeoMundi deployment](https://neomundi.io/contact-us/)**
