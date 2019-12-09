---
layout: post
title: "Identification of Neural Correlates of Face Recognition Using Machine Learning Approach"
date: 2019-03-05
excerpt: "My research experience under Dr. Tapan Gandhi, Indian Institute of Technology (IIT), Delhi, on using computational neuroscience and machine learning to design an artificial face recognition model for patients with Autism and Prosopagnosia."
project: true
tags: [machine learning, neuroscience, face recognition]
comments: false
---

In the summers of 2018, I had the opportunity to work under Dr. Tapan Gandhi, IIT Delhi, in his Neuroscience Lab, on using machine learning to design an Artificial Face Recognition model that worked similar to how a human brain recognises faces. 

## Problem

Existing face detection algorithms rely on massive amounts of data and perform poorly with angle and light variations [1]. Human brain, on the contrary, faces none of the above problems. Thence, using computational neuroscience to process MEG recordings of users, and support-vector machines for classification in MATLAB, I found responsive sensors and concentrated timestamps during which identification occurred.

## Findings

We found that human brain identifies a face between the first 120-240 ms of seeing it. Additionally, the most responsive sensors are located near occipitotemporal and occipitoparietal lobes and few in frontal lobe. Thus, by identifying the active sensors and the differentiating time stamps, the work was able to filter out noisy and less effective sensors and time slots. This mitigates the computational costs of the model built for face recognition by providing researchers the channels and slots to focus their research on.

The groundwork trims the active timestamp range by more than half of the existing state-of-the-art algorithm [2]. I presented this work at the ​IEEE International Symposium ISCMM 2019 (figure 1) ​and published it in the Scopus indexed ​Advances in Intelligent Systems and Computing ​(AISC) [3]. 

## Future Work

Using eye-tracking, the findings of this paper can be extended to extract features captured by the eyes during the mentioned time stamps (124–240 ms) which enabled brain to detect and classify faces.

> From this project, I learned the importance of pragmatic pre-processing and coding efficient solutions for real-life high-dimensional data.


<figure>
	<a href="/images/research/iitd/presentation.png"><img src="/images/research/iitd/presentation.png"></a>
</figure>

Conference Presentation Link: https://bit.ly/2r6kw9n


References:

[1] Khurana, P., Sharma, A., Singh, SN., Singh, P.K.: A survey on object recognition and segmentation techniques. In: 3rd International Conference on Computing for Sustainable Global Development (INDIACom), pp. 3822–3826 (2016)

[2] Streit, M., Dammers, J., Simsek-Kraues, S., Brinkmeyer, J., Wolwer, W., Ioannides, A.: Time course of regional brain activations during facial emotion recognition in humans. Neurosci. Lett. 342(12), 101–104 (2003)

[3] Gupta, S., Gandhi, T.: Identification of Neural Correlates of Face Recognition Using Machine Learning Approach. Advances in Intelligent Systems and Computing, vol 992. Springer, Singapore (2020)


