---
title: "A Deep Learning Model for Heart Sound Classification Fusing Time-Frequency Features"
collection: publications
category: manuscripts
permalink: /publication/pcg
excerpt: | 
    **Objective**: Cardiovascular diseases (CVDs) are a leading global health threat. The automatic classification of phonocardiogram (PCG) signals is crucial for their early diagnosis, yet existing models are often limited by analyzing features from only a single domain (time or frequency), failing to fuse complementary information. This study aims to develop a model that overcomes this limitation by effectively integrating both time-domain and frequency-domain features to improve classification accuracy and robustness. 

    **Methods**: We propose a novel end-to-end dual-branch deep learning model. The time-domain branch utilizes a 1D Convolutional Neural Network (CNN) with Transformer blocks to capture instantaneous dynamics and long-range dependencies. The frequency-domain branch uses a ResNet to extract robust spectral patterns from Mel-spectrograms. A key innovation is our bidirectional cross-attention fusion module, which facilitates deep interaction and mutual enhancement between the two feature modalities. Furthermore, we employ a transfer learning strategy to ensure robust performance on smaller or more challenging datasets. 

    **Results**: Comprehensive evaluations on multiple public datasets demonstrate that our model achieves state-of-the-art (SOTA) performance. On the 2016 PhysioNet Challenge dataset, it reached an accuracy of 98.86% and an F1-score of 97.19%, significantly outperforming existing baseline methods. 

    **Conclusion and Significance**: Our dual-branch fusion model provides a more effective and robust framework for heart sound classification. This work offers strong support for the development of highly accurate automated tools for the auxiliary diagnosis of CVDs, thereby holding the potential to enhance early detection and improve clinical outcomes.'
date: 2025-12-10
venue: 'IEEE Transactions on Biomedical Engineering'
paperurl: 'IEEE Transactions on Biomedical Engineering'
citation: 'Liu, N., Chen, X., Yu, Y., Guo, L., Guo, T., Qiu, B., ... & Wang, Y. (2025). A Deep Learning Model for Heart Sound Classification Fusing Time-Frequency Features. <i>IEEE Transactions on Biomedical Engineering</i>.'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
