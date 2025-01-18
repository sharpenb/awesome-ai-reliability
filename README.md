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
- **Bertrand Charpentier** - Working in academia and industry on Bayesian deep learning and uncertainty estimation. [Website](https://sharpenb.github.io/) | [Twitter](https://x.com/Bertrand_Charp) | [Bluesky](https://bsky.app/profile/bertrand-sharp.bsky.social) | [LinkedIn](https://www.linkedin.com/in/bertrand-charpentier-76995ab6/)
- **Stephan Günnemann** - Working in academia on robust machine learning and graph neural networks. 
- **Eyke Hüllermeier** - Working in academia on uncertainty quantification and decision theory. 
- **Viktor Bengs** - Working in academia on uncertainty quantification and decision theory.
- **Eric Nalisnick** - Working in academia on Bayesian deep learning and uncertainty estimation.
- **David Rügamer** - Working in academia on Bayesian/probabilistic deep learning and optimization. [Website](https://davidruegamer.github.io/)
- **Emanuel Sommer** - Working in academia on (sampling-based) Bayesian deep learning. [Website](https://emanuelsommer.github.io/my-yourney/) | [LinkedIn](https://www.linkedin.com/in/emanuelsommer/)
- **Timnit Gebru** - Working in industry on fairness and ethical AI.
- **Yarin Gal** - Working in academia on Bayesian methods and predictive uncertainty.
- **Zoubin Ghahramani** - Working in industry and academia on probabilistic models and Bayesian methods.
- **Balaji Lakshminarayanan** - Working in industry on deep ensembles and predictive uncertainty.
- **Dan Hendrycks** - Working in academia on robustness to distribution shifts and ML reliability.
- **Alexander Amini** - Working in academia on evidential learning and autonomous systems.
- **Nicholas Carlini** - Working in industry on adversarial robustness and secure ML.
- **Karen Simonyan** - Working in industry on vision-based reliability in deep learning.
- **Christian Szegedy** - Working in industry on adversarial defenses and vision.
- **Nick Bostrom** - Working in academia on AI safety and societal impacts.
- **Theodore Papamarkou** - Working in academia on Bayesian methods and uncertainty quantification.
- **Maria Skoularidou** - Working in academia on probabilistic models and generative AI.
- **Konstantina Palla** - Working in academia on Bayesian statistics and machine learning.
- **Laurence Aitchison** - Working in academia on neural computation and Bayesian methods.
- **Julyan Arbel** - Working in academia on probabilistic modeling and statistical inference.
- **David Dunson** - Working in academia on Bayesian inference and uncertainty quantification.
- **Maurizio Filippone** - Working in academia on scalable Gaussian processes and Bayesian methods.
- **Vincent Fortuin** - Working in academia on uncertainty estimation and deep learning.
- **Philipp Hennig** - Working in academia on optimization and probabilistic numerics.
- **Jose Miguel Hernandez-Lobato** - Working in academia on Bayesian deep learning.
- **Aliaksandr Hubin** - Working in academia on Bayesian statistics and model selection.
- **Alexander Immer** - Working in academia on Bayesian inference and machine learning.
- **Theofanis Karaletsos** - Working in academia and industry on Bayesian methods and generative models.
- **Mohammad Emtiyaz Khan** - Working in academia on variational inference and scalable Bayesian methods.
- **Agustinus Kristiadi** - Working in academia on uncertainty estimation and Bayesian deep learning.
- **Yingzhen Li** - Working in academia on probabilistic inference and Bayesian neural networks.
- **Stephan Mandt** - Working in academia on probabilistic modeling and scalable inference.
- **Christopher Nemeth** - Working in academia on statistical methods and uncertainty quantification.
- **Michael A. Osborne** - Working in academia on Bayesian optimization and probabilistic inference.
- **Tim G. J. Rudner** - Working in academia on reinforcement learning and Bayesian methods.
- **David Rugamer** - Working in academia on statistical modeling and Bayesian methods.
- **Yee Whye Teh** - Working in academia on Bayesian nonparametrics and deep learning.
- **Max Welling** - Working in academia on scalable Bayesian methods and probabilistic modeling.
- **Andrew Gordon Wilson** - Working in academia on Gaussian processes and probabilistic machine learning.
- **Ruqi Zhang** - Working in academia on Bayesian inference and deep generative models.

| Name | Affiliation | Research Interests | Social Media |
|------|-------------|-------------------|--------------|
| **Agustinus Kristiadi** | Postdoc, Vector Institute | <small>Probabilistic Inference, Decision-making, Foundation Models, AI4Science, Riemmanian Geometry</small> | - |
| **Aleksandar Bojchevski** | University of Cologne | <small>Machine Learning, Graphs/Networks, Trustworthy, Robustness, Uncertainty</small> | - |
| **Alexander Amini** | Computer Science, Massachusetts Institute of Technology | <small>Deep Learning, Artificial Intelligence, Robotics, Big Data</small> | - |
| **Alexander Immer** | PhD student, ETH Zürich, Max Planck Institute for Intelligent Systems | <small>Machine Learning, Approximate Bayesian Inference</small> | - |
| **Aliaksandr Hubin** | PhD, Associate Professor, University of Oslo, NMBU, OUC | <small>Statistics, Artificial Intelligence, Applied Statistics, Machine Learning, Operations Research</small> | - |
| **Amartya Sanyal, Ph.D.** | Associate Professor, BITS-Pilani Hyderabad Campus, India | <small>Genome Biology, Epigenetics, Genomics</small> | - |
| **Andrew Gordon Wilson** | New York University | <small>Machine Learning, Computer Science, Artificial Intelligence, Gaussian Processes, Deep Learning</small> | - |
| **Balaji Lakshminarayanan** | Senior Staff Research Scientist at Google DeepMind | <small>Machine Learning</small> | - |
| **Bertrand Charpentier** | Pruna AI, Ex-Technical University of Munich, Ex-Twitter | <small>Machine Learning, Efficiency, Uncertainty, Causality, Hierarchy</small> | - |
| **Christian Szegedy** | Researcher | <small>Deep learning, Formal reasoning</small> | - |
| **Christopher Nemeth** | Professor in Probabilistic Machine Learning, Lancaster University, UKRI Turing AI Fellow | <small>Bayesian inference, Computational Statistics, Monte Carlo methods, Machine Learning, Statistics</small> | - |
| **Dan Hendrycks** | Director of the Center for AI Safety (advisor for xAI and Scale) | <small>AI Safety, ML Reliability</small> | - |
| **Daniel Zügner** | Microsoft Research | <small>Machine Learning, Deep Learning on Graphs</small> | - |
| **David Dunson** | Arts & Sciences Professor of Statistical Science & Mathematics | <small>Bayesian statistics, machine learning, biostatistics, ecology, neuroscience</small> | - |
| **David Rügamer** | Professor at LMU Munich, PI at Munich Center for Machine Learning | <small>Deep Learning, Uncertainty Quantification, Optimization, Statistics</small> | - |
| **Dominik Fuchsgruber** | PhD student, Technical University of Munich | <small>machine learning, uncertainty estimation</small> | - |
| **Dylan Slack** | Google | <small>deep learning, natural language processing, robustness</small> | - |
| **Emanuel Sommer** | PhD Candidate @ Data Science Group of the Department of Statistics, LMU Munich | <small>Statistics, Machine Learning</small> | - |
| **Eric C. Wong** | Professor of Radiology and Psychiatry, University of California, San Diego | <small>Magnetic Resonance Imaging, Arterial Spin Labeling, Functional MRI, Ultrafast MRI, Diffusion MRI</small> | - |
| **Eric Nalisnick** | Assistant Professor, Johns Hopkins University | <small>Machine Learning</small> | - |
| **Eyke Hüllermeier** | Professor of Computer Science, Paderborn University | <small>Artificial Intelligence, Machine Learning, Fuzzy Logic, Bioinformatics</small> | - |
| **Fereshte Khani** | OpenAI | <small>machine learning, reliability, alignment, robustness, fairness</small> | - |
| **François-Xavier Briol** | Associate Professor in Statistical Science, UCL | <small>Bayesian Computation, Statistical Machine Learning, Computational Statistics, Robustness</small> | - |
| **Gautam Kamath** | Assistant Professor @ University of Waterloo, Faculty Member @ Vector Institute | <small>Statistics, Machine Learning, Privacy, Robustness</small> | - |
| **Hadi Salman** | OpenAI, MIT | <small>Deep Learning, Robustness, Trustworthy ML, LLMs</small> | - |
| **Johannes Gasteiger, né Klicpera** | Anthropic | <small>Machine Learning, AI Safety, Graphs, Robustness</small> | - |
| **Josh Gardner** | Apple | <small>Machine Learning, Robustness, Multimodal, Tabular Data, Music and Audio</small> | - |
| **José Miguel Hernández-Lobato** | Professor of Machine Learning, University of Cambridge | <small>Bayesian deep learning, approximate inference, deep generative modeling, automatic molecular design, reinforcement learning</small> | - |
| **Julyan Arbel** | Inria - Univ. Grenoble Alpes | <small>Bayesian deep learning, Bayesian nonparametrics, Statistics</small> | - |
| **Karen Simonyan** | Chief Scientist, Microsoft AI | <small>Artificial Intelligence, Deep Learning</small> | - |
| **Konstantina Palla** | Spotify | <small>Machine Learning</small> | - |
| **Laurence Aitchison** | University of Bristol | <small>Deep Learning</small> | - |
| **Maksym Andriushchenko** | Postdoctoral Researcher at EPFL | <small>Generalization, Robustness, AI Safety, LLMs</small> | - |
| **Maria Skoularidou,** | Postdoctoral Fellow, Schmidt Center, The Broad Institute of M.I.T. and Harvard | <small>Diffusion Models, Probabilistic Machine Learning, Computational Genomics and Imaging, Bayesian</small> | - |
| **Maurizio Filippone** | Associate Professor - Statistics Program, KAUST | <small>Bayesian Deep Learning, Gaussian Processes, Bayesian Inference, Computational Statistics</small> | - |
| **Max Welling** | CAIO CuspAI &  Professor Machine Learning, University of Amsterdam | <small>Machine Learning, Artificial Intelligence, Statistics</small> | - |
| **Michael A Osborne** | Professor of Machine Learning, University of Oxford | <small>Machine Learning, Technological Change, Probabilistic Numerics, Bayesian Optimization, Gaussian Processes</small> | - |
| **Mohammad Emtiyaz Khan** | Center for Advanced Intelligence Project (AIP), RIKEN, Tokyo | <small>Machine Learning, Approximate Bayesian Inference, Deep Learning, Artificial Intelligence</small> | - |
| **Natalie Dullerud** | Ph.D. Student, Stanford University | <small>machine learning, fairness, privacy, robustness</small> | - |
| **Nazneen Rajani** | Hugging Face | <small>Evaluation, Robustness, Interpretability, Natural Language Processing, Deep Learning</small> | - |
| **Nicholas Carlini** | Google DeepMind | <small></small> | - |
| **Nick Bostrom** | Professor, Director of the Future of Humanity Institute, Oxford University | <small>Philosophy, Artificial Intelligence, Ethics, Technology</small> | - |
| **Nick Pawlowski** | Senior Researcher, Microsoft Research | <small>Uncertainty Quantification, Causality, Robustness, Bayesian Deep Learning, Medical Image Analysis</small> | - |
| **Philipp Hennig** | University of Tübingen | <small>Probabilistic Numerics, Machine Learning, Computer Science</small> | - |
| **Polina Kirichenko** | New York University | <small>Deep Learning, Robustness, Uncertainty Estimation, Generative Models</small> | - |
| **Robert Geirhos** | Research Scientist, Google DeepMind | <small>Understanding DNNs, Deep Learning, Robustness, Human Vision, Psychophysics</small> | - |
| **Ruqi Zhang** | Assistant Professor of Computer Science, Purdue University | <small>Machine Learning, Artificial Intelligence, Deep Learning, Statistics</small> | - |
| **Sara Hooker** | Head of Cohere For AI | <small>Machine learning efficiency, robustness, interpretability, trustworthy ML</small> | - |
| **Serena Wang** | UC Berkeley | <small>machine learning, robustness, optimization, algorithms and society, causal inference</small> | - |
| **Seyed-Hassan Miraei Ashtiani** | PhD in Biosystems Engineering | <small>Food Safety, Postharvest Engineering, Digital Agriculture, Artificial Intelligence</small> | - |
| **Shaokai Ye** | EPFL | <small>LLM agents, Foundation models, Robustness, Model Compression</small> | - |
| **Simon Batzner** | Google DeepMind | <small>Deep Learning, Robustness, Graph Neural Networks, Physics</small> | - |
| **Souradip Chakraborty** | University of Maryland, College Park | Past : ML Research@Walmart Labs | <small>Reinforcement Learning, Deep Learning, Robustness, Uncertainty</small> | - |
| **Stephan Günnemann** | Professor of Computer Science, Technical University of Munich | <small>Machine Learning, Graphs, Graph Neural Networks, Robustness</small> | - |
| **Stephan Mandt** | Associate Professor, University of California, Irvine | <small>Machine Learning, Variational Inference, Neural Data Compression, ML for Science, Generative Models</small> | - |
| **Stephen Casper** | PhD student, MIT | <small>AI safety, AI responsibility, red-teaming, robustness, auditing</small> | - |
| **Sushrut Karmalkar** | University of Wisconsin-Madison | <small>Algorithms, Complexity, Regression, Robustness</small> | - |
| **Theodore Papamarkou** | Distinguished professor, Zhejiang Normal University | <small>Bayesian deep learning, Topological deep learning, Computing for healthcare</small> | - |
| **Theofanis Karaletsos** | Head of AI, CZI-Science | <small>Machine Learning, Probabilistic Modeling, Computer Vision, Computational Biology, Computational</small> | - |
| **Tim G. J. Rudner** | Faculty Fellow, New York University | <small>Robust Machine Learning, Uncertainty Quantification, Technical AI Governance, ML for Health</small> | - |
| **Timnit Gebru** | Google | <small>fairness</small> | - |
| **Tom Wollschläger** | PhD Student in Machine Learning, TUM | <small>machine learning, graph neural networks, quantum machine learning, uncertainty and robustness</small> | - |
| **Vignesh Srinivasan** | Fraunhofer HHI | <small>Machine Learning, Artificial Intelligence, Robustness</small> | - |
| **Viktor Bengs** | LMU Munich | <small>Bandit algorithms, Preference learning, Algorithm configuration, Change-point problems</small> | - |
| **Vincent Fortuin** | Principal Investigator, Helmholtz AI & TU Munich | <small>Bayesian deep learning, Deep generative AI, PAC-Bayes</small> | - |
| **Yarin Gal** | Associate Professor, University of Oxford | <small>Machine Learning, Artificial Intelligence, Probability Theory, Statistics</small> | - |
| **Yee Whye Teh** | Professor of Statistical Machine Learning, Oxford, Research Scientist, DeepMind | <small>Machine Learning, Artificial Intelligence, Statistics, Computer Science</small> | - |
| **Ying Zhen Li** | RISE Research Institutes of Sweden | <small>tunnel fire, fire dynamics, alternative fuel vehicle safety, scaling, CFD modelling</small> | - |
| **Zoubin Ghahramani** | Professor, University of Cambridge, and Distinguished Researcher, Google | <small>Machine Learning, Bayesian Statistics, Neural Networks, Artificial Intelligence</small> | - |

---

## Contributing 🤝
We welcome contributions! Please follow our [contribution guidelines](CONTRIBUTING.md) to share resources, tools, or ideas that align with the theme of ML reliability.

---

## License 📄
This project is licensed under the [MIT License](LICENSE). Feel free to share and use the resources as needed.

---
