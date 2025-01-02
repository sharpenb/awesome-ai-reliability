# 🌟 Awesome ML Reliability 🌟

![Awesome](https://awesome.re/badge.svg) ![MIT License](https://img.shields.io/badge/license-MIT-brightgreen)

A curated list of resources about Machine Learning (ML) reliability. It covers trustworthiness of ML systems by including resources on the topics listed below and more!

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
- *"[AI generates covertly racist decisions about people based on their dialect](https://www.nature.com/articles/s41586-024-07856-5)"* (2024) ![Fairness](https://img.shields.io/badge/Fairness-teal) - [Nature](https://www.nature.com/)
- *"[Training, Architecture, and Prior for Deterministic Uncertainty Methods?](https://openreview.net/forum?id=training-architecture-prior-dum)"* (2023) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Robustness](https://img.shields.io/badge/Robustness-green) - [TrustML - ICLR](https://iclr.cc/)
- *"[Revisiting uncertainty estimation for node classification: New benchmark and insights](https://openreview.net/forum?id=DB3BH3arU2Y)"* (2023) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [OpenReview](https://openreview.net/)
- *"[On second-order scoring rules for epistemic uncertainty quantification](https://arxiv.org/abs/2301.00345)"* (2023) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [ArXiv](https://arxiv.org/)
- *"[Disentangling epistemic and aleatoric uncertainty in reinforcement learning](https://proceedings.mlr.press/v162/aleatoric-epistemic-uncertainty-rl.pdf)"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - [DFUQ - ICML](https://icml.cc/)
- *"[Towards OOD detection in graph classification from uncertainty estimation perspective](https://arxiv.org/abs/2203.01791)"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [ArXiv](https://arxiv.org/)
- *"[Pitfalls of epistemic uncertainty quantification through loss minimisation](https://papers.nips.cc/paper/2022/file/epistemic-uncertainty.pdf)"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [NeurIPS](https://nips.cc/)
- *"[Distributional Reinforcement Learning](https://mitpress.mit.edu/9780262048261/)"* (2022) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - [MIT Press](https://mitpress.mit.edu/)
- *"[Deep ensembles work, but are they necessary?](https://papers.nips.cc/paper/2022/file/deep-ensembles.pdf)"* (2022) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Robustness](https://img.shields.io/badge/Robustness-green) - [NeurIPS](https://nips.cc/)
- *"[On the robustness and anomaly detection of sparse neural networks](https://arxiv.org/abs/2205.11789)"* (2022) ![Robustness](https://img.shields.io/badge/Robustness-green) - [SNN Workshop](https://neurips.cc/)
- *"[Natural posterior network: Deep Bayesian predictive uncertainty for exponential family distributions](https://openreview.net/forum?id=natpn)"* (2021) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [ICLR](https://iclr.cc/)
- *"[A review of uncertainty quantification in deep learning: Techniques, applications and challenges](https://doi.org/10.1016/j.inffus.2021.01.001)"* (2021) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [Information Fusion](https://www.journals.elsevier.com/information-fusion)
- *"[Graph posterior network: Bayesian predictive uncertainty for node classification](https://papers.nips.cc/paper/2021/file/graph-postnet.pdf)"* (2021) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [NeurIPS](https://nips.cc/)
- *"[A gentle introduction to conformal prediction and distribution-free uncertainty quantification](https://arxiv.org/abs/2107.07511)"* (2021) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [ArXiv](https://arxiv.org/)
- *"[Adversarial attack for uncertainty estimation: Identifying critical regions in neural networks](https://doi.org/10.1007/s11063-021-10562-3)"* (2021) ![Attack](https://img.shields.io/badge/Attack-red) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [Neural Processing Letters](https://www.springer.com/journal/11063)
- *"[Matérn Gaussian Processes on Graphs](https://proceedings.mlr.press/v130/borovitskiy21a.html)"* (2021) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [AISTATS](https://aistats.org/)
- *"[Privacy Issues of AI](https://link.springer.com/book/10.1007/978-3-030-75200-4)"* (2021) ![Privacy](https://img.shields.io/badge/Privacy-purple) - [Springer](https://link.springer.com/)
- *"[Getting a {clue}: A method for explaining uncertainty estimates](https://openreview.net/forum?id=clue)"* (2021) ![Explainability](https://img.shields.io/badge/Explainability-cyan) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [ICLR](https://iclr.cc/)
- *"[Evaluating robustness of predictive uncertainty estimation: Are Dirichlet-based models reliable?](https://proceedings.mlr.press/v119/dbu-robustness.pdf)"* (2020) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) ![Robustness](https://img.shields.io/badge/Robustness-green) ![Attack](https://img.shields.io/badge/Attack-red) ![Defense](https://img.shields.io/badge/Defense-blue) - [ICML](https://icml.cc/)
- *"[Deep evidential regression](https://papers.nips.cc/paper/2020/file/deep-evidential-regression.pdf)"* (2020) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - [NeurIPS](https://nips.cc/)
- *"[Posterior network: Uncertainty estimation without OOD samples via density-based pseudo-counts](https://papers.nips.cc/paper/2020/file/postnet.pdf)"* (2020) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [NeurIPS](https://nips.cc/)
- *"[Efficient robustness certificates for discrete data: Sparsity-aware randomized smoothing for graphs, images and more](https://proceedings.mlr.press/v119/bojchevski20a.html)"* (2020) ![Robustness](https://img.shields.io/badge/Robustness-green) - [ICML](https://icml.cc/)
- *"[Provable worst case guarantees for the detection of out-of-distribution data](https://papers.nips.cc/paper/2020/file/ood-detection.pdf)"* (2020) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [NeurIPS](https://nips.cc/)
- *"[Cold posteriors and aleatoric uncertainty](https://arxiv.org/abs/2008.00045)"* (2020) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [ArXiv](https://arxiv.org/)
- *"[Uncertainty on asynchronous time event prediction](https://papers.nips.cc/paper/2019/file/uncertainty-event-prediction.pdf)"* (2019) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [NeurIPS](https://nips.cc/)
- *"[Uncertainty-based continual learning with adaptive regularization](https://papers.nips.cc/paper/2019/file/uncertainty-continual-learning.pdf)"* (2019) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [NeurIPS](https://nips.cc/)
- *"[Certifiable robustness to graph perturbations](https://papers.nips.cc/paper/2019/file/robustness-graph-perturbations.pdf)"* (2019) ![Robustness](https://img.shields.io/badge/Robustness-green) - [NeurIPS](https://nips.cc/)
- *"[Explainable artificial intelligence (XAI): Concepts, taxonomies, opportunities and challenges toward responsible AI](https://doi.org/10.1016/j.inffus.2019.12.012)"* (2019) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - [Information Fusion](https://www.journals.elsevier.com/information-fusion)
- *"[Bayesian robust attributed graph clustering: Joint learning of partial anomalies and group structure](https://aaai.org/Library/AAAI/aaai18contents.php)"* (2018) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Robustness](https://img.shields.io/badge/Robustness-green) - [AAAI](https://aaai.org/)
- *"[BayesGrad: Explaining predictions of graph convolutional networks](https://papers.nips.cc/paper/2018/file/bayesgrad.pdf)"* (2018) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - [NeurIPS](https://nips.cc/)
- *"[Concerns about human agency, evolution and survival](https://www.pewresearch.org/internet/2018/12/10/concerns-about-human-agency-evolution-and-survival/)"* (2018) ![Fairness](https://img.shields.io/badge/Fairness-teal) - [Pew Research](https://www.pewresearch.org/)
- *"[Deep Gaussian embedding of graphs: Unsupervised inductive learning via ranking](https://arxiv.org/abs/1707.03815)"* (2017) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [ArXiv](https://arxiv.org/)
- *"[Variational inference: A review for statisticians](https://doi.org/10.1080/01621459.2017.1285773)"* (2017) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [Journal of the American Statistical Association](https://www.tandfonline.com/)
- *"[A distributional perspective on reinforcement learning](https://proceedings.mlr.press/v70/bellemare17a.html)"* (2017) ![Explainability](https://img.shields.io/badge/Explainability-cyan) - [ICML](https://icml.cc/)
- *"[A general framework for updating belief distributions](https://rss.onlinelibrary.wiley.com/doi/10.1111/rssb.12158)"* (2016) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [Journal of the Royal Statistical Society](https://rss.onlinelibrary.wiley.com/)
- *"[Concrete problems in AI safety](https://arxiv.org/abs/1606.06565)"* (2016) ![Defense](https://img.shields.io/badge/Defense-blue) - [ArXiv](https://arxiv.org/)
- *"[Weight uncertainty in neural networks](https://proceedings.mlr.press/v37/blundell15.html)"* (2015) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [ICML](https://icml.cc/)
- *"[The fundamental incompatibility of scalable Hamiltonian Monte Carlo and naive data subsampling](https://proceedings.mlr.press/v37/betancourt15.html)"* (2015) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [ICML](https://icml.cc/)
- *"[Superintelligence: Paths, Dangers, Strategies](https://global.oup.com/academic/product/superintelligence-9780198739838)"* (2014) ![Fairness](https://img.shields.io/badge/Fairness-teal) - [Oxford University Press](https://global.oup.com/)
- *"[Fluctuations in uncertainty](https://www.aeaweb.org/articles?id=10.1257/jep.28.2.153)"* (2014) ![Uncertainty](https://img.shields.io/badge/Uncertainty-orange) - [Journal of Economic Perspectives](https://www.aeaweb.org/)
- *"[Analysis of Thompson sampling for the multi-armed bandit problem](https://proceedings.mlr.press/v23/agrawal12/agrawal12.pdf)"* (2012) ![Bayesian](https://img.shields.io/badge/Bayesian-lime) - [COLT](https://www.learningtheory.org/)
  
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
- **Bertrand Charpentier** - Working in academia and industry on Bayesian deep learning and uncertainty estimation. [LinkedIn](https://www.linkedin.com/in/bertrand-charpentier/)
- **Stephan Günnemann** - Working in academia on robust machine learning and graph neural networks. [Website](https://www.professoren.tum.de/guennemann-stephan)
- **Eyke Hüllermeier** - Working in academia on uncertainty quantification and decision theory. [Website](https://www.uni-paderborn.de/en/person/16348)
- **Viktor Bengs** - Working in academia on uncertainty quantification and decision theory. [Website](https://www.uni-paderborn.de/en/person/16348)
- **Eric Nalisnick** - Working in academia on Bayesian deep learning and uncertainty estimation. [Website](https://www.cs.nott.ac.uk/~ean/)
- **Timnit Gebru** - Working in industry on fairness and ethical AI. [Twitter](https://twitter.com/timnitGebru) | [Website](https://www.dair-institute.org/)
- **Yarin Gal** - Working in academia on Bayesian methods and predictive uncertainty. [Twitter](https://twitter.com/yarin_gal) | [Website](https://yarin-gal.com/)
- **Zoubin Ghahramani** - Working in industry and academia on probabilistic models and Bayesian methods. [Twitter](https://twitter.com/zoubinghahramani) | [Website](https://mlg.eng.cam.ac.uk/zoubin/)
- **Balaji Lakshminarayanan** - Working in industry on deep ensembles and predictive uncertainty. [LinkedIn](https://www.linkedin.com/in/balaji-lakshminarayanan/) | [Website](https://balajiln.github.io/)
- **Dan Hendrycks** - Working in academia on robustness to distribution shifts and ML reliability. [Website](https://hendrycks.com/)
- **Alexander Amini** - Working in academia on evidential learning and autonomous systems. [Website](https://people.csail.mit.edu/amini/)
- **Dario Amodei** - Working in industry on AI alignment and safety. [LinkedIn](https://www.linkedin.com/in/darioamodei/)
- **Nicholas Carlini** - Working in industry on adversarial robustness and secure ML. [Website](https://nicholas.carlini.com/)
- **Chelsea Finn** - Working in academia on meta-learning and reliability in robotics. [Twitter](https://twitter.com/chelseabfinn) | [Website](https://cs.stanford.edu/people/cbfinn/)
- **Samy Bengio** - Working in industry on generative models and ML robustness. [LinkedIn](https://www.linkedin.com/in/samybengio/) | [Website](https://scholar.google.com/citations?user=jMshKJYAAAAJ)
- **Jascha Sohl-Dickstein** - Working in industry on diffusion models and generative methods. [Website](https://jaschasd.github.io/)
- **Karen Simonyan** - Working in industry on vision-based reliability in deep learning. [LinkedIn](https://www.linkedin.com/in/karen-simonyan-75827a33/)
- **Christian Szegedy** - Working in industry on adversarial defenses and vision. [LinkedIn](https://www.linkedin.com/in/christian-szegedy-23a3459/)
- **Nick Bostrom** - Working in academia on AI safety and societal impacts. [Website](https://www.nickbostrom.com/)
- **Marta Kwiatkowska** - Working in academia on formal verification for AI safety. [Website](https://www.cs.ox.ac.uk/marta.kwiatkowska/)
- **Ryan Adams** - Working in academia on scalable Bayesian inference and uncertainty quantification. [Twitter](https://twitter.com/ryanadamsML) | [Website](https://www.cs.princeton.edu/~rpa/)
- **Katherine Heller** - Working in academia and industry on probabilistic modeling and Bayesian inference. [LinkedIn](https://www.linkedin.com/in/kheller27/)
- **Chris Olah** - Working in industry on interpretability and neural network reliability. [Twitter](https://twitter.com/ch402) | [Website](https://colah.github.io/)
- **Arvind Narayanan** - Working in academia on fairness, privacy, and secure ML systems. [Twitter](https://twitter.com/random_walker) | [Website](https://randomwalker.info/)
- **Joan Bruna** - Working in academia on robust and reliable graph neural networks. [Website](https://cims.nyu.edu/~bruna/)
- **Percy Liang** - Working in academia on generalization and ML reliability. [Twitter](https://twitter.com/percyliang) | [Website](https://cs.stanford.edu/people/pliang/)
- **Shakir Mohamed** - Working in industry on equitable and reliable AI systems. [Twitter](https://twitter.com/shakir_za) | [Website](https://shakirm.com/)
- **Geoffrey Hinton** - Working in academia and industry on neural network reliability. [LinkedIn](https://www.linkedin.com/in/geoffrey-hinton/) | [Website](https://www.cs.toronto.edu/~hinton/)
- **Max Welling** - Working in academia on scalable Bayesian methods and ML uncertainty. [Twitter](https://twitter.com/wellingmax) | [Website](https://staff.fnwi.uva.nl/m.welling/)
- **Vladimir Vapnik** - Working in academia on generalization theories and SVMs. [Website](https://www.cs.columbia.edu/~vapnik/)
- **Leslie Kaelbling** - Working in academia on reliable reinforcement learning. [Website](https://www.lcs.mit.edu/leslie-kaelbling)
- **Pieter Abbeel** - Working in academia on robotics and real-world ML reliability. [Twitter](https://twitter.com/pabbeel) | [Website](https://people.eecs.berkeley.edu/~pabbeel/)
- **Sanja Fidler** - Working in academia on robust computer vision. [Website](https://www.cs.toronto.edu/~fidler/)
- **Thomas Dietterich** - Working in academia on fairness and reliability in ML. [Website](http://web.engr.oregonstate.edu/~tgd/)
- **Hanna Wallach** - Working in industry on societal impacts of ML and fairness. [Website](http://dirichlet.net/)
- **Anca Dragan** - Working in academia on reliable human-AI collaboration. [Website](https://people.eecs.berkeley.edu/~anca/)
- **David Silver** - Working in industry on reinforcement learning reliability. [LinkedIn](https://www.linkedin.com/in/david-silver-4b241/) | [Website](https://www.deepmind.com/research/highlighted-research/alphago)
- **Oriol Vinyals** - Working in industry on reliable multi-agent systems and RL. [LinkedIn](https://www.linkedin.com/in/oriol-vinyals-17721118/) | [Website](https://scholar.google.com/citations?user=ITRAiwIAAAAJ)
- **Kevin Murphy** - Working in academia and industry on probabilistic models and AI reliability. [Website](https://research.google/people/KevinMurphy/)
- **Cynthia Rudin** - Working in academia on interpretable and responsible AI. [Website](http://people.duke.edu/~cynthia/)
- **Pushmeet Kohli** - Working in industry on verifying ML robustness. [LinkedIn](https://www.linkedin.com/in/pushmeet/) | [Website](https://www.microsoft.com/en-us/research/people/pushmeet/)
- **Jonas Peters** - Working in academia on causal inference and reliable ML. [Website](https://jonas-peters.com/)
- **Adrian Weller** - Working in academia and industry on fairness and explainability. [Website](https://www.adrianweller.com/)

---

## Contributing 🤝
We welcome contributions! Please follow our [contribution guidelines](CONTRIBUTING.md) to share resources, tools, or ideas that align with the theme of ML reliability.

---

## License 📄
This project is licensed under the [MIT License](LICENSE). Feel free to share and use the resources as needed.

---
