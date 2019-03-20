# Modulabs_VQA
모두의 연구소 풀잎스쿨 질문을 해봐요! (2019.01.09~2019.03.27)

이벤트 사이트: https://event-us.kr/modu/event/4674

참가자: 김예찬, 문태봉, 오근수, 유준봉, 정민지, 조원호

퍼실이: 문태봉


## 1. Paper List : arXiv 날짜, 최초 제출 
## 특징
- **bold** : review

## 학회 
- NIPS, AAAI, ICML, CVPR, ICLR, ICCV 등의 oral, poster, spotlight, workshop 등은 구별O/구별X 섞여있음

### 자의적인 분류
- A : Neural Module Networks
- B : 각 단어가 이미지의 어떤 feature에 대응하게 Attention을 사용한 접근 방식, 단점 : 이미지 공간에서 명확한 의미론적인 내용을 담고 있지 않는 단어가 있다는 것. NLP Pipeline에서 해결해야 함
- C : Attention을 선택적으로 사용하는 방법 
- D : Softmax를 사용해서 attention의 가중치를 구함
- E : bilinear


### 2014
 - **(ICLR 2015) [Neural Machine Translation by Jointly Learning to Align and Translate(1409)](https://arxiv.org/abs/1409.0473)**

### 2015
 - (ICML 2015) [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention(1502)](https://arxiv.org/abs/1409.0473) : B, D
 - **(ICCV 2015) [Ask Your Neurons: A Neural-based Approach to Answering Questions about Images(1505)](https://arxiv.org/abs/1505.01121)**
 - **(ICCV 2015) [VQA: Visual Question Answering(1505)](https://arxiv.org/abs/1505.00468)**
 - **(CVPR 2016) [Stacked Attention Networks for Image Question Answering(1511)](https://arxiv.org/abs/1511.02274)** : B, D
 - **(CVPR 2016 talk) [Neural Module Networks(1511)](https://arxiv.org/abs/1511.02799)** : A
   - Deep Compositional Question Answering with Neural Module Networks
 - (CVPR 2016) [Visual7W: Grounded Question Answering in Images(1511)](https://arxiv.org/abs/1511.03416): D
 - (ECCV 2016) [Ask, Attend and Answer: Exploring Question-Guided Spatial Attention for Visual Question Answering(1511)](https://arxiv.org/abs/1511.05234) : B, D
 - (CVPR 2016) [Image Question Answering using Convolutional Neural Network with Dynamic Parameter Prediction(1511)](https://arxiv.org/abs/1511.05756)
 - (CoRR 2015) [ABC-CNN: An Attention Based Convolutional Neural Network for Visual Question Answering(1511)](https://arxiv.org/abs/1511.05960) : B, D
 - (CVPR 2016) [Compact Bilinear Pooling(1511)](https://arxiv.org/abs/1511.06062) : D
 - (CVPR 2016) [Where To Look: Focus Regions for Visual Question Answering(1511)](https://arxiv.org/abs/1511.07394) : D
 - (CoRR 2015) [Simple Baseline for Visual Question Answering(1512)](https://arxiv.org/abs/1512.02167)

### 2016
 - **(NAACL 2016 best paper) [Learning to Compose Neural Networks for Question Answering(1601)](https://arxiv.org/abs/1601.01705)** : A
 - (ICML 2016) [Dynamic Memory Networks for Visual and Textual Question Answering(1603)](https://arxiv.org/abs/1603.01417)
 - (CoRR 2016) [A Focused Dynamic Attention Model for Visual Question Answering(1604)](https://arxiv.org/abs/1604.01485)
 - (NIPS 2016 Spotlight) [Hierarchical Question-Image Co-Attention for Visual Question Answering(1606)](https://arxiv.org/abs/1606.00061) : B, D
 - (NIPS 2016) [Multimodal Residual Learning for Visual QA(1606)](https://arxiv.org/abs/1606.01455) : E
 - **(EMNLP 2016) [Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding(1606)](https://arxiv.org/abs/1606.01847)** : D, E
   - MCB
 - **(ICLR 2017) [Hadamard Product for Low-rank Bilinear Pooling(1610)](https://arxiv.org/abs/1610.04325)** : E
   - MLB
 - (AAAI 2018) [Diverse Beam Search: Decoding Diverse Solutions from Neural Sequence Models(1610)](https://arxiv.org/abs/1610.02424)
 - (CVPR 2017) [Dual attention networks for multimodal reasoning and matching(1611)](https://arxiv.org/abs/1611.00471)
 - (ICLR 2017) [dynamic Coattention Networks For Question Answering(1611)](https://arxiv.org/abs/1611.01604)
 - (CVPR 2017 Spotlight) [Modeling Relationship in Referential Expressions with Compositional Modular Networks(1611)](https://arxiv.org/abs/1611.09978) : A
 - (CVPR 2017) [Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering(1612)](https://arxiv.org/abs/1612.00837)
 - (CVPR 2017) [The VQA-Machine: Learning How to Use Existing Vision Algorithms to Answer New Questions(1612)](https://arxiv.org/abs/1612.05386)
 - **(CVPR 2017) [CLEVR: A Diagnostic Dataset for Compositional Language and Elementary Visual Reasoning(1612)](https://arxiv.org/abs/1612.06890)**

### 2017
 - (ICCV 2017) [An Analysis of Visual Question Answering Algorithms(1703)](https://arxiv.org/abs/1703.09684)
 - **(ICCV 2017 spotlight) [Learning to Reason: End-to-End Module Networks for Visual Question Answering(1704)](https://arxiv.org/abs/1704.05526)** : A, C
 - **(ICCV 2017) [Inferring and Executing Programs for Visual Reasoning(1705)](https://arxiv.org/abs/1705.03633)** : A
 - **(ICCV 2017) [MUTAN: Multimodal Tucker Fusion for Visual Question Answering(1705)](https://arxiv.org/abs/1705.06676)** : E
   - MUTAN
 - **(NIPS 2017) [Attention is All You Need(1706)](https://arxiv.org/abs/1706.03762)**
 - (NIPS 2017) [A simple neural network module for relational reasoning(1706)](https://arxiv.org/abs/1706.01427) : A
 - (CVPR 2018) [Visual Question Answering with Memory-Augmented Networks(1707)](https://arxiv.org/abs/1707.04968)
 - (CVPR 2018 full oral) [Bottom-up and top-down attention for image captioning and visual question answering(1707)](https://arxiv.org/abs/1707.07998) : B, D
 - **(ICCV 2016) [Multi-modal Factorized Bilinear Pooling with Co-Attention Learning for Visual Question Answering(1708)](https://arxiv.org/abs/1708.01471)** : E
   - MFB
 - (CVPR 2018) [Tips and Tricks for Visual Question Answering: Learning from the 2017 Challenge(1708)](https://arxiv.org/abs/1708.02711)
 - (CVPR 2018) [Beyond Bilinear: Generalized Multimodal Factorized High-Ordered Pooling for Visual Question Answering(1708)](https://arxiv.org/abs/1708.03619) : E
   - MFH 
 - (CoRR 2017) [Robustness Analysis of Visual QA Models by Basic Questions(1709)](https://arxiv.org/abs/1709.04625)
 - **(AAAI 2017) [FiLM: Visual Reasoning with a General Conditioning Layer(1709)](https://arxiv.org/abs/1709.07871)**
   - Learning Visual Reasoning Without Strong Priors(1707)
 - (CVPR 2018 Spotlight) [iVQA: Inverse Visual Question Answering(1710)](https://arxiv.org/abs/1710.03370v2)
 - (NIPS 2017) [High-Order Attention Models for Visual Question Answering(1711)](https://arxiv.org/abs/1711.04323)


### 2018 : 차후에 정리....
 - Structured Triplet
 - Transparency by Design: Closing the Gap Between Performance and Interpretability in Visual Reasoning(1803)
 - Improved Fusion of Visual and Language Representations by Dense Symmetric Co-Attention for Visual Question Answering(1804)
 - (NIPS 2018) Bilinear Attention Networks(1805)
 - Visual Reasoning by Progressive Module Network(1806)
 - Learning Answer Embeddings for Visual Question Answering(1806)
 - Latent Alignment and Variational Attention(1807)
 - Explainable Neural Computation via Stack Neural Module Networks(1807)


## 2. Schedule
### Week01 (19/01/09)
* Orientation
* VQA: Visual Question Answering
  + Presenter: 문태봉
  + Paper: https://arxiv.org/abs/1505.00468
  + Material: [문태봉님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week01/2019.01.09_vqa.pdf)


### Week02 (19/01/16)
* Ask Your Neurons: A Neural-based Approach to Answering Questions about Images
  + Presenter: 문태봉
  + Paper: https://arxiv.org/abs/1505.01121
  + Material: [Mateusz Malinowski 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week02/ask_your_neurons-slides-low_res.pdf)

* Neural Module Networks
  + Presenter: 김예찬
  + Paper: https://arxiv.org/abs/1511.02799
  + Material: [김예찬님 발표자료](https://www.slideshare.net/ssuserbd7730/neural-module-network)


### Week03 (19/01/23)
* Learning to Compose Neural Networks for Question Answering
  + Presenter: 정민지
  + Paper: https://arxiv.org/abs/1601.01705
  + Material: [정민지님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week03/learning_to_compose_neural_networks_for_qa.pdf)

* Learning to Reason: End-to-End Module Networks for Visual Question Answering
  + Presenter: 문태봉
  + Paper: https://arxiv.org/abs/1704.05526
  + Material: [문태봉님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week07/2019.02.27_vqa.pdf)


### Week04 (19/01/30)
* Neural Module Networks (코드구현)
  + Presenter: 김예찬
  + Paper: https://arxiv.org/abs/1511.02799
  + Material:


### Week05 (19/02/13)
* Neural Machine Translation by Jointly Learning to Align and Translate
  + Presenter: 조원호
  + Paper: https://arxiv.org/abs/1409.0473
  + Material: [조원호님 블로그 (NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING TO ALIGN AND TRANSLATE)](https://www.notion.so/wonhocho/NEURAL-MACHINE-TRANSLATION-BY-JOINTLY-LEARNING-TO-ALIGN-AND-TRANSLATE-87eb075e954d4020a4bd2eacfa7a80cb)
  + Reference: [조원호님 블로그 (Sequence to Sequence Learning with Neural Networks)](https://www.notion.so/wonhocho/Sequence-to-Sequence-Learning-with-Neural-Networks-d221d4ed2e9241e29047d95a6a9e00b2)

* TRANSLATION WITH A SEQUENCE TO SEQUENCE NETWORK AND ATTENTION (파이토치 튜토리얼)
  + Presenter: 문태봉
  + Site: https://arxiv.org/abs/1409.0473
  + Material: [문태봉님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week05/2019.02.14_vqa.pdf)
  + Reference: [파이토치 튜토리얼](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)

* Attention Is All You Need
  + Presenter: 정민지
  + Paper: https://arxiv.org/abs/1706.03762
  + Material: [이승재님 발표자료 (풀잎스쿨 NLP bootcamp)](https://github.com/modulabs/NLP-bootcamp/blob/master/1st/week07/Attention%20is%20All%20You%20Need_이승재.pdf)
  + Reference: [김승일님 발표자료 (모두연 딥인코)](http://www.modulabs.co.kr/DeepInCo/20067)
  + Reference: [Jay Alammar 블로그](http://jalammar.github.io/illustrated-transformer/?fbclid=IwAR00RzJ4AwnPjAAKveNWT91DzjksQq6D5Tlhj98HgIXxMPo2Yc5-MVqVGBw)
  
  
### Week06 (19/02/20)
* Stacked Attention Networks for Image Question Answering
  + Presenter: 오근수
  + Paper: https://arxiv.org/abs/1511.02274
  + Material: [오근수님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/b오그ob/master/week06/kunsu_190220.pdf)

* CLEVR: A Diagnostic Dataset for Compositional Language and Elementary Visual Reasoning
  + Presenter: 오근수
  + Paper: https://arxiv.org/abs/1612.06890
  + Material: [오근수님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/b오그ob/master/week06/kunsu_190220.pdf)

* Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding
  + Presenter: 김예찬
  + Paper: https://arxiv.org/abs/1606.01847
  + Material:
  
* Hadamard Product for Low-rank Bilinear Pooling
  + Presenter: 김예찬
  + Paper: https://arxiv.org/abs/1610.04325
  + Material: 

  
### Week07 (19/02/27)
* Learning to Reason: End-to-End Module Networks for Visual Question Answering (코드구현)
  + Presenter: 문태봉
  + Paper: https://arxiv.org/abs/1704.05526
  + Material: [문태봉님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week07/2019.02.27_vqa.pdf)

* MUTAN: Multimodal Tucker Fusion for Visual Question Answering
  + Presenter: 김예찬
  + Paper:
  + Material:
  
* Multi-modal Factorized Bilinear Pooling with Co-Attention Learning for Visual Question Answering
  + Presenter: 김예찬
  + Paper:
  + Material:
  

### Week08 (19/03/06)

* Inferring and Executing Programs for Visual Reasoning
  + Presentor: 문태봉
  + Paper: https://arxiv.org/abs/1705.03633
  + Material: [문태봉님 발표자료](https://github.com/ModulabsLVNA/Modulabs_VQA/blob/master/week08/PP_ProgramsForVisualReasoning.pdf)
  
* FiLM: Visual Reasoning with a General Conditioning Layer
  + Presenter: 김예찬
  + Paper: https://arxiv.org/abs/1709.07871
  + Material:


### Week09 (19/03/13)

* BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
  + Presenter: 조원호
  + Paper: https://arxiv.org/abs/1810.04805
  + Material: [조원호님 블로그 (BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding)](https://www.notion.so/BERT-Pre-training-of-Deep-Bidirectional-Transformers-for-Language-Understanding-8d16d11659814f8c97fcee0a727cfda9)



### Week10 (19/03/20)

* TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering
  + Presenter: 문태봉
  + Paper: https://arxiv.org/abs/1704.04497
  + Material:


### Week11 (19/03/27)
 
* MovieQA: Understanding Stories in Movies through Question-Answering
  + Presenter: 오근수
  + Paper: https://arxiv.org/abs/1512.02902
  + Material:
