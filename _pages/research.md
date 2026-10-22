---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /projects/
---

{% include base_path %}

My research explores a fundamental question in neurobiology: **how does local molecular organization dictate distinct cellular compartments to perform specialized functions in the nervous system?** 

During my doctoral research in Cellular Biology at the University of Georgia in the laboratory of Dr. Daichi Kamiyama, I investigated the cellular and molecular mechanisms that govern neural circuit assembly using the *Drosophila melanogaster* embryonic neuromuscular junction (NMJ). By integrating high-resolution live imaging, super-resolution microscopy (SMLM/STORM), and genetic labeling tools, my work uncovered novel principles of contact-mediated communication between motoneurons and postsynaptic target muscles. Building on these findings, my research vision connects the nanometer-scale assembly and remodeling of subcellular compartments to synaptic communication, neural homeostasis, and neurological health.

---

## 1. Spatially Distinct Muscle Filopodia in Axon Guidance vs. Synapse Formation

During embryonic development, motoneurons navigate complex cellular terrain to find and innervate specific target muscles. While previous studies focused heavily on presynaptic growth cone filopodia, the role of postsynaptic muscle filopodia (myopodia) remained largely unexplored.

Using orthogonal binary expression systems (**Gal4/UAS** and **LexA/LexAop**) to conduct two-color live imaging of individual NMJs in intact embryos, we discovered that individual muscles extend spatially separated populations of filopodia that interact with distinct motoneurons:
* **Synaptic Filopodial Clusters:** Form at the future neuromuscular junction and transition directly into functional, mature synapses.
* **Non-Synaptic Guidance Clusters:** Form along the muscle edges and contact navigating motor axons that do *not* form synapses with that muscle, serving as active, transient guideposts to steer axons into their proper muscle fields.

These findings demonstrated that muscle filopodia possess distinct compartmentalization and functional specialization, playing simultaneous but separate roles in axon guidance and synaptogenesis during normal circuit wiring.

<figure style="margin: 24px 0; text-align: center;">
  <img src="/images/research/working-model-myopodia.png" alt="Working model schematic of muscle filopodia in circuit development" style="max-width: 90%; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 8px;"><strong>Figure 1. Working Model of Muscle Filopodia Function in Circuit Development (Unpublished Schematic).</strong> In wild-type embryos, anterior muscle filopodia (M12) restrict motor axon (MN12) interaction domains, while posterior filopodia refine the defasciculation choice point of the SNa nerve near the muscle boundary. In filopodia-knockdown embryos, these targeting constraints are lost (adapted from dissertation Chapter 6).</figcaption>
</figure>

<figure style="margin: 24px 0; text-align: center;">
  <img src="/images/research/nmj-filopodia-sim-comparison.png" alt="Morphological characterization of NMJ and non-NMJ filopodia using 2-color SIM" style="max-width: 85%; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 8px;"><strong>Figure 2. Two-Color Structured Illumination Microscopy (SIM) of Filopodial Populations.</strong> Resolving distinctive morphological interactions, lengths, and widths between exploring neuronal growth cones and muscle filopodia at synaptic vs. non-synaptic sites (from dissertation Chapter 5).</figcaption>
</figure>

*Relevant Publications & Talks:*
* **Inal, M. A., & Kamiyama, D.** (2026). Selective muscle imaging reveals widespread myopodia clustering during *Drosophila* neuromuscular development. *Developmental Biology*.
* **Inal, M. A.**, Li, S., Kner, P., & Kamiyama, D. *Muscle Filopodia Relay Motor Axon to Target Muscle Field for Functional Synapse Formation.* ASCB 2024 (Selected Oral Presentation).

---

## 2. Molecular Differentiation of Subcellular Filopodial Interfaces

How does a single muscle cell coordinate two distinct filopodial populations with opposing developmental fates? To uncover the molecular differentiators of these dynamic sub-structures, we investigated the localization and organization of candidate synaptic and adhesion proteins.

To overcome antibody penetration limitations in deep embryonic tissue, we utilized the **split-GFP reconstitution system** for cell-type-specific endogenous protein labeling. We found that the cell adhesion molecule **Fas2 / NCAM** (as well as N-Cadherin) is highly enriched across both filopodial clusters, suggesting that similar core molecular modules are recruited to distinct cellular sites, where specialized multiprotein complexes and local geometry dictate functional divergence. This work highlighted how local molecular programs interact with surrounding cellular compartments to drive sub-cellular specialization during synaptogenesis.

*Relevant Publications:*
* **Inal, M. A.**, Banzai, K., Kamiyama, R., & Kamiyama, D. (2024). Chapter Eight - Cell-type-specific labeling of endogenous proteins using the split GFP system in *Drosophila*. *Methods in Cell Biology*, 200, 137–150.
* **Inal, M. A.** (2025). *High-Resolution Characterization of Filopodial Interactions Guiding Neuromuscular Circuit Development in Drosophila*. Ph.D. Dissertation, University of Georgia.

---

