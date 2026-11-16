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

### 1. Comment auditer les actions d'un agent IA ?

**Problème :** un agent prend des engagements ou déclare des actions. Comment comparer ses propos aux opérations enregistrées ?

- **AI Business / Express Test Purchase — référence contrôlée :** trois achats tests contrôlés, dont des reçus conformes et volontairement défectueux. **E2**, environnement synthétique ; aucun résultat de souscription ou d'assurance n'est revendiqué. [Examiner les preuves](https://github.com/neomundi-io/use-case-aibusiness-runtime-conformity).
- **Sergei Ponomarev / AI Business — étude en cours :** mesure indépendante des réponses pour alimenter une comparaison distincte entre promesses, dialogue et journal d'exécution. Série du **6 novembre au 5 décembre 2026**, **E0** ; résultats et identités des modèles encore non publiés. [Voir le protocole public](https://github.com/sergeiperm81-ux/ai-test-purchase).

**Valeur :** distinguer les observations de l'autorité chargée de juger l'exécution réelle de l'agent.

### 2. Comment contrôler l'exécution d'agents sans confondre mesure et permission ?

**Problème :** des mesures peuvent éclairer une politique, sans devenir elles-mêmes une autorisation d'exécution.

- **OASSE / FAM / Gatekeeper :** campagnes contrôlées de **1 000 et 60 requêtes**, séparant mesure, politique déterministe et traitement opérationnel. **E3** dans ce périmètre. Les historiques ALLOW/FLAG sont des classifications de mesure, pas des permissions d'exécution. [Consulter l'étude](https://github.com/neomundi-io/use-case-oasse-runtime-governance).
- **ManChine / RGE-01, REB-01, RiCo-01 :** architecture publique pour l'admissibilité pré-action, la frontière d'exécution et sa continuité. **E1** ; validation machine-à-machine complète en attente. [Consulter l'architecture](https://github.com/neomundi-io/use-case-rico-observation-to-admissibility).

**Valeur :** conserver des responsabilités séparées entre mesure, politique et décision opérationnelle.

### 3. Comment reconstruire et vérifier une preuve après une interaction IA ?

**Problème :** une réponse contestée ou un audit exige des enregistrements examinables, pas seulement un compte rendu.

- **FactNotebook :** **cinq cas PubMedQA** instrumentés, puis reconstruits par le partenaire. **E3** dans ce périmètre ; moteur de reconstruction non public, aucune vérité médicale établie. [Pilote NeoMundi](https://github.com/neomundi-io/use-case-factnotebook-pubmedqa) · [Reconstruction partenaire](https://github.com/factnotebook/public-reconstructions/tree/main/FN-NEOMUNDI-CTPUBMEDQA-001).
- **Mark Mocnaj / Project Petunia × Judicator (OGS) :** cinq payloads **synthétiques** d'interopérabilité et reçus liés aux payloads ; le replay déterministe interne a reproduit les cinq classifications. **E2** ; aucune action externe autorisée, aucune mesure réelle NeoMundi en production. [Étude publique d'interopérabilité](https://github.com/UmjetnaInteligencija/ogs-neomundi-public-interoperability-pilot).

**Valeur :** examiner ce que les preuves étayent réellement, avec intégrité et provenance explicites.

### 4. Comment vérifier qu'un assistant IA s'améliore ?

**Problème :** un assistant RAG a été corrigé. Comment comparer les résultats observables dans un protocole défini ?

- **Kabbalah App / RAG Test Bench :** **60 générations instrumentées par manche** ; alertes rapportées passant de **45/60 à 1/60** après correction. **E3** pour ce test borné. Banc d'essai, données brutes et correspondances de notation privés. [Synthèse publique](evidence/kabbalah-app-rag/README_FR.md).

**Valeur :** documenter les changements observés plutôt que se fier aux impressions.

---

## Aller plus loin sans alourdir la lecture

- [Catalogue technique complet — 12 entrées pilotes, statuts, niveaux de preuve et revues indépendantes](CATALOG_FR.md)
- [API de mesure](https://github.com/neomundi-io/neomundi-runtime-measurement) · [Station](https://github.com/neomundi-io/neomundi-station-public) · [Vérification Evidence](https://github.com/neomundi-io/neomundi-evidence-gateway)
- [Architecture produit NeoMundi](https://github.com/neomundi-io/.github/blob/main/docs/PRODUCT_ARCHITECTURE.md)

Ces cas sont des **démonstrations bornées et des pilotes de recherche**, et non des certifications, preuves de fiabilité générale ou preuves de conformité réglementaire. Chaque protocole lié définit sa couverture et ses limites.

## Et dans votre organisation ?

**[Explorer la démo](https://neomundi.io/fr/demonstration/)** · **[Étudier un déploiement](https://neomundi.io/fr/contact/)**
