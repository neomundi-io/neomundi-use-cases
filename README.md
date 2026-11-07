<div align="center">

<sub><b>English</b> · <a href="README_FR.md">Français</a></sub>

# NeoMundi — Use Cases

### AI measurement matters when it solves a real problem.

**Explore how independent measurement, contextual observation and verifiable evidence support AI agents, governance and system quality.**

**Measurement → Station → Evidence**

[![Measurement](https://img.shields.io/badge/Measurement-Measure-2563eb?style=flat-square)](https://github.com/neomundi-io/neomundi-runtime-measurement)
[![Station](https://img.shields.io/badge/Station-Observe-0f766e?style=flat-square)](https://github.com/neomundi-io/neomundi-station-public)
[![Evidence](https://img.shields.io/badge/Evidence-Verify-D4A545?style=flat-square)](https://github.com/neomundi-io/neomundi-evidence-public)
[![Use cases](https://img.shields.io/badge/Use_cases-Explore-64748b?style=flat-square)](https://github.com/neomundi-io/neomundi-use-cases)

**[API](https://github.com/neomundi-io/neomundi-runtime-measurement/blob/main/QUICKSTART.md)** · **[Create an account](https://controltower.neomundi.io/welcome)**

</div>

---

## Three documented applications

These results illustrate **different bounded use cases**. Their E3 levels describe the public evidence available for each scope, not a certification or general production qualification.

| Application | Challenge | Documented result | Evidence |
|---|---|---|---|
| **OASSE — Execution governance** | Keep independent measurement, deterministic policy and operational action separate. | Two controlled campaigns of **1,000 and 60 requests**, with distinct decision authorities. **E3**. | [OASSE study](https://github.com/neomundi-io/use-case-oasse-runtime-governance) |
| **FactNotebook — Evidence reconstruction** | Connect AI observations to an independent reconstruction of what the records support. | **5 PubMedQA cases** instrumented and reconstructed by the partner. The reconstruction engine is not public. **E3**. | [NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [Partner work](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001) |
| **Kabbalah App — RAG quality** | Observe and compare RAG benchmark alerts after a correction. | **60 instrumented generations per round**; reported alerts changed from **45/60 to 1/60**. Harness and raw data remain private. **E3**. | [Public summary](./evidence/kabbalah-app-rag/README.md) |

**[Explore all 11 use cases](#pilot-index)** · [Research collaborations](#research-collaborations) · [Propose a pilot](#work-with-neomundi)

## One chain, different applications

**Measurement** provides signals and their coverage. **Station** preserves observation conditions and campaign records. **Evidence** checks integrity and specified attestations of the resulting artefacts. Partners retain their own policies and decisions.

[Explore Measurement](https://github.com/neomundi-io/neomundi-runtime-measurement) · [Explore Station](https://github.com/neomundi-io/neomundi-station-public) · [Verify with Evidence](https://github.com/neomundi-io/neomundi-evidence-public)

## Explore by use case

- **Evidence and audit:** AI Business, FactNotebook, SEILX
- **Policy and execution:** OASSE, ManChine, VERITAS, Project Petunia × Judicator (OGS)
- **Observability and quality:** DriftShield, Kabbalah App
- **Agentic routing:** OmarAGI / REVAS
- **Measurement research:** Dr Islam Gouda, Farzad Abbasi / AEGIS

## Pilot index

Status applies only to the documented scope. It does not validate a partner technology generally or establish production readiness.

| # | Use case | Partner technology | NeoMundi role | Partner authority | Status | Evidence | Last identified verification | Public evidence and limits |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **01** | Insurance and risk evidence | AI Business / Express Test Purchase | Independent runtime measurement | Cross-references permissions, actions, logs and receipts; the underwriter assesses risk | In progress | **E0** | Not reported | No dedicated insurance result. The [related controlled audit](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) does not establish insurability or an underwriting outcome. |
| **02** | Agentic control and routing | OmarAGI / REVAS | Supplies synthetic runtime observation samples | REVAS produces its own pre-action admissibility artifacts | Pilot 01 documented · Pilot 02 planned | **E2** | Execution date not stated | Five synthetic cases are documented. No live Pilot 02 result, production validation or general reliability claim. [Partner repository](https://github.com/effacermonexistence/omaragi-neomundi-pilot). |
| **03** | Policy and enforcement | OASSE / FAM / Gatekeeper | Produces runtime measurements and historical measurement-layer classifications | FAM applies deterministic policy; Gatekeeper determines downstream operational handling and seals evidence | Controlled pilot validated | **E3** | 29 Jul and 4 Aug 2026 | Controlled runs of 1,000 and 60 requests. Historical **ALLOW/FLAG** values are measurement-layer classifications, not execution permissions. [Repository](https://github.com/neomundi-io/use-case-oasse-runtime-governance). [Oak & Sparrow case study](https://oakandsparrow.io/#/case-studies/neomundi). |
| **04** | Controlled AI agent audit | AI Business / Express Test Purchase | Measures the submitted validation observation | The authoritative journal records execution; a deterministic validator evaluates receipt conformity | Controlled pilot validated | **E2** | 3–4 Aug 2026 | Three controlled reference runs, including clean and deliberately defective receipt evidence. The environment is synthetic and does not establish general agent reliability. [Repository](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity). |
| **05** | Evidence reconstruction | FactNotebook | Measures five GPT-4o generations and exports runtime observations | FactNotebook reconstructs what the observations support; an accountable human authority decides | Completed bounded pilot | **E3** | Runtime export: 25 Jul 2026 · partner manifest: 7 Aug 2026 | Five PubMedQA cases were ingested. The partner publishes outputs, not its reconstruction engine; the work is not independently reproducible and does not establish medical truth. [NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [partner reconstruction](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001). |
| **06** | Parallel observability | DriftShield / HIC | Independently observes the same execution | Maintains its own observation and the existing X/Y/Z authority model | Minimum pilot reported | **E1** | Not reported | One real execution is reported, but no dedicated public evidence package, replication or public repository is identified here. |
| **07** | Governance through verifiable evidence | SEILX | Produces an observation and associated artifacts | Captures, preserves and time-anchors artifacts for later integrity checks | In progress | **E0** | Not reported | No final result or dedicated public evidence package. Integrity and provenance do not establish factual truth or execution permission. |
| **08** | Admissibility and execution continuity | ManChine / RGE-01 / REB-01 / RiCo-01 | Supplies runtime observational evidence | RGE-01 evaluates admissibility before activation; REB-01 governs the execution boundary; RiCo-01 addresses continuity after activation | Architecture documented · validation pending | **E1** | No completed run | The architecture and sample payloads are public; a complete machine-to-machine exchange is not. [Repository](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility). |
| **09** | RAG runtime quality detection | Kabbalah App / RAG Test Bench | Produces runtime measurement signals during the evaluation | The test bench owns retrieval, scoring, diagnosis and model choices | Bounded field test documented | **E3** | Study: 23 Aug 2026 · report: 20 Sep 2026 | The report documents 60 instrumented generations per round, with reported alerts falling from 45/60 to 1/60 after correction. The private harness, questions, scoring mappings and raw package are not public. [Evidence summary](./evidence/kabbalah-app-rag/README.md). |
| **10** | Signed signal verification | VERITAS | Produces signed RGC observations | VERITAS verifies evidence under its trust policy and retains governance and execution authority | Adapter validated · real live proof pending | **E2** | No public closure of the real-observation PoC | Adapter and synthetic paths are documented. No real NeoMundi observation is published in the partner repository. [Adapter](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-adapter.md) · [real-observation PoC runbook](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-real-observation-poc.md). |
| **11** | Governance-object interoperability | Mark Mocnaj / Project Petunia × Judicator (OGS) | Provides the runtime-observation model represented by synthetic payloads | OGS evaluates what the signals may support and prohibits unsupported downstream use | Public synthetic pilot documented | **E2** | Execution date not stated | Five synthetic observation payloads, governance objects and payload-bound receipts are public; internal deterministic replay reproduced all five documented classifications. No external action was authorized. The result is internally verified, not independently reproduced and not production-derived; no real NeoMundi measurement is included. [Partner repository](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot). |

## Evidence levels

These levels describe the public evidence available for a specific use case. They are not certifications, partner ratings or a universal maturity scale.

| Level | Meaning |
| --- | --- |
| **E0 — Declared** | Object and status are public, but no result is claimed or publicly evidenced. |
| **E1 — Documented** | An architecture, plan or account is public; no completed public execution is demonstrated. |
| **E2 — Controlled execution** | Inspectable artifacts document a synthetic or controlled execution. |
| **E3 — Bounded real observation** | Public evidence documents real data or a real bounded execution, with stated limits. |
| **E4 — Independent reproduction** | A third party can independently reproduce the result from the published protocol and materials. |

No use case in this index is currently presented as E4.

## Partner integration — Hivolvia (private pilot)

**Use case:** connect independent AI model/service monitoring to NeoMundi measurement signals. Stéphane Lauga reports that his cross-platform Rust connector, built for his own observability environment and adapted to the NeoMundi OBS API, has been delivered for evaluation. The connector is a **third-party implementation**, with source ownership, maintenance and remote pilot support retained by its developer.

**Evidence level: E0 for independent qualification.** The developer reported a successful API exchange on 2 September 2026 and delivery of the connector on 18 September 2026; these are partner-reported milestones, not an independently reproduced test. A current-version end-to-end run, security assessment, signed pilot distribution terms and evidence of actual measurement consumption are not published. Evaluation is restricted to named pilots by agreement; no public download is offered. Public partner attribution remains subject to final confirmation.

[Integration overview — Station](https://github.com/neomundi-io/neomundi-station-public#partner-integrations--private-pilots)

## Research collaborations

Research collaborations are listed separately from product pilots. They document questions, methods, roles and limits; they are not customer references or certifications.

| Collaboration | Research question | Public evidence | Status and limits |
| --- | --- | --- | --- |
| **NeoMundi × ASRO — Runtime Governance Evidence** | Can behavioral measurement and governance-state witnessing remain independent without circular validation? | **E1** · [Bilingual research card](./collaborations/asro/runtime-governance-evidence.md) · [Original repository](https://github.com/neomundi-io/runtime-governance-evidence) | Methodology documented; no completed scientific validation, certification or public execution package. |
| **NeoMundi × ASRO — Independent Evidence Review, Round 2** | Can a third-party reviewer examine versioned and sealed measurement artifacts while roles remain separate? | **E1** · [Bilingual protocol card](./collaborations/asro/independent-evidence-review-round-2.md) · [Original repository](https://github.com/neomundi-io/neomundi-asro-round2-protocol) | Protocol work is active; final freeze, execution, sealed record and independent review remain open. |

ASRO is not presented as NeoMundi's certification body. James/ASRO's contribution is limited here to the documented scope of proof discipline, governance-state witnessing, reviewability and authority separation.

## Ongoing studies

These studies are in progress. No result or evidence level is assigned here.

| Study | Object | Status |
| --- | --- | --- |
| Dr Islam Gouda | Measurement uncertainty and evaluator repeatability | In progress |
| Farzad Abbasi — AEGIS | Document-grounded AI evaluation and measurement diagnostics | In progress |

## What has been demonstrated

Within their published boundaries:

- third-party systems can consume NeoMundi runtime observations while retaining separate authority;
- controlled evidence can preserve distinctions between measurement, deterministic conformity, policy and downstream action;
- bounded real-data work is documented for OASSE, FactNotebook and Kabbalah App;
- synthetic and controlled paths are documented for OmarAGI / REVAS, AI Business, VERITAS and Project Petunia × Judicator (OGS);
- architectural separation is documented for ManChine.

## What remains unverified

This index does not establish:

- certification, regulatory compliance, insurability or production-scale reliability;
- factual truth or medical validity;
- superiority of a model or partner technology;
- independent reproduction of any listed result;
- a public result for DriftShield or SEILX;
- completed live interoperability for ManChine, the real-observation VERITAS path or the proposed OGS experiment using real NeoMundi measurements.

A missing public artifact is not replaced by a status label. Synthetic, controlled, single-execution and report-only evidence must remain identified as such.

## Detailed evidence

- [AI Business — controlled agent audit](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity)
- [OmarAGI / REVAS — partner pilot](https://github.com/effacermonexistence/omaragi-neomundi-pilot)
- [OASSE — runtime governance](https://github.com/neomundi-io/use-case-oasse-runtime-governance)
- [FactNotebook — NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa)
- [FactNotebook — bounded partner reconstruction](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001)
- [ManChine — observation to admissibility](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility)
- [Kabbalah App — public evidence summary](./evidence/kabbalah-app-rag/README.md)
- [VERITAS — RGC v0.2 adapter](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-adapter.md)
- [Mark Mocnaj / Project Petunia × Judicator (OGS) — public interoperability pilot](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot)
- [NeoMundi × ASRO — Runtime Governance Evidence](./collaborations/asro/runtime-governance-evidence.md)
- [NeoMundi × ASRO — Independent Evidence Review, Round 2](./collaborations/asro/independent-evidence-review-round-2.md)

## Infrastructure & Program Support

NeoMundi's independent AI observation and measurement initiative benefits from infrastructure and startup program support:

- **[Infomaniak](https://www.infomaniak.com/)** — Infrastructure partner supporting the development of NeoMundi's independent AI observation instrument.
- **[OVHcloud Startup Program](https://startup.ovhcloud.com/)** — Startup support program participant.
- **[NVIDIA Inception](https://www.nvidia.com/en-us/startups/)** — Member of NVIDIA's program for innovative startups.

These relationships support NeoMundi's development and do not imply certification or endorsement of its scientific results.

## Work with NeoMundi

A useful pilot, research collaboration or audit starts with a bounded question, explicit roles, a reproducible protocol and a clear statement of what the evidence cannot establish.

When opening a proposal, include:

1. the practical question and intended decision context;
2. the system or workflow to observe;
3. the available data and its publication constraints;
4. the evidence level sought and success criteria;
5. the accountable decision-maker and all role boundaries;
6. the artifacts that may be published after the work.

[Propose a scenario through the repository issues](https://github.com/neomundi-io/neomundi-use-cases/issues). Do not include secrets, personal data, confidential agreements or private experimental archives.
