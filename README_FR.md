[English](./README.md)

# Des mesures d'IA aux preuves examinables

**Une primitive de mesure. Plusieurs applications. Des frontières explicites.**

NeoMundi produit des signaux indépendants de mesure runtime. Les systèmes partenaires peuvent interpréter ces signaux, les combiner avec leurs propres preuves et décider ou agir sous leur propre autorité.

> **La mesure n’est pas l’interprétation. L’interprétation n’est pas une décision. Un signal n’est pas une permission d’agir.**

## Explorer NeoMundi

[![Station — Observer et expérimenter](https://img.shields.io/badge/Station-Observer_%26_experimenter-7c3aed?style=flat-square)](https://github.com/neomundi-io/neomundi-station-public)
[![Runtime Measurement — Mesurer et intégrer](https://img.shields.io/badge/Runtime_Measurement-Mesurer_%26_integrer-2563eb?style=flat-square)](https://github.com/neomundi-io/neomundi-runtime-measurement)
[![Use Cases — Applications, pilotes et preuves](https://img.shields.io/badge/Use_Cases-Applications%2C_pilotes_%26_preuves-059669?style=flat-square)](https://github.com/neomundi-io/neomundi-use-cases)
[![Créer un compte — ControlTower](https://img.shields.io/badge/Creer_un_compte-ControlTower-ea580c?style=flat-square)](https://controltower.neomundi.io/welcome)

## Explorer par usage

- **Preuve et audit :** AI Business, FactNotebook, SEILX
- **Politique et exécution indépendantes :** OASSE, ManChine, VERITAS
- **Observabilité et qualité :** DriftShield, Kabbalah App
- **Routage agentique :** OmarAGI / REVAS
- **Recherche sur la mesure :** Dr Islam Gouda, Farzad Abbasi / AEGIS

## Niveaux de preuve

Ces niveaux décrivent les preuves publiques disponibles pour un cas précis. Ce ne sont ni des certifications, ni des notes attribuées aux partenaires, ni une échelle universelle de maturité.

| Niveau | Signification |
| --- | --- |
| **E0 — Déclaré** | L’objet et le statut sont publics, mais aucun résultat n’est revendiqué ni publiquement étayé. |
| **E1 — Documenté** | Une architecture, un plan ou un compte rendu est public ; aucune exécution publique achevée n’est démontrée. |
| **E2 — Exécution contrôlée** | Des artefacts examinables documentent une exécution synthétique ou contrôlée. |
| **E3 — Observation réelle bornée** | Des preuves publiques documentent des données réelles ou une exécution réelle bornée, avec ses limites. |
| **E4 — Reproduction indépendante** | Un tiers peut reproduire indépendamment le résultat à partir du protocole et des matériaux publiés. |

Aucun cas de cet index n’est actuellement présenté comme E4.

## Index des pilotes

Le statut s’applique uniquement au périmètre documenté. Il ne valide pas globalement la technologie d’un partenaire et n’établit pas une disponibilité en production.

| # | Cas d’usage | Technologie partenaire | Rôle de NeoMundi | Autorité partenaire | Statut | Preuve | Dernière vérification identifiable | Preuves publiques et limites |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **01** | Preuves pour l’assurance et l’analyse du risque | AI Business / Express Test Purchase | Mesure runtime indépendante | Recoupe permissions, actions, journaux et reçus ; l’assureur évalue le risque | En cours | **E0** | Non indiquée | Aucun résultat assurantiel dédié. L’[audit contrôlé connexe](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity) n’établit ni assurabilité ni décision de souscription. |
| **02** | Contrôle et routage agentiques | OmarAGI / REVAS | Fournit des exemples synthétiques d’observation runtime | REVAS produit ses propres artefacts d’admissibilité pré-action | Pilote 01 documenté · Pilote 02 planifié | **E2** | Date d’exécution non indiquée | Cinq cas synthétiques sont documentés. Aucun résultat live du Pilote 02, aucune validation de production ni conclusion générale de fiabilité. [Dépôt partenaire](https://github.com/effacermonexistence/omaragi-neomundi-pilot). |
| **03** | Politique et enforcement | OASSE / FAM / Gatekeeper | Produit des mesures runtime et des classifications historiques de couche de mesure | FAM applique la politique déterministe ; Gatekeeper détermine le traitement opérationnel en aval et scelle les preuves | Pilote contrôlé validé | **E3** | 29 juillet et 4 août 2026 | Runs contrôlés de 1 000 et 60 requêtes. Les valeurs historiques **ALLOW/FLAG** sont des classifications de mesure, pas des permissions d’exécution. [Dépôt](https://github.com/neomundi-io/use-case-oasse-runtime-governance). |
| **04** | Audit contrôlé d’un agent IA | AI Business / Express Test Purchase | Mesure l’observation de validation soumise | Le journal autoritatif enregistre l’exécution ; un validateur déterministe évalue la conformité du reçu | Pilote contrôlé validé | **E2** | 3–4 août 2026 | Trois runs de référence contrôlés, dont une preuve de reçu propre et une volontairement défaillante. L’environnement est synthétique et n’établit pas la fiabilité générale de l’agent. [Dépôt](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity). |
| **05** | Reconstruction de preuve | FactNotebook | Mesure cinq générations GPT‑4o et exporte les observations runtime | FactNotebook reconstruit ce que les observations permettent d’établir ; une autorité humaine responsable décide | Pilote borné terminé | **E3** | Export runtime : 25 juillet 2026 · manifeste partenaire : 7 août 2026 | Cinq cas PubMedQA ont été ingérés. Le partenaire publie les sorties, pas son moteur de reconstruction ; le travail n’est pas reproductible indépendamment et n’établit pas une vérité médicale. [Pilote NeoMundi](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [reconstruction partenaire](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001). |
| **06** | Observabilité parallèle | DriftShield / HIC | Observe indépendamment la même exécution | Conserve sa propre observation et le modèle d’autorité X/Y/Z existant | Pilote minimal rapporté | **E1** | Non indiquée | Une exécution réelle est rapportée, mais aucun paquet public dédié, aucune réplication et aucun dépôt public ne sont identifiés ici. |
| **07** | Gouvernance par des preuves vérifiables | SEILX | Produit une observation et les artefacts associés | Capture, préserve et ancre temporellement les artefacts pour des contrôles d’intégrité ultérieurs | En cours | **E0** | Non indiquée | Aucun résultat final ni paquet de preuve public dédié. L’intégrité et la provenance n’établissent ni vérité factuelle ni permission d’exécution. |
| **08** | Admissibilité et continuité d’exécution | ManChine / RGE‑01 / REB‑01 / RiCo‑01 | Fournit une preuve observationnelle runtime | RGE‑01 évalue l’admissibilité avant activation ; REB‑01 gouverne la frontière d’exécution ; RiCo‑01 traite la continuité après activation | Architecture documentée · validation en attente | **E1** | Aucun run terminé | L’architecture et des payloads d’exemple sont publics ; un échange machine-à-machine complet ne l’est pas. [Dépôt](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility). |
| **09** | Détection de qualité runtime RAG | Kabbalah App / RAG Test Bench | Produit des signaux de mesure runtime pendant l’évaluation | Le banc d’essai conserve le retrieval, la notation, le diagnostic et le choix des modèles | Test de terrain borné documenté | **E3** | Étude : 23 août 2026 · rapport : 20 septembre 2026 | Le rapport documente 60 générations instrumentées par manche, avec des alertes rapportées passant de 45/60 à 1/60 après correction. Le harness privé, les questions, les mappings de notation et le paquet brut ne sont pas publics. [Synthèse des preuves](./evidence/kabbalah-app-rag/README_FR.md). |
| **10** | Vérification de signaux signés | VERITAS | Produit des observations RGC signées | VERITAS vérifie les preuves selon sa politique de confiance et conserve l’autorité de gouvernance et d’exécution | Adaptateur validé · preuve live réelle en attente | **E2** | Aucune clôture publique du PoC d’observation réelle | L’adaptateur et les chemins synthétiques sont documentés. Aucune observation NeoMundi réelle n’est publiée dans le dépôt partenaire. [Adaptateur](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-adapter.md) · [runbook du PoC réel](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-real-observation-poc.md). |

## Études en cours

Ces études sont en cours. Aucun résultat ni niveau de preuve ne leur est attribué ici.

| Étude | Objet | Statut |
| --- | --- | --- |
| Dr Islam Gouda | Incertitude de mesure et répétabilité des évaluateurs | En cours |
| Farzad Abbasi — AEGIS | Évaluation documentaire et diagnostic des signaux de mesure | En cours |

## Ce qui a été démontré

Dans les limites publiées :

- des systèmes tiers peuvent consommer des observations runtime NeoMundi tout en conservant une autorité séparée ;
- des preuves contrôlées peuvent préserver la distinction entre mesure, conformité déterministe, politique et action en aval ;
- des travaux bornés sur données ou exécutions réelles sont documentés pour OASSE, FactNotebook et Kabbalah App ;
- des chemins synthétiques ou contrôlés sont documentés pour OmarAGI / REVAS, AI Business et VERITAS ;
- la séparation architecturale est documentée pour ManChine.

## Ce qui reste non vérifié

Cet index n’établit pas :

- une certification, une conformité réglementaire, une assurabilité ou une fiabilité à l’échelle de la production ;
- une vérité factuelle ou une validité médicale ;
- la supériorité d’un modèle ou d’une technologie partenaire ;
- la reproduction indépendante d’un résultat présenté ;
- un résultat public pour DriftShield ou SEILX ;
- une interopérabilité live achevée pour ManChine ou le chemin d’observation réelle de VERITAS.

Un artefact public manquant n’est pas remplacé par un statut. Les preuves synthétiques, contrôlées, limitées à une exécution ou limitées à un rapport doivent rester identifiées comme telles.

## Preuves détaillées

- [AI Business — audit contrôlé d’un agent](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity)
- [OmarAGI / REVAS — pilote partenaire](https://github.com/effacermonexistence/omaragi-neomundi-pilot)
- [OASSE — gouvernance runtime](https://github.com/neomundi-io/use-case-oasse-runtime-governance)
- [FactNotebook — pilote NeoMundi](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa)
- [FactNotebook — reconstruction partenaire bornée](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001)
- [ManChine — de l’observation à l’admissibilité](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility)
- [Kabbalah App — synthèse publique des preuves](./evidence/kabbalah-app-rag/README_FR.md)
- [VERITAS — adaptateur RGC v0.2](https://github.com/veritasfuji-japan/veritas_os/blob/main/docs/en/architecture/neomundi-rgc-v02-adapter.md)

## Infrastructure et programmes de soutien

L'initiative indépendante de NeoMundi pour l'observation et la mesure des IA bénéficie de soutiens en matière d'infrastructure et de programmes d'accompagnement :

- **[Infomaniak](https://www.infomaniak.com/fr)** — Partenaire infrastructure soutenant le développement de l'instrument indépendant d'observation des IA de NeoMundi.
- **[OVHcloud Startup Program](https://startup.ovhcloud.com/fr/)** — NeoMundi participe au programme d'accompagnement des startups d'OVHcloud.
- **[NVIDIA Inception](https://www.nvidia.com/fr-fr/startups/)** — NeoMundi est membre du programme de NVIDIA pour les startups innovantes.

Ces relations soutiennent le développement de NeoMundi et n'impliquent ni certification ni approbation de ses résultats scientifiques.

---

## Proposer un pilote

Un pilote utile commence par une question bornée, des responsabilités explicites, un protocole reproductible et une formulation claire de ce que les preuves ne permettent pas d’établir.

[Proposer un cas d’usage dans les issues du dépôt](https://github.com/neomundi-io/neomundi-use-cases/issues). Ne publiez ni secret, ni donnée personnelle, ni archive expérimentale privée.
