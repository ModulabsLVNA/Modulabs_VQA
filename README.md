# Modulabs_VQA
모두의 연구소 풀잎스쿨 질문을 해봐요! (2019.01.09~2019.03.27)

이벤트 사이트: https://event-us.kr/modu/event/4674

참가자: 김예찬, 문태봉, 오근수, 유준봉, 정민지, 조원호

퍼실이: 문태봉


## Paper List : arXiv기준

### 큰 그림 그리는 기준(김예찬 기준...)
- A : Neural Module Networks
- B : 각 단어가 이미지의 어떤 feature에 대응하게 Attention을 사용한 접근 방식, 단점 : 이미지 공간에서 명확한 의미론적인 내용을 담고 있지 않는 단어가 있다는 것. NLP Pipeline에서 해결해야 함
- C : Attention을 선택적으로 사용하는 방법 
- D : Softmax를 사용해서 attention의 가중치를 구함
- E : bilinear


### 2014
 - Neural Machine Translation by Jointly Learning to Align and Translate(1409)

### 2015
 - Show, Attend and Tell: Neural Image Caption Generation with Visual Attention(1502) : B, D
 - Ask Your Neurons: A Neural-based Approach to Answering Questions about Images(1505)
 - VQA: Visual Question Answering(1505)
 - Stacked Attention Networks for Image Question Answering(1511) : B, D
 - Neural Module Networks(1511) = Deep Compositional Question Answering with Neural Module Networks(같음) : A
 - Visual7W: Grounded Question Answering in Images(1511) : D
 - Ask, Attend and Answer: Exploring Question-Guided Spatial Attention for Visual Question Answering(1511) : B, D
 - Image Question Answering using Convolutional Neural Network with Dynamic Parameter Prediction(1511)
 - ABC-CNN: An Attention Based Convolutional Neural Network for Visual Question Answering(1511) : B, D
 - Compact Bilinear Pooling(1511) : D
 - Where To Look: Focus Regions for Visual Question Answering(1511) : D
 - Simple Baseline for Visual Question Answering(1512)

### 2016
 - Learning to Compose Neural Networks for Question Answering(1601) : A
 - Dynamic Memory Networks for Visual and Textual Question Answering(1603)
 - A Focused Dynamic Attention Model for Visual Question Answering(1604)
 - Hierarchical Question-Image Co-Attention for Visual Question Answering(1606) : B, D
 - Multimodal Residual Learning for Visual QA(1606) : E
 - **(MCB)** Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding(1606) : D, E
 - **(MLB)** Hadamard Product for Low-rank Bilinear Pooling(1610) : E
 - Diverse Beam Search: Decoding Diverse Solutions from Neural Sequence Models(1610)
 - Modeling Relationship in Referential Expressions with Compositional Modular Networks(1611)
 - Dual attention networks for multimodal reasoning and matching(1611)
 - Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering(1612)
 - The VQA-Machine: Learning How to Use Existing Vision Algorithms to Answer New Questions(1612)

### 2017
 - An Analysis of Visual Question Answering Algorithms(1703)
 - Learning to Reason: End-to-End Module Networks for Visual Question Answering(1704) : A, C
 - Inferring and Executing Programs for Visual Reasoning(1705) : A
 - **(MUTAN)** MUTAN: Multimodal Tucker Fusion for Visual Question Answering(1705) : E
 - Attention is All You Need(1706)
 - A simple neural network module for relational reasoning(1706)
 - Learning Visual Reasoning Without Strong Priors(1707)
 - Bottom-up and top-down attention for image captioning and visual question answering(1707) : B, D
 - **(MFB)** Multi-modal Factorized Bilinear Pooling with Co-Attention Learning for Visual Question Answering(1708) : E
 - Tips and Tricks for Visual Question Answering: Learning from the 2017 Challenge(1708)
 - **(MFH)** Beyond Bilinear: Generalized Multimodal Factorized High-Ordered Pooling for Visual Question Answering(1708) : E
 - Robustness Analysis of Visual QA Models by Basic Questions(1709)
 - FiLM: Visual Reasoning with a General Conditioning Layer(1709)
 - High-Order Attention Models for Visual Question Answering(1711)


### 2018 : 차후에 정리....
 - Structured Triplet
 - Transparency by Design: Closing the Gap Between Performance and Interpretability in Visual Reasoning(1803)
 - Improved Fusion of Visual and Language Representations by Dense Symmetric Co-Attention for Visual Question Answering(1804)
 - Bilinear Attention Networks(1805)
 - Visual Reasoning by Progressive Module Network(1806)
 - Learning Answer Embeddings for Visual Question Answering(1806)
 - Latent Alignment and Variational Attention(1807)


## Schedule
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
  + Material:

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
* Multimodal Compact Bilinear Pooling for Visual Question Answering and Visual Grounding
  + Presenter: 김예찬
  + Paper: https://arxiv.org/abs/1606.01847
  + Material:

* Stacked Attention Networks for Image Question Answering
  + Presenter: 오근수
  + Paper: https://arxiv.org/abs/1511.02274
  + Material:
  
### Week07 (19/02/27)
* Learning to Reason: End-to-End Module Networks for Visual Question Answering (코드구현)
  + Presenter: 문태봉
  + Paper: https://arxiv.org/abs/1704.05526
  + Material:

* ???
  + Presenter:
  + Paper:
  + Material:

### Week08 (19/03/06)
* ???
  + Presenter:
  + Paper:
  + Material:

* ???
  + Presenter:
  + Paper:
  + Material:

### Week09 (19/03/13)
* ???
  + Presenter:
  + Paper:
  + Material:

* ???
  + Presenter:
  + Paper:
  + Material:

### Week10 (19/03/20)
* MovieQA: Understanding Stories in Movies through Question-Answering
  + Presenter:
  + Paper: https://arxiv.org/abs/1512.02902
  + Material:

* MarioQA: Answering Questions by Watching Gameplay Videos
  + Presenter:
  + Paper: https://arxiv.org/abs/1612.01669
  + Material:

### Week11 (19/03/27)
* TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering
  + Presenter:
  + Paper: https://arxiv.org/abs/1704.04497
  + Material:

* DeepStory: Video Story QA by Deep Embedded Memory Networks
  + Presenter:
  + Paper: https://arxiv.org/abs/1707.00836
  + Material:
