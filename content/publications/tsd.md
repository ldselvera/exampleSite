---
title: "Quantized Spectral Clustering with Seq2Seq Attention Model to Predict Cognitive State from Behavior Variables"
date: 2021-05-21
pubtype: "Paper"
featured: true
description: "Arun Das, Nima Ebadi, Luis Selvera, Jeffrey Mock, Edward J. Golob, Peyman Najafirad"
link: "https://openreview.net/forum?id=ZdnfEr4ESWv"
weight: 400
sitemap:
  priority : 0.8
---


Abstract

Human behavior is a reflection of brain activity, and brain disorders often result in abnormal behavior. Traditionally, interventions for brain disorders focus on either behavior, such as psychotherapy, or brain (e.g. medication, surgery), but not both. There are benefits of utilizing both brain and behavior modalities, such as early detection, treatment monitoring, and use of precision medicine to take into account individual differences. However, the central challenge in multimodal behavior and neurocognitive learning involves learning representations that can process and relate information from both modalities. In this study, we examine adults who stutter (AWS) as a testbed to use Artificial Intelligence (AI) algorithms to infer the hidden state of brain processes based on subtle observable behavior. The speech in AWS is sometimes normal, and on other occasions clearly abnormal. This dichotomy allows for classification of two behavioral states that may be related to their respective underlying brain states. By designing a sequence-to-sequence attention model, we learn the correlations between internal neurocognitive states and external facial muscle movements as AWS subjects are about to speak. We denoise and quantize the EEG signals and use the facial muscle movement sequences to predict these quantized EEG sequences. Additionally, the trained attention weights shed light into the correlations between specific brain regions and facial muscle group activity. We validate our methodology by carrying out a comprehensive study using a controlled experimental speech-behavior paradigm and by collecting the first real-world synchronized EEG and face multimodal dataset of AWS subjects. We found strong correlations among upper and lower facial regions to left-temporal and bilateral frontal brain regions. Interestingly, the brain regions identified are also the same regions that differ both structurally and functionally between people who stutter and fluent controls.