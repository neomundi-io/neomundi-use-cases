<div align="center">

<sub><a href="README.md">English</a> · <b>Français</b></sub>

# NeoMundi — Cas d’usage

### La mesure devient utile lorsqu’elle répond à un problème concret.

**Découvrez comment la mesure indépendante, l’observation contextualisée et les preuves vérifiables s’appliquent aux agents IA, à la gouvernance et à la qualité des systèmes.**

**Measurement → Station → Evidence**

[![Measurement](https://img.shields.io/badge/Measurement-Mesurer-2563eb?style=flat-square)](https://github.com/neomundi-io/neomundi-runtime-measurement/blob/main/README_FR.md)
[![Station](https://img.shields.io/badge/Station-Observer-0f766e?style=flat-square)](https://github.com/neomundi-io/neomundi-station-public/blob/main/README.fr.md)
[![Evidence](https://img.shields.io/badge/Evidence-Verifier-D4A545?style=flat-square)](https://github.com/neomundi-io/neomundi-evidence-public/blob/main/README.fr.md)
[![Use cases](https://img.shields.io/badge/Cas_d_usage-Explorer-64748b?style=flat-square)](https://github.com/neomundi-io/neomundi-use-cases/blob/main/README_FR.md)

**[API](https://github.com/neomundi-io/neomundi-runtime-measurement/blob/main/QUICKSTART.md)** · **[Créer un compte](https://controltower.neomundi.io/welcome)**

</div>

---

## Trois applications documentées

Les résultats ci-dessous illustrent des **cas distincts** ; leur niveau E3 décrit les preuves publiques disponibles pour chaque périmètre, pas une certification ou une qualification générale en production.

| Application | Problème traité | Résultat documenté | Preuves |
|---|---|---|---|
| **OASSE — Gouvernance d’exécution** | Séparer mesure indépendante, politique déterministe et décision opérationnelle. | Deux campagnes contrôlées de **1 000 et 60 requêtes**, avec rôles d’autorité séparés. **E3**. | [Étude OASSE](https://github.com/neomundi-io/use-case-oasse-runtime-governance) |
| **FactNotebook — Reconstruction des preuves** | Relier les observations d’IA à une reconstruction indépendante de ce qu’elles permettent d’établir. | **5 cas PubMedQA** instrumentés, puis reconstruits par le partenaire. Le moteur de reconstruction n’est pas public. **E3**. | [Pilote NeoMundi](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [Travail partenaire](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001) |
| **Kabbalah App — Qualité d’un RAG** | Observer les alertes d’un banc RAG et les comparer après correction. | **60 générations instrumentées par manche** ; alertes rapportées passant de **45/60 à 1/60**. Banc et données brutes privés. **E3**. | [Synthèse publique](./evidence/kabbalah-app-rag/README_FR.md) |

**[Explorer les 11 cas d’usage](#index-des-pilotes)** · [Examiner les collaborations scientifiques](#collaborations-de-recherche) · [Proposer un pilote](#travailler-avec-neomundi)

## Une chaîne, des applications différentes

**Measurement** produit des signaux et leur couverture. **Station** conserve les conditions d’observation et les dossiers de campagne. **Evidence** permet de contrôler l’intégrité et certaines attestations des artefacts. Les partenaires conservent leurs politiques et décisions.

[Découvrir Measurement](https://github.com/neomundi-io/neomundi-runtime-measurement/blob/main/README_FR.md) · [Explorer Station](https://github.com/neomundi-io/neomundi-station-public/blob/main/README.fr.md) · [Vérifier avec Evidence](https://github.com/neomundi-io/neomundi-evidence-public/blob/main/README.fr.md)

## Explorer par usage

- **Preuve et audit :** AI Business, FactNotebook, SEILX
- **Gouvernance et exécution :** OASSE, ManChine, VERITAS, Project Petunia × Judicator (OGS)
- **Observabilité et qualité :** DriftShield, Kabbalah App
- **Routage agentique :** OmarAGI / REVAS
- **Recherche sur la mesure :** Dr Islam Gouda, Farzad Abbasi / AEGIS

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
| **11** | Interopérabilité d’objets de gouvernance | Mark Mocnaj / Project Petunia × Judicator (OGS) | Fournit le modèle d’observation runtime représenté par des payloads synthétiques | OGS évalue ce que les signaux peuvent légitimement étayer et interdit les usages aval non étayés | Pilote synthétique public documenté | **E2** | Date d’exécution non indiquée | Cinq payloads d’observation synthétiques, objets de gouvernance et reçus liés aux payloads sont publics ; le replay déterministe interne a reproduit les cinq classifications documentées. Aucune action externe n’a été autorisée. Le résultat est vérifié en interne, non reproduit indépendamment et non issu de la production ; aucune mesure NeoMundi réelle n’est incluse. [Dépôt partenaire](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot). |

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

## Intégration partenaire — Hivolvia (pilote privé)

**Cas d'usage :** relier une supervision indépendante de modèles et de services d'IA aux signaux de mesure NeoMundi. Stéphane Lauga indique avoir livré pour évaluation son connecteur Rust multiplateforme, initialement conçu pour son environnement d'observabilité puis adapté à l'API OBS de NeoMundi. Il s'agit d'une **implémentation tierce** dont l'auteur conserve les sources, la maintenance et le support à distance des pilotes.

**Niveau de preuve : E0 pour la qualification indépendante.** Le développeur a rapporté un échange API réussi le 2 septembre 2026 et une livraison le 18 septembre 2026. Ces étapes sont déclarées par le partenaire, pas reproduites indépendamment. Aucun test de bout en bout avec la version actuelle, audit de sécurité, accord de distribution pilote signé ou preuve publiée de consommation effective des mesures n'est disponible ici. L'évaluation est réservée à des pilotes identifiés dans un cadre convenu ; aucun téléchargement public. L'attribution publique reste à confirmer définitivement.

[Présentation de l'intégration — Station](https://github.com/neomundi-io/neomundi-station-public/blob/main/README.fr.md#intégrations-partenaires--pilotes-privés)

## Collaborations de recherche

Les collaborations de recherche sont séparées des pilotes produit. Elles documentent des questions, méthodes, rôles et limites ; elles ne constituent ni des références clients ni des certifications.

| Collaboration | Question de recherche | Preuve publique | Statut et limites |
| --- | --- | --- | --- |
| **NeoMundi × ASRO — Runtime Governance Evidence** | La mesure comportementale et l’observation de l’état de gouvernance peuvent-elles rester indépendantes sans validation circulaire ? | **E1** · [Fiche de recherche bilingue](./collaborations/asro/runtime-governance-evidence.md) · [Dépôt original](https://github.com/neomundi-io/runtime-governance-evidence) | Méthodologie documentée ; aucune validation scientifique achevée, certification ou exécution publique complète. |
| **NeoMundi × ASRO — Independent Evidence Review, Round 2** | Un reviewer tiers peut-il examiner des artefacts versionnés et scellés tout en préservant la séparation des rôles ? | **E1** · [Fiche de protocole bilingue](./collaborations/asro/independent-evidence-review-round-2.md) · [Dépôt original](https://github.com/neomundi-io/neomundi-asro-round2-protocol) | Protocole actif ; gel final, exécution, dossier scellé et revue indépendante encore ouverts. |

ASRO n’est pas présenté comme organisme certificateur de NeoMundi. La contribution de James/ASRO est limitée ici au périmètre documenté : discipline de preuve, observation de l’état de gouvernance, examinabilité et séparation des autorités.

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
- des chemins synthétiques ou contrôlés sont documentés pour OmarAGI / REVAS, AI Business, VERITAS et Project Petunia × Judicator (OGS) ;
- la séparation architecturale est documentée pour ManChine.

## Ce qui reste non vérifié

Cet index n’établit pas :

- une certification, une conformité réglementaire, une assurabilité ou une fiabilité à l’échelle de la production ;
- une vérité factuelle ou une validité médicale ;
- la supériorité d’un modèle ou d’une technologie partenaire ;
- la reproduction indépendante d’un résultat présenté ;
- un résultat public pour DriftShield ou SEILX ;
- une interopérabilité live achevée pour ManChine, le chemin d’observation réelle de VERITAS ou l’expérience OGS proposée avec de vraies mesures NeoMundi.

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
- [Mark Mocnaj / Project Petunia × Judicator (OGS) — pilote public d’interopérabilité](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot)
- [NeoMundi × ASRO — Runtime Governance Evidence](./collaborations/asro/runtime-governance-evidence.md)
- [NeoMundi × ASRO — Independent Evidence Review, Round 2](./collaborations/asro/independent-evidence-review-round-2.md)

## Infrastructure et programmes de soutien

La démarche indépendante d'observation et de mesure des IA de NeoMundi bénéficie de soutiens en matière d'infrastructure et de programmes d'accompagnement des startups :

- **[Infomaniak](https://www.infomaniak.com/)** — Partenaire infrastructure soutenant le développement de l'instrument indépendant d'observation des IA de NeoMundi.
- **[OVHcloud Startup Program](https://startup.ovhcloud.com/)** — NeoMundi participe au programme d'accompagnement des startups.
- **[NVIDIA Inception](https://www.nvidia.com/en-us/startups/)** — NeoMundi est membre du programme NVIDIA Inception destiné aux startups innovantes.

Ces relations soutiennent le développement de NeoMundi et n'impliquent ni certification ni approbation de ses résultats scientifiques.

## Travailler avec NeoMundi

Un pilote, une collaboration de recherche ou un audit utile commence par une question bornée, des rôles explicites, un protocole reproductible et une formulation claire de ce que les preuves ne permettent pas d’établir.

La proposition devrait préciser :

1. la question pratique et le contexte de décision ;
2. le système ou workflow à observer ;
3. les données disponibles et leurs contraintes de publication ;
4. le niveau de preuve visé et les critères de réussite ;
5. le décideur responsable et les frontières de rôle ;
6. les artefacts susceptibles d’être publiés après le travail.

[Proposer un scénario dans les issues du dépôt](https://github.com/neomundi-io/neomundi-use-cases/issues). Ne publiez ni secret, ni donnée personnelle, ni accord confidentiel, ni archive expérimentale privée.
