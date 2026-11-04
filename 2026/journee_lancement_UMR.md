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

| Horaire       | Intervenant(e)                    | Titre |
| ------------- | --------------------------------- | ----- |
| 10h - 10h45   | Claudia d'Ambrosio (CNRS, LIX)    | [Mixed-integer nonlinear programming](#dambrosio) |
| 10h50 - 11h35 | Thomas Deschatre (EDF)               | [Rainfall is rough](#deschatre) |
| 11h40 - 12h25 | Greg Pavliotis (Imperial College) | [Optimizing Langevin dynamics: from convergence to equilibrium to transport coefficients](#pavliotis) |

Déjeuner de 12h30 à 13h45 à la cantine de l'ENPC dans un espace dédié

### Exposés du CERMICS (13h45 - 17h15)

| Horaire       | Intervenant(e)                    | Titre |
| ------------- | --------------------------------- | ----- |
| 13h45 - 14h15 | Laura Grazioli (recrutement CNRS) | Differential geometry for the calculation of electronic excited states |

#### Session Pôle Optim

| Horaire       | Intervenant(e)                     | Titre |
| ------------- | ---------------------------------- | ----- |
| 14h15 - 14h30 | Axel Parmentier (Permanent)        | À venir |
| 14h30 - 14h45 | Héloïse Gachet (Doctorante)        | [Balanced Assignments of Periodic Tasks](#gachet) |
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
| 16h10 - 16h25 | Amaury Hayat (Permanent)                   | [The place of AI in the practice of mathematics](#hayat) |
| 16h25 - 16h40 | Annamaria Massimini (Post-doctorante)      | [Cross-diffusion in multi-component mixtures: From modeling to numerical approximation](#massimini) |
| 16h40 - 16h55 | Jérôme Bonelle (Ancien doctorant)          | [CDO schemes: an EDF–CERMICS collaboration, from mathematics to industrial applications](#bonelle) |
| 16h55 - 17h10 | Geneviève Robin (Ancienne post-doctorante) | À venir |

### Clôture

| Horaire       |                                     |
| ------------- | ----------------------------------- |
| 17h15 - 17h30 | Mots de conclusion par Yves Bréchet |

## Résumés

### Claudia d'Ambrosio {#dambrosio}

**Mixed-integer nonlinear programming**

Decision-making problems are ubiquitous — in energy systems, logistics, engineering design, and finance — and they often combine a large number of discrete choices with nonlinear constraints and objectives. Linear models and heuristics, though widely used, either oversimplify such problems or provide no guarantee of optimality, and general-purpose solvers often fail to scale. Mixed-integer nonlinear programming (MINLP) offers the right mathematical framework, but its full potential remains locked behind hard combinatorial structure. In this talk, I will present a tailored exact method for a class of MINLP problems, provably converging to a global optimum. I will conclude with perspectives and ongoing work on the topic.

[↑ Retour au programme](#programme)

### Thomas Deschatre {#deschatre}

**Rainfall is rough**

We propose a new approach to model rainfall by combining heterogeneous data sources at different time scales. Continuous arrivals of rain cells are incorporated into a Hawkes process formalism that encompasses the classical Bartlett-Lewis and Neyman-Scott models, thereby providing a more flexible representation of clustering. Analysis of high frequency rainfall data (at the minute scale over several years) indicates that critical Hawkes processes with heavy-tailed power-law kernels yield a superior fit relative to classical models and alternative kernel specifications. Scaling arguments inspired by Jaisson and Rosenbaum (2016) imply that aggregated rainfall at coarse time scales converges to a rough fractional process with Hurst exponent close to zero. This prediction is supported by empirical evidence from low-frequency data (annual observations spanning centuries to millennia), where the Hurst exponent is estimated to lie between 0.01 and 0.1 based on either direct observations from weather stations or proxy reconstructions such as tree-ring records. These results establish a connection between rainfall dynamics and models developed in quantitative finance for market microstructure and volatility. They also provide a new perspective on classical scaling phenomena originally studied by Hurst and Mandelbrot.

[↑ Retour au programme](#programme)

### Greg Pavliotis {#pavliotis}

**Optimizing Langevin dynamics: from convergence to equilibrium to transport coefficients**

In this talk I will give an overview of some of the work that Tony Lelièvre, Gabriel Stoltz and I have done over the last 15 years, together with other colleagues and former and current PhD students, in particular Urbain Vaes. I will first show how non-reversible perturbations accelerate convergence to equilibrium and reduce the asymptotic variance of ergodic averages. I will then discuss how the diffusion coefficient of reversible dynamics can be optimized with respect to the spectral gap, subject to an appropriate constraint. Finally, I will discuss briefly the calculation of transport coefficients, focusing on a kinetic system of weakly interacting diffusions in a periodic potential. We will study its joint mean-field/diffusive limit and compute the diffusion coefficient of the limiting Brownian motion. The effect of phase transitions of the mean-field dynamics on the diffusion coefficient will be elucidated.

[↑ Retour au programme](#programme)

### Héloïse Gachet {#gachet}

**Balanced Assignments of Periodic Tasks**

We address the problem of assigning periodic tasks to workers in a balanced way, i.e., so that each worker performs every task with the same frequency over the long term. Given a list of tasks to be repeated weekly at fixed times and a number of indistinguishable workers, we establish a necessary and sufficient condition for the existence of a balanced assignment when the sole constraint is that no worker performs two tasks simultaneously. Additional periodicity and complexity results are also established for this basic version. In the extended version, additional constraints can be introduced, such as a limit on the total number of working hours per week. For this extended version, it is demonstrated that whenever a balanced assignment exists, a periodic balanced assignment exists as well.

[↑ Retour au programme](#programme)

### François Pacaud {#pacaud}

**Logical constraints in nonlinear programming: the case for complementarity constraints**

Many engineering problems, such as security constrained optimal power flow, contact-rich robotics and market clearing, formulate as nonlinear programs with logical constraints. Unfortunately, the traditional reformulation with binary and integer variables yields mixed integer nonlinear programs (MINLP) that are often intractable for modern optimization solvers. Instead, we formulate the logical conditions with complementarity constraints that keep the combinatorial structure explicit while remaining continuous. We solve the resulting problem with a specialized interior-point method, using the celebrated Scholtes relaxation. We introduce in our new solver CCOpt several regularization methods to address the structural ill-conditioning caused by the combinatorial structure. Our numerical results prove that this new solver is effective at solving recent benchmark problems in robotics, energy markets, and power systems.

[↑ Retour au programme](#programme)

### Amaury Hayat {#hayat}

**The place of AI in the practice of mathematics**

AI capabilities in mathematics have seen impressive progress over the last few years. This talk will review how we got there, looking beyond the recent AI-generated results in mathematics, and what the next steps could be.

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

Between 2011 and 2020, three CIFRE PhD projects, supervised by Alexandre Ern and supported by EDF, led to the design and analysis of CDO (Compatible Discrete Operators) schemes and their integration into code_saturne, EDF's open-source CFD software. This collaboration between CERMICS and EDF gave rise to a new generation of spatial discretization methods designed to preserve the fundamental structures of the governing equations at the discrete level. These developments are now used in several areas of industrial relevance, including subsurface flows, particularly in the context of the Cigéo deep geological repository for radioactive waste, solidification processes, and turbulent flows in the primary loops of nuclear power plants.

[↑ Retour au programme](#programme)
