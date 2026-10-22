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

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin: 24px 0;">
  <div style="flex: 1 1 260px; max-width: 320px; text-align: center;">
    <img src="/images/research/fig1_wt_model_clean.png" alt="Working model of muscle filopodia in circuit development" style="width: 100%; border-radius: 6px; box-shadow: 0 2px 8px rgba(0,0,0,0.08);">
    <p style="font-size: 0.85em; color: #555; margin-top: 10px; line-height: 1.4; text-align: left;">
      <strong>Figure 1. Working Model of Muscle Filopodia in Target Selection.</strong> In wild-type embryos, anterior muscle filopodia (M12) restrict motor axon (MN12) interaction domains, refining synaptic targeting choice points (adapted from dissertation Chapter 6).
    </p>
  </div>
  <div style="flex: 2 1 320px;">
    <p>Using orthogonal binary expression systems (<strong>Gal4/UAS</strong> and <strong>LexA/LexAop</strong>) to conduct two-color live imaging of individual NMJs in intact embryos, we discovered that individual muscles extend spatially separated populations of filopodia that interact with distinct motoneurons:</p>
    <ul style="line-height: 1.6;">
      <li><strong>Synaptic Filopodial Clusters:</strong> Form at the future neuromuscular junction and transition directly into functional, mature synapses.</li>
      <li><strong>Non-Synaptic Guidance Clusters:</strong> Form along the muscle edges and contact navigating motor axons that do <em>not</em> form synapses with that muscle, serving as active, transient guideposts to steer axons into their proper muscle fields.</li>
    </ul>
    <p>These findings demonstrate that muscle filopodia possess distinct compartmentalization and functional specialization, playing simultaneous but separate roles in axon guidance and synaptogenesis during normal circuit wiring.</p>
  </div>
</div>

*Relevant Publications & Talks:*
* **Inal, M. A., & Kamiyama, D.** (2026). Selective muscle imaging reveals widespread myopodia clustering during *Drosophila* neuromuscular development. *Developmental Biology*.
* **Inal, M. A.**, Li, S., Kner, P., & Kamiyama, D. *Muscle Filopodia Relay Motor Axon to Target Muscle Field for Functional Synapse Formation.* ASCB 2024 (Selected Oral Presentation).

---

## 2. Molecular Differentiation of Subcellular Filopodial Interfaces

How does a single muscle cell coordinate two distinct filopodial populations with opposing developmental fates? To uncover the molecular differentiators of these dynamic sub-structures, we investigated the localization and organization of candidate synaptic and adhesion proteins.

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin: 24px 0;">
  <div style="flex: 1 1 240px; max-width: 300px; text-align: center;">
    <img src="/images/research/fig2_split_gfp_clean.png" alt="Split-GFP reconstitution visualizing cell-type-specific endogenous protein localization" style="width: 100%; border-radius: 6px; box-shadow: 0 2px 8px rgba(0,0,0,0.08);">
    <p style="font-size: 0.85em; color: #555; margin-top: 10px; line-height: 1.4; text-align: left;">
      <strong>Figure 2. Cell-Type-Specific Split-GFP Labeling.</strong> Endogenous reconstitution of fluorescent signals across subcellular interfaces, resolving synaptic adhesion complexes without antibody penetration artifacts (from <em>Methods in Cell Biology</em>, 2024).
    </p>
  </div>
  <div style="flex: 2 1 320px;">
    <p>To overcome antibody penetration limitations in deep embryonic tissue, we utilized the <strong>split-GFP reconstitution system</strong> for cell-type-specific endogenous protein labeling:</p>
    <ul style="line-height: 1.6;">
      <li><strong>Endogenous Signal Reconstitution:</strong> Allowed precise visualization of adhesion complexes exclusively at defined cell-cell contact interfaces.</li>
      <li><strong>Conserved Adhesion Modules:</strong> Identified that the cell adhesion molecule <strong>Fas2 / NCAM</strong> (as well as N-Cadherin) is highly enriched across both filopodial clusters.</li>
      <li><strong>Local Functional Divergence:</strong> Revealed that similar core molecular modules are recruited to distinct cellular sites, where specialized multiprotein assemblies and local geometry dictate whether a filopodium acts as a transient guidepost or a stable nascent synapse.</li>
    </ul>
  </div>
