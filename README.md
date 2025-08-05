# Embodied-AI-Paper-TopConf
🔥ICCV2025 &amp; ICML2025 &amp; RSS2025 &amp; CVPR2025 &amp; ICLR2025 Embodied AI Paper List  Resources.

[03/22/2025] We plan to organize more papers on Embodied AI from top conferences in the future and build a more comprehensive paper list. If there are any conference papers you would like to browse or if you have any other suggestions, please feel free to leave an issue.

[04/12/2025] We are updating Embodied AI papers accepted by RSS2025 (Robotics Top Conference)!

[05/21/2025] We are updating Embodied AI papers accepted by ICML2025!

[08/05/2025] We are updating Embodied AI papers accepted by ICCV2025!


## 📖 Paper List
- [📖 ICCV2025](#iccv2025)
  - [Vision-Language-Action Model](#vision-language-action-model)
  - [Vision-Language-Navigation Model](#vision-language-navigation-model)
  - [Hierarchical Planning](#hierarchical-planning)
  - [World Model](#world-model)
  - [Policy](#policy)
  - [Accelerating and Deploying](#accelerating-and-deploying)
  - [Perception](#perception)
  - [Benchmark and Dataset](#benchmark-and-dataset)
- [📖 ICML2025](#icml2025)
  - [Vision-Language-Action Models](#vision-language-action-models)
  - [Planning and Reasoning](#planning-and-reasoning)
  - [Policies](#policies)
  - [3D Vision](#3d-vision)
  - [Dataset](#dataset)
- [📖 RSS2025](#rss2025)
- [📖 CVPR2025](#cvpr2025)
  - [Vision-Language-Action Models](#vision-language-action-models)
  - [Policies](#policies)
  - [Grasp](#grasp)
  - [Humanoid](#humanoid)
  - [Planning and Reasoning](#planning-and-reasoning)
  - [3D Vision](#3d-vision)
  - [Sim2real and Real2sim](#sim2real-and-real2sim)
  - [Benchmark and Dataset](#benchmark-and-dataset)
- [📖 ICLR2025](#iclr2025)
  - [Vision-Language-Action Models](#vision-language-action-models)
  - [Policies](#policies)
  - [Planning and Reasoning](#planning-and-reasoning)
  - [3D Vision](#3d-vision)
  - [Sim2real and Real2sim](#sim2real-and-real2sim)
- [📖 ICRA2025](#icra2025)


# ICCV2025

## Vision-Language-Action Model
- Exploring the Adversarial Vulnerabilities of Vision-Language-Action Models in Robotics [Paper](https://arxiv.org/abs/2411.13587) [page](https://vlaattacker.github.io/)
- **VQ-VLA**: Improving Vision-Language-Action Models via Scaling Vector-Quantized Action Tokenizers [Paper](https://arxiv.org/abs/2507.01016) [page](https://xiaoxiao0406.github.io/vqvla.github.io)
- **Dita**: Scaling Diffusion Transformer for Generalist Vision-Language-Action Policy [Paper](https://arxiv.org/abs/2503.19757) [page](https://robodita.github.io/)
- **Moto**: Latent Motion Token as the Bridging Language for Learning Robot Manipulation from Videos [Paper](https://arxiv.org/abs/2412.04445) [page](https://chenyi99.github.io/moto/)
- **A0**: An Affordance-Aware Hierarchical Model for General Robotic Manipulation [Paper](https://arxiv.org/abs/2504.12636) [page](https://a-embodied.github.io/A0/)
- **Embodied VideoAgent**: Persistent Memory from Egocentric Videos and Embodied Sensors Enables Dynamic Scene Understanding [Paper](https://arxiv.org/abs/2501.00358) [page](https://embodied-videoagent.github.io/)
- **CoA-VLA**: Improving Vision-Language-Action Models via Visual-Text Chain-of-Affordance [Paper](https://iccv.thecvf.com/virtual/2025/poster/542)
- **FedVLA**: Federated Vision-Language-Action Learning with Dual Gating Mixture-of-Experts for Robotic Manipulation [Paper](https://iccv.thecvf.com/virtual/2025/poster/1325)
- Towards Long-Horizon Vision-Language-Action System: Reasoning, Acting and Memory [Paper](https://iccv.thecvf.com/virtual/2025/poster/1915)
- **PASG**: A Closed-Loop Framework for Automated Geometric Primitive Extraction and Semantic Anchoring in Robotic Manipulation [Paper](https://iccv.thecvf.com/virtual/2025/poster/225)
- **SD2Actor**: Continuous State Decomposition via Diffusion Embeddings for Robotic Manipulation [Paper](https://iccv.thecvf.com/virtual/2025/poster/1571)

## Vision-Language-Navigation Model
- **Move to Understand a 3D Scene**: Bridging Visual Grounding and Exploration for Efficient and Versatile Embodied Navigation [Paper](https://arxiv.org/abs/2507.04047) [page](https://mtu3d.github.io/)
- Rethinking the Embodied Gap in Vision-and-Language Navigation: A Holistic Study of Physical and Visual Disparities [Paper](https://arxiv.org/abs/2507.13019) [page](https://crystalsixone.github.io/vln_pe.github.io/)
- **P3Nav**: A Unified Framework for Embodied Navigation Integrating Perception, Planning, and Prediction [Paper](https://arxiv.org/abs/2503.18525)
- **SAME**: Learning Generic Language-Guided Visual Navigation with State-Adaptive Mixture of Experts [Paper](https://arxiv.org/abs/2412.05552) [page](https://github.com/GengzeZhou/SAME)
- **NavMorph**: A Self-Evolving World Model for Vision-and-Language Navigation in Continuous Environments  [Paper](https://arxiv.org/abs/2506.23468) [page](https://github.com/Feliciaxyao/NavMorph)
- Harnessing Input-adaptive Inference for Efficient VLN [Paper](https://openreview.net/pdf?id=5gptKWnVPF)
- Embodied Navigation with Auxiliary Task of Action Description Prediction [Paper](https://iccv.thecvf.com/virtual/2025/poster/1984)
- 3D Gaussian Map with Open-Set Semantic Grouping for Vision-Language Navigation [Paper](https://iccv.thecvf.com/virtual/2025/poster/299)
- **NavQ**: Learning a Q-Model for Foresighted Vision-and-Language Navigation [Paper](https://iccv.thecvf.com/virtual/2025/poster/944)
- **monoVLN**: Bridging the Observation Gap between Monocular and Panoramic Vision and Language Navigation [Paper](https://iccv.thecvf.com/virtual/2025/poster/1792)

## Hierarchical Planning
- Adaptive Articulated Object Manipulation On The Fly with Foundation Model Reasoning and Part Grounding [Paper](https://arxiv.org/abs/2507.18276)
- **CogNav**: Cognitive Process Modeling for Object Goal Navigation with LLMs [Paper](https://arxiv.org/abs/2412.10439) [page](https://yhancao.github.io/CogNav/)
- **RoBridge**: A Hierarchical Architecture Bridging Cognition and Execution for General Robotic Manipulation [Paper](https://arxiv.org/abs/2505.01709) [page](https://abliao.github.io/RoBridge/)

## World Model
- **IRASim**: A Fine-Grained World Model for Robot Manipulation [Paper](https://arxiv.org/abs/2406.14540) [page](https://gen-irasim.github.io/)
- **GWM**: Towards Scalable Gaussian World Models for Robotic Manipulation [Paper](https://ziweiwangthu.github.io/data/GWM.pdf) [page](https://gaussian-world-model.github.io/)
- **DyWA**: Dynamics-adaptive World Action Model for Generalizable Non-prehensile Manipulation [Paper](https://arxiv.org/abs/2503.16806) [page](https://pku-epic.github.io/DyWA/)
- Diffusion-Based Imaginative Coordination for Bimanual Manipulation [Paper](https://arxiv.org/abs/2507.11296)
- Learning 4D Embodied World Models [Paper](https://openreview.net/pdf?id=mnwlhvmKMN)

## Policy
- Rethinking Bimanual Robotic Manipulation: Learning with Decoupled Interaction Framework [Paper](https://arxiv.org/abs/2503.09186)
- **EC-Flow**: Enabling Versatile Robotic Manipulation from Action-Unlabeled Videos via Embodiment-Centric Flow [Paper](https://arxiv.org/abs/2507.06224) [page](https://ec-flow1.github.io/)
- **Dense Policy**: Bidirectional Autoregressive Learning of Actions [Paper](https://arxiv.org/abs/2503.13217) [page](https://selen-suyue.github.io/DspNet/)
- **AnyBimanual**: Transferring Unimanual Policy for General Bimanual Manipulation [Paper](https://arxiv.org/abs/2412.06779) [page](https://anybimanual.github.io/)
- Learning Precise Affordances from Egocentric Videos for Robotic Manipulation [Paper](https://arxiv.org/abs/2408.10123v1) [page](https://reagan1311.github.io/affgrasp)
- **iManip**: Skill-Incremental Learning for Robotic Manipulation [Paper](https://arxiv.org/abs/2503.07087) 
- Spatial-Temporal Aware Visuomotor Diffusion Policy Learning [Paper](https://arxiv.org/abs/2507.06710) [page](https://zhenyangliu.github.io/DP4/)
- **Wavelet Policy**: Lifting Scheme for Policy Learning in Long-Horizon Tasks [Paper](https://arxiv.org/abs/2507.04331) [page](https://hhuang-code.github.io/wavelet_policy/)
- 4D Visual Pre-training for Robot Learning [Paper](https://iccv.thecvf.com/virtual/2025/poster/972)

## Accelerating and Deploying
- Saliency-Aware Quantized Imitation Learning for Efficient Robotic Control [Paper](https://arxiv.org/abs/2505.15304)
- On-Device Diffusion Transformer Policy for Efficient Robot Manipulation [Paper](https://arxiv.org/abs/2508.00697)
- **COSMO**: Combination of Selective Memorization for Low-cost Vision-and-Language Navigation [Paper](https://arxiv.org/abs/2503.24065)
- **CARP**: Coarse-to-Fine Autoregressive Prediction for Visuomotor Policy Learning [Paper](https://arxiv.org/abs/2412.06782) [page](https://carp-robot.github.io/)

## Perception
- **EmbodiedOcc**: Embodied 3D Occupancy Prediction for Vision-based Online Scene Understanding [Paper](https://arxiv.org/abs/2412.04380) [page](https://ykiwu.github.io/EmbodiedOcc/)
- **Embodied Image Captioning**: Self-supervised Learning Agents for Spatially Coherent Image Descriptions [Paper](https://arxiv.org/abs/2504.08531) [page](https://hsp-iit.github.io/embodied-captioning/)

## Benchmark and Dataset
- **VLABench**: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks [Paper](https://arxiv.org/abs/2412.18194) [page](https://iranqin.github.io/robofactory/)
- **RoboFactory**: Exploring Embodied Agent Collaboration with Compositional Constraints [Paper](https://arxiv.org/abs/2503.16408) [page](https://vlabench.github.io/)
- **HUMOTO**: A 4D Dataset of Mocap Human Object Interactions [Paper](https://arxiv.org/abs/2504.10414) [page](https://jiaxin-lu.github.io/humoto/)
- **RoboMM**: All-in-One Multimodal Large Model for Robotic Manipulation [Paper](https://arxiv.org/abs/2412.07215)
- **MoMa-Kitchen**: A 100K+ Benchmark for Affordance-Grounded Last-Mile Navigation in Mobile Manipulation [Paper](https://arxiv.org/abs/2503.11081) [page](https://momakitchen.github.io/)
- **RoboPearls**: Editable Video Simulation for Robot Manipulation [Paper](https://arxiv.org/abs/2506.22756) [page](https://tangtaogo.github.io/RoboPearls/)
- **DexH2R**: A Benchmark for Dynamic Dexterous Grasping in Human-to-Robot Handover [Paper](https://arxiv.org/abs/2506.23152) [page](https://dexh2r.github.io/)
- **Beyond the Destination**: A Novel Benchmark for Exploration-Aware Embodied Question Answering [Paper](https://arxiv.org/abs/2503.11117) [page](https://github.com/HCPLab-SYSU/EXPRESS-Bench)
- **RobAVA**: A Large-scale Dataset and Baseline Towards Video based Robotic Arm Action Understanding [Paper](https://iccv.thecvf.com/virtual/2025/poster/1787)
- **RoboAnnotatorX**: A Comprehensive and Universal Annotation Framework for Accurate Understanding of Long-horizon Robot Demonstration [Paper](https://iccv.thecvf.com/virtual/2025/poster/2215)

# ICML2025

## Vision-Language-Action Models
- **Hi Robot**: Open-Ended Instruction Following with Hierarchical Vision-Language-Action Models [Paper](https://arxiv.org/abs/2502.19417)
- **OTTER**: A Vision-Language-Action Model with Text-Aware Visual Feature Extraction [paper](https://arxiv.org/pdf/2503.03734) [page](https://ottervla.github.io/)
- **UP-VLA**: A Unified Understanding and Prediction Model for Embodied Agent [paper](https://arxiv.org/abs/2501.18867)
- **ELEMENTAL**: Interactive Learning from Demonstrations and Vision-Language Models for Reward Design in Robotics [paper](https://arxiv.org/abs/2411.18825)
- **ReinboT**: Amplifying Robot Visual-Language Manipulation with Reinforcement Learning [paper](https://arxiv.org/abs/2505.07395)
- **A Large Recurrent Action Model:** xLSTM enables Fast Inference for Robotics Tasks [paper](https://arxiv.org/abs/2410.22391) [page](https://github.com/ml-jku/LRAM)

## Planning and Reasoning
- Efficient Robotic Policy Learning via Latent Space Backward Planning [paper](https://arxiv.org/abs/2505.06861) [page](https://lbp-authors.github.io/)
- Closed-Loop Long-Horizon Robotic Planning via Equilibrium Sequence Modeling [paper](https://arxiv.org/pdf/2410.01440) [page](https://github.com/Singularity0104/equilibrium-planner)

## Policies

- **SAM2Act**:Integrating Visual Foundation Model with A Memory Architecture for Robotic Manipulation [paper](https://arxiv.org/abs/2501.18564)
- Pre-training Auto-regressive Robotic Models with 4D Representations [paper](https://arxiv.org/pdf/2502.13142) [page](https://arm4r.github.io/)
- Flow-based Domain Randomization for Learning and Sequencing Robotic Skills [paper](https://arxiv.org/pdf/2502.01800)
- **EmbodiedBench**: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents [paper](https://arxiv.org/abs/2502.09560) [page](https://embodiedbench.github.io/)
- Learning Policy Committees for Effective Personalization in MDPs with Diverse Tasks [paper](https://arxiv.org/abs/2503.01885)
- Video Prediction Policy: A Generalist Robot Policy with Predictive Visual Representations [paper](https://arxiv.org/abs/2412.14803) [page](https://video-prediction-policy.github.io/)

## 3D Vision
- Unifying 2D and 3D Vision-Language Understanding [paper](https://arxiv.org/abs/2503.10745) [page](https://univlg.github.io/)
- GAPrompt: Geometry-Aware Point Cloud Prompt for 3D Vision Model [paper](https://arxiv.org/abs/2505.04119) [page](https://github.com/zhoujiahuan1991/ICML2025-GAPrompt)

## Dataset
- WOMD-Reasoning: A Large-Scale Dataset for Interaction Reasoning in Driving [paper](https://arxiv.org/abs/2407.04281) [page](https://github.com/yhli123/WOMD-Reasoning)

# RSS2025

- **Unified World Models**: Coupling Video and Action Diffusion for Pretraining on Large Robotic Datasets [Paper](https://arxiv.org/abs/2504.02792) [Page](https://weirdlabuw.github.io/uwm/)
- **CordViP**: Correspondence-based Visuomotor Policy for Dexterous Manipulation in Real-World [Paper](https://arxiv.org/pdf/2502.08449) [Page](https://aureleopku.github.io/CordViP/)
- **Reactive Diffusion Policy**: Slow-Fast Visual-Tactile Policy Learning for Contact-Rich Manipulation [Paper](https://arxiv.org/pdf/2503.02881) [Page](https://reactive-diffusion-policy.github.io/)
- Dynamic Rank Adjustment in Diffusion Policies for Efficient and Flexible Training [Paper](https://arxiv.org/abs/2502.03822)
- **SpatialVLA**: Exploring Spatial Representations for Visual-Language-Action Model [Paper](https://arxiv.org/abs/2501.15830)
- **Sketch-to-Skill**: Bootstrapping Robot Learning with Human Drawn Trajectory Sketches [Paper](https://arxiv.org/abs/2503.11918)
- **NaVILA**: Legged Robot Vision-Language-Action Model for Navigation [Paper](https://arxiv.org/abs/2412.04453) [Page](https://navila-bot.github.io/)
- **ConRFT**: A Reinforced Fine-tuning Method for VLA Models via Consistency Policy [Paper](https://arxiv.org/abs/2502.05450) [Page](https://cccedric.github.io/conrft/)
- **You Only Teach Once**: Learn One-Shot Bimanual Robotic Manipulation from Video Demonstrations [Paper](https://arxiv.org/abs/2501.14208) [Page](https://hnuzhy.github.io/projects/YOTO/)
- **ASAP**: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills [Paper](https://arxiv.org/abs/2502.01143) [Page](https://agile.human2humanoid.com/)
- **Flying Hand**: End-Effector-Centric Framework for Versatile Aerial Manipulation Teleoperation and Policy Learning [Paper](https://lecar-lab.github.io/flying_hand/static/pdf/flying_hand.pdf) [Page](https://lecar-lab.github.io/flying_hand/)
- **DemoGen**: Synthetic Demonstration Generation for Data-Efficient Visuomotor Policy Learning [Paper](https://arxiv.org/abs/2502.16932) [Page](https://demo-generation.github.io/)
- **DOGlove**: Dexterous Manipulation with a Low-Cost Open-Source Haptic Force Feedback Glove [Paper](https://arxiv.org/pdf/2502.07730) [Page](https://do-glove.github.io/)
- **RoboSplat**: Novel Demonstration Generation with Gaussian Splatting Enables Robust One-Shot Manipulation [Paper](https://arxiv.org/abs/2504.13175) [Page](https://yangsizhe.github.io/robosplat/)
- Enhancing Autonomous Driving Systems with On-Board Deployed Large Language Models [Paper](https://arxiv.org/abs/2504.11514)
- **SATA**: Safe and Adaptive Torque-Based Locomotion Policies Inspired by Animal Learning [Paper](https://arxiv.org/abs/2502.12674) [Video](https://youtu.be/b1cpTq0Rc5w?si=sAd9y5LE2sWynu7v)
- **FACTR**: Force-Attending Curriculum Training for Contact-Rich Policy Learning [Paper](https://arxiv.org/abs/2502.17432) [Page](https://jasonjzliu.com/factr/)
- **RoboVerse**: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning [Paper](https://arxiv.org/abs/2504.18904) [Page](https://roboverseorg.github.io/)
- **STDArm**: Transferring Visuomotor Policies From Static Data Training to Dynamic Robot Manipulation [Paper](https://arxiv.org/abs/2504.18792)

  
# CVPR2025

## Vision-Language-Action Models

- **UniAct**: Universal Actions For Enhanced Embodied Foundation Models [Paper](https://arxiv.org/abs/2501.10105) [Page](https://2toinf.github.io/UniAct/)
- **MoManipVLA**: Transferring Vision-language-action Models for General Mobile Manipulation [Paper](https://arxiv.org/abs/2503.13446) [Page](https://gary3410.github.io/momanipVLA/)
- **CoT-VLA**: Visual Chain-of-Thought Reasoning for Vision-Language-Action Models [Paper](https://cvpr.thecvf.com/virtual/2025/poster/33233)
- **SOLAMI**: Social Vision-Language-Action Modeling for Immersive Interaction with 3D Autonomous Characters [Paper](https://arxiv.org/abs/2412.00174) [Page](https://solami-ai.github.io/)
- A Data-Centric Revisit of Pre-Trained Vision Models for Robot Learning [Paper](https://arxiv.org/abs/2503.06960) [Page](https://github.com/CVMI-Lab/SlotMIM)
- **Think Small, Act Big**: Primitive Prompt Learning for Lifelong Robot Manipulation
- **Phoenix**: A Motion-based Self-Reflection Framework for Fine-grained Robotic Action Correction [Paper](https://cvpr.thecvf.com/virtual/2025/poster/32789)
- **OmniManip**: Towards General Robotic Manipulation via Object-Centric Interaction Primitives as Spatial Constraints [Paper](https://arxiv.org/abs/2501.03841) [Page](https://omnimanip.github.io/)
- Mitigating the Human-Robot Domain Discrepancy in Visual Pre-training for Robotic Manipulation [Paper](https://arxiv.org/abs/2406.14235)
- Object-Centric Prompt-Driven Vision-Language-Action Model for Robotic Manipulation [Abstract](https://cvpr.thecvf.com/virtual/2025/poster/34522)
- Robotic Visual Instruction
- **RoboGround**: Robot Manipulation with Grounded Vision-Language Priors

## Policies
- **KStar Diffuser**: Spatial-Temporal Graph Diffusion Policy with Kinematics Modeling for Bimanual Robotic Manipulation [Paper](https://arxiv.org/abs/2503.10743)
- **RoboPEPP**: Vision-Based Robot Pose and Joint Angle Estimation through Embedding Predictive Pre-Training [Paper](https://arxiv.org/abs/2411.17662)
- **Lift3D Policy**: Lifting 2D Foundation Models for Robust 3D Robotic Manipulation [Paper](https://arxiv.org/abs/2411.18623) [Page](https://lift3d-web.github.io/)
- **PDFactor**: Learning Tri-Perspective View Policy Diffusion Field for Multi-Task Robotic Manipulation [Abstract](https://cvpr.thecvf.com/virtual/2025/poster/33943)
- **Two by Two**: Learning Cross-Task Pairwise Objects Assembly for Generalizable Robot Manipulation
- **FlowRAM**: Grounding Flow Matching Policy with Region-Aware Mamba Framework for Robotic Manipulation [Abstract](https://cvpr.thecvf.com/virtual/2025/poster/33579)
- **G3Flow**: Generative 3D Semantic Flow for Pose-aware and Generalizable Object Manipulation [Paper](https://arxiv.org/abs/2411.18369) [Page](https://tianxingchen.github.io/G3Flow/)
- **DexHandDiff**: Interaction-aware Diffusion Planning for Adaptive Dexterous Manipulation [Paper](https://arxiv.org/abs/2411.18562) [Page](https://dexdiffuser.github.io/)
- **Tra-MoE**: Learning Trajectory Prediction Model from Multiple Domains for Adaptive Policy Conditioning [Paper](https://arxiv.org/abs/2411.14519)
- **AffordDP**: Generalizable Diffusion Policy with Transferable Affordance[Paper](https://arxiv.org/abs/2412.03142) [Page](https://afforddp.github.io/)
- **Tra-MoE**: Learning Trajectory Prediction Model from Multiple Domains for Adaptive Policy Conditioning [Paper](https://arxiv.org/abs/2411.14519) [Page](https://github.com/MCG-NJU/Tra-MoE)

## Grasp
- **UniGraspTransformer**: Simplified Policy Distillation for Scalable Dexterous Robotic Grasping [Paper](https://arxiv.org/abs/2412.02699) [Page](https://dexhand.github.io/UniGraspTransformer/)
- **DexGrasp Anything**: Towards Universal Robotic Dexterous Grasping with Physics Awareness [Paper](https://arxiv.org/abs/2503.08257) [Page](https://github.com/4DVLab/DexGrasp-Anything)
- **ZeroGrasp**: Zero-Shot Shape Reconstruction Enabled Robotic Grasping [Paper](https://cvpr.thecvf.com/virtual/2025/poster/32440)

## Humanoid
- Let Humanoid Robots Go Hiking! Integrative Skill Development over Complex Trails [Paper](https://cvpr.thecvf.com/virtual/2025/poster/34565) [Page](https://lego-h-humanoidrobothiking.github.io/)
- **MobileH2R**: Learning Generalizable Human to Mobile Robot Handover Exclusively from Scalable and Diverse Synthetic Data [Paper](https://arxiv.org/abs/2501.04595)

## 3D Vision
- **3D-MVP**: 3D Multiview Pretraining for Robotic Manipulation [Paper](https://arxiv.org/abs/2406.18158) [Page](https://jasonqsy.github.io/3DMVP/)
- **VidBot**: Learning Generalizable 3D Actions from In-the-Wild 2D Human Videos for Zero-Shot Robotic Manipulation[Paper](https://arxiv.org/abs/2503.07135) [Page](https://hanzhic.github.io/vidbot-project/)
- **Touch2Shape**: Touch-Conditioned 3D Diffusion for Shape Exploration and Reconstruction [Abs](https://cvpr.thecvf.com/virtual/2025/poster/33415)

## Planning and Reasoning
- **RoboBrain**: A Unified Brain Model for Robotic Manipulation from Abstract to Concrete [Paper](https://arxiv.org/abs/2502.21257)
- **PhysVLM**: Enabling Visual Language Models to Understand Robotic Physical Reachability [Paper](https://arxiv.org/abs/2503.08481)
- **RoboSpatial**: Teaching Spatial Understanding to 2D and 3D Vision-Language Models for Robotics [Paper](https://arxiv.org/abs/2411.16537)
- **Tartan IMU**: A Light Foundation Model for Inertial Positioning in Robotics [Abstract](https://cvpr.thecvf.com/virtual/2025/poster/33873)
- **Code-as-Monitor**: Constraint-aware Visual Programming for Reactive and Proactive Robotic Failure Detection [Paper](https://arxiv.org/abs/2412.04455) [Page](https://zhoues.github.io/Code-as-Monitor/)

## Video

- **TASTE-Rob**: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation [Paper](https://arxiv.org/abs/2503.11423)
- **GraphMimic**: Graph-to-Graphs Generative Modeling from Videos for Policy Learning [Paper](https://cvpr.thecvf.com/virtual/2025/poster/34942)


## Sim2real and Real2sim
- **Prof. Robot**: Differentiable Robot Rendering Without Static and Self-Collisions [Paper](https://arxiv.org/abs/2503.11269) [Page](https://www.qrcat.cn/prof-robot/)
- **AutoURDF**: Unsupervised Robot Modeling from Point Cloud Frames Using Cluster Registration [Paper](https://arxiv.org/abs/2412.05507) [Page](https://github.com/jl6017/AutoURDF)

## Benchmark and Dataset
- **RoboTwin**: Dual-Arm Robot Benchmark with Generative Digital Twins (early version)[Paper](https://arxiv.org/abs/2409.02920) [Page](https://robotwin-benchmark.github.io/early-version/)
- Pixel-aligned RGB-NIR Stereo Imaging and Dataset for Robot Vision [Paper](https://arxiv.org/abs/2411.18025)
- **RoboSense**: Large-scale Dataset and Benchmark for Egocentric Robot Perception and Navigation in Crowded and Unstructured Environments [Paper](https://arxiv.org/abs/2408.15503) [Page](https://github.com/suhaisheng/RoboSense)

# ICLR2025

## Vision-Language-Action Models

- **LLaRA**: Supercharging Robot Learning Data for Vision-Language Policy [Paper](https://arxiv.org/abs/2406.20095) [Page](https://github.com/LostXine/LLaRA)
- **VLAS**: Vision-Language-Action Model With Speech Instructions For Customized Robot Manipulation [Paper](https://arxiv.org/abs/2502.13508) [Page](https://github.com/whichwhichgone/VLAS)
- **TraceVLA**: Visual Trace Prompting Enhances Spatial-Temporal Awareness for Generalist Robotic Policies [Paper](https://arxiv.org/abs/2412.10345) [Page](https://tracevla.github.io/)
- **Robots Pre-train Robots**: Manipulation-Centric Robotic Representation from Large-Scale Robot Datasets [Paper](https://arxiv.org/abs/2410.22325) [Page](https://robots-pretrain-robots.github.io/)
- **PIDM**: Predictive Inverse Dynamics Models are Scalable Learners for Robotic Manipulation [Paper](https://arxiv.org/abs/2412.15109) [Page](https://nimolty.github.io/Seer/)

## Policies

- **GravMAD**: Grounded Spatial Value Maps Guided Action Diffusion for Generalized 3D Manipulation [Paper](https://arxiv.org/abs/2409.20154) [Page](https://gravmad.github.io/)
- **ReViWo**: Learning View-invariant World Models for Visual Robotic Manipulation [Paper](https://openreview.net/forum?id=vJwjWyt4Ed) [zhihu](https://zhuanlan.zhihu.com/p/26181243574)
- **HAMSTER**: Hierarchical Action Models For Open-World Robot Manipulation [Paper](https://arxiv.org/abs/2502.05485) [Page](https://hamster-robot.github.io/)
- **BadRobot**: Jailbreaking Embodied LLMs in the Physical World [Paper](https://arxiv.org/abs/2407.20242) [Page](https://embodied-llms-safety.github.io/)
- **STRAP**: Robot Sub-Trajectory Retrieval for Augmented Policy Learning [Paper](https://arxiv.org/abs/2412.15182) [Page](https://weirdlabuw.github.io/strap/)
- **SRSA**: Skill Retrieval and Adaptation for Robotic Assembly Tasks [Paper](https://arxiv.org/abs/2503.04538) [Page](https://srsa2024.github.io/)
- Data Scaling Laws in Imitation Learning for Robotic Manipulation [Paper](https://arxiv.org/abs/2410.18647) [Page](https://data-scaling-laws.github.io/)
- **Stem-OB**: Generalizable Visual Imitation Learning with Stem-Like Convergent Observation through Diffusion Inversion [Paper](https://arxiv.org/abs/2411.04919) [Page](https://hukz18.github.io/Stem-Ob/)

## 3D Vision
- **Dream to Manipulate**: Compositional World Models Empowering Robot Imitation Learning with Imagination [Paper](https://arxiv.org/abs/2412.14957) [Page](https://leobarcellona.github.io/DreamToManipulate/)
- **SPA***: 3D Spatial-Awareness Enables Effective Embodied Representation [Paper](https://arxiv.org/abs/2410.08208) [Page](https://haoyizhu.github.io/spa/)

## Planning and Reasoning
- **LASeR**: Towards Diversified and Generalizable Robot Design with Large Language Models [Paper](https://openreview.net/forum?id=7mlvOHL6qJ) [Page](https://github.com/WoodySJR/LASeR)
- Physics-informed Temporal Difference Metric Learning for Robot Motion Planning [Paper](https://openreview.net/forum?id=TOiageVNru) [Page](https://github.com/ruiqini/ntrl-demo)
- **AHA**: A Vision-Language-Model for Detecting and Reasoning Over Failures in Robotic Manipulation [Paper](https://arxiv.org/abs/2410.00371) [Page](https://aha-vlm.github.io/)
- **EMOS**: Embodiment-aware Heterogeneous Multi-robot Operating System with LLM Agents[Paper](https://arxiv.org/abs/2410.22662) [Page](https://arxiv.org/abs/2410.22662)
- **VisualPredicator**: Learning Abstract World Models with Neuro-Symbolic Predicates for Robot Planning [Paper](https://arxiv.org/abs/2410.23156) [Page](https://arxiv.org/abs/2410.23156)
- **DenseMatcher**: Learning 3D Semantic Correspondence for Category-Level Manipulation from a Single Demo [Paper](https://arxiv.org/abs/2412.05268) [Page](https://tea-lab.github.io/DenseMatcher/)
- 6D Object Pose Tracking in Internet Videos for Robotic Manipulation [Paper](https://arxiv.org/abs/2503.10307) [Page](https://ponimatkin.github.io/freepose/)

## Planning and Reasoning
- Multi-Robot Motion Planning with Diffusion Models [Paper](https://arxiv.org/abs/2410.03072) [Page](https://github.com/yoraish/mmd)

## Video
- **GEVRM**: Goal-Expressive Video Generation Model For Robust Visual Manipulation [Paper](https://arxiv.org/abs/2502.09268)

## Sim2real and Real2sim
- **ReGen**: Generative Robot Simulation via Inverse Design [Paper](https://openreview.net/forum?id=EbCUbPZjM1) [Page](https://regen-sim.github.io/)
  
# ICRA2025
- **MoRE**: Unlocking Scalability in Reinforcement Learning for Quadruped Vision-Language-Action Models [Paper](https://arxiv.org/abs/2503.08007)
- **QUART-Online**: Latency-Free Large Multimodal Language Model for Quadruped Robot Learning [Paper](https://arxiv.org/abs/2412.15576) [Page](https://quart-online.github.io/)
- **SpatialBot**: Precise Spatial Understanding with Vision Language Models [Paper](https://arxiv.org/pdf/2406.13642) [Page](https://github.com/BAAI-DCAI/SpatialBot)


