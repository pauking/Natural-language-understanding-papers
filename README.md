# Natural-language-understanding-papers
A list of recent papers regarding natural language understanding and spoken language understanding. <br>
It contains sequence labelling, sentence classification, dialogue act classification, dialogue state tracking and so on.

# Bookmarks
  * [Variant networks](#variant-networks)
  * [Robustness to ASR-error](#robustness-to-ASR-error)
  * [Zero-shot learning and domain adaptation](#zero-shot-learning-and-domain-adaptation)
  * [Which may inspire us]($which-may-inspire-us)

## Variant networks
  * [Using Recurrent Neural Networks for Slot Filling in Spoken Language Understanding](https://ieeexplore.ieee.org/document/6998838/). Grégoire Mesnil, et al.. TASLP, 2015. [[Code+data](https://github.com/mesnilgr/is13)]
  * [Attention-based recurrent neural network models for joint intent detection and slot filling](https://pdfs.semanticscholar.org/84a9/bc5294dded8d597c9d1c958fe21e4614ff8f.pdf). Bing Liu and Ian Lane. InterSpeech, 2016. [[Code1](https://github.com/HadoopIt/rnn-nlu)] [[Code2](https://github.com/applenob/RNN-for-Joint-NLU)]
  * [Encoder-decoder with Focus-mechanism for Sequence Labelling Based Spoken Language Understanding](https://speechlab.sjtu.edu.cn/papers/sz128-zhu-icassp17.pdf). Su Zhu and Kai Yu. ICASSP, 2017. [[Code](https://github.com/sz128/SLU_focus_and_crf)]
  * [Neural Models for Sequence Chunking](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14776/14262). Fei Zhai, et al. AAAI, 2017.
  * [End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF](https://arxiv.org/abs/1603.01354). Xuezhe Ma, Eduard Hovy. ACL, 2016.
  * [A Bi-model based RNN Semantic Frame Parsing Model for Intent Detection and Slot Filling](http://aclweb.org/anthology/N18-2050). Yu Wang, et al. NAACL 2018.
  * [Improving Slot Filling in Spoken Language Understanding with Joint Pointer and Attention](http://aclweb.org/anthology/P18-2068). Lin Zhao and Zhe Feng. ACL, 2018.
  
## Robustness to ASR-error
 * [Discriminative spoken language understanding using word confusion networks](http://www.matthen.com/assets/pdf/Discriminative_Spoken_Language_Understanding_Using_Word_Confusion_Networks.pdf). Matthew Henderson, et al.. SLT, 2012. [[Data](https://www.repository.cam.ac.uk/handle/1810/248271;jsessionid=D40F449AE8CD5D93EF215715D1726E13)]
 * [Using word confusion networks for slot filling in spoken language understanding](http://www.isca-speech.org/archive/interspeech_2015/papers/i15_1353.pdf). Xiaohao Yang and Jia Liu. Interspeech, 2015.
 * [Joint Online Spoken Language Understanding and Language Modeling with Recurrent Neural Networks](http://www.aclweb.org/anthology/W16-3603). Bing Liu and Ian Lane. SIGDIAL, 2016. [[Code](https://github.com/HadoopIt/joint-slu-lm)]
 * [Robust Spoken Language Understanding with unsupervised ASR-error adaptation](https://speechlab.sjtu.edu.cn/papers/sz128-zhu-icassp18.pdf). Su Zhu, et al.. ICASSP, 2018.
 * [Neural Confnet Classification: Fully Neural Network Based Spoken Utterance Classification Using Word Confusion Networks](http://mirlab.org/conference_papers/International_Conference/ICASSP%202018/pdfs/0006039.pdf). Ryo Masumura, et al.. ICASSP, 2018.
 
 ## Zero-shot learning and domain adaptation
  * [A model of zero-shot learning of spoken language understanding](http://www.anthology.aclweb.org/D/D15/D15-1027.pdf). Majid Yazdani and James Henderson. EMNLP, 2015.
  * [Zero-shot Learning Of Intent Embeddings For Expansion By Convolutional Deep Structured Semantic Models](https://www.csie.ntu.edu.tw/~yvchen/doc/ICASSP16_ZeroShot.pdf). Yun-Nung Chen, et al.. ICASSP 2016.
  * [Online Adaptative Zero-shot Learning Spoken Language Understanding Using Word-embedding](https://ieeexplore.ieee.org/document/7178987/).  Emmanuel Ferreira, et al. ICASSP 2015.
  * [Towards Zero-Shot Frame Semantic Parsing for Domain Scaling](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/0518.PDF).  Ankur Bapna, et al. Interspeech, 2017.
  * [Domain Attention with an Ensemble of Experts](http://www.karlstratos.com/publications/acl17ensemble.pdf). Young-Bum Kim, et al.. ACL, 2017.
  * [Adversarial Adaptation of Synthetic or Stale Data](http://karlstratos.com/publications/acl17adversarial.pdf). Young-Bum Kim, et al.. ACL, 2017.
  * [Concept Transfer Learning for Adaptive Language Understanding](http://aclweb.org/anthology/W18-5047). Su Zhu and Kai Yu. SIGDIAL, 2018.
  * [An End-to-end Approach for Handling Unknown Slot Values in Dialogue State Tracking](http://aclweb.org/anthology/P18-1134). Puyang Xu and Qi Hu. ACL, 2018.
  * [Large-Scale Multi-Domain Belief Tracking with Knowledge Sharing](http://aclweb.org/anthology/P18-2069). Osman Ramadan, et al.. ACL, 2018.
  * [Fast and Scalable Expansion of Natural Language Understanding Functionality for Intelligent Agents](http://aclweb.org/anthology/N18-3018). Anuj Goyal, et al. NAACL, 2018. [from Amazon Alexa Machine Learning]
  * [Bag of Experts Architectures for Model Reuse in Conversational Language Understanding](http://aclweb.org/anthology/N18-3019). Rahul Jha, et al. NAACL, 2018. [from Microsoft Corporation]

 ## Which may inspire us
  * [Jointly Predicting Predicates and Arguments in Neural Semantic Role Labeling](http://aclweb.org/anthology/P18-2058). Luheng He, et al. ACL, 2018. [[Code](https://github.com/luheng/lsgn)]
  * [Sentence-State LSTM for Text Representation](http://aclweb.org/anthology/P18-1030). Yue Zhang, et al. ACL, 2018. [[Code](https://github.com/leuchine/S-LSTM)]
  * [Chinese NER Using Lattice LSTM](http://aclweb.org/anthology/P18-1144). Yue Zhang, et al. ACL, 2018. [[Code+data](https://github.com/jiesutd/LatticeLSTM)]
  * [SoPa: Bridging CNNs, RNNs, and Weighted Finite-State Machines](http://aclweb.org/anthology/P18-1028). Roy Schwartz, et al. ACL, 2018. [[Code](https://github.com/Noahs-ARK/soft_patterns)]
  * [Coarse-to-Fine Decoding for Neural Semantic Parsing](http://homepages.inf.ed.ac.uk/s1478528/acl18-coarse2fine.pdf). Li Dong and Mirella Lapata. ACL, 2018. [[Code](https://github.com/donglixp/coarse2fine)]