</div>

*Relevant Publications:*
* **Inal, M. A.**, Banzai, K., Kamiyama, R., & Kamiyama, D. (2024). Chapter Eight - Cell-type-specific labeling of endogenous proteins using the split GFP system in *Drosophila*. *Methods in Cell Biology*, 200, 137–150.
* **Inal, M. A.** (2025). *High-Resolution Characterization of Filopodial Interactions Guiding Neuromuscular Circuit Development in Drosophila*. Ph.D. Dissertation, University of Georgia.

---

## 3. Optical Pipeline Development: High-Resolution Retrograde Tracing & In Vivo SMLM/STORM

Filopodia typically measure 100–200 nm in width—well below the diffraction limit of conventional light microscopy (~250 nm). Resolving their fine ultrastructure and molecular architecture in living animals requires advanced optical strategies tailored for deep, light-scattering tissues. To address these challenges, our work established two complementary imaging pipelines:

### A. In Vivo Retrograde Lipophilic Dye Labeling

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin: 20px 0;">
  <div style="flex: 1 1 240px; max-width: 280px; text-align: center;">
    <img src="/images/research/fig4_retrograde_panel_a_clean.png" alt="Retrograde lipophilic dye labeling of embryonic motoneurons" style="width: 100%; border-radius: 6px; box-shadow: 0 2px 8px rgba(0,0,0,0.08);">
    <p style="font-size: 0.85em; color: #555; margin-top: 10px; line-height: 1.4; text-align: left;">
      <strong>Figure 3. Retrograde Fluorescent Dye Labeling (<em>JoVE</em>, 2020).</strong> Multi-color lipophilic dye retrograde tracing of specific embryonic motoneurons (aCC, RP3) innervating distinct target muscle fields.
    </p>
  </div>
  <div style="flex: 2 1 320px;">
    <ul style="line-height: 1.6;">
      <li><strong>Targeted Motoneuron Labeling:</strong> Standardized single- and multi-color lipophilic fluorescent dye protocols in embryonic motoneurons.</li>
      <li><strong>Subcellular Process Tracing:</strong> Enabled high-contrast tracing of fine cellular processes—including individual neurites, navigating growth cones, and exploratory filopodia—in intact embryonic preparations.</li>
      <li><strong>Circuit Dissection:</strong> Established a versatile platform for mapping motoneuron-to-muscle connectivity and evaluating axonal guidance defects.</li>
    </ul>
  </div>
</div>

### B. Deep-Tissue SMLM / STORM Super-Resolution Microscopy

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: flex-start; margin: 20px 0;">
  <div style="flex: 1 1 280px; max-width: 360px; text-align: center;">
    <img src="/images/research/fig3_storm_panel_a_clean.png" alt="Super-resolution STORM vs. conventional wide-field imaging" style="width: 100%; border-radius: 6px; box-shadow: 0 2px 8px rgba(0,0,0,0.08);">
    <p style="font-size: 0.85em; color: #555; margin-top: 10px; line-height: 1.4; text-align: left;">
      <strong>Figure 4. Super-Resolution STORM vs. Wide-Field (<em>Current Protocols</em>, 2021).</strong> Resolving motoneuron axonal membranes and sub-diffraction structures in dissected embryos at ~20-nm lateral resolution.
    </p>
  </div>
  <div style="flex: 2 1 320px;">
    <ul style="line-height: 1.6;">
      <li><strong>Nanometer Lateral Resolution:</strong> Standardized a Stochastic Optical Reconstruction Microscopy (STORM) pipeline for in vivo and in vitro neurons, achieving <strong>~20-nm lateral resolution</strong> in 20–50 µm thick specimens.</li>
      <li><strong>Photoblinking Optimization:</strong> Engineered optimized buffer conditions and specimen mounting strategies that achieved a 3-fold improvement in signal sensitivity in light-scattering tissues.</li>
      <li><strong>Ultrastructural Nanodomains:</strong> Uncovered previously unresolvable nanoscale structural features along navigating neurites and interaction interfaces.</li>
    </ul>
  </div>
</div>

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
