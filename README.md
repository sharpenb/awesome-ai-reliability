# 🌟 Awesome AI Reliability 🌟

![Awesome](https://awesome.re/badge.svg) ![MIT License](https://img.shields.io/badge/license-MIT-brightgreen)

A curated list of resources about Machine Learning (ML) reliability. It covers trustworthiness of ML systems by including resources on the topics listed below and more! You can expect this repository to become more and more complete with time :)

### Topics Summary 🎨

| Topic            | Description                                    | Badge Example                                          |
|-------------------|------------------------------------------------|-------------------------------------------------------|
| **Uncertainty**   | Quantifying and managing uncertainty           | ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) |
| **Bayesian**      | Bayesian approaches to ML                      | ![Bayesian](https://img.shields.io/badge/Bayesian-lime) |
| **Robustness**    | Ensuring robustness to various conditions      | ![Robustness](https://img.shields.io/badge/Robustness-green) |
| **Attack**       | Exploring adversarial attacks                  | ![Attack](https://img.shields.io/badge/Attack-red) |
| **Defense**       | Defense mechanisms against vulnerabilities     | ![Defense](https://img.shields.io/badge/Defense-blue) |
| **Privacy**       | Addressing privacy concerns in ML systems      | ![Privacy](https://img.shields.io/badge/Privacy-purple) |
| **Fairness**      | Ensuring fairness and equity in AI             | ![Fairness](https://img.shields.io/badge/Fairness-teal) |
| **Explainability**| Improving interpretability of AI systems       | ![Explainability](https://img.shields.io/badge/Explainability-cyan) |

If you find this list helpful, give it a ⭐ on GitHub, share it, and feel free to contribute by submitting a pull request or issue!

---

## Table of Contents
- [Facts/Numbers 📊](#factsnumbers-📊)
- [Tools 🛠️](#tools-🛠️)
- [Newspaper Articles 📰](#newspaper-articles-📰)
- [Blog Articles 🗒️](#blog-articles-🗒️)
- [Research Articles 🕌](#research-articles-🕌)
- [Books 📚](#books-📚)
- [Lectures 🎓](#lectures-🎓)
- [People 🧑‍💻](#people-🧑‍💻)

---

## Facts 📊
- **Hundreds of millions**: Number of people interacting with AI models ([Source](https://arxiv.org/abs/2405.01470), 2024, [Source](https://arxiv.org/abs/2309.11998), 2024)
- **80%**: Percentage of ML projects that fail due to issues with data quality and system reliability ([Source](https://www.tomshardware.com/tech-industry/artificial-intelligence/research-shows-more-than-80-of-ai-projects-fail-wasting-billions-of-dollars-in-capital-and-resources-report), 2024).
- **60%**: Percentage of businesses using AI but which aren't developing ethical AI policies ([Source](https://www.venasolutions.com/blog/ai-statistics), 2024).
- **10,000+**: Research papers on ML robustness ([Source](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html), 2024).

---

## Tools 🛠️
- **[Uncertainty Baselines](https://github.com/google/uncertainty-baselines)**: High-quality implementations of standard and SOTA methods on a variety of tasks.
- **[Uncertainty Toolbox](https://uncertainty-toolbox.github.io/)**: A Python toolbox for predictive uncertainty quantification, calibration, metrics, and visualization.
- **[RobustBench](https://robustbench.github.io/)**: A standardized benchmark for adversarial robustness.
- **[TorchMetrics](https://lightning.ai/docs/torchmetrics/stable/)**: A collection of 100+ PyTorch metrics implementations and an easy-to-use API to create custom metrics.
- **[Cleanlab](https://github.com/cleanlab/cleanlab)**: A Python library for finding and fixing label errors in datasets.
- **[DeepChecks](https://github.com/deepchecks/deepchecks)**: Comprehensive library for testing ML systems and datasets.
- **[Laplace](https://github.com/AlexImmer/Laplace/)**: Flexible library for Laplace approximation for neural networks.
- **[Crepes](https://github.com/henrikbostrom/crepes)**: Python package for conformal prediction that implements conformal classifiers, regressors, and predictive systems on top of any standard classifier and regressor.

---

## Newspaper Articles 📰
- *"[Research shows more than 80% of AI projects fail, wasting billions of dollars in capital and resources: Report
](https://www.tomshardware.com/tech-industry/artificial-intelligence/research-shows-more-than-80-of-ai-projects-fail-wasting-billions-of-dollars-in-capital-and-resources-report)"* (2024) - [Tom's Hardware](https://www.tomshardware.com/)
- *"[80 AI Statistics Shaping Business in 2024](https://www.venasolutions.com/blog/ai-statistics)"* (2024) - [Vena Solutions](https://www.venasolutions.com/)
- *"[OopsGPT](https://www.theatlantic.com/technology/archive/2024/07/searchgpt-openai-error/679248/?)"* (2024) - [The Atlantic](https://www.theatlantic.com/world/)

---

## Blog Articles 📝
- *"[A Complete List of All (arXiv) Adversarial Example Papers](https://nicholas.carlini.com/writing/2019/all-adversarial-example-papers.html)"* (Maintained) ![Robustness](https://img.shields.io/badge/Robustness-green) ![Attack](https://img.shields.io/badge/Attack-red) ![Defense](https://img.shields.io/badge/Defense-blue) - [Nicholas Carlini](https://nicholas.carlini.com/)
- *"[Adversarial Machine Learning Reading List](https://nicholas.carlini.com/writing/2018/adversarial-machine-learning-reading-list.html)"* (2019) ![Robustness](https://img.shields.io/badge/Robustness-green) ![Attack](https://img.shields.io/badge/Attack-red) ![Defense](https://img.shields.io/badge/Defense-blue) - [Nicholas Carlini](https://nicholas.carlini.com/)

---

## Research Articles 📄
- *"Connecting the Dots: Is Mode-Connectedness the Key to Feasible Sample-Based Inference in Bayesian Neural Networks?"* (2024) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ICML
- *"Position: Bayesian Deep Learning is Needed in the Age of Large-Scale AI"* (2024) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ICML
- *"Bayesian Semi-structured Subspace Inference"* (2024) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - AISTATS
- *"AI generates covertly racist decisions about people based on their dialect"* (2024) ![Fairness](https://img.shields.io/badge/Fairness-teal) - Nature
- *"Training, Architecture, and Prior for Deterministic Uncertainty Methods?"* (2023) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Robustness](https://img.shields.io/badge/Robustness-green) - TrustML - ICLR
- *"Revisiting uncertainty estimation for node classification: New benchmark and insights"* (2023) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - OpenReview
- *"On second-order scoring rules for epistemic uncertainty quantification"* (2023) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ArXiv
- *"Disentangling epistemic and aleatoric uncertainty in reinforcement learning"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - DFUQ - ICML
- *"Towards OOD detection in graph classification from uncertainty estimation perspective"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ArXiv
- *"Pitfalls of epistemic uncertainty quantification through loss minimisation"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - NeurIPS
- *"Distributional Reinforcement Learning"* (2022) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - MIT Press
- *"Deep ensembles work, but are they necessary?"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Robustness](https://img.shields.io/badge/Robustness-green) - NeurIPS
- *"On the robustness and anomaly detection of sparse neural networks"* (2022) ![Robustness](https://img.shields.io/badge/Robustness-green) - SNN Workshop
- *"Natural posterior network: Deep Bayesian predictive uncertainty for exponential family distributions"* (2021) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ICLR
- *"A review of uncertainty quantification in deep learning: Techniques, applications and challenges"* (2021) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - Information Fusion
- *"Graph posterior network: Bayesian predictive uncertainty for node classification"* (2021) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - NeurIPS
- *"A gentle introduction to conformal prediction and distribution-free uncertainty quantification"* (2021) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ArXiv
- *"Adversarial attack for uncertainty estimation: Identifying critical regions in neural networks"* (2021) ![Attack](https://img.shields.io/badge/Attack-red) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - Neural Processing Letters
- *"Matérn Gaussian Processes on Graphs"* (2021) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - AISTATS
- *"Privacy Issues of AI"* (2021) ![Privacy](https://img.shields.io/badge/Privacy-purple) - Springer
- *"Getting a {clue}: A method for explaining uncertainty estimates"* (2021) ![Explainability](https://img.shields.io/badge/Explainability-cyan) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ICLR
- *"Evaluating robustness of predictive uncertainty estimation: Are Dirichlet-based models reliable?"* (2020) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Robustness](https://img.shields.io/badge/Robustness-green) ![Attack](https://img.shields.io/badge/Attack-red) ![Defense](https://img.shields.io/badge/Defense-blue) - ICML
- *"Deep evidential regression"* (2020) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - NeurIPS
- *"Posterior network: Uncertainty estimation without OOD samples via density-based pseudo-counts"* (2020) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - NeurIPS
- *"Efficient robustness certificates for discrete data: Sparsity-aware randomized smoothing for graphs, images and more"* (2020) ![Robustness](https://img.shields.io/badge/Robustness-green) - ICML
- *"Provable worst case guarantees for the detection of out-of-distribution data"* (2020) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - NeurIPS
- *"Cold posteriors and aleatoric uncertainty"* (2020) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - ArXiv
- *"Uncertainty on asynchronous time event prediction"* (2019) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - NeurIPS
- *"Uncertainty-based continual learning with adaptive regularization"* (2019) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - NeurIPS
- *"Certifiable robustness to graph perturbations"* (2019) ![Robustness](https://img.shields.io/badge/Robustness-green) - NeurIPS
- *"Explainable artificial intelligence (XAI): Concepts, taxonomies, opportunities and challenges toward responsible AI"* (2019) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - Information Fusion
- *"Bayesian robust attributed graph clustering: Joint learning of partial anomalies and group structure"* (2018) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Robustness](https://img.shields.io/badge/Robustness-green) - AAAI
- *"BayesGrad: Explaining predictions of graph convolutional networks"* (2018) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - NeurIPS
- *"Concerns about human agency, evolution and survival"* (2018) ![Fairness](https://img.shields.io/badge/Fairness-teal) - Pew Research
- *"Deep Gaussian embedding of graphs: Unsupervised inductive learning via ranking"* (2017) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - ArXiv
- *"Variational inference: A review for statisticians"* (2017) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - Journal of the American Statistical Association
- *"A distributional perspective on reinforcement learning"* (2017) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - ICML
- *"A general framework for updating belief distributions"* (2016) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - Journal of the Royal Statistical Society
- *"Concrete problems in AI safety"* (2016) ![Defense](https://img.shields.io/badge/Defense-blue) - ArXiv
- *"Weight uncertainty in neural networks"* (2015) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - ICML
- *"The fundamental incompatibility of scalable Hamiltonian Monte Carlo and naive data subsampling"* (2015) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - ICML
- *"Superintelligence: Paths, Dangers, Strategies"* (2014) ![Fairness](https://img.shields.io/badge/Fairness-teal) - Oxford University Press
- *"Fluctuations in uncertainty"* (2014) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - Journal of Economic Perspectives
- *"Analysis of Thompson sampling for the multi-armed bandit problem"* (2012) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - COLT
  
---

## Books 📚
- **[Introduction to AI Safety, Ethics, and Society](https://www.youtube.com/watch?v=veYq6EWZyVc)** (2024), Dan Hendrycks
- **[Uncertainty Estimation for Independent and Non-Independent Data](https://mediatum.ub.tum.de/doc/1705567/x8kpdzxccp0egtst8uh60kfj1.dissertation.pdf)** (2024) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Bayesian](https://img.shields.io/badge/Bayesian-lime), Bertrand Charpentier
- **[Uncertainty in Deep Learning](https://www.cs.ox.ac.uk/people/yarin.gal/website/thesis/thesis.pdf)** (2016) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Bayesian](https://img.shields.io/badge/Bayesian-lime), Yarin Gal


---

## Lectures 🎓
- **[Introduction to Uncertainty in Deep Learning](https://www.gatsby.ucl.ac.uk/~balaji/balaji-uncertainty-talk-cifar-dlrl.pdf)** (2020) - NeurIPS Tutorial by Balaji Lakshminarayanan (Google Brain)
- **[Practical Uncertainty Estimation and OOD Robustness in Deep Learning](https://www.youtube.com/watch?v=veYq6EWZyVc)** (2022) - MIT Lecture by Jaspaer Snoek (Google Brain)

---

## People 🧑‍💻

| Name | Affiliation | Research Interests | Social Media |
|------|-------------|-------------------|--------------|
| **Agustinus Kristiadi** | Postdoc, Vector Institute | <sub>Probabilistic Inference, Decision-making, Foundation Models, AI4Science, Riemmanian Geometry</sub> | - |
| **Aleksandar Bojchevski** | University of Cologne | <sub>Machine Learning, Graphs/Networks, Trustworthy, Robustness, Uncertainty</sub> | - |
| **Alexander Amini** | Computer Science, Massachusetts Institute of Technology | <sub>Deep Learning, Artificial Intelligence, Robotics, Big Data</sub> | - |
| **Alexander Immer** | PhD student, ETH Zürich, Max Planck Institute for Intelligent Systems | <sub>Machine Learning, Approximate Bayesian Inference</sub> | - |
| **Aliaksandr Hubin** | PhD, Associate Professor, University of Oslo, NMBU, OUC | <sub>Statistics, Artificial Intelligence, Applied Statistics, Machine Learning, Operations Research</sub> | - |
| **Amartya Sanyal** | University of Copenhagen | <sub>Privacy, Machine Learning, Adversarial Learning, Learning Theory, Robustness</sub> | - |
| **Amini Mitamo Alexandre** | Junior Lecturer, Université Catholique du Graben | <sub>Urology</sub> | - |
| **Andrew Gordon Wilson** | New York University | <sub>Machine Learning, Computer Science, Artificial Intelligence, Gaussian Processes, Deep Learning</sub> | - |
| **Balaji Lakshminarayanan** | Senior Staff Research Scientist at Google DeepMind | <sub>Machine Learning</sub> | - |
| **Bertrand Charpentier** | Pruna AI, Ex-Technical University of Munich, Ex-Twitter | <sub>Machine Learning, Efficiency, Uncertainty, Causality, Hierarchy</sub> | <sub>[Website](https://sharpenb.github.io/) - [Twitter](https://x.com/Bertrand_Charp) - [Bluesky](https://bsky.app/profile/bertrand-sharp.bsky.social) - [LinkedIn](https://www.linkedin.com/in/bertrand-charpentier-76995ab6/)</sub> |
| **Christian Szegedy** | Researcher | <sub>Deep learning, Formal reasoning</sub> | - |
| **Christopher Nemeth** | Professor in Probabilistic Machine Learning, Lancaster University, UKRI Turing AI Fellow | <sub>Bayesian inference, Computational Statistics, Monte Carlo methods, Machine Learning, Statistics</sub> | - |
| **Dan Hendrycks** | Director of the Center for AI Safety (advisor for xAI and Scale) | <sub>AI Safety, ML Reliability</sub> | - |
| **Daniel Zügner** | Microsoft Research | <sub>Machine Learning, Deep Learning on Graphs</sub> | - |
| **David Dunson** | Arts & Sciences Professor of Statistical Science & Mathematics | <sub>Bayesian statistics, machine learning, biostatistics, ecology, neuroscience</sub> | - |
| **David Rügamer** | Professor at LMU Munich, PI at Munich Center for Machine Learning | <sub>Deep Learning, Uncertainty Quantification, Optimization, Statistics</sub> | <sub>[Website](https://davidruegamer.github.io/)</sub> |
| **Dominik Fuchsgruber** | PhD student, Technical University of Munich | <sub>machine learning, uncertainty estimation</sub> | - |
| **Dylan Wiwad** | Slack | <sub>Socioeconomic Inequality, Psychometrics, Item Response Theory, Prosocial behavior, Political Ideology</sub> | - |
| **Emanuel Sommer** | PhD Candidate @ Data Science Group of the Department of Statistics, LMU Munich | <sub>Statistics, Machine Learning</sub> | <sub>[Website](https://emanuelsommer.github.io/my-yourney/) - [LinkedIn](https://www.linkedin.com/in/emanuelsommer/)</sub> |
| **Eric Nalisnick** | Assistant Professor, Johns Hopkins University | <sub>Machine Learning</sub> | - |
| **Eric Wong** | University of Pennsylvania | <sub>Reliable Machine Learning, Optimization, Explainability, Robustness, Debugging</sub> | - |
| **Eyke Hüllermeier** | Professor of Computer Science, Paderborn University | <sub>Artificial Intelligence, Machine Learning, Fuzzy Logic, Bioinformatics</sub> | - |
| **Fereshte Khani** | OpenAI | <sub>machine learning, reliability, alignment, robustness, fairness</sub> | - |
| **François-Xavier Briol** | Associate Professor in Statistical Science, UCL | <sub>Bayesian Computation, Statistical Machine Learning, Computational Statistics, Robustness</sub> | - |
| **Gautam Kamath** | Assistant Professor @ University of Waterloo, Faculty Member @ Vector Institute | <sub>Statistics, Machine Learning, Privacy, Robustness</sub> | - |
| **Hadi Salman** | OpenAI, MIT | <sub>Deep Learning, Robustness, Trustworthy ML, LLMs</sub> | - |
| **Hassan Ashtiani** | McMaster University | <sub>Machine Learning, Statistics, Privacy, Robustness</sub> | - |
| **Jan Schuchardt** | Technical University of Munich | <sub>Adversarial Robustness, Graph Machine Learning, Geometric Machine Learning, Differential Privacy</sub> | - |
| **Johannes Gasteiger, né Klicpera** | Anthropic | <sub>Machine Learning, AI Safety, Graphs, Robustness</sub> | - |
| **Josh Gardner** | Apple | <sub>Machine Learning, Robustness, Multimodal, Tabular Data, Music and Audio</sub> | - |
| **José Miguel Hernández-Lobato** | Professor of Machine Learning, University of Cambridge | <sub>Bayesian deep learning, approximate inference, deep generative modeling, automatic molecular design, reinforcement learning</sub> | - |
| **Julyan Arbel** | Inria - Univ. Grenoble Alpes | <sub>Bayesian deep learning, Bayesian nonparametrics, Statistics</sub> | - |
| **Karen Simonyan** | Chief Scientist, Microsoft AI | <sub>Artificial Intelligence, Deep Learning</sub> | - |
| **Konstantina Palla** | Spotify | <sub>Machine Learning</sub> | - |
| **Laurence Aitchison** | University of Bristol | <sub>Deep Learning</sub> | - |
| **Maksym Andriushchenko** | Postdoctoral Researcher at EPFL | <sub>Generalization, Robustness, AI Safety, LLMs</sub> | - |
| **Maria Skoularidou,** | Postdoctoral Fellow, Schmidt Center, The Broad Institute of M.I.T. and Harvard | <sub>Diffusion Models, Probabilistic Machine Learning, Computational Genomics and Imaging, Bayesian</sub> | - |
| **Maurizio Filippone** | Associate Professor - Statistics Program, KAUST | <sub>Bayesian Deep Learning, Gaussian Processes, Bayesian Inference, Computational Statistics</sub> | - |
| **Max Welling** | CAIO CuspAI &  Professor Machine Learning, University of Amsterdam | <sub>Machine Learning, Artificial Intelligence, Statistics</sub> | - |
| **Michael A Osborne** | Professor of Machine Learning, University of Oxford | <sub>Machine Learning, Technological Change, Probabilistic Numerics, Bayesian Optimization, Gaussian Processes</sub> | - |
| **Mohammad Emtiyaz Khan** | Center for Advanced Intelligence Project (AIP), RIKEN, Tokyo | <sub>Machine Learning, Approximate Bayesian Inference, Deep Learning, Artificial Intelligence</sub> | - |
| **Natalie Dullerud** | Ph.D. Student, Stanford University | <sub>machine learning, fairness, privacy, robustness</sub> | - |
| **Nazneen Rajani** | Hugging Face | <sub>Evaluation, Robustness, Interpretability, Natural Language Processing, Deep Learning</sub> | - |
| **Nicholas Carlini** | Google DeepMind | <sub></sub> | - |
| **Nick Bostrom** | Professor, Director of the Future of Humanity Institute, Oxford University | <sub>Philosophy, Artificial Intelligence, Ethics, Technology</sub> | - |
| **Nick Pawlowski** | Senior Researcher, Microsoft Research | <sub>Uncertainty Quantification, Causality, Robustness, Bayesian Deep Learning, Medical Image Analysis</sub> | - |
| **Philipp Hennig** | University of Tübingen | <sub>Probabilistic Numerics, Machine Learning, Computer Science</sub> | - |
| **Polina Kirichenko** | New York University | <sub>Deep Learning, Robustness, Uncertainty Estimation, Generative Models</sub> | - |
| **Rob Romijnders** | PhD with Max Welling, Christos Louizos, Yuki M Asano, sponsored by Qualcomm; prev. Google Research | <sub>Differential Privacy, Representation learning, Statistical Methods, Information Theory</sub> | - |
| **Robert Geirhos** | Research Scientist, Google DeepMind | <sub>Understanding DNNs, Deep Learning, Robustness, Human Vision, Psychophysics</sub> | - |
| **Ruqi Zhang** | Assistant Professor of Computer Science, Purdue University | <sub>Machine Learning, Artificial Intelligence, Deep Learning, Statistics</sub> | - |
| **Sara Hooker** | Head of Cohere For AI | <sub>Machine learning efficiency, robustness, interpretability, trustworthy ML</sub> | - |
| **Serena Wang** | UC Berkeley | <sub>machine learning, robustness, optimization, algorithms and society, causal inference</sub> | - |
| **Shaokai Ye** | EPFL | <sub>LLM agents, Foundation models, Robustness, Model Compression</sub> | - |
| **Simon Batzner** | Google DeepMind | <sub>Deep Learning, Robustness, Graph Neural Networks, Physics</sub> | - |
| **Souradip Chakraborty** | University of Maryland, College Park - Past : ML Research@Walmart Labs | <sub>Reinforcement Learning, Deep Learning, Robustness, Uncertainty</sub> | - |
| **Stephan Günnemann** | Professor of Computer Science, Technical University of Munich | <sub>Machine Learning, Graphs, Graph Neural Networks, Robustness</sub> | - |
| **Stephan Mandt** | Associate Professor, University of California, Irvine | <sub>Machine Learning, Variational Inference, Neural Data Compression, ML for Science, Generative Models</sub> | - |
| **Stephen Casper** | PhD student, MIT | <sub>AI safety, AI responsibility, red-teaming, robustness, auditing</sub> | - |
| **Sushrut Karmalkar** | University of Wisconsin-Madison | <sub>Algorithms, Complexity, Regression, Robustness</sub> | - |
| **Theodore Papamarkou** | Distinguished professor, Zhejiang Normal University | <sub>Bayesian deep learning, Topological deep learning, Computing for healthcare</sub> | - |
| **Theofanis Karaletsos** | Head of AI, CZI-Science | <sub>Machine Learning, Probabilistic Modeling, Computer Vision, Computational Biology, Computational</sub> | - |
| **Tim G. J. Rudner** | Faculty Fellow, New York University | <sub>Robust Machine Learning, Uncertainty Quantification, Technical AI Governance, ML for Health</sub> | - |
| **Timnit Gebru** | Google | <sub>fairness</sub> | - |
| **Tom Wollschläger** | PhD Student in Machine Learning, TUM | <sub>machine learning, graph neural networks, quantum machine learning, uncertainty and robustness</sub> | - |
| **Vignesh Srinivasan** | Fraunhofer HHI | <sub>Machine Learning, Artificial Intelligence, Robustness</sub> | - |
| **Viktor Bengs** | LMU Munich | <sub>Bandit algorithms, Preference learning, Algorithm configuration, Change-point problems</sub> | - |
| **Vincent Fortuin** | Principal Investigator, Helmholtz AI & TU Munich | <sub>Bayesian deep learning, Deep generative AI, PAC-Bayes</sub> | - |
| **Yarin Gal** | Associate Professor, University of Oxford | <sub>Machine Learning, Artificial Intelligence, Probability Theory, Statistics</sub> | - |
| **Yee Whye Teh** | Professor of Statistical Machine Learning, Oxford, Research Scientist, DeepMind | <sub>Machine Learning, Artificial Intelligence, Statistics, Computer Science</sub> | - |
| **Yingzhen Li** | Imperial College London | <sub>Artificial Intelligence, Machine Learning, Statistics</sub> | - |
| **Zoubin Ghahramani** | Professor, University of Cambridge, and Distinguished Researcher, Google | <sub>Machine Learning, Bayesian Statistics, Neural Networks, Artificial Intelligence</sub> | - |

<img src="citations_per_author.png" width="800"/>
![Citations per Year](citations_by_year.png)
![Coauthorship Network](coauthorship_network.png)
![Citations per Author](citations_per_author.png)

---

## Contributing 🤝
We welcome contributions! Please follow our [contribution guidelines](CONTRIBUTING.md) to share resources, tools, or ideas that align with the theme of ML reliability.

---

## License 📄
This project is licensed under the [MIT License](LICENSE). Feel free to share and use the resources as needed.

---
