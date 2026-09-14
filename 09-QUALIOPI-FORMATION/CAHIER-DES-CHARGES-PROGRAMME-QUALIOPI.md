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

## 3. Squelette Qualiopi — rempli pour les 10 modules

Qualiopi exige, pour chaque module, un **objectif pédagogique mesurable**, pas juste un titre. Chaque ligne respecte le garde-fou de [`FAISABILITE-TECHNIQUE.md`](../02-OFFRES-ET-SERVICES/FAISABILITE-TECHNIQUE.md) : **on enseigne du supervisé et du borné, jamais de l'« autonome » ou du « 24/7 » sans preuve** — donc les objectifs pédagogiques des modules 5-7 (automatisation, agents) parlent de « configurer avec supervision », pas de « rendre autonome ».

| # | Objectif pédagogique | Modalité | Durée | Évaluation |
|---|---|---|---|---|
| 1 | Identifier 3 usages concrets de l'IA applicables à sa propre agence et formuler sa légitimité de référent IA en interne | Distanciel asynchrone (vidéo) | 1h30 | Questionnaire de positionnement complété |
| 2 | Produire un visuel et une vidéo courte IA à partir d'un listing réel, en respectant un gabarit de prompt fourni | Distanciel asynchrone + exercice pratique | 2h contenu + 1h30 exercice | Livrable rendu (1 visuel + 1 vidéo) noté sur grille |
| 3 | Remplir une grille d'audit IA en 15 points sur sa propre agence et en tirer 3 priorités d'action | Distanciel asynchrone + exercice pratique noté | 2h contenu + 1h exercice | Grille d'audit complétée et corrigée |
| 4 | Préparer une présentation interne de l'IA à son agence/réseau et anticiper 3 objections (image de marque, juridique, éthique) | Distanciel asynchrone + étude de cas | 1h30 | Plan de présentation évalué par grille |
| 5 | Configurer, **avec supervision**, une automatisation n8n simple (relance, alerte ou classement) sur son propre cas d'usage | Distanciel asynchrone + atelier pratique guidé | 2h contenu + 2h atelier | Workflow n8n fonctionnel démontré |
| 6 | Décrire le périmètre borné d'un agent IA (qualification de leads ou réponse DM) et ses limites de supervision obligatoires | Distanciel asynchrone + étude de cas | 1h30 | Quiz de validation + cas pratique commenté |
| 7 | Utiliser Claude Code/Cowork pour organiser une tâche récurrente de son activité (veille, contenu) | Distanciel asynchrone + démonstration commentée | 1h30 | Restitution d'un cas d'usage personnel |
| 8 | Construire une grille tarifaire pour sa propre offre IA immobilier et simuler un argumentaire de closing | Distanciel asynchrone + jeu de rôle (si atelier équipe) | 2h | Grille tarifaire personnelle produite |
| 9 | Rédiger une séquence de prospection ciblée (LinkedIn/outbound) pour son activité IA immobilier | Distanciel asynchrone + exercice pratique | 1h30 | Séquence de 3 messages rédigée et corrigée |
| 10 | Préparer un argumentaire de présentation à un réseau/franchise incluant l'argument de financement Qualiopi/OPCO | Distanciel asynchrone + étude de cas | 1h30 | Argumentaire évalué par grille |

**Total programme** : ~19h de contenu + exercices — cohérent avec le format « cours en ligne » de la grille tarifaire (490-990 €, §4) et volontairement loin des 70h+ de brAIn (cf. §5).

---

## 3bis. Briques Qualiopi transverses (hors modules, obligatoires pour le dépôt)

| Brique | Ce que c'est concrètement | Qui la porte | Statut |
|---|---|---|---|
| **Positionnement pré-formation** | Questionnaire court (attentes, niveau de départ) envoyé avant le premier module | Katerina — formulaire Notion/Typeform | 🔴 à créer |
| **Évaluation finale** | Livrable de synthèse : le stagiaire présente son plan d'action IA immobilier à 90 jours, construit à partir des 10 livrables de modules | Katerina — grille de correction à écrire | 🔴 à créer |
| **Attestation de fin de formation** | Document généré automatiquement à la validation de l'évaluation finale | Katerina — modèle à préparer une fois | 🔴 à créer |
| **Enquête de satisfaction stagiaires** | Formulaire envoyé à J+7 après la fin | Katerina — Typeform/Google Form | 🔴 à créer |
| **Référent handicap** | Personne identifiée + modalités d'adaptation (rythme, support alternatif) | Katerina elle-même, en solo, avec un protocole écrit d'adaptation | 🔴 à formaliser |
| **Feuilles d'émargement** | Uniquement nécessaires pour les sessions synchrones (atelier d'équipe présentiel/visio) — pas pour le cours asynchrone individuel | Katerina | 🟡 à créer, format atelier seulement |

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

## 6. Plateforme &amp; outils — rester léger, pas de LMS lourd

Cohérent avec le budget "outils" déjà posé dans [`10-PITCH-INVESTISSEUR/PITCH-INVESTISSEUR.html`](../10-PITCH-INVESTISSEUR/PITCH-INVESTISSEUR.html) (2 400-4 800 €/an) et avec l'inspection technique de brAIn (le vrai coût est dans la plateforme membre, pas la vitrine) :

