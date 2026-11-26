<div align="center">

# Embodied Lower-limb Exoskeleton Assistance: Survey, Challenges, and Perspectives

</div>

This repository accompanies the survey **Embodied Lower-limb Exoskeleton Assistance: Survey, Challenges, and Perspectives** — an embodied survey of how mechanical structure, high-level perception and decision-making, and low-level control keep lower-limb exoskeleton assistance effective and comfortable as the task, the wearer, and the environment change.

- 📄 We maintain a curated list of papers, code, websites, and datasets on embodied lower-limb exoskeleton assistance, emphasizing work from about 2020 onward in IEEE TRO, IEEE/ASME TMECH, IEEE TCYB, IEEE ICRA, and IJRR, together with Science, Nature, and their family journals, as well as other journals in robotics.
- 🧭 The list is organized around structural self-adaptation, task adaptation, user-specific adaptation, and control self-regulation. Structural self-adaptation concerns the physical embodiment; task adaptation and user-specific adaptation concern the high-level controller; control self-regulation concerns the low-level controller. A paper that supports two questions is listed under both, and representative works that are not yet formally published are marked as arXiv.
- 🙌 If you find missing papers, outdated links, or incorrect metadata, please feel free to open an issue or submit a pull request!

## Table of Contents

- [1. Structural Self-Adaptation](#1-structural-self-adaptation)
  - [1.1 Kinematic Compatibility](#11-kinematic-compatibility)
  - [1.2 Dynamic Compatibility](#12-dynamic-compatibility)
- [2. Task Adaptation](#2-task-adaptation)
  - [2.1 Multimodal Information Fusion](#21-multimodal-information-fusion)
    - [2.1.1 Torque Prediction](#211-torque-prediction)
    - [2.1.2 Trajectory Prediction](#212-trajectory-prediction)
  - [2.2 Musculoskeletal-Based Policy Learning](#22-musculoskeletal-based-policy-learning)
    - [2.2.1 Musculoskeletal Locomotion Policy Training](#221-musculoskeletal-locomotion-policy-training)
    - [2.2.2 Exoskeleton Policy Training](#222-exoskeleton-policy-training)
- [3. User-Specific Adaptation](#3-user-specific-adaptation)
  - [3.1 Human-in-the-Loop Optimization](#31-human-in-the-loop-optimization)
    - [3.1.1 Physiological-Signal-Based Optimization](#311-physiological-signal-based-optimization)
    - [3.1.2 Preference-Based Optimization](#312-preference-based-optimization)
  - [3.2 Cross-Subject Transfer](#32-cross-subject-transfer)
    - [3.2.1 Multi-Subject Shared Representation](#321-multi-subject-shared-representation)
    - [3.2.2 Cross-Subject Domain Adaptation](#322-cross-subject-domain-adaptation)
- [4. Control Self-Regulation](#4-control-self-regulation)
  - [4.1 Control Compensation](#41-control-compensation)
  - [4.2 Control Optimization](#42-control-optimization)

---

<a id="1-structural-self-adaptation"></a>

## 1. Structural Self-Adaptation

> Mechanical design matches joint geometry, mass distribution, and interaction impedance to the wearer, so assistance is transmitted while misalignment loads and the burden of wearing the device remain limited.

<a id="11-kinematic-compatibility"></a>

### 1.1 Kinematic Compatibility

> Self-aligning mechanisms, polycentric joints, and adjustable interfaces match anatomical axes and the reachable workspace, so assistance follows joint motion and parasitic forces are suppressed.

- **[IEEE TRO 2025] Yu**-Autonomous synthesis of self-aligning knee joint exoskeleton mechanisms[[Paper]](https://doi.org/10.1109/tro.2025.3547274)
- **[IJRR 2026] Xu**-Bioinspired multisegment knee exoskeletons with variable stiffness and kinematic compatibility[[Paper]](https://doi.org/10.1177/02783649261443651)
- **[IEEE TBME 2026] Li**-A Bioinspired Gear-Rolling Knee Exoskeleton for Enhanced Human-Exoskeleton Kinematic Compatibility[[Paper]](https://doi.org/10.1109/tbme.2026.3664052)
- **[IEEE TNSRE 2024] Li**-Development and validation of a self-aligning knee exoskeleton with hip rotation capability[[Paper]](https://doi.org/10.1109/tnsre.2024.3354806)
- **[IEEE TBME 2024] Zhang**-Parallel elastic self-alignment mechanism enhances energy efficiency and reduces misalignment in a powered knee exoskeleton[[Paper]](https://doi.org/10.1109/tbme.2024.3461880)
- **[IEEE TMRB 2020] Sarkisian**-Design, development, and validation of a self-aligning mechanism for high-torque powered knee exoskeletons[[Paper]](https://doi.org/10.1109/tmrb.2020.2981951)
- **[IEEE TBME 2025] Lambranzi**-Impact of a lower limb exosuit anchor points on energetics and biomechanics[[Paper]](https://doi.org/10.1109/tbme.2025.3593040)
- **[Sci. Transl. Med. 2017] Awad**-A soft robotic exosuit improves walking in patients after stroke[[Paper]](https://doi.org/10.1126/scitranslmed.aai9084)
- **[Nat. Mach. Intell. 2024] Tricomi**-Soft robotic shorts improve outdoor walking efficiency in older adults[[Paper]](https://doi.org/10.1038/s42256-024-00894-8)
- **[Nat. Commun. 2026] Pruyn**-Portable hip exoskeleton improves walking economy for stroke survivors[[Paper]](https://doi.org/10.1038/s41467-026-69580-0)
- **[IJRR 2021] Bryan**-A hip-knee-ankle exoskeleton emulator for studying gait assistance[[Paper]](https://doi.org/10.1177/0278364920961452)

<a id="12-dynamic-compatibility"></a>

### 1.2 Dynamic Compatibility

> Proximal or off-board mass placement, quasi-direct drive, series elasticity, and phase-dependent stiffness preserve the required torque and power while reducing added mass and interaction impedance.

- **[IEEE TRO 2022] Huang**-Modeling and stiffness-based continuous torque control of lightweight quasi-direct-drive knee exoskeletons for versatile walking assistance[[Paper]](https://doi.org/10.1109/tro.2022.3170287)
- **[IEEE/ASME TMECH 2020] Yu**-Quasi-direct drive actuation for a lightweight hip exoskeleton with high backdrivability and high bandwidth[[Paper]](https://doi.org/10.1109/tmech.2020.2995134)
- **[IEEE/ASME TMECH 2022] Qian**-Toward improving actuation transparency and safety of a hip exoskeleton with a novel nonlinear series elastic actuator[[Paper]](https://doi.org/10.1109/tmech.2022.3201255)
- **[IEEE TRO 2025] Chen**-Hip-knee-ankle rehabilitation exoskeleton with compliant actuators: From human-robot interaction control to clinical evaluation[[Paper]](https://doi.org/10.1109/tro.2024.3502226)
- **[IEEE/ASME TMECH 2025] Yan**-Compact and foldable hip exoskeleton with high torque density actuator for walking and stair-climbing assistance in young and older adults[[Paper]](https://doi.org/10.1109/tmech.2025.3576123)
- **[IEEE/ASME TMECH 2025] Choi**-Flexi-SEA: Flexible-Shaft-Driven Series Elastic Actuator for Wearable Robots[[Paper]](https://doi.org/10.1109/tmech.2025.3537113)
- **[IEEE/ASME TMECH 2022] Ishmael**-A powered hip exoskeleton with high torque density for walking, running, and stair ascent[[Paper]](https://doi.org/10.1109/tmech.2022.3159506)
- **[IEEE TRO 2025] Archangeli**-A lightweight powered hip exoskeleton with parallel actuation for frontal and sagittal plane assistance[[Paper]](https://doi.org/10.1109/tro.2025.3539172)
- **[IEEE TRO 2025] Feng**-A wearable isokinetic training robot for enhanced bedside knee rehabilitation[[Paper]](https://doi.org/10.1109/tro.2025.3552332)
- **[Nature 2026] Li**-Spinal neuromotor rehabilitation using a portable isokinetic training robot[[Paper]](https://doi.org/10.1038/s41586-026-10642-0)
- **[IEEE/ASME TMECH 2022] Li**-Mechanical compliance and dynamic load isolation design of lower limb exoskeleton for locomotion assistance[[Paper]](https://doi.org/10.1109/tmech.2022.3181261)
- **[Science 2021] Riemer**-Extracting electricity with exosuit braking[[Paper]](https://doi.org/10.1126/science.abh4007)
- **[Sci. Robot. 2022] Schmitz**-Modulation of Achilles tendon force with load carriage and exosuit assistance[[Paper]](https://doi.org/10.1126/scirobotics.abq1514)
- **[IEEE RA-L 2024] Wu**-Novel lightweight lower limb exoskeleton design for single-motor sequential assistance of knee and ankle joints in real world[[Paper]](https://doi.org/10.1109/lra.2024.3354618)
- **[Sci. Robot. 2017] Quinlivan**-Assistance magnitude versus metabolic cost reductions for a tethered multiarticular soft exosuit[[Paper]](https://doi.org/10.1126/scirobotics.aah4416)
- **[Sci. Robot. 2017] Lee**-Reducing the metabolic cost of running with a tethered soft exosuit[[Paper]](https://doi.org/10.1126/scirobotics.aan6708)
- **[IEEE RA-L 2022] Orekhov**-Design and electromechanical performance evaluation of a powered parallel-elastic ankle exoskeleton[[Paper]](https://doi.org/10.1109/lra.2022.3185372)

---

<a id="2-task-adaptation"></a>

## 2. Task Adaptation

> Torque or trajectory commands that vary with task and terrain are learned from multimodal observations or from musculoskeletal simulation, so the exoskeleton can assist across different movements.

Related roadmap: **[Nat. Mach. Intell. 2026] Shepherd**-A roadmap for end-to-end task-agnostic exoskeleton control[[Paper]](https://doi.org/10.1038/s42256-026-01297-7)

<a id="21-multimodal-information-fusion"></a>

### 2.1 Multimodal Information Fusion

> Human motion, exoskeleton state, and environmental observations are fused into a mapping from sensor inputs to joint torque or motion trajectories, which supplies task-dependent high-level commands.

<a id="211-torque-prediction"></a>

#### 2.1.1 Torque Prediction

> Temporal models trained on torque labels from inverse dynamics, electromyography, or in vivo measurement estimate biological joint moments in real time and scale them into exoskeleton assistance.

- **[Nature 2024] Molinaro**-Task-agnostic exoskeleton control via biological joint moment estimation[[Paper]](https://doi.org/10.1038/s41586-024-08157-7)[[Code]](https://doi.org/10.24433/CO.7641031.v2)
- **[Sci. Robot. 2024] Molinaro**-Estimating human joint moments unifies exoskeleton control, reducing user effort[[Paper]](https://doi.org/10.1126/scirobotics.adi8852)[[Data]](https://datadryad.org/dataset/doi:10.5061/dryad.8kprr4xsv)
- **[Sci. Robot. 2026] Bird**-Ultra-wideband radar to measure in vivo muscle forces[[Paper]](https://doi.org/10.1126/scirobotics.aed5865)
- **[arXiv 2026] Anonymous**-Assistance Torque Estimation via Dynamics-Aware Optimization for Lower-Limb Exoskeleton in Complex Environments
- **[IJRR 2026] Quesada**-EMG-to-torque models for exoskeleton assistance: a framework for the evaluation of in situ calibration[[Paper]](https://doi.org/10.1177/02783649251414884)
- **[IEEE TBME 2023] Dinovitzer**-Accurate Real-Time Joint Torque Estimation for Dynamic Prediction of Human Locomotion[[Paper]](https://doi.org/10.1109/tbme.2023.3240879)
- **[IEEE RA-L 2021] Caulcrick**-Human Joint Torque Modelling With MMG and EMG During Lower Limb Human-Exoskeleton Interaction[[Paper]](https://doi.org/10.1109/lra.2021.3097832)

<a id="212-trajectory-prediction"></a>

#### 2.1.2 Trajectory Prediction

> Past motion and terrain information are used to predict future joint trajectories or a compact set of trajectory parameters, which a low-level controller then tracks to deliver assistance.

- **[IEEE TRO 2025] Tricomi**-Leveraging geometric modeling-based computer vision for context aware control in a hip exosuit[[Paper]](https://doi.org/10.1109/tro.2025.3567489)
- **[IEEE TRO 2024] Chen**-Learning to assist different wearers in multitasks: efficient and individualized human-in-the-loop adaptation framework for lower-limb exoskeleton[[Paper]](https://doi.org/10.1109/tro.2024.3468768)
- **[IEEE TRO 2025] Dong**-Toward Physician-Level Performance in Robot-Assisted Ankle Rehabilitation via Imitation Learning with Empirical and Temporal Adaptation[[Paper]](https://doi.org/10.1109/tro.2025.3600162)
- **[IEEE TSMC 2023] Wu**-The visual footsteps planning system for exoskeleton robots under complex terrain[[Paper]](https://doi.org/10.1109/tsmc.2023.3260870)
- **[IEEE TSMC 2021] Liu**-Vision-Assisted Autonomous Lower-Limb Exoskeleton Robot[[Paper]](https://doi.org/10.1109/tsmc.2019.2932892)
- **[IEEE TNNLS 2023] Chen**-Gait Prediction and Variable Admittance Control for Lower Limb Exoskeleton With Measurement Delay and Extended-State-Observer[[Paper]](https://doi.org/10.1109/tnnls.2022.3152255)
- **[arXiv 2026] Anonymous**-ExoTraj: A General Lower-limb Exoskeleton Assistance Policy for Complex Environments

<a id="22-musculoskeletal-based-policy-learning"></a>

### 2.2 Musculoskeletal-Based Policy Learning

> A musculoskeletal model is first trained to reproduce human-like walking, and an exoskeleton torque policy is then learned in the same simulation, which reduces the cost of physical data collection and online human–robot interaction.

<a id="221-musculoskeletal-locomotion-policy-training"></a>

#### 2.2.1 Musculoskeletal Locomotion Policy Training

> Muscle-synergy dimensionality reduction or bioinspired exploration makes reinforcement learning tractable in a high-dimensional muscle space and yields policies for human-like walking.

- **[ICLR 2023] Schumacher**-DEP-RL: Embodied Exploration for Reinforcement Learning in Overactuated and Musculoskeletal Systems[[Paper]](https://openreview.net/forum?id=C-xa_D3oTj6)[[Code]](https://github.com/martius-lab/depRL)[[Website]](https://sites.google.com/view/dep-rl)
- **[ICML 2024] He**-DynSyn: Dynamical Synergistic Representation for Efficient Learning and Control in Overactuated Embodied Systems[[Paper]](https://proceedings.mlr.press/v235/he24o.html)[[Code]](https://github.com/Beanpow/DynSyn)[[Website]](https://sites.google.com/view/dynsyn)
- **[IEEE ICRA 2024] Zuo**-Self model for embodied intelligence: Modeling full-body human musculoskeletal system and locomotion control with hierarchical low-dimensional representation[[Paper]](https://doi.org/10.1109/icra57147.2024.10610081)[[Code]](https://github.com/LNSGroup/MS-Human-700)[[Website]](https://lnsgroup.cc/research/MS-Human)
- **[NeurIPS 2023] Chiappa**-Latent exploration for reinforcement learning[[Paper]](https://doi.org/10.52202/075280-2466)[[Code]](https://github.com/amathislab/lattice)
- **[Auton. Robots 2024] Berg**-SAR: Generalization of physiological agility and dexterity via synergistic action representation[[Paper]](https://doi.org/10.1007/s10514-024-10182-4)[[Code]](https://github.com/MyoHub/myosuite)
- **[iScience 2025] Schumacher**-Emergence of natural and robust bipedal walking by learning from biologically plausible objectives[[Paper]](https://doi.org/10.1016/j.isci.2025.112203)

<a id="222-exoskeleton-policy-training"></a>

#### 2.2.2 Exoskeleton Policy Training

> Muscle control and exoskeleton torque are optimized jointly or in stages inside a coupled human–robot simulation, so walking is completed while the user's physical burden is reduced.

- **[Nature 2024] Luo**-Experiment-free exoskeleton assistance via learning in simulation[[Paper]](https://doi.org/10.1038/s41586-024-07382-4)[[Code]](https://github.com/IntelligentRobotLearning/pseudocode_learning_in_simulation)
- **[J. Neuroeng. Rehabil. 2023] Luo**-Robust walking control of a lower limb rehabilitation exoskeleton coupled with a musculoskeletal model via deep reinforcement learning[[Paper]](https://doi.org/10.1186/s12984-023-01147-2)
- **[J. Neuroeng. Rehabil. 2025] Luo**-Robust neural network controller for a lower limb exoskeleton with minimal sensor configuration: a deep reinforcement learning approach with policy distillation[[Paper]](https://doi.org/10.1186/s12984-025-01854-y)
- **[IEEE TNSRE 2026] Bonab**-Musculoskeletal Simulation-Based Multi-Criteria Optimization Framework for Exoskeleton Design[[Paper]](https://doi.org/10.1109/tnsre.2026.3658597)
- **[IEEE RA-L 2026] Liu**-Modeling and Analysis of a Coupled Human–Robot System With Walking Assistance by Exoskeletons[[Paper]](https://doi.org/10.1109/lra.2026.3706935)
- **[arXiv 2026] Park**-Learning Hip Exoskeleton Control Policy via Predictive Neuromusculoskeletal Simulation[[Paper]](https://arxiv.org/abs/2603.04166)
- **[arXiv 2026] Li**-Learning a Speed-adaptive Hip Exoskeleton Control Policy Via Sim-to-real Reinforcement Learning[[Paper]](https://arxiv.org/abs/2609.28027)
- **[arXiv 2026] Yuan**-SMAT: Staged Multi-Agent Training for Co-Adaptive Exoskeleton Control[[Paper]](https://arxiv.org/abs/2603.07618)[[Code]](https://github.com/Fitz-Yuan/SMAT-Exo)
- **[arXiv 2026] Yuan**-Multi-Agent Reinforcement Learning of Co-Adaptive Hip Exoskeleton Control (MARL-Exo) for Metabolic Energy Reduction[[Paper]](https://arxiv.org/abs/2610.37441)
- **[arXiv 2026] Leem**-Exo-Plore: Exploring Exoskeleton Control Space through Human-aligned Simulation[[Paper]](https://arxiv.org/abs/2601.22550)

---

<a id="3-user-specific-adaptation"></a>

## 3. User-Specific Adaptation

> Assistance parameters are tuned, or predictive models are transferred, according to each wearer's metabolic response, preference, and motor distribution, so the same task receives individualized assistance.

<a id="31-human-in-the-loop-optimization"></a>

### 3.1 Human-in-the-Loop Optimization

> A small number of trials during real wearing iteratively updates low-dimensional assistance parameters from physiological measurements or subjective preference.

<a id="311-physiological-signal-based-optimization"></a>

#### 3.1.1 Physiological-Signal-Based Optimization

> Bayesian optimization or an evolution strategy adjusts the magnitude, timing, and scaling of the torque profile to reduce metabolic rate, muscle activation, or a composite of these signals.

- **[Sci. Robot. 2020] Witte**-Improving the energy economy of human running with powered and unpowered ankle exoskeleton assistance[[Paper]](https://doi.org/10.1126/scirobotics.aay9108)
- **[Sci. Robot. 2021] Poggensee**-How adaptation, training, and customization contribute to benefits from exoskeleton assistance[[Paper]](https://doi.org/10.1126/scirobotics.abf1078)
- **[Sci. Robot. 2021] Nuckols**-Individualization of exosuit assistance based on measured muscle dynamics during versatile walking[[Paper]](https://doi.org/10.1126/scirobotics.abj1362)
- **[IEEE TRO 2022] Gordon**-Human-in-the-Loop Optimization of Exoskeleton Assistance Via Online Simulation of Metabolic Cost[[Paper]](https://doi.org/10.1109/tro.2021.3133137)
- **[IEEE TRO 2025] Kang**-Online Adaptation Framework Enables Personalization of Exoskeleton Assistance During Locomotion in Patients Affected by Stroke[[Paper]](https://doi.org/10.1109/tro.2025.3595701)
- **[IEEE TBME 2025] Park**-Human-in-the-loop Optimization of Hip Exoskeleton Assistance During Stair Climbing[[Paper]](https://doi.org/10.1109/tbme.2025.3536516)
- **[IEEE RA-L 2025] Wang**-Human-in-the-Loop Optimization for Knee Exoskeleton Flexion Assistance[[Paper]](https://doi.org/10.1109/lra.2025.3526558)
- **[IEEE RA-L 2025] Zhang**-Multi-Objective Human-in-the-Loop Optimization of Exoskeleton Assistance for Dropfoot Gait[[Paper]](https://doi.org/10.1109/lra.2025.3587560)
- **[IEEE TMRB 2026] Powell**-Optimized Mappings From Biological Hip Moment Estimates to Exoskeleton Torque Can Personalize Assistance Across Users and Generalize Across Tasks[[Paper]](https://doi.org/10.1109/tmrb.2026.3712823)
- **[IEEE TMRB 2024] Chen**-Bayesian Algorithm-Based Force Profiles Optimization of Hip-Assistive Soft Exosuits Under Variable Walking Speeds[[Paper]](https://doi.org/10.1109/tmrb.2024.3408308)
- **[IEEE TNSRE 2021] Han**-Selection of Muscle-Activity-Based Cost Function in Human-in-the-Loop Optimization of Multi-Gait Ankle Exoskeleton Assistance[[Paper]](https://doi.org/10.1109/tnsre.2021.3082198)

<a id="312-preference-based-optimization"></a>

#### 3.1.2 Preference-Based Optimization

> Comparisons among candidate assistance profiles are used to learn an implicit objective, which then guides the search for more comfortable user-specific parameters.

- **[Nature 2022] Slade**-Personalizing exoskeleton assistance while walking in the real world[[Paper]](https://doi.org/10.1038/s41586-022-05191-1)[[Code]](https://drive.google.com/file/d/1BcPlB9INjvtRXufwh82feyDCBAMBgO0w/view)[[Data]](https://drive.google.com/file/d/1m2G7y4I_MBpTbeATv_tD70687qYoT8Cm/view)
- **[Sci. Robot. 2023] Lee**-User preference optimization for control of ankle exoskeletons using sample efficient active learning[[Paper]](https://doi.org/10.1126/scirobotics.adg3705)
- **[Sci. Robot. 2022] Ingraham**-The role of user preference in the customized control of robotic exoskeletons[[Paper]](https://doi.org/10.1126/scirobotics.abj3487)
- **[Sci. Adv. 2025] Arens**-Preference-based assistance optimization for lifting and lowering with a soft back exosuit[[Paper]](https://doi.org/10.1126/sciadv.adu2099)
- **[IEEE ICRA 2021] Li**-ROIAL: Region of Interest Active Learning for Characterizing Exoskeleton Gait Preference Landscapes[[Paper]](https://doi.org/10.1109/icra48506.2021.9560840)
- **[IEEE ICRA 2024] Li**-Human-Exoskeleton Locomotion Interaction Experience Transfer: Speeding up and Improving the Performance of Preference-based Optimizations of Exoskeleton Assistance During Walking[[Paper]](https://doi.org/10.1109/icra57147.2024.10611497)
- **[IEEE ICRA 2025] Ramella**-Rapid Online Learning of Hip Exoskeleton Assistance Preferences[[Paper]](https://doi.org/10.1109/icra55743.2025.11128809)
- **[npj Biomed. Innov. 2026] Schäfer**-User preference-based human-in-the-loop tuning of exoskeleton assistance during walking[[Paper]](https://doi.org/10.1038/s44385-026-00085-7)
- **[arXiv 2026] Anonymous**-Personalized Lower-limb Exoskeleton Assistance via Preference-based Bayesian Optimization

<a id="32-cross-subject-transfer"></a>

### 3.2 Cross-Subject Transfer

> Shared representations are learned from multiple subjects, or source and target feature distributions are aligned, so that torque and motion-intention prediction generalizes to a new user.

<a id="321-multi-subject-shared-representation"></a>

#### 3.2.1 Multi-Subject Shared Representation

> An encoder trained on many subjects extracts shared motion features, and a lightweight adapter then maps them to a new user's torque or trajectory.

- **[Nature 2024] Molinaro**-Task-agnostic exoskeleton control via biological joint moment estimation[[Paper]](https://doi.org/10.1038/s41586-024-08157-7)[[Code]](https://doi.org/10.24433/CO.7641031.v2)
- **[Sci. Robot. 2024] Molinaro**-Estimating human joint moments unifies exoskeleton control, reducing user effort[[Paper]](https://doi.org/10.1126/scirobotics.adi8852)[[Data]](https://datadryad.org/dataset/doi:10.5061/dryad.8kprr4xsv)
- **[Nat. Biomed. Eng. 2026] Tan**-GaitDynamics: a generative foundation model for analyzing human walking and running[[Paper]](https://doi.org/10.1038/s41551-025-01565-8)[[Code]](https://github.com/stanfordnmbl/GaitDynamics)[[Website]](https://huggingface.co/spaces/alanttan/GaitDynamics)[[Data]](https://addbiomechanics.org/download_data.html)
- **[IEEE TNSRE 2024] Chen**-Cross-subject lifelong learning for continuous estimation from surface electromyographic signal[[Paper]](https://doi.org/10.1109/tnsre.2024.3400535)
- **[IEEE TCYB 2026] Fu**-An Effective Semi-Subject-Independent sEMG-Based Learning Framework to Continuously Predict Knee Joint Trajectory[[Paper]](https://doi.org/10.1109/tcyb.2026.3715977)
- **[iScience 2026] Tu**-Personalized gait trajectory generation for lower-limb rehabilitation robots using anthropometric features[[Paper]](https://doi.org/10.1016/j.isci.2026.116958)

<a id="322-cross-subject-domain-adaptation"></a>

#### 3.2.2 Cross-Subject Domain Adaptation

> Discrepancy minimization or source reweighting aligns other users' data with the target user, so motion intention is predicted from limited target data.

- **[Sci. Robot. 2025] Scherpereel**-Deep domain adaptation eliminates costly data required for task-agnostic wearable robotic control[[Paper]](https://doi.org/10.1126/scirobotics.ads8652)
- **[IEEE TCYB 2025] Anonymous**-A Weight-Aware-Based Multisource Unsupervised Domain Adaptation Method for Human Motion Intention Recognition
- **[Pattern Recognit. 2022] Zhang**-Gaussian-guided feature alignment for unsupervised cross-subject adaptation[[Paper]](https://doi.org/10.1016/j.patcog.2021.108332)

---

<a id="4-control-self-regulation"></a>

## 4. Control Self-Regulation

> Under human–exoskeleton coupling, transmission friction, and uncertain foot–ground contact, tracking error is compensated and the interaction is optimized so that high-level commands are executed accurately and safely.

<a id="41-control-compensation"></a>

### 4.1 Control Compensation

> Model-based feedforward, disturbance observation, adaptive approximation, and cross-stride iterative learning compensate dynamic error and track the commanded trajectory or torque in real time.

**Feedforward and observer-based compensation**

- **[IEEE/ASME TMECH 2022] Sharifi**-Autonomous locomotion trajectory shaping and nonlinear control for lower limb exoskeletons[[Paper]](https://doi.org/10.1109/tmech.2022.3156168)
- **[IEEE/ASME TMECH 2023] Chen**-Output constrained control of lower limb exoskeleton based on knee motion probabilistic model with finite-time extended state observer[[Paper]](https://doi.org/10.1109/tmech.2023.3235054)
- **[IEEE TRO 2022] Durandau**-Neuromechanical Model-Based Adaptive Control of Bilateral Ankle Exoskeletons: Biological Joint Torque and Electromyogram Reduction Across Walking Conditions[[Paper]](https://doi.org/10.1109/tro.2022.3170239)
- **[IEEE TRO 2019] Lim**-Delayed output feedback control for gait assistance with a robotic hip exoskeleton[[Paper]](https://doi.org/10.1109/tro.2019.2913318)

**Adaptive and learning-based compensation**

- **[IEEE TCYB 2023] Li**-Human-in-the-loop adaptive control of a soft exo-suit with actuator dynamics and ankle impedance adaptation[[Paper]](https://doi.org/10.1109/tcyb.2023.3240231)
- **[IEEE TCYB 2025] Li**-Dynamic locomotion synchronization and fuzzy control of a lower limb exoskeleton with body weight support for active following human operator[[Paper]](https://doi.org/10.1109/tcyb.2025.3558616)
- **[IEEE TCYB 2021] Sun**-Reduced adaptive fuzzy decoupling control for lower limb exoskeleton[[Paper]](https://doi.org/10.1109/tcyb.2020.2972582)
- **[IEEE TCYB 2022] Yang**-Spatial iterative learning control for robotic path learning[[Paper]](https://doi.org/10.1109/tcyb.2021.3138992)
- **[IEEE/ASME TMECH 2024] Xing**-Spatial iterative learning torque control of robotic exoskeletons for high accuracy and rapid convergence assistance[[Paper]](https://doi.org/10.1109/tmech.2024.3365045)
- **[IEEE TRO 2022] Livolsi**-A novel wavelet-based gait segmentation method for a portable hip exoskeleton[[Paper]](https://doi.org/10.1109/tro.2021.3122975)

<a id="42-control-optimization"></a>

### 4.2 Control Optimization

> Impedance or torque is optimized against task error, safety constraints, and the user's voluntary effort, so assistance is sufficient without suppressing voluntary motion.

**Impedance interaction optimization**

- **[IEEE TRO 2022] Huo**-Impedance modulation control of a lower-limb exoskeleton to assist sit-to-stand movements[[Paper]](https://doi.org/10.1109/tro.2021.3104244)
- **[IEEE TRO 2022] Li**-Human-in-the-loop control of soft exosuits using impedance learning on different terrains[[Paper]](https://doi.org/10.1109/tro.2022.3160052)
- **[IEEE/ASME TMECH 2024] Wang**-PI2-Based Adaptive Impedance Control for Gait Adaption of Lower Limb Exoskeleton[[Paper]](https://doi.org/10.1109/tmech.2024.3370954)
- **[IEEE TASE 2025] Zhong**-Hierarchical optimal admittance control of cable-driven lower limb exoskeletons with unknown human and system dynamics[[Paper]](https://doi.org/10.1109/tase.2025.3627801)

**Constrained assistance optimization**

- **[IEEE TRO 2024] Küçüktabak**-Haptic transparency and interaction force control for a lower limb exoskeleton[[Paper]](https://doi.org/10.1109/tro.2024.3359541)
- **[IEEE TCYB 2025] Yang**-Multicontact safety-critical planning and adaptive neural control of a soft exosuit over different terrains[[Paper]](https://doi.org/10.1109/tcyb.2025.3550746)
- **[IEEE TCYB 2025] Xu**-Robust model predictive control of a gait rehabilitation exoskeleton with whole body motion planning and neuro-dynamics optimization[[Paper]](https://doi.org/10.1109/tcyb.2025.3545064)
- **[IEEE TCST 2024] Lin**-A modular framework for task-agnostic, energy shaping control of lower limb exoskeletons[[Paper]](https://doi.org/10.1109/tcst.2024.3429908)
- **[IEEE TRO 2026] Walters**-Optimal energy shaping and force amplification framework for task-agnostic, biomimetic ankle exoskeletons[[Paper]](https://doi.org/10.1109/tro.2026.3686250)
