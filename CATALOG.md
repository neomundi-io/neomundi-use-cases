# NeoMundi — Technical use-case catalogue

[English](CATALOG.md) · [Français](CATALOG_FR.md) · [Market-facing use cases](README.md)

**Technical register, not the commercial landing page.** This retains the existing pilot index, statuses, public evidence references and independent technical reviews as documented on 16 November 2026. Each status is bounded to its cited protocol; these are neither customer endorsements nor certifications. See individual source repositories for subsequent updates.

---

## Pilot index

Status applies only to the documented scope. It does not validate a partner technology generally or establish production readiness.

| # | Use case | Partner technology | NeoMundi role | Partner authority | Status | Evidence | Last identified verification | Public evidence and limits |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **01** | AI test purchase — exploratory application | AI Business / Express Test Purchase | Independent runtime measurement | AI Business compares declared commitments, agent statements and recorded operations; NeoMundi does not assess execution conformity | In progress | **E0** | Not reported | Exploratory test-purchase use case; no dedicated result is claimed here. See the [August controlled reference](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) and the separate November series (#12). No insurance or underwriting outcome is claimed. |
| **02** | Agentic control and routing | OmarAGI / REVAS | Supplies synthetic runtime observation samples | REVAS produces its own pre-action admissibility artifacts | Pilot 01 documented · Pilot 02 planned | **E2** | Execution date not stated | Five synthetic cases are documented. No live Pilot 02 result, production validation or general reliability claim. [Partner repository](https://github.com/effacermonexistence/omaragi-neomundi-pilot). |
| **03** | Policy and enforcement | OASSE / FAM / Gatekeeper | Produces runtime measurements and historical measurement-layer classifications | FAM applies deterministic policy; Gatekeeper determines downstream operational handling and seals evidence | Controlled pilot validated | **E3** | 29 Jul and 4 Aug 2026 | Controlled runs of 1,000 and 60 requests. Historical **ALLOW/FLAG** values are measurement-layer classifications, not execution permissions. [Repository](https://github.com/neomundi-io/use-case-oasse-runtime-governance). [Oak & Sparrow case study](https://oakandsparrow.io/#/case-studies/neomundi). |
| **04** | Controlled AI-agent test-purchase reference | AI Business / Express Test Purchase | Measures the submitted validation observation | The authoritative journal records execution; a deterministic validator evaluates receipt conformity | Controlled pilot validated | **E2** | 3–4 Aug 2026 | Three controlled reference runs, including clean and deliberately defective receipt evidence. The environment is synthetic and does not establish general agent reliability. [Repository](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity). |
| **05** | Evidence reconstruction | FactNotebook | Measures five GPT-4o generations and exports runtime observations | FactNotebook reconstructs what the observations support; an accountable human authority decides | Completed bounded pilot | **E3** | Runtime export: 25 Jul 2026 · partner manifest: 7 Aug 2026 | Five PubMedQA cases were ingested. The partner publishes outputs, not its reconstruction engine; the work is not independently reproducible and does not establish medical truth. [NeoMundi pilot](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [partner reconstruction](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001). |
| **06** | Parallel observability | DriftShield / HIC | Independently observes the same execution | Maintains its own observation and the existing X/Y/Z authority model | Minimum pilot reported | **E1** | Not reported | One real execution is reported, but no dedicated public evidence package, replication or public repository is identified here. |
| **07** | Governance through verifiable evidence | SEILX | Produces an observation and associated artifacts | Captures, preserves and time-anchors artifacts for later integrity checks | In progress | **E0** | Not reported | No final result or dedicated public evidence package. Integrity and provenance do not establish factual truth or execution permission. |
| **08** | Admissibility and execution continuity | ManChine / RGE-01 / REB-01 / RiCo-01 | Supplies runtime observational evidence | RGE-01 evaluates admissibility before activation; REB-01 governs the execution boundary; RiCo-01 addresses continuity after activation | Architecture documented · validation pending | **E1** | No completed run | The architecture and sample payloads are public; a complete machine-to-machine exchange is not. [Repository](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility). |
| **09** | RAG runtime quality detection | Kabbalah App / RAG Test Bench | Produces runtime measurement signals during the evaluation | The test bench owns retrieval, scoring, diagnosis and model choices | Bounded field test documented | **E3** | Study: 23 Aug 2026 · report: 20 Sep 2026 | The report documents 60 instrumented generations per round, with reported alerts falling from 45/60 to 1/60 after correction. The private harness, questions, scoring mappings and raw package are not public. [Evidence summary](./evidence/kabbalah-app-rag/README.md). |
| **10** | Signed signal verification | VERITAS | Produces signed RGC observations | VERITAS verifies evidence under its trust policy and retains governance and execution authority | Adapter validated · real live proof pending | **E2** | No public closure of the real-observation PoC | Adapter and synthetic paths are documented. No real NeoMundi observation is published in the partner repository. [Adapter](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-adapter.md) · [real-observation PoC runbook](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-real-observation-poc.md). |
| **11** | Governance-object interoperability | Mark Mocnaj / Project Petunia × Judicator (OGS) | Provides the runtime-observation model represented by synthetic payloads | OGS evaluates what the signals may support and prohibits unsupported downstream use | Public synthetic pilot documented | **E2** | Execution date not stated | Five synthetic observation payloads, governance objects and payload-bound receipts are public; internal deterministic replay reproduced all five documented classifications. No external action was authorized. The result is internally verified, not independently reproduced and not production-derived; no real NeoMundi measurement is included. [Partner repository](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot). |
| **12** | AI agent test-purchase series (Nov 2026) | Sergei Ponomarev / AI Business | Independent runtime measurement of agent replies | Sergei owns the protocol, promise/dialogue/journal comparison and interpretation | Series ongoing (6 Nov–5 Dec 2026) | **E0** | Results not yet published | [Public protocol and prompts](https://github.com/sergeiperm81-ux/ai-test-purchase); model identities and results held until 5 December. No certification or ranking by NeoMundi. |

## Independent Evidence Reviews

**Independent reviewers can test NeoMundi's evidence boundaries without becoming customers, endorsers or certification bodies.** These bounded reviews document what an observation proves, what it does not prove, and how findings inform verification design.

### Mark Mocnaj — Project Petunia × Judicator (OGS)

**Independent Evidence Review — OGS Interoperability and Ingestion.** The OGS B-3 v2 submission helped test NeoMundi Evidence ingestion, schema compatibility, artifact integrity and deterministic replay. It exposed four ingestion discrepancies: execution-kind representation, timestamp format, missing artifact role and list-valued pilot metadata. The adapter was corrected and regression-tested. The unchanged candidate then passed the documented technical ingestion checks, including 19 artifact hashes and byte counts and five deterministic replay cases.

**Limit:** This establishes bounded ingestion compatibility, not upstream claim certification, general production readiness or complete scientific validation. [Technical reference — engine PR #24, merge commit `330ecb03`, 11 November 2026](https://github.com/neomundi-io/neomundi-evidence-gateway/blob/main/references/REVIEWS.md#mark-mocnaj--project-petunia--judicator-ogs). The Evidence engine repository is private; the pull request, its diff and its merge commit exist unchanged inside it, and the full reference is recorded on the linked page.

### Dennis Christie — ASIN-HHC / CP8

**Independent Evidence Review — Reproducibility and execution evidence.** Dennis independently examined NeoMundi measurement receipts and evidence-verification boundaries using an existing controlled CP8 execution packet and reconciliation materials. His review distinguished a reported AI measurement from the underlying external tool execution. It also identified a raw aggregate (0.3863) versus an older normalized dashboard display (0.594): two NeoMundi representations, not conflicting measurements from two parties.

The findings informed stronger digest-coverage handling, clearer separation of declared and independently verified relationships, additional regression checks and documentation improvements. [Technical reference — engine PR #38, merge commit `439d1549`, 13 November 2026](https://github.com/neomundi-io/neomundi-evidence-gateway/blob/main/references/REVIEWS.md#dennis-christie--asin-hhc--cp8). The Evidence engine repository is private; the pull request, its diff and its merge commit exist unchanged inside it, and the full reference is recorded on the linked page.

**Limits:** External execution is not yet cryptographically or operationally bound to the separate AI measurement. A SHA-256 digest is not a signature and does not authenticate an issuer. Issuer authentication and excerpt retention remain open. This is a bounded methodological review, not independent end-to-end validation, general performance certification or endorsement of the platform.

### Pradeep Kumar — AI Systems Architect & STANAIC Fellow

**Independent Evidence Review — Adversarial Testing, Schema Compatibility and Cryptographic Ledger Hardening.** Credit: [Pradeep Kumar — AI Systems Architect & STANAIC Fellow (@pradeepkumar-ai-byte)](https://github.com/pradeepkumar-ai-byte).

Pradeep submitted a technical audit and solutions package, followed by a hardened v1.1 package for counter-audit. His work raised practical questions concerning observation linkage, schema compatibility, streaming invariance, verification, proposed calibration methods and **cryptographic ledger hardening**. These contributions helped identify areas for further testing and qualification of NeoMundi Evidence.

In his 17 November 2026 RC1 feedback, Pradeep reported **partial alignment** with `leader/1`: his LEADER execution receipts form structured leaf records with authority nonces, and he considered the `leader_receipt.py` leaf-flattening normalizer a suitable tamper-evident representation of those trees. He endorsed strict schema refusals (`additionalProperties: false`) alongside UTF-8 BOM acceptance, and considered the limitations in `05_KNOWN_LIMITATIONS.md` appropriately bounded.

**Limits:** These are Pradeep's review observations, not independently replicated end-to-end results, proof that submitted modules were deployed in NeoMundi production, certification of `leader/1` compatibility, scientific calibration of evaluators or endorsement of the platform. [Attribution and wording explicitly approved by Pradeep, 17 November 2026](https://github.com/pradeepkumar-ai-byte).

### Olusanya Timothy — Conformance corpus and CLI verification contract

**Independent Evidence Review — Dependency diagnostics and verification states.** In his November 2026 review, Timothy independently flagged misleading dependency diagnostics in the conformance harness: an optional dependency absent from the execution environment was being reported as a regression rather than identified as a missing prerequisite. He also raised a question about CLI exit-code contract semantics: **incomplete verification and failed verification are distinct states**. This is a contract-design discussion, **not a defect fix attributed to the reviewer**.

The strict-mode coverage gap was already recorded in NeoMundi release notes. Timothy located it **in those notes** and relayed the flag; the original discovery and corrective implementation remain NeoMundi's. The resulting investigation and corrections were released in conformance corpus **1.3.0**. Timothy reported rerunning checks **on that release, not on his own branch**: 172 digests, byte-for-byte reproduction of 121 fixtures and 11 passing checks in his available Python environment; the Rust toolchain was not exercised by him.

**Limits:** The review has open items. This credit does **not** imply that Timothy closed, validated, certified or signed off on the corpus, or endorsed NeoMundi. The observations and corrective code authorship are distinguished. Technical trace: engine PRs #39 (corpus change) and #40 (acknowledgment), archived in the private engine repository; the latter was merged on 14 November 2026 as commit `6c5bb4c5`.

Future contributor-specific reviews will be published only after explicit approval of their wording and attribution. No private execution packet or unapproved case-study claim is included.

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

- **ODA3 Institute — independent Evidence review (6 Nov 2026):** [PR #10 consolidation record](./catalog/oda3/pr-10/ODA3_CONSOLIDATION.md) · [PR #11 provenance R-6](./catalog/oda3/pr-11/R6_PROVENANCE_CONTRACT.md) · [PR #11 comparative replay](./catalog/oda3/pr-11/COMPARATIVE_REPORT.md). These are verbatim copies of selected merged technical documents from the private Evidence repository, **not** replacements for the original PR histories or the complete reproducibility package. Independent verification remains limited to the evidence and instruments made accessible; the documented `NOT TESTED` and open issues remain unchanged.


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

## Interoperability & integration

**[NeoMundi Measurement Interoperability — RGC JSON contract](https://github.com/neomundi-io/neomundi-measurement-interoperability)** is the technical exchange interface between runtime measurement and independent consumer systems. It documents versioned measurement records, signing, schemas, verification and consumer examples. Downstream systems retain their interpretation, policy and execution authority; this contract is **not** itself a business pilot, a certification or the independent Evidence archive verifier.

The contract is maintained in its own repository as the single source of truth. See its documentation for version, tier and endpoint requirements.

## Infrastructure & Program Support

NeoMundi's independent AI observation and measurement initiative benefits from infrastructure and startup program support:

- **[Infomaniak](https://www.infomaniak.com/)** — Infrastructure partner supporting the development of NeoMundi's independent AI observation instrument.
- **[OVHcloud Startup Program](https://startup.ovhcloud.com/)** — Startup support program participant.
- **[NVIDIA Inception](https://www.nvidia.com/en-us/startups/)** — Member of NVIDIA's program for innovative startups.

These relationships support NeoMundi's development and do not imply certification or endorsement of its scientific results.

## Scope and provenance

The public marketing selection is deliberately narrower than this catalogue. Technical reviews are not client case studies. For research collaboration documentation, consult the original source repositories under their existing publication and attribution agreements; no research cards or private working drafts are republished here.
