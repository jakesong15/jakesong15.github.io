---
title: "Confined polymer physics"
excerpt: "<img src='/images/500x300.png'><br/>I developed and used coarse-grained models for polymers to study their mechanics under nanoscale confinement."
collection: research
---

In many modern electronics and structural materials, polymers are often confined to nanoscopic dimensions, which change their mechanical properties relative to bulk conditions. These confinement effects can arise due to changes in chain mobility – whereas free surfaces (for instance in thin films) can accelerate chain mobility and soften the polymer matrix, substrates and fillers (for instance in nanocomposites) can decelerate chain mobility and stiffen the polymer matrix. In the [Keten group](https://keten-group.northwestern.edu/) at Northwestern, I used molecular dynamics simulations to study the extent and length-scale of such nanoconfinement effects in common industrial polymers.

Coarse-grained modeling
======

Nanoconfinement effects can occur over tens of nanometers, which can be challenging to simulate using conventional atomistic simulation techniques. An approach to circumvent this problem is to utilize coarse-grained models that reduce the structural degrees-of-freedom, which allows tractable simulations of materials which are hundreds of nanometers in size. However, such coarse-graining methods will necessarily result in inaccurate dynamical properties relative to atomistic systems. To address this problem. [Wenjie Xia](https://faculty.sites.iastate.edu/wxia/) and I developed a coarse-graining algorithm for polymers in which the interaction potential of the coarse-grained model is “renormalized” to the atomistic model based on their glassy dynamics and cage mobility. We successfully developed models for the thermoplastic polystryrene[1], the rubbery polymer polybutadiene[2], and molecular glass forming liquid ortho-terphenyl[3]. <img src='/images/500x300.png'><br/>Representative coarse-grained images of polybutadiene and polystyrene, taken from Song et al [2].

Nanoconfinement effects on chain mobility
======

Next, using these models, we studied the dynamics of polymers under different confinement effects arising from free surfaces, polymeric substrates, and rigid substrates and fillers. We demonstrated that polymer architecture can play a significant role in the nanoconfinement effect, as polymers with bulkier side-chains undergo a greater increase in chain mobility under free-surface confinement[4], but a smaller decrease in chain mobility under substrate confinement[5]. We also demonstrated that a large interphase region can exist when both of these polymers form a soft interface with each other[6]. <img src='/images/500x300.png'><br/>Representative free-standing thin film configurations, taken from Hsu et al [4].

Nanomechanical characterization
======

Lastly, we used these models to study the nanoscale mechanical response of substrate and filler-confined thin films using indentation – a common experimental approach to quantify the interphase length-scale. We showed that indentation techniques can overestimate the interphase length-scale due to the stress field propagation arising from the indentation[7], an effect which can be exacerbated at elevated temperatures due to viscous flow at higher temperatures[8]. <img src='/images/500x300.png'><br/>Illustration of our nanoindentation study on the front cover of Soft Matter, taken from Song et al [8].
