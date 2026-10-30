[Français](./README_FR.md)

# From AI measurements to inspectable evidence

**One measurement primitive. Multiple applications. Explicit boundaries.**

NeoMundi produces independent runtime measurement signals. Partner systems may interpret those signals, combine them with their own evidence and decide or act under their own authority.

> **Measurement is not interpretation. Interpretation is not a decision. A signal is not permission to act.**

## Explore NeoMundi

[**Station** — Observe & experiment](https://github.com/neomundi-io/neomundi-station-public) ·
[**Runtime Measurement** — Measure & integrate](https://github.com/neomundi-io/neomundi-runtime-measurement) ·
[**Use Cases** — Applications, pilots & evidence](https://github.com/neomundi-io/neomundi-use-cases) ·
[**Create an Account** — ControlTower](https://controltower.neomundi.io/welcome)

## Explore by use case

- **Evidence and audit:** AI Business, FactNotebook, SEILX
- **Independent policy and execution:** OASSE, ManChine, VERITAS
- **Observability and quality:** DriftShield, Kabbalah App
- **Agentic routing:** OmarAGI / REVAS
- **Measurement research:** Dr Islam Gouda, Farzad Abbasi / AEGIS

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

## Pilot index

Status applies only to the documented scope. It does not validate a partner technology generally or establish production readiness.

| # | Use case | Partner technology | NeoMundi role | Partner authority | Status | Evidence | Last identified verification | Public evidence and limits |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **01** | Insurance and risk evidence | AI Business / Express Test Purchase | Independent runtime measurement | Cross-references permissions, actions, logs and receipts; the underwriter assesses risk | In progress | **E0** | Not reported | No dedicated insurance result. The [related controlled audit](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) does not establish insurability or an underwriting outcome. |
| **02** | Agentic control and routing | OmarAGI / REVAS | Supplies synthetic runtime observation samples | REVAS produces its own pre-action admissibility artifacts | Pilot 01 documented · Pilot 02 planned | **E2** | Execution date not stated | Five synthetic cases are documented. No live Pilot 02 result, production validation or general reliability claim. [Partner repository](https://github.com/effacermonexistence/omaragi-neomundi-pilot). |
| **03** | Policy and enforcement | OASSE / FAM / Gatekeeper | Produces runtime measurements and historical measurement-layer classifications | FAM applies deterministic policy; Gatekeeper determines downstream operational handling and seals evidence | Controlled pilot validated | **E3** | 29 Jul and 4 Aug 2026 | Controlled runs of 1,000 and 60 requests. Historical **ALLOW/FLAG** values are measurement-layer classifications, not execution permissions. [Repository](https://github.com/neomundi-io/use-case-oasse-runtime-governance). |
| **04** | Controlled AI agent audit | AI Business / Express Test Purchase | Measures the submitted validation observation | The authoritative journal records execution; a deterministic validator evaluates receipt conformity | Controlled pilot validated | **E2** | 3–4 Aug 2026 | Three controlled reference runs, including clean and deliberately defective receipt evidence. The environment is synthetic and does not establish general agent reliability. [Repository](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity). |
| **05** | Evidence reconstruction | FactNotebook | Measures five GPT-4o generations and exports runtime observations | FactNotebook reconstructs what the observations support; an accountable human authority decides | Completed bounded pilot | **E3** | Runtime export: 25 Jul 2026 · partner manifest: 7 Aug 2026 | Five PubMedQA cases were ingested. The partner publishes outputs, not its reconstruction engine; the work is not independently reproducible and does not establish medical truth. [NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [partner reconstruction](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001). |
| **06** | Parallel observability | DriftShield / HIC | Independently observes the same execution | Maintains its own observation and the existing X/Y/Z authority model | Minimum pilot reported | **E1** | Not reported | One real execution is reported, but no dedicated public evidence package, replication or public repository is identified here. |
| **07** | Governance through verifiable evidence | SEILX | Produces an observation and associated artifacts | Captures, preserves and time-anchors artifacts for later integrity checks | In progress | **E0** | Not reported | No final result or dedicated public evidence package. Integrity and provenance do not establish factual truth or execution permission. |
| **08** | Admissibility and execution continuity | ManChine / RGE-01 / REB-01 / RiCo-01 | Supplies runtime observational evidence | RGE-01 evaluates admissibility before activation; REB-01 governs the execution boundary; RiCo-01 addresses continuity after activation | Architecture documented · validation pending | **E1** | No completed run | The architecture and sample payloads are public; a complete machine-to-machine exchange is not. [Repository](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility). |
| **09** | RAG runtime quality detection | Kabbalah App / RAG Test Bench | Produces runtime measurement signals during the evaluation | The test bench owns retrieval, scoring, diagnosis and model choices | Bounded field test documented | **E3** | Study: 23 Aug 2026 · report: 20 Sep 2026 | The report documents 60 instrumented generations per round, with reported alerts falling from 45/60 to 1/60 after correction. The private harness, questions, scoring mappings and raw package are not public. [Evidence summary](./evidence/kabbalah-app-rag/README.md). |
| **10** | Signed signal verification | VERITAS | Produces signed RGC observations | VERITAS verifies evidence under its trust policy and retains governance and execution authority | Adapter validated · real live proof pending | **E2** | No public closure of the real-observation PoC | Adapter and synthetic paths are documented. No real NeoMundi observation is published in the partner repository. [Adapter](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-adapter.md) · [real-observation PoC runbook](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-real-observation-poc.md). |
| **11** | Measurement uncertainty and evaluator repeatability | Dr Islam Gouda | Measurement research | External research authority remains separate | **In progress** | **E0 — no public result claimed** | Not reported | Object and status only. No result, experimental detail or dedicated repository is published here. |
| **12** | Document-grounded AI evaluation and measurement diagnostics | Farzad Abbasi / AEGIS | Measurement diagnostics | External evaluation authority remains separate | **In progress** | **E0 — no public result claimed** | Not reported | Object and status only. No result, experimental detail or dedicated repository is published here. |

## What has been demonstrated

Within their published boundaries:

- third-party systems can consume NeoMundi runtime observations while retaining separate authority;
- controlled evidence can preserve distinctions between measurement, deterministic conformity, policy and downstream action;
- bounded real-data work is documented for OASSE, FactNotebook and Kabbalah App;
- synthetic and controlled paths are documented for OmarAGI / REVAS, AI Business and VERITAS;
- architectural separation is documented for ManChine.

## What remains unverified

This index does not establish:

- certification, regulatory compliance, insurability or production-scale reliability;
- factual truth or medical validity;
- superiority of a model or partner technology;
- independent reproduction of any listed result;
- a public result for DriftShield, SEILX, Dr Islam Gouda or AEGIS;
- completed live interoperability for ManChine or the real-observation VERITAS path.

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

## Propose a pilot

A useful pilot begins with a bounded question, explicit responsibilities, a reproducible protocol and a clear statement of what the evidence cannot establish.

[Propose a use case through the repository issues](https://github.com/neomundi-io/neomundi-use-cases/issues/new). Do not include secrets, personal data or private experimental archives.
