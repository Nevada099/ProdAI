# 🎓 Cahier des charges — Programme PROD'AI Academy (Qualiopi)
### 14 septembre 2026 · structure reprise du programme brAIn (10 modules), contenu 100% PROD'AI / immobilier

> **Source de la structure :** [`06-RECHERCHE-ET-BENCHMARKS/BrAIn-case-study/FICHE-BRAIN-ECOSYSTEME.md`](../06-RECHERCHE-ET-BENCHMARKS/BrAIn-case-study/FICHE-BRAIN-ECOSYSTEME.md) — brAIn structure son "Protocole" en 10 modules qui suivent le cycle de vie complet d'une agence naissante (positionnement → compétence → diagnostic client → automatisation → offre → acquisition → scale). **On reprend cette progression, jamais le contenu** : chaque module ci-dessous est rempli avec la matière déjà existante dans ce repo (templates, offres, grille tarifaire), pas avec du contenu générique.
>
> **Où ça s'insère :** ce programme est la version formalisée, finançable OPCO, de l'**OFFRE B — Formation** décrite dans [`02-OFFRES-ET-SERVICES/OFFRE-Agence-et-Formation.md`](../02-OFFRES-ET-SERVICES/OFFRE-Agence-et-Formation.md) et tarifée dans [`02-OFFRES-ET-SERVICES/GRILLE-TARIFAIRE-MASTER-PRODAI.md`](../02-OFFRES-ET-SERVICES/GRILLE-TARIFAIRE-MASTER-PRODAI.md) (§8 — PROD'AI Academy).
>
> **Statut : PROPOSITION à valider par Katerina** avant tout dépôt Qualiopi / dossier OPCO — rien ici n'est encore un programme déposé.

---

## 1. Ce qu'on garde de brAIn, ce qu'on change

| | brAIn (générique, toutes verticales) | PROD'AI Academy (immobilier) |
|---|---|---|
| Progression | positionnement → compétence → diagnostic → référent → automatisation → agents → outil quotidien → offre → leads → scale | **identique** |
| Nombre de modules | 10 | **10** |
| Prérequis technique | aucun | **aucun** (même promesse : cible = agents/directeurs d'agence, pas des développeurs) |
| Contenu | générique, multi-secteurs | **100% immobilier** : listings, visites virtuelles, CRM agence, réseaux (Century 21, Orpi, IAD…) |
| Preuve | missions de l'agence mère brAIn | **cas Cherpantier, Bubble, Bouygues/Emerige** (déjà dans `03-CAS-ET-PREUVES/`) |
| Financement | non mentionné | **Qualiopi → OPCO**, argument que brAIn n'a pas |

---

## 2. Le programme — 10 modules

| # | Module brAIn (référence structure) | Module PROD'AI Academy | Contenu source déjà existant à réutiliser |
|---|---|---|---|
| 1 | Bases IA et positionnement stratégique | **Bases IA appliquées à l'immobilier** — panorama des usages concrets (visuel, texte, vidéo, automatisation), se positionner comme référent IA dans son agence ou son réseau | `07-CONCEPT-ANALYSE.md` (JTBD, douleurs immo) |
| 2 | Expertise opérationnelle (prompt engineering, automatisation) | **Créer ses premiers visuels et vidéos IA** — prompt engineering pour listings, visuels (NanoBanana/Midjourney), vidéo (Kling/Seedance), voix off | Template Reel listing 30s, template visite virtuelle (`ROADMAP-PRODAI-33-ACTIONS.md` Phase 3) |
| 3 | Identifier les besoins entreprise et audit IA | **Diagnostiquer une agence immobilière** — grille d'audit IA (15 questions), identifier les quick wins | Template "audit IA pour agence immo" déjà prévu (Phase 3, tâche 🧠) |
| 4 | Devenir Référent/Formateur IA | **Devenir le référent IA de son agence ou réseau** — présenter l'IA en interne, lever les résistances (image de marque, juridique, éthique) | à créer — nouveau contenu, aucune source existante |
| 5 | Expert automatisation (n8n, workflows sectoriels) | **Automatiser son activité avec n8n** — check-in Airbnb/Booking, relance acquéreur, CRM, alertes | Système de check-in existant, workflows JobsAI/Booking déjà en prod |
| 6 | Agents IA 2.0 (agents spécialisés, orchestration) | **Agents IA appliqués à l'immobilier** — agent de qualification de leads, agent de réponse DM Instagram, orchestration multi-agents pour une agence | Template réponse commentaire Instagram (ChatPlace), Phase 3 |
| 7 | Claude Code/Cowork (cerveau opérationnel) | **Claude Code / Cowork comme assistant quotidien** — organiser son activité, automatiser sa veille, produire du contenu en continu | Méthode de travail de Katerina elle-même (à documenter — bon candidat pour un module "vécu") |
| 8 | Offre high-ticket (packaging, prix, closing) | **Construire et vendre son offre IA immobilier** — packaging, tarifs, closing | `GRILLE-TARIFAIRE-MASTER-PRODAI.md` directement réutilisable comme étude de cas |
| 9 | Génération de leads (Instagram, LinkedIn, Lemlist, Meta Ads) | **Générer des leads pour son activité IA immobilier** — LinkedIn B2B, Instagram, outbound ciblé agences/réseaux | Phase 4 de la roadmap (SEO, LinkedIn, Meta Ads, outbound) |
| 10 | Scaler son agence (closing B2B, branding, site web) | **Présenter son offre à un réseau ou une franchise** — argument Qualiopi/OPCO comme levier de vente B2B | Partenariats réseaux immo déjà identifiés (Century 21, Orpi, IAD — Phase 4) |

**Modules à construire en priorité** (aucune matière existante) : **4** (référent IA en interne) et **7** (méthode Claude Code documentée) — les 8 autres partent d'un actif déjà produit dans ce repo, donc coût de création plus faible.

---

## 3. Squelette Qualiopi — à compléter module par module

Qualiopi exige, pour chaque module, un **objectif pédagogique mesurable**, pas juste un titre. Gabarit à remplir avant tout dépôt :

| Champ | Exemple (module 3) |
|---|---|
| **Objectif pédagogique** | « À l'issue du module, le stagiaire est capable de remplir une grille d'audit IA en 15 points sur sa propre agence et d'en tirer 3 priorités d'action » |
| **Public visé / prérequis** | Agents et directeurs d'agence immobilière, aucun prérequis technique |
| **Modalité** | Distanciel asynchrone (vidéo) + exercice pratique noté |
| **Durée indicative** | 2h contenu + 1h exercice |
| **Modalité d'évaluation** | Grille d'audit complétée et corrigée, quiz de validation |
| **Moyens pédagogiques** | Vidéo HD, support téléchargeable (grille PDF), correction type |

À dupliquer pour les 10 modules avant tout dossier. Autres briques Qualiopi transverses à ne pas oublier (statut : à faire, hors périmètre de ce document) :
- Positionnement pré-formation (test de niveau/attentes à l'entrée)
- Évaluation finale + attestation de fin de formation
- Enquête de satisfaction stagiaires
- Modalités d'accessibilité (référent handicap)
- Feuilles d'émargement / preuve d'exécution si présentiel ou visio synchrone

---

## 4. Formats et durée — alignés sur l'offre déjà tarifée

D'après `GRILLE-TARIFAIRE-MASTER-PRODAI.md` §8, deux formats existent déjà :

| Format | Durée totale suggérée | Prix (déjà validé dans la grille) |
|---|---|---|
| **Cours en ligne / cohorte individuelle** | 10 modules en asynchrone, ~20-25h de contenu total (vs 70h+ chez brAIn — volontairement plus court, plus dense, sans dilution) | 490-990 € |
| **Atelier / formation d'équipe** (éligible OPCO) | Format condensé, présentiel ou visio synchrone, 1-2 jours | 1 200-3 000 €/session |

**Différence assumée avec brAIn** : brAIn vend 70h+ de contenu généraliste. PROD'AI n'a pas besoin de ce volume — la spécialisation immobilière permet d'aller plus vite à l'essentiel. Le programme condensé est un argument de vente, pas un manque.

---

## 5. Ce qu'il ne faut pas copier de brAIn ici

- **Ne pas viser 70h+ de contenu** — dilue le message, coûte cher à produire seule. Rester sur un format court et dense.
- **Ne pas ouvrir de "Sharing" (leads partagés) dans la formation elle-même** — cf. `ROADMAP-PRODAI-33-ACTIONS.md` Phase 5 : le lead sharing se fait via un petit cercle fermé (15-20 pros), pas via la formation.
- **Ne pas promettre de résultat financier chiffré** ("vivre de l'IA en 60 jours") — rester sur des objectifs pédagogiques vérifiables (cf. §3), plus défendable devant un OPCO et plus honnête.

---

## 6. Prochaines actions

1. Katerina valide la liste des 10 modules (§2) et leurs titres définitifs.
2. Remplir le gabarit Qualiopi (§3) pour chacun — commencer par les modules déjà sourcés (1, 2, 3, 5, 6, 8, 9, 10).
3. Produire le contenu des 2 modules sans source existante (4 et 7).
4. Router ce programme dans le dossier de certification Qualiopi existant (`Dropbox/QUALIOPI/`) une fois les modules figés.

---

*Lié à : `06-RECHERCHE-ET-BENCHMARKS/BrAIn-case-study/` (structure source) · `02-OFFRES-ET-SERVICES/OFFRE-Agence-et-Formation.md` (positionnement Offre B) · `02-OFFRES-ET-SERVICES/GRILLE-TARIFAIRE-MASTER-PRODAI.md` §8 (prix) · `07-SYSTEMES-ET-PROCESS/` (templates à transformer en modules).*
