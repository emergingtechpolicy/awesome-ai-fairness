# Awesome AI Fairness [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Toolkits and Open-source libraries
[IBM's AI Fairness 360](https://aif360.mybluemix.net/) (most comprehensive to date)
Most comprehensive AI Fairness toolkit to date.

### Bias Detection
[Fairness Measures](http://www.fairness-measures.org/)
Fairness benchmarking tool for machine learning – provides several fairness metrics like difference of means, disparate impact and odds ratio, along with datasets though some are not in the public domain.

[FairML](https://github.com/adebayoj/fairml)
Auditing tool for blackbox predictive models by quantifying the relative effects of various input on the model's predictions

[Fairtest](https://github.com/columbia/fairtest)
Checks for associations between predicted labels and protected attributes. Provides a way to identify regions of the input space where an algorithm might incur unusually high errors. Also includes a catalog of many datasets.

[Aequitas](https://dsapp.uchicago.edu/projects/aequitas/) (*not for commerical use*)
Friendly for both data scientists and policymakers, with a Python library and a website to upload data for bias analysis. Several fairness maetrics (demographic, statistical parity, disparate impact etc.) and a "fairness tree" to help users identify the correct metric to use for their particular situation.

[Themis](https://github.com/LASER-UMASS/Themis)
Automatically generates test suites to measure discrimination in decisions made by a predictive system

### Bias Detection and Mitigation
[Themis-ML](https://github.com/cosmicBboy/themis-ml)
Has both fairness metrics and bias mitigation algorithms like relabeling, additive counterfactually fair estimator, and reject option classification.

[Fairness Comparison](https://github.com/algofairness/fairness-comparison)
Several bias detection metrics and bias mitigation methods like disparate impact remover, prejudice remover and two-Naive Bayes.

## Research Papers 

Elisa Celis, Lingxiao Huang, Vijay Keswani, Nisheeth Vishnoi, [“Classification with Fairness Constraints: A Meta-Algorithm with Provable Guarantees”](https://arxiv.org/abs/1806.06055), 2018

Brian Hu Zhang, Blake Lemoine, and Margaret Mitchell, [“Mitigating Unwanted Biases with Adversarial Learning”](http://www.aies-conference.com/wp-content/papers/main/AIES_2018_paper_162.pdf), AAAI/ACM Conference on Artificial Intelligence, Ethics, and Society, 2018.

Till Speicher, Hoda Heidari, Nina Grgic-Hlaca, Krishna P. Gummadi, Adish Singla, Adrian Weller, and Muhammad Bilal Zafar, [“A Unified Approach to Quantifying Algorithmic Unfairness: Measuring Individual & Group Unfairness via Inequality Indices”](https://doi.org/10.1145/3219819.3220046), ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2018.

Flavio P. Calmon, Dennis Wei, Bhanukiran Vinzamuri, Karthikeyan Natesan Ramamurthy, and Kush R. Varshney, [“Optimized Pre-Processing for Discrimination Prevention”](http://papers.nips.cc/paper/6988-optimized-pre-processing-for-discrimination-prevention), Conference on Neural Information Processing Systems, 2017.

Geoff Pleiss, Manish Raghavan, Felix Wu, Jon Kleinberg, and Kilian Q. Weinberger, [“On Fairness and Calibration”](https://papers.nips.cc/paper/7151-on-fairness-and-calibration), Conference on Neural Information Processing Systems, 2017.

Moritz Hardt, Eric Price, and Nathan Srebro, [“Equality of Opportunity in Supervised Learning”](https://papers.nips.cc/paper/6374-equality-of-opportunity-in-supervised-learning), Conference on Neural Information Processing Systems, 2016.

Michael Feldman, Sorelle A. Friedler, John Moeller, Carlos Scheidegger, and Suresh Venkatasubramanian, [“Certifying and Removing Disparate Impact”](https://doi.org/10.1145/2783258.2783311), ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2015.

Richard Zemel, Yu (Ledell) Wu, Kevin Swersky, Toniann Pitassi, and Cynthia Dwork, [“Learning Fair Representations”](http://proceedings.mlr.press/v28/zemel13.html), International Conference on Machine Learning, 2013.

Faisal Kamiran and Toon Calders, [“Data Preprocessing Techniques for Classification without Discrimination”](http://doi.org/10.1007/s10115-011-0463-8), Knowledge and Information Systems, 2012.

Faisal Kamiran, Asim Karim, and Xiangliang Zhang, [“Decision Theory for Discrimination-Aware Classification”](https://doi.org/10.1109/ICDM.2012.45), IEEE International Conference on Data Mining, 2012.

Toshihiro Kamishima, Shotaro Akaho, Hideki Asoh, and Jun Sakuma, [“Fairness-Aware Classifier with Prejudice Remover Regularizer”](https://rd.springer.com/chapter/10.1007/978-3-642-33486-3_3), Joint European Conference on Machine Learning and Knowledge Discovery in Databases, 2012.







## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the Emerging Technologies Policy Forum has waived all copyright and related or neighboring rights to this work.
