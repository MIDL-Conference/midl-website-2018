---
title: "Scientific program"
---

{% from "_macros.html" import paper %}

# Scientific program

Below you can find the keynotes, oral presentations and poster presentations, with links to the videos, the papers, slides, code, and data.
The original timetable can be found in the [conference book](/conference_book.pdf).

## Keynotes

[% .papers %]
{{ paper('Efficient techniques for learning confidence.',
         'Graham Taylor, *University of Guelph*.',
         'Modern neural networks are very powerful predictive models, but they are often incapable of recognizing when their predictions may be wrong. I will discuss a method of learning confidence estimates for neural networks that is simple to implement, computationally efficient and produces intuitively interpretable outputs. I will demonstrate that on the task of out-of-distribution detection, our technique surpasses recently proposed techniques which construct confidence based on the network’s output distribution, without requiring any additional labels or access to out-of-distribution examples. I will also show that it can generate per-pixel confidence maps and image-level prediction of failure in medical image segmentation.',
         'https://youtu.be/YedM4Cslj0g')
}}
{{ paper('The impact of deep learning and artificial intelligence on radiology.',
         'Ronald Summers, *NIH*.',
         'Major advances in computer science and artificial intelligence, in particular “deep learning”, are beginning to have an impact on radiology. There has been an explosion of research interest and number of publications about the use of deep learning in radiology. In this presentation, I will show examples of how deep learning has led to major improvements in automated radiology image analysis, especially for image segmentation and computer aided diagnosis. I will also show how the radiology report can be used to do bulk annotation of images for training the deep learning systems.')
}}
{{ paper('Deep learning for genomics and graph-structured data.',
         'Adriana Romero, *Facebook AI Research*.',
         'In the recent years, deep learning has achieved promising results in medical imaging analysis. However, in order to fully exploit the richness of healthcare data, new models able to deal with a variety of modalities have to be designed. In this talk, I will discuss recent advances in deep learning for genomics and graph-structured data. I will present Diet Networks, a recent contribution which copes with the high dimensionality of genomic data. Then, I will introduce our work on Graph Attention Networks, which has recently shown to improve results on protein-protein interaction networks and mesh-based parcellation of the cerebral cortex.')
}}
{{ paper('Detecting lung nodules using deep learning.',
         'Tim Salimans, *Open AI*.',
         'Lung cancer is the leading cause of cancer-related death worldwide. By screening high risk individuals for lung nodules using low-dose CT scans, this type of cancer can be detected when it is still treatable. However, large-scale implementation of such screening programs requires radiologists to evaluate a huge number of scans, which is costly and error-prone. Aidence is an Amsterdam start-up developing an AI assistant for helping radiologists with detecting, reporting and tracking of lung nodules. This talk covers the deep learning techniques that we use to obtain state of the art accuracy in this domain, as well as the requirements and challenges faced when developing a deep learning system for use in clinical practice.')
}}
[% / %]

## Oral presentations

[% .papers %]
{{ paper('Cancer Metastasis Detection With Neural Conditional Random Field.',
         'Yi Li, Wei Ping, *Baidu Silicon Valley Artificial Intelligence Lab, US*',
         'Breast cancer diagnosis often requires accurate detection of metastasis in lymph nodes through Whole-slide Images (WSIs). Recent advances in deep convolutional neural networks (CNNs) have shown significant successes in medical image analysis and particularly in computational histopathology. Because of the outrageous large size of WSIs, most of the methods divide one slide into lots of small image patches and perform classification on each patch independently. However, neighboring patches often share spatial correlations, and ignoring these spatial correlations may result in inconsistent predictions. In this paper, we propose a neural conditional random field (NCRF) deep learning framework to detect cancer metastasis in WSIs. NCRF considers the spatial correlations between neighboring patches through a fully connected CRF which is directly incorporated on top of a CNN feature extractor. The whole deep network can be trained end-to-end with standard back-propagation algorithm with minor computational overhead from the CRF component. The CNN feature extractor can also benefit from considering spatial correlations via the CRF component. Compared to the baseline method without considering spatial correlations, we show that the proposed NCRF framework obtains probability maps of patch predictions with better visual quality. We also demonstrate that our method outperforms the baseline in cancer metastasis detection on the Camelyon16 dataset and achieves an average FROC score of 0.8096 on the test set. NCRF is open sourced at https://github.com/baidu-research/NCRF.',
         'https://youtu.be/FetHmp6k4K8',
         'https://openreview.net/forum?id=S1aY66iiM',
         'https://openreview.net/pdf?id=S1aY66iiM',
         'https://github.com/baidu-research/NCRF')
}}
[% / %]