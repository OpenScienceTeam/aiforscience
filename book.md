
# Generative Models for Materials Science

## Part I — Foundations

<!-- ### Chapter 1: Introduction to Materials Informatics
- What is materials informatics?
- Forward vs inverse problems in materials science
- Role of computation, experiments, and data
- Overview of generative modeling in materials discovery -->

### Chapter 1: Basics of Materials Science
- Crystal structures and symmetry
<!-- - Electronic structure and energy landscapes -->
- Thermodynamics and free energy
<!-- - Structure–property relationships -->
- Free energy landscape
- Reaction transition states, energy barriers and mechanisms
- Path sampling

    *Definition, implication and conventional sampling methods.* 

### Chapter 2: Probability and Statistical Modeling
- Random variables and distributions
- Bayesian inference basics
- Likelihood, prior, posterior
<!-- - High-dimensional probability intuition -->

### Chapter 3: Machine Learning Fundamentals
- Supervised vs unsupervised learning
- Representation learning
- Overfitting, generalization, and inductive bias
<!-- - Neural networks basics -->

---

## Part II — Representations of Materials

### Chapter 4: Representing Atomic Structures
<!-- - Periodic boundary conditions and spectra analysis -->
- Graph representations of crystals
<!-- - Point clouds and voxel grids -->
<!-- - Symmetry-aware representations -->
<!-- 
### Chapter 6: Equivariant and Symmetry-Preserving Models -->
- Translation, rotation, permutation symmetry
- SE(3)/E(3)-equivariant networks
    - Equivariant deep neural network
    - Message passing neural networks (MPNNs)
    - Equivariant transformer
<!-- - Practical design constraints -->

<!-- ### Chapter 7: Energy Landscapes and Physical Priors
- Potential energy surfaces
- Role of physics constraints in ML models
- Energy-based representations -->

---

## Part III — Core Generative Models

### Chapter 5: Variational Autoencoders (VAEs)
- Latent variable models
- Amortized inference
- Crystal VAEs and compositional design
- Trade-offs in latent space interpretability
    
    *Refer to [1]*

### Chapter 6: Generative Adversarial Networks (GANs)
- Adversarial training principles
- Stability issues
- CrystalGAN and structure generation
- Mode collapse in materials space

     *Refer to [1]*

### Chapter 7: Normalizing Flows
- Invertible transformations
    - Boltzmann generators
<!-- - Exact likelihood training -->
- Flow Matching and Transport Models
    - Optimal transport formulation
    - Deterministic vs stochastic sampling
    - Likelihood evaluation
- Discrete representations
    - Flows on categorical variables  
    - Graph flows  
    - Permutation-based invertible mappings  

### Chapter 8: Diffusion Models
- Forward noising and reverse denoising
- Score-based generative modeling
<!-- - SE(3)-equivariant diffusion for molecules and crystals -->
- Sampling efficiency and guidance methods
    - Langevin Dynamics
    - Guidance

### Chapter 9: Autoregressive Models for Materials
- Sequence modeling for atomic structures
    - Limitations for periodic systems
- Applications in crystal generation


---

## Part V — Conditional and Inverse Design

### Chapter 10: Conditional Generation
- Conditioning on composition, structure, or properties
    - Inpainting
    - Guidance
- Multi-objective constraints

### Chapter 11: Inverse Materials Design
- Property-to-structure mapping
- Bayesian optimization vs generative models
- Multi-fidelity design pipelines


---

## Part VI — Applications

### Chapter 12: Crystal and Solid-State Materials
- Inorganic crystal generation
- Phase diagram generation
- Defect, surface, and interface structures

### Chapter 13: Molecular and Soft Materials
- Polymers, MOFs, and organic crystals
- Drug-like molecules vs materials design

### Chapter 14: Kinetic simulations
<!-- - Active site generation
- Surface reactions -->
<!-- - Catalyst discovery pipelines -->
- Free energy landscape and reaction pathway
- Reaction network
- Kinetic Monte Carlo

### Chapter 15: Energy Materials
<!-- - Batteries, photovoltaics, hydrogen storage
- Stability under operating conditions -->

---

## Part VII — Training and Evaluation

### Chapter 16: Datasets in Materials Science
- Materials Project, OQMD, NOMAD
- Data cleaning and bias issues
- Synthetic data generation

### Chapter 17: Training Challenges
- Data scarcity and imbalance
- Symmetry enforcement in training
- Scalability issues

### Chapter 18: Evaluation Metrics
- Validity, uniqueness, novelty
- Physical stability criteria
- Property prediction accuracy


---

## Part VIII — Advanced Topics and Frontiers

### Chapter 19: Multi-Scale Generative Modeling
- Atomistic to mesoscale coupling
- Coarse-graining and backmapping

### Chapter 20: Uncertainty Quantification
- Bayesian deep learning
- Calibration of generative outputs

### Chapter 21: Active Learning and Closed-Loop Discovery
- Experiment–model feedback loops
- Autonomous materials labs

### Chapter 22: Scientific Discovery with Generative Models
- Hypothesis generation
- Discovering new physical laws
- Interpretability challenges

---

<!-- ## Part IX — Computational Practice

### Chapter 30: Implementing Generative Models
- Frameworks (PyTorch, JAX)
- Equivariant libraries (e3nn, NequIP-style architectures)
- Training pipelines

### Chapter 31: Case Studies
- Crystal diffusion model implementation
- VAE for composition design
- Flow matching for reaction pathways

--- -->

## Appendices
- A: Mathematical background (group theory, thermodynamics)
- B: Common datasets and benchmarks
- C: Software libraries
- D: Notation and conventions

---

## References

[1] MIT EECS, Fall 2024, Kaiming He:
https://mit-6s978.github.io/schedule.html