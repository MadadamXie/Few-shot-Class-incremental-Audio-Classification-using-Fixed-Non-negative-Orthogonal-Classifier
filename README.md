# Few-shot Class-incremental Audio Classification using Fixed Non-negative Orthogonal Classifier

**Yuhan Xie<sup>1</sup>, Wei Xie<sup>1,2,*</sup>, Xuanyan Chen<sup>1</sup>, Chuanqi Huang<sup>1</sup>, Xilin Liu<sup>1</sup>**

<sup>1</sup> School of Computer, Electronics and Information, Guangxi University, Nanning 530004, China

<sup>2</sup> Guangxi Academy of Artificial Intelligence, Nanning 530028, China

📧 xieyuhan@st.gxu.edu.cn, xiewei@gxu.edu.cn

\* Corresponding Author

## Abstract

Few-shot class-incremental audio classification (FCAC) aims to simulate real-world scenarios in which a deployed model must continually adapt to novel classes with only a limited number of samples. Most existing FCAC methods adopt a decoupled training strategy with an extensible prototype-based classifier, whose performance critically depends on strong inter-class separability and intra-class compactness.

To address this challenge, we propose a novel FCAC framework that integrates three key components:
1. **Extensible Fixed Non-negative Orthogonal (EFNO) Classifier**  
   Anchors features of different classes to mutually orthogonal directions, thereby enhancing inter-class separability.
2. **Semantic-Guided Pseudo Incremental Learning (SGPIL)**  
   Introduces pseudo novel samples during the base session to effectively promote intra-class compactness.
3. **Memory Replay Scheme (MRS)**  

Preserves and replays a small number of samples per class to maintain both inter-class separability and intra-class compactness throughout incremental sessions.
Extensive experiments demonstrate that the proposed method outperforms existing baselines in terms of both **Average Accuracy (AA)** and **Comprehensive Performance Score (CPS)**.

![Framework](fig/Frameworks(1)_01.png)

