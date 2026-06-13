<link rel="icon" type="image/png" href="/assets/favicon.png">
# Professional Biography
Below you will find a summary of my academic background, primary research lines, technical interests, and core competencies (e.g., Numerical Analysis, Scientific Machine Learning (SciML), Data Science, Mathematical Modeling, and Optimization).

## 📄 Curriculum Vitae
* **Descargar en formato PDF:**[ [Versión Impresa - Español]](./cv-latex/CV_Francisco_Garcia_Atienza_es.pdf)
* **Download in PDF format:**[ [Print Version - English]](./cv-latex/CV_Francisco_Garcia_Atienza_en.pdf)
* **Ladda ner i PDF-format:**[ [utskriftsversion - Svenska]](./cv-latex/CV_Francisco_Garcia_Atienza_sv.pdf)
 
## 💼 Research & Professional Experience
* **Graduate Researcher (Numerical Analysis & SciML)** | Lund University (2025-2026)
    * **Project:** Data-Driven Reduced-Order Modeling via Adjoint-Based Optimization.
    * *Description:* Developed a novel training framework coupling continuous-time operator inference with the adjoint-state method to construct robust, stable reduced-order models (ROMs) from noisy and sparsely sampled snapshot data. 
    * *Methodologies:* Formulated continuous adjoint equations for efficient gradient computation, implemented a gradient-based optimizer, and validated robustness against standard operator inference across multiple PDE systems (viscous Burgers’, 2D Fisher-KPP, and advection-diffusion equations).
    * *Publication:* D. Liu, **F. García Atienza**, M. Guo. *An adjoint method for training data-driven reduced-order models*. **Journal of Computational Physics** (Manuscript JCOMP-D-26-00090).
    * 📂 **Resources:** [[Preprint DOI (arXiv)]](https://doi.org/10.48550/arXiv.2601.07579) • [[Download PDF]](./cv-latex/adjoint_method_jcp.pdf)

## 🎓 Education
* **M.Sc. in Mathematics** | Lund University (2023 - 2025)
    * **Master's Thesis:** [“Training Robust Reduced-Order Models using the Adjoint Method”](https://lup.lub.lu.se/student-papers/record/9200627)
    * *Description:* Developed numerical techniques for constructing stable and efficient reduced-order models, leveraging adjoint-based optimization to enhance robustness in data-driven settings.
* **B.Sc. in Mathematics** | Lund University (2020 - 2023)
    * **Bachelor's Thesis:** [“A Continuous-Time ODE Framework to Centrality in Dynamic Networks”](https://lup.lub.lu.se/student-papers/record/9120052)
    * *Description:* Explored novel mathematical models for measuring centrality in evolving networks through a continuous-time ODE approach in order to analyze dynamic interactions.

## 🚀 Featured Projects

* **[MCMC: Monte Carlo Simulation of Potts & Ising Models](https://github.com/fragarat/MCMC)**
    * *Core:* High-performance Python framework utilizing Metropolis-Hastings Markov Chain Monte Carlo (MCMC) algorithms on 2D lattices.
    * *Application:* Simulates and visualizes spin configuration dynamics, phase transitions, and energy minimization in ferromagnetic systems under periodic boundary conditions.

* **[Random Forest: Predictive Plant Geography & Carbon Fluxes](https://github.com/fragarat/RandomForest)**
    * *Core:* Machine learning framework evaluating Random Forest Classifiers and Regressors as high-efficiency numerical surrogates for process-based vegetation models (LPJ-GUESS).
    * *Application:* Leverages climatic, edaphic, and geographic datasets to predict macro-scale biome distributions and carbon ecosystem fluxes ($VegC$), testing cross-continental predictability and generalization limits.

* **[Cell Reprogramming: Gene Regulatory Network Simulation](https://github.com/fragarat/CellReprogramming)**
    * *Core:* Systems biology framework modeling the establishment of cellular pluripotency via a non-linear system of Ordinary Differential Equations (ODEs).
    * *Application:* Simulates dynamic interactions within the Nanog-Oct4-Tet1 network to test cellular reprogramming strategies, tracking how transient overexpressions drive cells across non-linear bifurcation boundaries.

* **[Numerical Methods for Differential Equations (PDEs & ODEs)](https://github.com/fragarat/PDEs)**
    * *Core:* Comprehensive suite of advanced computational solvers for complex physical and dynamic systems.
    * [[Evolution Equations & FDMs]](https://github.com/fragarat/PDEs): Solves time-dependent parabolic/hyperbolic PDEs using advanced implicit/explicit time-stepping integration algorithms to analyze non-linear shock wave formation.
    * [[Two-Point BVPs & Sturm-Liouville]](https://github.com/fragarat/Schrodinger): Implements Finite Difference Methods (FDM) via sparse matrices to solve the Beam Equation and the Stationary Schrödinger Equation.
    * [[Adaptive Solvers & Stiffness]](https://github.com/fragarat/OdeStiffness): Codes adaptive numerical ODE solvers designed to handle severe stiffness phenomena in non-linear dynamics.

* **[Analysis of Augmented Krylov Subspace Methods](https://github.com/fragarat/AugmentedKrylov)**
    * *Core:* High-performance numerical linear algebra framework implementing advanced subspace acceleration techniques based on Yousef Saad's theoretical paradigms (1997).
    * *Application:* Benchmarks the convergence behaviors of standard, Restarted, Block, and Flexible/Deflated GMRES (DGMRES), analyzing how augmenting Krylov subspaces mitigates stalling effects caused by isolated eigenvalues near the origin.

* **[Non-Linear Least Squares Optimization: Gauss-Newton Method](https://github.com/fragarat/gaussnewton)**
    * *Core:* Robust, production-ready Python framework implementing the classic Gauss-Newton algorithm paired with a custom Armijo backtracking line search.
    * *Application:* Guarantees global convergence for fitting non-linear mathematical models to empirical datasets, showcasing clean software architecture and vectorized operations via NumPy.



<style>footer { display: none !important; }</style>
