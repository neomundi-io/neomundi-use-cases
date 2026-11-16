<div align="center">

<sub><a href="README.md">English</a> · <b>Français</b></sub>

# Des problèmes métier. Des résultats documentés. Des preuves consultables.

**Comprendre ce que font vos IA, examiner ce qui s'est passé et décider à partir de mesures traçables.**

**INSTALL → TRACE → MEASURE → VERIFY → ACT**

[**LIVE DEMO**](https://neomundi.io/fr/demonstration/) · [**Déployer NeoMundi**](https://neomundi.io/fr/contact/) · [Architecture produit](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

</div>

---

## Partir du problème métier

Les applications ci-dessous distinguent les rôles de la mesure, de la preuve et des décisions en aval. **Un pilote n'est pas une référence client commerciale** ; les résultats restent limités aux conditions publiées.

**Accès direct :** [Audit des agents](#01--audit-des-agents-ia) · [Contrôle d'exécution](#02--contrôle-de-lexécution) · [Preuve & audit](#03--preuve--audit) · [Qualité RAG](#04--qualité-des-assistants-rag)

---

## 01 — AUDIT DES AGENTS IA

### Comment auditer les actions d'un agent IA ?

> **Problème métier**  
> Un agent prend des engagements ou déclare des actions. Comment comparer ses propos aux opérations enregistrées ?

| Application documentée | Résultats et périmètre | Preuves |
| --- | --- | --- |
| **AI Business / Express Test Purchase** · **E2 — Contrôlé** | Trois achats tests contrôlés, dont des reçus conformes et volontairement défectueux. **Environnement synthétique** ; aucun résultat de souscription ou d'assurance n'est revendiqué. | [Preuves contrôlées](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) |
| **Sergei Ponomarev / AI Business** · **E0 — En cours** | Mesure indépendante des réponses pour alimenter une comparaison distincte entre promesses, dialogue et journal d'exécution. Série du **6 novembre au 5 décembre 2026** ; résultats et identités des modèles **non publiés**. | [Protocole public](https://github.com/sergeiperm81-ux/ai-test-purchase) |

**Valeur métier →** Distinguer les observations de l'autorité chargée de juger l'exécution réelle de l'agent.

---

## 02 — CONTRÔLE DE L'EXÉCUTION

### Comment contrôler l'exécution d'agents sans confondre mesure et permission ?

> **Problème métier**  
> Des mesures peuvent éclairer une politique, sans devenir elles-mêmes une autorisation d'exécution.

| Application documentée | Résultats et périmètre | Preuves |
| --- | --- | --- |
| **OASSE / FAM / Gatekeeper** · **E3 — Borné** | Campagnes contrôlées de **1 000 et 60 requêtes**, séparant mesure, politique déterministe et traitement opérationnel. Les historiques **ALLOW/FLAG** sont des classifications de mesure, **pas des permissions d'exécution**. | [Étude](https://github.com/neomundi-io/use-case-oasse-runtime-governance) |
| **ManChine / RGE-01, REB-01, RiCo-01** · **E1 — Documenté** | Architecture publique pour l'admissibilité pré-action, la frontière d'exécution et sa continuité ; **validation machine-à-machine complète en attente**. | [Architecture](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility) |

**Valeur métier →** Conserver des responsabilités séparées entre mesure, politique et décision opérationnelle.

---

## 03 — PREUVE & AUDIT

### Comment reconstruire et vérifier une preuve après une interaction IA ?

> **Problème métier**  
> Une réponse contestée ou un audit exige des enregistrements examinables, pas seulement un compte rendu.

| Application documentée | Résultats et périmètre | Preuves |
| --- | --- | --- |
| **FactNotebook** · **E3 — Borné** | **Cinq cas PubMedQA** instrumentés, puis reconstruits par le partenaire. **Moteur de reconstruction non public** ; aucune vérité médicale établie. | [Pilote NeoMundi](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [Reconstruction partenaire](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001) |
| **Mark Mocnaj / Project Petunia × Judicator (OGS)** · **E2 — Synthétique** | Cinq payloads synthétiques d'interopérabilité et reçus liés aux payloads ; le replay déterministe interne a reproduit les cinq classifications. **Aucune action externe autorisée ; aucune mesure réelle NeoMundi en production**. | [Étude d'interopérabilité](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot) |

**Valeur métier →** Examiner ce que les preuves étayent réellement, avec intégrité et provenance explicites.

---

## 04 — QUALITÉ DES ASSISTANTS RAG

### Comment vérifier qu'un assistant IA s'améliore ?

> **Problème métier**  
> Un assistant RAG a été corrigé. Comment comparer les résultats observables dans un protocole défini ?

| Application documentée | Résultats et périmètre | Preuves |
| --- | --- | --- |
| **Kabbalah App / RAG Test Bench** · **E3 — Borné** | **60 générations instrumentées par manche** ; alertes rapportées passant de **45/60 à 1/60** après correction. **Banc d'essai, données brutes et correspondances de notation privés**. | [Synthèse publique](evidence/kabbalah-app-rag/README_FR.md) |

**Valeur métier →** Documenter les changements observés plutôt que se fier aux impressions.

---

## Aller plus loin sans alourdir la lecture

- [Catalogue technique complet — 12 entrées pilotes, statuts, niveaux de preuve et revues indépendantes](CATALOG_FR.md)
- [API de mesure](https://github.com/neomundi-io/neomundi-runtime-measurement) · [Station](https://github.com/neomundi-io/neomundi-station-public) · [Interface Evidence](https://github.com/neomundi-io/neomundi-evidence-gateway)
- [Architecture produit NeoMundi](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

Ces cas sont des **démonstrations bornées et des pilotes de recherche**, et non des certifications, preuves de fiabilité générale ou preuves de conformité réglementaire. Chaque protocole lié définit sa couverture et ses limites.

## Et dans votre organisation ?

**[Explorer la démo](https://neomundi.io/fr/demonstration/)** · **[Étudier un déploiement](https://neomundi.io/fr/contact/)**
