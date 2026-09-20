[English](./README.md) · [Index des cas d’usage](../../README_FR.md)

# Kabbalah App × NeoMundi — Preuve de détection runtime RAG

**Statut: Validated field test**

## Contexte

Kabbalah App a évalué un banc d’essai RAG hébreu–français orienté production. L’étude date du 23 août 2026 ; le rapport public autorisé est daté du 20 septembre 2026. Son corpus comprend 2 633 passages alignés, indexés dans les deux langues.

NeoMundi Continuous Control Launcher a instrumenté les mesures runtime. Les métriques de retrieval, la notation de génération à l’aveugle, le diagnostic, les corrections, le choix des fournisseurs et les décisions opérationnelles sont restés du ressort de l’application et de ses évaluateurs.

## Protocole

Le retrieval et la génération ont été évalués séparément ; le moteur de retrieval a été sélectionné avant l’évaluation de génération. Le jeu de retrieval comprenait 99 questions synthétiques difficiles, avec sept questions réelles anonymisées utilisées uniquement comme témoin limité. Aucun contenu de question n’est reproduit ici.

L’évaluation de génération portait sur 30 questions et deux candidats, soit **60 générations instrumentées** dans une manche, avec le même contexte retrouvé, une présentation randomisée et une notation à l’aveugle. Le rapport compare v1 et v2 avec un dénominateur de 60 pour chaque manche ; il ne s’agit pas de 60 questions utilisateur distinctes.

Le signal runtime a révélé la dégradation avant que l’investigation humaine identifie des instructions de prompt contradictoires et des variables de gabarit non substituées. La manche défectueuse a été invalidée pour la comparaison des modèles. Après correction, une autre manche rapportée a montré moins d’alertes et une stabilité accrue.

## Observations documentées

| Mesure | Avant correction (v1) | Après correction (v2) |
| --- | --- | --- |
| Générations instrumentées, dénominateur par manche | 60 | 60 |
| Alertes d’hallucination rapportées | 45/60 | 1/60 |
| Stabilité moyenne, plage rapportée | 0.68–0.77 | 0.915–0.923 |

Les plages de stabilité sont reprises telles que rapportées, sans être interprétées comme des intervalles de confiance. Les alertes sont des signaux de mesure, pas des taux d’erreurs factuelles établis indépendamment.

## Claim admissible

> Dans ce banc d’essai RAG, le signal runtime NeoMundi a détecté une dégradation réelle avant que sa cause technique soit identifiée, puis a reflété le retour à un comportement plus stable après correction.

Formulation anglaise canonique :

> In this RAG test bench, the NeoMundi runtime signal detected a real degradation before its technical cause was identified, then reflected the return to more stable behavior after correction.

## Limites

- Les observations sont propres à ce corpus, à ce protocole, aux versions de modèles et aux conditions de mesure ; elles ne constituent ni certification générale du RAG ni garantie de vérité factuelle.
- NeoMundi n’a pas déterminé quel modèle concurrent était le meilleur. Un composant d’évaluation appartenait à une famille de modèles incluse dans la comparaison : le signal ne peut donc pas arbitrer seul entre fournisseurs.
- La longueur des réponses affectait la qualité de génération perçue ; le témoin de sept questions réelles n’est pas une base statistique autonome. Un candidat de retrieval n’a pas pu être mesuré en raison d’une limite fournisseur.
- Le rapport relève des contraintes d’intégration liées aux prompts longs et à la latence. Les détails de sécurité et d’implémentation restent hors de ce dossier public.
- Les mesures runtime complètent la vérité terrain métier et l’évaluation humaine ; interprétation, politiques, décisions et actions restent externes à NeoMundi.
- Ce dépôt fournit un rapport public, pas le harnais privé, les questions brutes, les correspondances de notation à l’aveugle ni un ensemble exécutable de reproduction.

## Preuve publique

[Lire le rapport public autorisé en français](./NEOMUNDI_KABBALAH_APP_RAG_PUBLIC_EVIDENCE_REPORT_FR.pdf) — notamment le protocole (page 3), la manche invalidée (page 5), les observations runtime (page 6) et les limites (page 8).

Le PDF est copié sans modification. Le rapport indique que sa publication est autorisée par le porteur du projet Kabbalah App. Aucune question utilisateur brute, donnée personnelle, clé, adresse privée, code sensible ou artefact d’infrastructure réservé ne l’accompagne.
