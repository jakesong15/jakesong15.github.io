---
title: <div align="center">Confined polymer physics</div>
excerpt: "<img src='/images/toc_cg.png'><br/>I developed and used coarse-grained models for polymers to study their mechanics under nanoscale confinement."
collection: research
---

In many modern electronics and structural materials, polymers are often confined to nanoscopic dimensions, which change their mechanical properties relative to bulk conditions. These confinement effects can arise due to changes in chain mobility – whereas free surfaces (for instance in thin films) can accelerate chain mobility and soften the polymer matrix, substrates and fillers (for instance in nanocomposites) can decelerate chain mobility and stiffen the polymer matrix. In the [Keten group](https://keten-group.northwestern.edu/) at Northwestern, I used molecular dynamics simulations to study the extent and length-scale of such nanoconfinement effects in common industrial polymers.

Coarse-grained modeling
------

Nanoconfinement effects can occur over tens of nanometers, which is beyond the length-scale accessible using conventional atomistic simulation techniques. An approach to circumvent this problem is to utilize coarse-grained models that reduce the structural degrees-of-freedom, which allows tractable simulations of materials which are hundreds of nanometers in size. However, such coarse-graining methods will necessarily result in inaccurate dynamical properties relative to atomistic systems. To address this problem. [Wenjie Xia](https://faculty.sites.iastate.edu/wxia/) and I developed a coarse-graining algorithm for polymers in which the interaction potential of the coarse-grained model is “renormalized” to the atomistic model based on their glassy dynamics and cage mobility. We successfully developed models for the thermoplastic polystryrene [1], the rubbery polymer polybutadiene [2], and molecular glass forming liquid ortho-terphenyl [3]. 
      
  <img src='/images/CG11.jpeg' width="50%" style="display: block; margin: 0 auto;"><br/><em style="text-align: center; display: inline-block; width: 100%;">Representative coarse-grained images of polybutadiene and polystyrene, taken from Song et al &#91;2&#93;.</em>

Nanoconfinement effects on chain mobility
------

Next, using these models, we studied the dynamics of polymers under different confinement effects arising from free surfaces, polymeric substrates, and rigid substrates and fillers. We demonstrated that polymer architecture can play a significant role in the nanoconfinement effect, as polymers with bulkier side-chains undergo a greater increase in chain mobility under free-surface confinement [4], but a smaller decrease in chain mobility under substrate confinement [5]. We also demonstrated that a large interphase region can exist when both of these polymers form a soft interface with each other [6]. 

<img src='/images/CG2.jpeg' width="50%" style="display: block; margin: 0 auto;"><br/> <em style="text-align: center; display: inline-block; width: 100%;">Representative free-standing thin film configurations, taken from Hsu et al [4].</em>

Nanomechanical characterization
------

Lastly, we used these models to study the nanoscale mechanical response of substrate and filler-confined thin films using indentation – a common experimental approach to quantify the interphase length-scale. We showed that indentation techniques can overestimate the interphase length-scale due to the stress field propagation arising from the indentation [7], an effect which can be exacerbated at elevated temperatures due to viscous flow at higher temperatures [8]. 

<img src='/images/CG33.png' width="50%" style="display: block; margin: 0 auto;"><br/><em style="text-align: center; display: inline-block; width: 100%;">Illustration of the nanoindentation study which was selected as the front cover of Soft Matter, taken from Song et al [8].</em>

## References

1. Xia, W.&#42;, <b>Song, J.&#42;</b>, Jeong, C., Hsu, D. D., Phelan, F. R., Douglas, J. F., & Keten, S. “Energy Renormalization for Temperature Transferable Coarse-Graining of Polymer Dynamics”. <em>Macromolecules</em>. 50(21), 8787-8796 (2017)
2. <b>Song, J.</b>, Hsu, D. D., Shull, K. R., Phelan Jr, F. R., Douglas, J. F., Xia, W., & Keten, S. “Coarse-Grained Modelling of Polymer Viscoelasticity via Energy Renormalization.” <em>Macromolecules</em>. 51(10), 3818-3827 (2018)
3. Xia, W., <b>Song, J.</b>., Krishnamurthy, N., Phelan Jr, F. R., Keten, S., & Douglas, J. F.  “Energy Renormalization for Coarse-Graining the Dynamics of a Model Glass-Forming Liquid”. <em>Journal of Physical Chemistry B</em>. 122(6), 2040-2045 (2018)
4. Hsu, D. D., Xia, W., <b>Song, J.</b>, & Keten, S. “Glass-Transition and Side-Chain Dynamics in Thin Films: Explaining Dissimilar Free Surface Effects for Polystyrene vs Poly(methyl methacrylate)”. <em>ACS Macro Letters.</em> 5, 481-486 (2016)
5. Xia, W., <b>Song, J.</b>, Hsu, D. D., & Keten, S. “Side-Group Size Effects on Interfaces and Glass Formation in Supported Polymer Thin Films”. <em>The Journal of Chemical Physics</em>. 146(20), 203311 (2017)
6. Hsu, D. D., Xia, W.,  <b>Song, J.</b>, & Keten, S. “Prediction of Local Glass Transition Temperature of Polystyrene and Poly(methyl methacrylate) Bilayer Thin Films”. <em>MRS Communications</em>. 7(4), 832-839 (2017)
7. Xia, W.*, <b>Song, J.&#42;</b>, Hsu, D. D., & Keten, S. “Understanding the Interfacial Mechanical Response of Nanoscale Polymer Thin Films via Nanoindentation”. <em>Macromolecules</em>. 49(10), 3810-3817 (2016)
8. <b>Song, J.*</b>,Kahraman, R.&#42;, Collinson, D.&#42;, Xia, W., Brinson, L. C., & Keten, S. “Temperature Effects on the Nanoindentation Characterization of Stiffness Gradients in Confined Polymers”. <em>Soft Matter</em>. 15(3), 359-370 (2019)
