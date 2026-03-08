---
title: "Specialized Convolutional Neural Network Models for Echolocation-Based Perception"
collection: publications
category: manuscripts
permalink: /publication/2025-9-8-IeeeAccess
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2025-9-8
venue: 'IEEE Access'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11153442'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'HS Kwon, G. U. Patil, B. I. Epureanu, and B.-I. Popa*, <i>IEEE Access</i>, vol. 13, pp. 156811-156823, 2025'
#  &quot;Broadband sound barriers with bianisotropic metasurfaces,&quot;
---
Abstract: Echolocating animals can rapidly learn echoic signatures of newly encountered objects from relatively few probing ultrasound pulses. Significant research has recently focused on replicating this ability in engineered systems, but the most promising methods rely on a single deep neural network classifier requiring very large training sets and posing significant challenges to learning additional objects. This work analyzes a perception framework in which multiple (but shallow) specialized convolutional neural networks acting in parallel identify and locate newly encountered objects using small training sets. In this approach, each recognized object has two associated networks, one specialized to identify the object and the other to locate it. Thus, learning an additional object only requires training two new networks without changing the previously trained ones. This paper shows that this architecture performs well even in cluttered environments containing closely spaced objects. More importantly, analysis of the trained neural networks provides insights into the echolocation process, such as salient echo features differentiating the echoes produced by various objects. The specialized neural network framework promises to bring the performance of artificial ultrasound perception closer to that of its biological counterparts.