## 3. Optical Pipeline Development: High-Resolution Retrograde Tracing & In Vivo SMLM/STORM

Filopodia typically measure 100–200 nm in width—well below the diffraction limit of conventional light microscopy (~250 nm). Resolving their fine ultrastructure and molecular architecture in living animals requires advanced optical strategies tailored for deep, light-scattering tissues.

To address these challenges, our work established two complementary imaging methodologies:
1. **Retrograde Lipophilic Dye Labeling:** Standardized single- and multi-color lipophilic fluorescent dye labeling protocols in embryonic motoneurons, enabling high-resolution tracing of fine cellular processes including neurites, growth cones, and individual filopodia.
2. **Deep-Tissue SMLM / STORM:** In collaboration with optical engineers, developed and standardized a Stochastic Optical Reconstruction Microscopy pipeline for in vivo and in vitro neurons. By optimizing photoblinking buffer conditions and sample mounting for 20–50 µm thick specimens, we achieved **20-nm lateral resolution** with a 3-fold improvement in signal sensitivity. This pipeline uncovered previously hidden ultrastructural features, including a characteristic **"beads-on-a-string"** nanoscale filopodial morphology.

<figure style="margin: 24px 0; text-align: center;">
  <img src="/images/research/storm-super-resolution-panel.png" alt="Conventional wide-field vs. super-resolution STORM imaging of motor neurons" style="max-width: 85%; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 8px;"><strong>Figure 3. Super-Resolution STORM vs. Wide-Field Imaging (Published in <em>Current Protocols</em>, 2021).</strong> Resolving motoneuron axonal membranes and sub-diffraction structures in dissected embryos at ~20-nm lateral resolution compared to conventional wide-field fluorescence (Inal et al., 2021).</figcaption>
</figure>

<figure style="margin: 24px 0; text-align: center;">
  <img src="/images/research/storm-m12-nmj-ultrastructure.png" alt="Two-color STORM image of M12 neuromuscular junction" style="max-width: 75%; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 8px;"><strong>Figure 4. Two-Color STORM Nanoscale Filopodial Ultrastructure.</strong> High-precision dual-color localization of motoneuron (anti-HRP, magenta) and muscle (anti-GFP, green) membranes reveals characteristic fusiform "beads-on-a-string" nanodomains at active interaction sites (from dissertation Supplementary Figure 6.2).</figcaption>
</figure>

<figure style="margin: 24px 0; text-align: center;">
  <img src="/images/research/retrograde-tracing-panel.png" alt="Retrograde lipophilic dye labeling and muscle wall schematic" style="max-width: 90%; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1);">
  <figcaption style="font-size: 0.9em; color: #555; margin-top: 8px;"><strong>Figure 5. Retrograde Fluorescent Dye Labeling of Motor Neurons (Published in <em>JoVE</em>, 2020).</strong> (A) Multi-color lipophilic dye retrograde tracing of specific embryonic motor neurons (aCC, RP3) innervating distinct target muscles (DiO, DiD). (B) Schematic diagram of body wall muscle architecture and dye application sites (Inal et al., 2020).</figcaption>
</figure>

*Relevant Publications & Protocols:*
* **Inal, M. A.**, Bui, K. C., Marar, A., Li, S., Kner, P., & Kamiyama, D. (2021). Imaging of In Vitro and In Vivo Neurons in *Drosophila* Using Stochastic Optical Reconstruction Microscopy. *Current Protocols*, 1(7), e203.
* **Inal, M. A.**, Banzai, K., & Kamiyama, D. (2020). Retrograde Tracing of *Drosophila* Embryonic Motor Neurons Using Lipophilic Fluorescent Dyes. *Journal of Visualized Experiments*, (155).

---

## Future Directions: Nanoscale Molecular Organization in Neural Specialization

Building on my doctoral discoveries, my future research program investigates how local molecular organization supports the distinct but coordinated functions of cells throughout the nervous system.

A central interest lies in **astrocytes**, whose highly ramified processes simultaneously engage neuronal synapses, blood vessels, and neighboring glia through distinct subcellular interfaces. Within these interfaces, I am investigating how nanoscale molecular assemblies—such as **Neurexin-1 (Nrxn1)** and associated cell adhesion complexes—are organized and remodeled during development to sustain divergent local functions (e.g., glutamate clearance and ion homeostasis at synapses versus metabolic support and water flux at perivascular endfeet).

To bridge spatial resolution and dynamic temporal signaling, I aim to combine:
* **Multiplexed Super-Resolution Imaging** (e.g., pan-ExM-t) to map nanoscale macromolecular architectures;
* **Live Biosensors** (such as iGluSnFR for glutamate handling and GCaMP for calcium dynamics) in intact tissue;
* **Computational & Geometric Modeling** to integrate dynamic intracellular events with sub-micron structural geometries.

*Long-term Goal:* To build an independent academic research group dedicated to understanding how the assembly, maintenance, and disruption of nanoscale subcellular specializations regulate neural circuit communication and contribute to neurological disease.
