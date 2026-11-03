---
title: Journée de lancement de l'UMR CERMICS
---

## Détails

- Date : vendredi 6 novembre 2026
- Lieu : amphi Cauchy (bâtiment principal), École des Ponts, RER A : Noisy-Champs

## Organisateurs

Aurélien Alfonsi, Pierre-Cyril Aubin, Alexandre Ern

## Programme

| Horaire      | Intervenant(e) / Session |
| ------------ | ------------------------ |
| 8h45 - 9h15  | Accueil café |
| 9h15 - 9h35  | Présentation du CERMICS et des invités institutionnels (Gabriel Stoltz) |
| 9h35 - 9h55  | Mots d'introduction de Christophe Besse (CNRS/INSMI), d'Anthony Briant (ENPC), de Jamal Atif (IP Paris) et de Pietro Congedo (Inria) |

### Conférences plénières (10h - 12h25)

| Horaire       | Intervenant(e)                                | Titre    |
| ------------- | --------------------------------------------- | -------- |
| 10h - 10h45   | Claudia d'Ambrosio (CNRS, LIX)                | À venir  |
| 10h50 - 11h35 | Mathieu Rosenbaum (Université Paris Dauphine) | À venir  |
| 11h40 - 12h25 | Greg Pavliotis (Imperial College)             | À venir  |

Déjeuner de 12h30 à 13h45 à la cantine de l'ENPC dans un espace dédié

### Exposés du CERMICS (13h45 - 17h15)

| Horaire       | Intervenant(e)                    | Titre   |
| ------------- | --------------------------------- | ------- |
| 13h45 - 14h15 | Laura Grazioli (recrutement CNRS) | À venir |

#### Session Pôle Optim

| Horaire       | Intervenant(e)                     | Titre |
| ------------- | ---------------------------------- | ----- |
| 14h15 - 14h30 | Axel Parmentier (Permanent)        | À venir |
| 14h30 - 14h45 | Héloïse Gachet (Doctorante)        | À venir |
| 14h45 - 15h00 | François Pacaud (Ancien doctorant) | [Logical constraints in nonlinear programming: the case for complementarity constraints](#pacaud) |

#### Session Pôle Proba

| Horaire       | Intervenant(e)                   | Titre |
| ------------- | -------------------------------- | ----- |
| 15h10 - 15h25 | Andrew McRae (Permanent)         | Random optimization geometry in statistical estimation |
| 15h25 - 15h40 | Paul Invernizzi (Doctorant)      | A study of the reflected kinetic Langevin process |
| 15h40 - 15h55 | Clément Hardy (Ancien doctorant) | Drug discovery as a multi-fidelity, multi-objective Bayesian optimization problem |

Pause café de 15h55 à 16h10

#### Session Pôle MAS

| Horaire       | Intervenant(e)                             | Titre |
| ------------- | ------------------------------------------ | ----- |
| 16h10 - 16h25 | Amaury Hayat (Permanent)                   | À venir |
| 16h25 - 16h40 | Annamaria Massimini (Post-doctorante)      | [Cross-diffusion in multi-component mixtures: From modeling to numerical approximation](#massimini) |
| 16h40 - 16h55 | Jérôme Bonelle (Ancien doctorant)          | [CDO schemes: an EDF–CERMICS collaboration, from mathematics to industrial applications](#bonelle) |
| 16h55 - 17h10 | Geneviève Robin (Ancienne post-doctorante) | À venir |

### Clôture

| Horaire       |                                     |
| ------------- | ----------------------------------- |
| 17h15 - 17h30 | Mots de conclusion par Yves Bréchet |

## Résumés

### François Pacaud {#pacaud}

**Logical constraints in nonlinear programming: the case for complementarity constraints**

Many engineering problems, such as security constrained optimal power flow, contact-rich robotics and market clearing, formulate as nonlinear programs with logical constraints. Unfortunately, the traditional reformulation with binary and integer variables yields mixed integer nonlinear programs (MINLP) that are often intractable for modern optimization solvers. Instead, we formulate the logical conditions with complementarity constraints that keep the combinatorial structure explicit while remaining continuous. We solve the resulting problem with a specialized interior-point method, using the celebrated Scholtes relaxation. We introduce in our new solver CCOpt several regularization methods to address the structural ill-conditioning caused by the combinatorial structure. Our numerical results prove that this new solver is effective at solving recent benchmark problems in robotics, energy markets, and power systems.

[↑ Retour au programme](#programme)

### Annamaria Massimini {#massimini}

**Cross-diffusion in multi-component mixtures: From modeling to numerical approximation**

In multi-component mixtures, diffusion dynamics go beyond the classical Fickian picture, in which each component diffuses down its own concentration gradient.

In this talk, I will first introduce the phenomenon of cross-diffusion, explain why it is interesting and important to study, and discuss the analytical and numerical challenges arising from the nonlinear systems of PDEs describing such processes.

I will then focus on the construction of two structure-preserving finite volume schemes for discretizing two different cross-diffusion systems. The first is a two-point flux approximation (TPFA) scheme for a generalized Poisson–Nernst–Planck system on orthogonal meshes; the second is a hybrid finite volume (HFV) scheme for an anisotropic cross-diffusion system on general meshes.

I will conclude by discussing some open questions and possible directions for future research.

[↑ Retour au programme](#programme)

### Jérôme Bonelle {#bonelle}

**CDO schemes: an EDF–CERMICS collaboration, from mathematics to industrial applications**

Between 2011 and 2020, three CIFRE PhD projects, supervised by Alexandre Ern and supported by EDF, led to the design and analysis of CDO (Compatible Discrete Operators) schemes and their integration into code_saturne, EDF's open-source CFD software. This collaboration between CERMICS and EDF gave rise to a new generation of spatial discretization methods designed to preserve the fundamental structures of the governing equations at the discrete level. These developments are now used in several areas of industrial relevance, including subsurface flows, particularly in the context of the Cigéo project, solidification processes, and turbulent flows in the primary loops of nuclear power plants.

[↑ Retour au programme](#programme)
