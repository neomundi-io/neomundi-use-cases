[English](./README.md)

# Cas d’usage NeoMundi

**Une primitive de mesure. Plusieurs applications. Plusieurs infrastructures.**

**NeoMundi apporte le signal. Chaque système externe conserve l’interprétation, les politiques et l’autorité d’action.**

Cet index public canonique rassemble les cas d’usage NeoMundi et leurs preuves d’interopérabilité. NeoMundi mesure le comportement runtime et apporte un signal indépendant. Les partenaires conservent les décisions, l’autorité opérationnelle et les mécanismes d’exécution.

D’une intuition, le 27 septembre 2025, à nos premiers pilotes et partenaires.

## Vue d’ensemble

Le statut décrit le périmètre documenté d’un pilote, pas une validation générale de la technologie partenaire. La disponibilité des preuves est indiquée séparément. Mise à jour : 20 septembre 2026.

| Cas d’usage | Technologie partenaire | Fonction | Statut | Niveau de preuve | Ce que cela démontre | Preuve publique |
| --- | --- | --- | --- | --- | --- | --- |
| Preuves pour l’assurance et l’analyse du risque | AI Business / Express Test Purchase | Observations indépendantes pour examen par l’assureur | Pilot in progress | Évaluation en cours ; aucun résultat assurantiel final | Évalue la complémentarité des preuves ; l’assureur évalue le risque | Aucune preuve assurantielle dédiée ; [audit contrôlé connexe](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) |
| Contrôle et routage agentiques | OmarAGI / REVAS | Consommation du signal par une orchestration indépendante | Pilot 01 documented · Pilot 02 live planned | Cinq cas synthétiques NeoMundi ; aucune fiabilité générale ni validation de production | Transformation de signaux synthétiques en artefacts REVAS d’admissibilité pré-action | [Dépôt partenaire](https://github.com/effacermonexistence/omaragi-neomundi-pilot) |
| Politique et application | OASSE / FAM / Gatekeeper | Politique déterministe et application externe | Validated pilot | Pilote documenté | La mesure peut alimenter des couches distinctes de politique et d’application | [Dépôt](https://github.com/neomundi-io/use-case-oasse-runtime-governance) |
| Audit contrôlé d’un agent IA | AI Business / Express Test Purchase | Mesure runtime et conformité du reçu | Validated pilot | Environnement de référence synthétique contrôlé | Les enregistrements séparés de la même exécution peuvent être recoupés | [Dépôt](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) |
| Reconstruction de preuves | FactNotebook | Ingestion de la mesure et de sa provenance | Validated pilot | Expérience PubMedQA documentée | Un système indépendant peut reconstruire des preuves en préservant la provenance | [Dépôt](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) |
| Observabilité parallèle | DriftShield / HIC | Observation indépendante de la même exécution | Validated minimum pilot | Une exécution réelle ; preuves publiques détaillées indisponibles ici | Observations distinctes et recoupables sans partage de la réponse brute | Aucun dépôt public NeoMundi dédié identifié |
| Gouvernance par des preuves vérifiables | SEILX | Capture, préservation et ancrage temporel | Pilot in progress | Évaluation en cours ; aucun résultat final | Évalue la vérification ultérieure de l’intégrité et de la provenance | Aucun dépôt public NeoMundi dédié identifié |
| Admissibilité et continuité d’exécution | ManChine / RGE-01 / REB-01 / RiCo-01 | Séparation de l’observation, de la continuité, de la détermination et de l’application | Architecture documented · Validation in progress | Documentation architecturale | Les responsabilités peuvent rester distinctes ; validation machine-à-machine complète en attente | [Dépôt](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility) |
| Détection de la qualité runtime d’un RAG | Kabbalah App / RAG Test Bench | Détection d’une dégradation et observation du rétablissement | Validated field test | Rapport terrain public ; 60 générations instrumentées par manche rapportée | Le signal a précédé le diagnostic et reflété la stabilité accrue après correction | [Preuve et rapport](./evidence/kabbalah-app-rag/README_FR.md) |
| Vérification d’un signal signé | VERITAS | Vérification indépendante d’observations RGC v0.2 signées | Adapter validated · Live interoperability pending | Adaptateur et vérification synthétique ; observation réelle signée en attente | Intégration de l’adaptateur documentée ; interopérabilité live complète non encore démontrée | [Dépôt](https://github.com/veritasfuji-japan/veritas_os) |

## Cas d’usage

### 01 · AI Business / Express Test Purchase — Preuves pour l’assurance et l’analyse du risque

**Pilot in progress.** NeoMundi et Express Test Purchase observent indépendamment la même exécution. NeoMundi mesure le comportement runtime ; Express Test Purchase recoupe permissions, actions, journaux et reçus. Leurs enregistrements restent séparés et peuvent être mis en correspondance pour examen. Il ne s’agit pas d’une chaîne de traitement séquentielle. Le pilote évalue des preuves complémentaires pour l’assureur. L’évaluation du risque appartient à l’assureur, ou underwriter. L’audit contrôlé ci-dessous n’établit pas de résultat assurantiel.

Aucune preuve assurantielle dédiée ; [audit contrôlé connexe](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity).

### 02 · OmarAGI / REVAS — Contrôle et routage agentiques

**Pilot 01 documented · Pilot 02 live planned.** Pilot 01 documente la transformation de cinq cas synthétiques d’observabilité runtime NeoMundi en artefacts REVAS d’admissibilité pré-action. Pilot 02 est un test live avec ControlTower planifié ; il n’est pas présenté comme terminé. Ces preuves se limitent aux cas synthétiques documentés et n’établissent ni fiabilité générale ni validation de production.

[Dépôt partenaire](https://github.com/effacermonexistence/omaragi-neomundi-pilot).

### 03 · OASSE / FAM / Gatekeeper — Politique et application

**Validated pilot.** NeoMundi mesure. La couche de politique OASSE applique des règles déterministes : **OASSE policy layer applies deterministic rules**. Gatekeeper applique les verdicts **ALLOW / TRANSFORM / HOLD / DENY**. Les politiques, les décisions et leur application restent externes à NeoMundi. Le pilote documenté étaye cette séparation dans son périmètre testé, pas la validité générale des politiques.

[Dépôt](https://github.com/neomundi-io/use-case-oasse-runtime-governance).

### 04 · AI Business / Express Test Purchase — Audit contrôlé d’un agent IA

**Validated pilot.** NeoMundi enregistre les mesures runtime tandis qu’Express Test Purchase vérifie indépendamment la même exécution à travers les actions de l’agent, le journal autoritatif et le reçu. Les enregistrements restent séparés et recoupables ; aucun ne remplace l’autre. La mesure comportementale et la conformité du reçu sont des variables distinctes. Le validateur métier reste externe à NeoMundi. La preuve concerne un environnement de référence synthétique, pas une fiabilité générale des agents ni une validation assurantielle.

[Dépôt](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity).

### 05 · FactNotebook — Reconstruction de preuves

**Validated pilot.** FactNotebook ingère les mesures NeoMundi et leur provenance pour reconstruire des objets de preuve et de gouvernance. L’expérience PubMedQA documente une intégration sans altération de la provenance. La reconstruction de preuves n’établit pas à elle seule la vérité factuelle ni une validité médicale générale.

[Dépôt](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa).

### 06 · DriftShield / HIC — Observabilité parallèle

**Validated minimum pilot.** NeoMundi et DriftShield/HIC ont observé indépendamment une exécution réelle. Les observations sont restées distinctes et recoupables sans partage de la réponse brute ni modification de l’autorité X/Y/Z existante. La preuve se limite à cette exécution unique ; elle n’établit ni répétabilité, ni performance à l’échelle de la production, ni interopérabilité générale. Aucun dossier public de preuves dédié n’est disponible ici.

Aucun dépôt public NeoMundi dédié identifié.

### 07 · SEILX — Gouvernance par des preuves vérifiables

**Pilot in progress.** Le pilote évalue la capture, la préservation et l’ancrage temporel par SEILX des artefacts associés à une observation NeoMundi, pour vérifier ultérieurement l’intégrité et la provenance. Aucun résultat final n’est revendiqué. L’intégrité d’une preuve est distincte de la vérité du contenu observé et d’une permission opérationnelle.

Aucun dépôt public NeoMundi dédié identifié.

### 08 · ManChine / RGE-01 / REB-01 / RiCo-01 — Admissibilité et continuité d’exécution

**Architecture documented · Validation in progress.** NeoMundi observe les conditions runtime. RiCo-01 vérifie la continuité de la correspondance de gouvernance runtime et identifie l’effet éventuel sur la portabilité de la gouvernance antérieure. RGE-01 produit une nouvelle **Admissibility Determination** lorsqu’un nouveau point de décision existe. REB-01 applique l’état de gouvernance applicable à la frontière d’exécution conséquente.

Le dépôt lié constitue une référence architecturale. La validation machine-à-machine complète n’est pas encore disponible. RiCo ne produit pas l’Admissibility Determination ; l’observation ne confère aucune autorité d’exécution à NeoMundi.

[Dépôt](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility).

### 09 · Kabbalah App / RAG Test Bench — Détection de la qualité runtime d’un RAG

**Validated field test.** Une évaluation RAG bilingue orientée production a instrumenté 60 générations par manche rapportée. Les alertes sont passées de **45/60** avant correction du prompt à **1/60** après correction ; la stabilité moyenne est passée de **0.68–0.77** à **0.915–0.923**.

> Dans ce banc d’essai RAG, le signal runtime NeoMundi a détecté une dégradation réelle avant que sa cause technique soit identifiée, puis a reflété le retour à un comportement plus stable après correction.

NeoMundi n’a pas désigné le meilleur modèle. Un composant d’évaluation appartenait à une famille de modèles incluse dans la comparaison ; la longueur des réponses affectait également le classement de génération. Les prompts longs et la latence imposaient des contraintes d’intégration. Ces observations sont propres à ce banc d’essai et ne garantissent pas une exactitude générale.

[Preuve et rapport](./evidence/kabbalah-app-rag/README_FR.md).

### 10 · VERITAS — Vérification d’un signal signé

**Adapter validated · Live interoperability pending.** L’état documenté est un adaptateur NeoMundi RGC v0.2 intégré, une validation après fusion verte et un chemin de vérification synthétique testé dans VERITAS. L’objectif est la vérification indépendante d’une observation NeoMundi réelle et signée, suivie de l’évaluation de gouvernance de VERITAS et d’un reçu auditable ou Evidence Packet. L’interopérabilité live complète n’a pas encore été démontrée. Vérification de signature, évaluation de gouvernance et permission d’exécution restent des responsabilités distinctes.

[Dépôt](https://github.com/veritasfuji-japan/veritas_os).

## Maturité et preuves

Ces libellés qualifient un périmètre précis ; ils ne constituent ni des certifications ni une échelle universelle de progression. Les preuves publiques peuvent être moins avancées que le statut documenté du pilote. Les libellés anglais sont conservés pour assurer la correspondance exacte entre les deux versions.

| Libellé | Signification |
| --- | --- |
| Architecture documented | Architecture documentée : responsabilités et interfaces décrites ; cela ne démontre pas à lui seul une intégration live. |
| Pilot in progress | Pilote en cours : évaluation en cours ; aucun résultat final établi. |
| Controlled run completed | Exécution contrôlée terminée : essai borné dans des conditions définies ; aucune validation générale ou à l’échelle de la production n’en découle. |
| Validated minimum pilot | Pilote minimal validé : interaction minimale démontrée ; pour DriftShield/HIC, une seule exécution réelle. |
| Validated pilot | Pilote validé : objectif annoncé démontré dans le périmètre documenté ; la technologie partenaire n’est pas validée en général. |
| Live interoperability pending | Interopérabilité live en attente : échange complet avec une observation réelle encore à démontrer, même si un adaptateur ou un chemin synthétique fonctionne. |
| Validated field test | Test terrain validé : observation bornée documentée dans une évaluation terrain ; ici, dégradation RAG et rétablissement après correction. |
| Adapter validated | Adaptateur validé : contrôles de l’adaptateur et chemin de vérification synthétique documentés ; cela ne remplace pas la preuve d’interopérabilité live. |

## Ce que cela prouve

Dans les périmètres documentés, une même primitive de mesure peut servir des fonctions distinctes d’orchestration, de politique, de preuve, d’observabilité et de diagnostic. Les artefacts liés distinguent les tests terminés, les références architecturales et les évaluations en cours. La mesure peut rester indépendante des systèmes qui l’interprètent et agissent.

## Ce que cela ne prouve pas

Ces cas n’établissent ni certification générale, ni vérité factuelle, ni conformité réglementaire, ni assurabilité, ni fiabilité à l’échelle de la production, ni supériorité d’un modèle ou d’un partenaire. Un signal ou une observation signée n’est pas une autorisation. Les libellés de statut ne remplacent pas les artefacts publics manquants ; les tests synthétiques ou sur une exécution unique n’établissent pas une interopérabilité live générale.

## Preuves et dépôts publics

- [AI Business](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity)
- [OmarAGI / REVAS — dépôt partenaire](https://github.com/effacermonexistence/omaragi-neomundi-pilot)
- [OASSE](https://github.com/neomundi-io/use-case-oasse-runtime-governance)
- [FactNotebook](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa)
- [ManChine — référence architecturale](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility)
- [Kabbalah App — preuve publique](./evidence/kabbalah-app-rag/README_FR.md) · [PDF (français)](./evidence/kabbalah-app-rag/NEOMUNDI_KABBALAH_APP_RAG_PUBLIC_EVIDENCE_REPORT_FR.pdf)
- [VERITAS — dépôt partenaire](https://github.com/veritasfuji-japan/veritas_os)

## NeoMundi

- [NeoMundi — applications et pilotes](https://neomundi.io/)
- [NeoMundi Research](https://neomundi.org/)
- [Contrat d’interopérabilité runtime](https://github.com/neomundi-io/runtime-interoperability-contract)
- [ControlTower](https://controltower.neomundi.io/welcome)
- [Observatoire IA NeoMundi](https://github.com/neomundi-io/neomundi-ai-observatory)
