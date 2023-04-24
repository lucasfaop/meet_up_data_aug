
# Meet Up de Data Augmentation

Esse repositório contém informações do Meet Up apresentado no dia 27/04 sobre técnicas de Data Augmentation em NLP. Esse também apresenta códigos para apresentação no dia.


### Survey
| Paper |
| -- | 
| A Survey of Data Augmentation Approaches for NLP [ACL '21] (https://aclanthology.org/2021.findings-acl.84.pdf) [code](https://github.com/styfeng/DataAug4NLP) | 
| A Survey on Data Augmentation for Text Classification [ACM '22] (https://arxiv.org/abs/2107.03158) | 
| Data augmentation techniques in natural language processing [ASOC '23] (https://www.sciencedirect.com/science/article/pii/S1568494622008523) [code] (https://github.com/lucasfaop/survey_text_augmentation) | 

### Papers de Técnicas específicas
| Paper | Técnica | Categoria |
| -- |
| Synonym Replacement (Character-Level Convolutional Networks for Text Classification, [NeurIPS '15](https://papers.nips.cc/paper/2015/file/250cf8b51c773f3f8dc8b4be867a9a02-Paper.pdf)) | Troca por Sinônimos | Nível de palavra |
| Robust Training under Linguistic Adversity [(EACL '17)](https://www.aclweb.org/anthology/E17-2004/) [code](https://github.com/lrank/Linguistic_adversity) |
| Contextual Augmentation: Data Augmentation by Words with Paradigmatic Relations [(NAACL '18)](https://www.aclweb.org/anthology/N18-2072.pdf) [code](https://github.com/pfnet-research/contextual_augmentation) |  C-BERT | Nível de palavra |
| EDA: Easy Data Augmentation Techniques for Boosting Performance on Text Classification Tasks [(EMNLP '19)](http://dx.doi.org/10.18653/v1/D19-1670) [code](https://github.com/jasonwei20/eda_nlp) | EDA | Nível de palavra |
| A Closer Look At Feature Space Data Augmentation For Few-Shot Intent Classification [(DeepLo @ EMNLP '19)](https://arxiv.org/abs/1910.04176) | Adição de ruído | Espaço de variáveis |
| Nonlinear Mixup: Out-Of-Manifold Data Augmentation for Text Classification [(AAAI '20)](https://doi.org/10.1609/aaai.v34i04.5822) | Mix-Up | Espaço de variáveis |
| MixText: Linguistically-Informed Interpolation of Hidden Space for Semi-Supervised Text Classification [(ACL '20)](https://www.aclweb.org/anthology/2020.acl-main.194/) [code](https://github.com/GT-SALT/MixText) | Mix-Up | Espaço de variáveis |
| Not Enough Data? Deep Learning to the Rescue! [(AAAI '20)](https://arxiv.org/abs/1911.03118) | LAMBADA | Nível de Documento |
| Data Augmentation using Pre-trained Transformer Models [LifeLongNLP @ AACL '20](https://arxiv.org/abs/2003.02245), [code](https://github.com/varunkumar-dev/TransformersDataAugmentation) | Contextual Embedding | Nível de palavra |
| SSMBA: Self-Supervised Manifold Based Data Augmentation for Improving Out-of-Domain Robustness [(EMNLP '20)](https://www.aclweb.org/anthology/2020.emnlp-main.97/) [code](https://github.com/nng555/ssmba) | SSMBA | Nível de palavra | 
| Data Boost: Text Data Augmentation Through Reinforcement Learning Guided Conditional Generation [(EMNLP '20)](https://www.aclweb.org/anthology/2020.emnlp-main.726/) | Data Boost | Nível de documento |
| GPT3Mix: Leveraging Large-scale Language Models for Text Augmentation [(arXiv '21)](https://arxiv.org/abs/2104.08826) | Prompt | Nível de Documento |
| Few-Shot Text Classification with Triplet Loss, Data Augmentation, and Curriculum Learning [(NAACL '21)](https://arxiv.org/abs/2103.07552) [code](https://github.com/jasonwei20/triplet-loss) | HUFF, COV-Q, AMZN, FEWREL | 
| Text AutoAugment: Learning Compositional Augmentation Policy for Text Classification [(EMNLP '21)](https://arxiv.org/abs/2109.00523) [code](https://github.com/lancopku/text-autoaugment) | AutoAugment | Nível de palavra |
| AEDA: An Easier Data Augmentation Technique for Text Classification [(EMNLP '21)](https://arxiv.org/abs/2108.13230) [code](https://github.com/akkarimi/aeda_nlp) | AEDA | Nível de palavra |


### Retirada de Viés
| Paper |
| -- | 
| Gender Bias in Coreference Resolution: Evaluation and Debiasing Methods. [(NAACL '18)](https://www.aclweb.org/anthology/N18-2003/) [code](https://github.com/uclanlp/corefBias) | 
| Counterfactual Data Augmentation for Mitigating Gender Stereotypes in Languages with Rich Morphology [(ACL '19)](https://www.aclweb.org/anthology/P19-1161/) [code](https://github.com/rycolab/biasCDA) | 
| CONAN - COunter NArratives through Nichesourcing: a Multilingual Dataset of Responses to Fight Online Hate Speech [(ACL '19)](https://aclanthology.org/P19-1271.pdf) [Dataset](https://github.com/marcoguerini/CONAN)|
| It’s All in the Name: Mitigating Gender Bias with Name-Based Counterfactual Data Substitution [(EMNLP '19)](https://www.aclweb.org/anthology/D19-1530/) [code](https://github.com/rowanhm/counterfactual-data-substitution) | 
| Gender Bias in Neural Natural Language Processing. [(Springer '20)](https://link.springer.com/chapter/10.1007%2F978-3-030-62077-6_14 ) |
| Improving Robustness by Augmenting Training Sentences with Predicate-Argument Structures [(arxiv '20)](https://arxiv.org/abs/2010.12510) | 

### Balanceamento
| Paper |
| -- | 
| SMOTE: Synthetic Minority Over-sampling Technique [(Journal of Artificial Intelligence Research '02)](https://www.jair.org/index.php/jair/article/view/10302) |
| Active Learning for Word Sense Disambiguation with Methods for Addressing the Class Imbalance Problem [(EMNLP '07)](https://www.aclweb.org/anthology/D07-1082/) | 
| MLSMOTE: Approaching imbalanced multilabel learning through synthetic instance generation [(Knowledge-Based Systems '15)](https://www.sciencedirect.com/science/article/abs/pii/S0950705115002737?via%3Dihub) |
| SMOTE for Learning from Imbalanced Data: Progress and Challenges, Marking the 15-year Anniversary [(Journal of Artificial Intelligence Research '18)](https://www.jair.org/index.php/jair/article/view/11192) |



### Popular Resources
- [A visual survey of data augmentation in NLP](https://amitness.com/2020/05/data-augmentation-for-nlp/)
- [nlpaug](https://github.com/makcedward/nlpaug)
- [TextAttack](https://github.com/QData/TextAttack)
- [AugLy](https://github.com/facebookresearch/AugLy)
- [NL-Augmenter 🦎 → 🐍](https://github.com/GEM-benchmark/NL-Augmenter/)