| Besoin | Outil recommandé | Pourquoi |
|---|---|---|
| Hébergement des modules (vidéo + supports) | Notion (pages par module) + vidéos hébergées Loom ou Vimeo privé | Pas de développement, coût quasi nul, éditable seule |
| Suivi des stagiaires (positionnement, livrables, évaluation finale) | Airtable — une ligne par stagiaire | Déjà dans la stack recommandée pour la Library de templates (réutilisation d'outil) |
| Format "atelier d'équipe" (synchrone) | Visio (Zoom/Meet) + feuille d'émargement Airtable | Seul format nécessitant une preuve d'exécution en temps réel |
| Questionnaires (positionnement, satisfaction) | Typeform ou Google Form | Gratuit ou quasi, suffisant au volume actuel |
| Communauté / cohorte (si plusieurs stagiaires en même temps) | Groupe fermé Telegram/WhatsApp — **pas de Skool** | Cohérent avec la décision déjà prise (cf. `ROADMAP-PRODAI-33-ACTIONS.md` Phase 5) : un outil dédié type Skool est trop énergivore pour le volume actuel |

**Ne pas construire de plateforme sur-mesure** — chaque outil ci-dessus existe déjà dans la stack de Katerina ou coûte moins de 20 €/mois.

---

## 7. Équipe pédagogique

En solo, Qualiopi n'impose pas une équipe pédagogique nombreuse, mais exige des **rôles identifiés**, même portés par une seule personne :

| Rôle Qualiopi | Qui | Remarque |
|---|---|---|
| Formatrice / conceptrice du programme | Katerina | Rôle principal |
| Référent pédagogique | Katerina | À déclarer explicitement dans le dossier, même en solo |
| Référent handicap | Katerina | Avec un protocole écrit d'adaptation (cf. §3bis) — pas besoin d'une personne dédiée à ce volume |
| Correction des évaluations | Katerina | Pas d'obligation d'évaluateur externe à ce stade |

**Point de vigilance** : la contrainte "solo ou +1 assistant" du plan maître (`00-PLAN-MAITRE.md`) s'applique aussi ici — si le nombre de stagiaires dépasse ce qu'une personne peut corriger/accompagner, prévoir un assistant pédagogique avant de scaler, pas après.

---

## 8. Calendrier de déploiement — aligné sur le MVP 90 jours

Reprend directement le calendrier déjà posé dans `10-PITCH-INVESTISSEUR/PITCH-INVESTISSEUR.html` §06 :

| Période | Action formation |
|---|---|
| Semaines 1-4 | Finaliser les 8 modules déjà sourcés (1, 2, 3, 5, 6, 8, 9, 10) — contenu vidéo + supports |
| Semaines 4-6 | Produire les 2 modules sans source existante (4 — référent IA interne, 7 — méthode Claude Code) |
| Semaines 6-8 | Créer les briques transverses (§3bis) : positionnement, évaluation finale, attestation, enquête satisfaction |
| Semaines 8-10 | Monter le dossier de dépôt Qualiopi pour ce nouveau programme (dans `Dropbox/QUALIOPI/`) |
| Semaines 10-12 | Premier test du programme sur 1-2 stagiaires pilotes avant ouverture officielle |

---

## 9. Checklist finale avant dépôt Qualiopi

- [ ] Les 10 modules ont un objectif pédagogique mesurable rempli (§3)
- [ ] Les briques transverses existent (positionnement, évaluation finale, attestation, satisfaction, référent handicap) (§3bis)
- [ ] Le format et la durée sont cohérents avec le prix affiché (§4)
- [ ] Aucune promesse "autonome" ou de résultat financier chiffré dans les supports (§5)
- [ ] Le programme est routé dans le dossier de certification existant (`Dropbox/QUALIOPI/`)
- [ ] Un test pilote (1-2 stagiaires) a été fait avant l'ouverture officielle

---

## 10. Prochaines actions

1. Katerina valide la liste des 10 modules (§2) et les objectifs pédagogiques (§3).
2. Produire le contenu des 2 modules sans source existante (4 et 7) — le reste part d'un actif déjà produit.
3. Créer les briques transverses (§3bis) — aucune n'existe encore.
4. Router ce programme dans le dossier de certification Qualiopi existant (`Dropbox/QUALIOPI/`) une fois les modules figés.
5. Tester sur 1-2 stagiaires pilotes avant ouverture officielle (§8).

---

*Lié à : `06-RECHERCHE-ET-BENCHMARKS/BrAIn-case-study/` (structure source) · `02-OFFRES-ET-SERVICES/OFFRE-Agence-et-Formation.md` (positionnement Offre B) · `02-OFFRES-ET-SERVICES/GRILLE-TARIFAIRE-MASTER-PRODAI.md` §8 (prix) · `02-OFFRES-ET-SERVICES/FAISABILITE-TECHNIQUE.md` (garde-fous respectés en §3) · `10-PITCH-INVESTISSEUR/` (calendrier et budget) · `07-SYSTEMES-ET-PROCESS/` (templates à transformer en modules).*
