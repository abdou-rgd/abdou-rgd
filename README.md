### Abdallah Ragued

Pharmacometrics and health data science. Master's in pharmacokinetic modelling at Université Paris Cité (PBPK, PK/PD, population PK), after a Master's in health data science at Université Paris-Saclay (biostatistics, machine learning, causal inference). Looking for a PhD at the meeting point of DMPK and AI.

**Recently.** Six months as a pharmacometrics intern at Sanofi R&D (Montpellier): evaluation and optimisation of population PK trial designs with Fisher information methods in NONMEM 7.5.1 (`$DESIGN`), benchmarked against clinical trial simulations, and an R/Shiny application (13 modules, 123 unit tests) to post-process and compare design outputs. Presented at the Congrès Junior Pluridisciplinaire (Paris-Saclay and ENS, May 2026; one of three awards among 53 talks) and as a poster at the DMDG-GMP-SPS joint meeting (October 2026).

**Building, in the open.** Officina, a local, verifiable DMPK toolchain on one consumer PC. In one sentence: an open, deterministic and verified pharmacokinetic engine, with a local assistant that never computes a number itself.

- [Caladrius](https://github.com/abdou-rgd/caladrius): a pharmacokinetic engine in Rust (NCA, one- and two-compartment models, weighted least-squares fitting, a desktop UI that also runs in the browser, CLI, MCP server). Every number is checked against independent calculations (PKNCA, R `nls`, 256-bit closed forms): 48,955 of 48,955 expected values at stated tolerances, and a validation section that says what is not covered.
- [Apothicaire](https://github.com/abdou-rgd/apothicaire): a local AI assistant (a 27B ternary model on a 12 GB card) that calls Caladrius and is not allowed to compute a number itself; a deterministic gate flags any number not traceable to a tool result (one regeneration, then a visible marker). Benchmark of 25 simulated exercises, in-sample: 76 of 932 numbers in first drafts not traceable with six tools, 0 of 926 after the engine gained a compare command.
- [OptChat](https://github.com/abdou-rgd/optchat): the assistant's memory, an endless chat kept as a tree of summary lines on disk (after Victor Taelin's idea), recall measured 8/8, 7/8 and 8/8 over three runs on the local model.

**Tools I use.** R (Shiny, tidyverse, testthat), Python, Julia (Pumas), NONMEM and PsN, Rust (with AI coding agents under a written contract), Git and Linux.

**Interests.** Optimal design, model-informed drug development, local AI and small decision models, reproducible numerical software.

French (native), English (C1). Paris.
