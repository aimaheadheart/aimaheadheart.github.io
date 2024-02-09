---
# the default layout is 'page'
icon: fas fa-file-contract
order: 2
---

## Table of Contents

- [Recent Papers](#recent-papers)
- [Review and General Papers](#review-and-general-papers)
- [Measurements of Fairness](#measurements-of-fairness)
- Demonstration of Bias Phemomenon in Various Applications
  + [Bias in Machine Learning Models](#bias-in-machine-learning-models)
  + [Bias in Representations](#bias-in-representations)
- Mitigation of Unfairness
  + [Mitigation of Machine Learning Models](#mitigation-of-machine-learning-models)
    * Adversarial Learning
    * Calibration
    * Incorporating Priors into Feature Attribution
    * Data Collection
    * Other Mitigation Methods
  + [Mitigation of Representations](#mitigation-of-representations)
- [Fairness Packages and Frameworks](#fairness-packages-and-frameworks)
- [Conferences](#conferences)
- [Other Fairness Relevant Interpretability Resources](#other-fairness-relevant-interpretability-resources)

## Recent Papers

- Racial and Ethnic Disparities in Epidural Blood Patch Utilization Among Obstetric Patients in the United States: A Nationwide Analysis, 2016-2020 (In Press)
- [Large Language Models for Healthcare Data Augmentation: An Example on Patient-Trial Matching](https://arxiv.org/abs/2303.16756)
- [Does synthetic data generation of llms help clinical text mining?](https://arxiv.org/abs/2303.04360)
- [FERI: A Multitask-based Fairness Achieving Algorithm with Applications to Fair Organ Transplantation](https://arxiv.org/pdf/2310.13820.pdf)
- [A Transformer-Based Deep Learning Approach for Fairly Predicting Post-Liver Transplant Risk Factors](https://arxiv.org/pdf/2304.02780)
- [Multi-Task Learning for Post-transplant Cause of Death Analysis: A Case Study on Liver Transplant](https://arxiv.org/pdf/2304.00012)
- [Fairly Predicting Graft Failure in Liver Transplant for Organ Assigning](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10148275/)
- [Predicting Mortality in Liver Transplant Candidates](https://link.springer.com/chapter/10.1007/978-3-030-53352-6_31)
- [Fulminant Lung Fibrosis in Non-resolvable COVID-19 Requiring Transplantation](https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(22)00533-3/fulltext)
- [Jugular Venous Congestion During Off‐pump Lung Transplantation is not Associated with an Increased Risk of Postoperative Delirium](https://onlinelibrary.wiley.com/doi/pdf/10.1111/ctr.14794)
- [Incidence and Predictive Factors of Acute Kidney Injury After Off-pump Lung Transplantation](https://www.sciencedirect.com/science/article/pii/S1053077021008351)
- [Hypoxemia Secondary to Acute Mitral Regurgitation Induced by Systolic Anterior Motion of the Mitral Valve during Lung Transplantation](https://pubmed.ncbi.nlm.nih.gov/34798702/)
- [Privacy-preserving Techniques of Genomic Data—A Survey](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6585383/)
- [Featured Research on Equity and Sustained Participation in Engineering, Computing, and Technology](https://ieeexplore.ieee.org/iel7/5992/9167170/09167302.pdf)
- [Fair Machine Learning in Healthcare: A Review](https://arxiv.org/pdf/2206.14397)

## Review and General Papers

- [Fairness in Deep Learning: A Computational Perspective](https://arxiv.org/pdf/1908.08843.pdf)
- [The Measure and Mismeasure of Fairness: A Critical Review of Fair Machine Learning](https://arxiv.org/pdf/1808.00023.pdf)
- [Fairness and machine learning](https://fairmlbook.org/)
- [A Survey on Bias and Fairness in Machine Learning](https://arxiv.org/pdf/1908.09635.pdf)
- [The Frontiers of Fairness in Machine Learning](https://arxiv.org/pdf/1810.08810.pdf)
- [Ensuring fairness in machine learning to advance health equity](https://annals.org/aim/fullarticle/2717119)
- [Mitigating Gender Bias in Natural Language Processing: Literature Review](https://www.aclweb.org/anthology/P19-1159.pdf)
- [Fairness in Recommender Systems](http://www.ec.tuwien.ac.at/~dimitris/research/recsys-fairness.html)
- [Implementations in Machine Ethics: A Survey](https://arxiv.org/pdf/2001.07573.pdf)



## Measurements of Fairness

- [On Formalizing Fairness in Prediction with Machine Learning](https://arxiv.org/pdf/1710.03184.pdf)
- [Equality of Opportunity in Supervised Learning](https://arxiv.org/pdf/1610.02413.pdf)
- [Certifying and removing disparate impact](https://arxiv.org/pdf/1412.3756.pdf)
- [Does mitigating ML's impact disparity require treatment disparity?](https://papers.nips.cc/paper/8035-does-mitigating-mls-impact-disparity-require-treatment-disparity.pdf)
- [Putting Fairness Principles into Practice: Challenges, Metrics, and Improvements](https://arxiv.org/pdf/1901.04562.pdf)
- [Beyond Parity: Fairness Objectives for Collaborative Filtering](https://arxiv.org/pdf/1705.08804.pdf)
- [50 Years of Test (Un)fairness: Lessons for Machine Learning](https://arxiv.org/pdf/1811.10104.pdf)
- [Fairness Definitions Explained](https://fairware.cs.umass.edu/papers/Verma.pdf)
- [Algorithmic Fairness](https://arxiv.org/abs/2001.09784)
- [Bias in data‐driven artificial intelligence systems—An introductory survey](https://onlinelibrary.wiley.com/doi/full/10.1002/widm.1356)
- [Fairness is not Static: Deeper Understanding of Long Term Fairness via Simulation Studies](https://github.com/google/ml-fairness-gym/blob/master/papers/acm_fat_2020_fairness_is_not_static.pdf)
- [Delayed Impact of Fair Machine Learning](http://proceedings.mlr.press/v80/liu18c/liu18c.pdf)

## Demonstration of Bias Phemomenon in Various Applications
### Bias in Machine Learning Models
  - [Gender Shades: Intersectional Accuracy Disparities in Commercial Gender Classification](http://proceedings.mlr.press/v81/buolamwini18a/buolamwini18a.pdf)
  - [Deep Learning for Face Recognition: Pride or Prejudiced?](https://arxiv.org/pdf/1904.01219.pdf)
  - [Examining Gender and Race Bias in Two Hundred Sentiment Analysis Systems](https://arxiv.org/pdf/1805.04508.pdf)
  - [Demographic Dialectal Variation in Social Media: A Case Study of African-American English](https://aclweb.org/anthology/D16-1120/)
  - [Feature-Wise Bias Amplification](https://arxiv.org/pdf/1812.08999.pdf)
  - [ConvNets and ImageNet Beyond Accuracy: Understanding Mistakes and Uncovering Biases](https://arxiv.org/pdf/1711.11443.pdf)



### Bias in Representations
  - [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://arxiv.org/pdf/1607.06520.pdf)
  - [Gender Bias in Contextualized Word Embeddings](https://arxiv.org/pdf/1904.03310.pdf)
  - [Assessing Social and Intersectional Biases in Contextualized Word Representations](http://papers.nips.cc/paper/9479-assessing-social-and-intersectional-biases-in-contextualized-word-representations.pdf)



## Mitigation of Unfairness

### Mitigation of Machine Learning Models
- Adversarial Learning
  + [Data Decisions and Theoretical Implications when Adversarially Learning Fair Representations](https://arxiv.org/pdf/1707.00075.pdf)
  + [Achieving Fairness through Adversarial Learning: an Application to Recidivism Prediction](https://arxiv.org/pdf/1807.00199.pdf)
  + [Balanced Datasets Are Not Enough: Estimating and Mitigating Gender Bias in Deep Image Representations](https://arxiv.org/pdf/1811.08489.pdf)
  + [Mitigating Unwanted Biases with Adversarial Learning](https://arxiv.org/pdf/1801.07593.pdf)
  + [Adversarial Removal of Demographic Attributes from Text Data](https://arxiv.org/pdf/1808.06640.pdf)
  + [Compositional Fairness Constraints for Graph Embeddings](http://proceedings.mlr.press/v97/bose19a/bose19a.pdf)

- Calibration
  + [Men Also Like Shopping: Reducing Gender Bias Amplification using Corpus-level Constraints](https://arxiv.org/pdf/1707.09457.pdf)
  + [Equality of Opportunity in Supervised Learning](https://arxiv.org/pdf/1610.02413.pdf)



- Incorporating Priors into Feature Attribution
  + [Mitigating Gender Bias in Captioning Systems](https://arxiv.org/abs/2006.08315)
  + [Incorporating priors with feature attribution on text classification](https://www.aclweb.org/anthology/P19-1631.pdf)
  + [Women Also Snowboard: Overcoming Bias in Captioning Models](http://openaccess.thecvf.com/content_ECCV_2018/papers/Lisa_Anne_Hendricks_Women_also_Snowboard_ECCV_2018_paper.pdf)
  + [Learning Credible Deep Neural Networks with Rationale Regularization](https://arxiv.org/pdf/1908.05601.pdf)


- Data Collection
  + [Why Is My Classifier Discriminatory?](https://papers.nips.cc/paper/7613-why-is-my-classifier-discriminatory.pdf)
  + [Incorporating Dialectal Variability for Socially Equitable Language Identification](https://www.aclweb.org/anthology/P17-2009/)
  + [REPAIR: Removing Representation Bias by Dataset Resampling](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_REPAIR_Removing_Representation_Bias_by_Dataset_Resampling_CVPR_2019_paper.pdf)




- Other Mitigation Methods
  + [Mitigating Bias in Gender, Age and Ethnicity Classification: a Multi-Task Convolution Neural Network Approach](https://hal.inria.fr/hal-01892103/document)
  + [InclusiveFaceNet: Improving Face Attribute Detection with Race and Gender Diversity](https://arxiv.org/pdf/1712.00193.pdf)
  + [Reducing Gender Bias in Abusive Language Detection](https://arxiv.org/pdf/1808.07231.pdf)
  + [Fairness-aware Learning through Regularization Approach](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6137441&tag=1)
  + [Fairness Constraints: Mechanisms for Fair Classification](https://arxiv.org/pdf/1507.05259.pdf)
  + [Penalizing Unfairness in Binary Classification](https://arxiv.org/pdf/1707.00044.pdf)
  + [Fairness Constraints:A Flexible Approach for Fair Classification](http://www.jmlr.org/papers/volume20/18-262/18-262.pdf)
  + [A General Framework for Fair Regression](https://arxiv.org/abs/1810.05041)
  + [Fair Regression: Quantitative Definitions and Reduction-based Algorithms](http://proceedings.mlr.press/v97/agarwal19d/agarwal19d.pdf)





### Mitigation of Representations
  - [Man is to Computer Programmer as Woman is to Homemaker? Debiasing Word Embeddings](https://arxiv.org/pdf/1607.06520.pdf)
  - [Learning Gender-Neutral Word Embeddings](https://arxiv.org/pdf/1809.01496.pdf)
  - [Flexibly Fair Representation Learning by Disentanglement](https://arxiv.org/pdf/1906.02589.pdf)
  - [Turning a Blind Eye: Explicit Removal of Biases and Variation from Deep Neural Network Embeddings](https://arxiv.org/pdf/1809.02169.pdf)






## Fairness Packages and Frameworks

- [FairMLHealth](https://dl.acm.org/doi/abs/10.1145/3462203.3475894)
- [AI Fairness 360](https://github.com/IBM/AIF360)
- [Fairlearn: Fairness in machine learning mitigation algorithms](https://github.com/fairlearn/fairlearn)
- [Fairness-comparison](https://dl.acm.org/doi/10.1145/3287560.3287589)
- [Algofairness](https://github.com/algofairness)
  - [fairness: Benchmarking of fairness aware machine learning algorithms](https://github.com/algofairness/fairness-comparison)
- [MEASURES](https://dl.acm.org/doi/abs/10.1145/3306618.3314262)
- [Themis-ml](https://www.tandfonline.com/doi/full/10.1080/15228835.2017.1416512?scroll=top&needAccess=true)
- [FairML](https://dspace.mit.edu/bitstream/handle/1721.1/108212/980349219-MIT.pdf?sequence=1&isAllowed=y)
- [Black Box Auditing](https://ieeexplore.ieee.org/document/7837824)
- [What-If Tool](https://pair-code.github.io/what-if-tool/)
- [FairSight: Visual Analytics for Fairness in Decision Making](https://github.com/ayong8/FairSight)
- [GD-IQ: Spellcheck for Bias (code not available)](https://seejane.org/video/gd-iq-spellcheck-for-bias/)
- [Aequitas: Bias and Fairness Audit Toolkit](https://github.com/dssg/aequitas)
- [DECAF](https://proceedings.neurips.cc/paper/2021/file/ba9fab001f67381e56e410575874d967-Paper.pdf)
- [REPAIR](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_REPAIR_Removing_Representation_Bias_by_Dataset_Resampling_CVPR_2019_paper.pdf)
- [CERTIFAI: A Common Framework to Provide Explanations and Analyse the Fairness and Robustness of Black-box Models](https://www.aies-conference.com/2020/wp-content/papers/099.pdf)
- [ML-fairness-gym: Google's implementation based on OpenAI's Gym](https://github.com/google/ml-fairness-gym)
- [Fairness-indicators: Tensorflow's Fairness Evaluation and Visualization Toolkit](https://github.com/tensorflow/fairness-indicators)
- [Adv-Demog-Text](https://arxiv.org/pdf/1808.06640.pdf)
- [GN-GloVe](https://arxiv.org/pdf/1809.01496.pdf)
- [Tensorflow Constrained Optimization](https://proceedings.mlr.press/v97/cotter19b/cotter19b.pdf)
- [scikit-fairness](https://github.com/koaning/scikit-fairness)
- [Mitigating Gender Bias In Captioning System](https://github.com/CaptionGenderBias2020/Mitigating_Gender_Bias_In_Captioning_System_NIPS2020)
- [Dataset Nutrition Label](https://arxiv.org/pdf/1805.03677.pdf)


## Conferences

- [FAT\-: ACM Conference on Fairness, Accountability, and Transparency](https://fatconference.org/)
- [FATML: Fairness, Accountability, and Transparency in Machine Learning Workshop](https://www.fatml.org/)
- [AIES: AAAI/ACM Conference on AI, Ethics, and Society](http://www.aies-conference.com/2020/)


## Other Fairness Relevant Interpretability Resources

- [Awesome machine learning interpretability resources](https://github.com/jphall663/awesome-machine-learning-interpretability)
- [The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490.pdf)
- [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/pdf/1702.08608.pdf)
- [Techniques for Interpretable Machine Learning](https://arxiv.org/pdf/1808.00033.pdf)
- [Methods for Interpreting and Understanding Deep Neural Networks](https://arxiv.org/pdf/1706.07979.pdf)
