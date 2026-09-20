[Français](./README_FR.md) · [Use-case index](../../README.md)

# Kabbalah App × NeoMundi — RAG Runtime Detection Evidence

**Status: Validated field test**

## Context

Kabbalah App evaluated a production-oriented Hebrew–French RAG test bench. The study took place on August 23, 2026; the authorized public report is dated September 20, 2026. Its corpus contains 2,633 aligned passages, indexed in both languages.

NeoMundi Continuous Control Launcher instrumented runtime measurements. Retrieval metrics, blind generation scoring, diagnosis, corrections, provider selection and operational decisions remained with the application and its evaluators.

## Protocol

Retrieval and generation were evaluated separately; the retrieval engine was selected before generation evaluation. The retrieval set contained 99 difficult synthetic questions, with seven anonymized real questions used only as a limited control. No question content is reproduced here.

Generation evaluation used 30 questions and two candidates, giving **60 instrumented generations** in a round, with the same retrieved context, randomized presentation and blind scoring. The report compares v1 and v2 using a denominator of 60 for each round; these are not 60 unique user questions.

The runtime signal revealed degradation before human investigation identified contradictory prompt instructions and unsubstituted template variables. The faulty round was invalidated for model comparison. After correction, another reported round showed fewer alerts and greater stability.

## Documented observations

| Measurement | Before correction (v1) | After correction (v2) |
| --- | --- | --- |
| Instrumented generations, denominator per round | 60 | 60 |
| Reported hallucination alerts | 45/60 | 1/60 |
| Average stability, reported range | 0.68–0.77 | 0.915–0.923 |

The stability ranges are reproduced as reported, not interpreted as confidence intervals. Alerts are measurement signals, not independently established factual error rates.

## Admissible claim

> In this RAG test bench, the NeoMundi runtime signal detected a real degradation before its technical cause was identified, then reflected the return to more stable behavior after correction.

## Limits

- Findings are specific to this corpus, protocol, model versions and measurement conditions; they are not general RAG certification or a guarantee of factual truth.
- NeoMundi did not determine which competing model was better. One evaluation component belonged to a model family included in the comparison, so the signal cannot alone arbitrate between providers.
- Response length confounded perceived generation quality; the seven-question real control is not an independent statistical basis. One retrieval candidate could not be measured because of a provider limit.
- The report identifies long-prompt and latency integration constraints. Security and implementation details remain outside this public package.
- Runtime measurements supplement business ground truth and human evaluation; interpretation, policies, decisions and actions remain external to NeoMundi.
- This repository provides a public report, not the private harness, raw questions, blind-scoring mappings or an executable reproduction package.

## Public evidence

[Read the authorized public report in French](./NEOMUNDI_KABBALAH_APP_RAG_PUBLIC_EVIDENCE_REPORT_FR.pdf) — especially protocol (page 3), the invalidated round (page 5), runtime observations (page 6) and limits (page 8).

The PDF is copied without modification. The report states that publication is authorized by the Kabbalah App project owner. No raw user questions, personal data, credentials, private endpoints, sensitive code or restricted infrastructure artifacts accompany it.
