---
layout: page
title: Projects
slug: Projects
menu: true
order: 2
description: >
---

1. **T-Net: Weakly Supervised Graph Learning for Combatting Human Trafficking**

   Posed the problem of detecting organized crime groups from online escort markets as node classification in graphs. Introduced labelling functions to obtain weak labels and combined a weakly supervised approach with graph contrastive learning. This approach effectively detected suspicious groups with a 7% increase in accuracy over previous methods.   

2. **Person Name Extraction for Fighting Human Trafficking**

   Proposed a weak supervision pipeline to obtain person names from noisy, user-generated escort ads by combining multiple NER models (including rule-based, dictionary and various language models). Such a combination improved extraction accuracy by 19%

3. **VisPaD - Visualization and Pattern Discovery for Fighting Human Trafficking**

   An interactive visual system designed for domain experts to annotate clusters of escort ads based on suspiciousness of trafficking. It makes use of micro-clusters obtained by running Infoshield algorithm. [Code](https://github.com/nair-p/VisPaD) [Poster](assets/VisPaD_poster.pdf)

4. **Mortality prediction on MIMIC-III using a latent topic model**  

   Introduced the idea of treating different types of clinical notes from EHR (physician notes, nurses notes, etc) as different modalities in learning latent topics from MIMIC-III data and using the learned topics for making clinically relevant predictions.

5. **Group Equivariant Deep Reinforcement-Learning**

   Used an equivariant CNN for approximating Q-values using Deep Q-Network algorithm for symmetric RL environments like Snake and Pacman. Currently under review in an ML conferencce.

6. **Method Summarization from Code**

   This work was carried out while I was an intern at **IBM Research AI Lab, Bangalore** from May'18 to Aug'18. I worked with **Rahul AR** on using sequence-to-sequence models models for solving problems prevalent in Software Engineering -- the automatic generation of method names from method bodies.

7. **Automatic ROI detection from Histopathological slides**

   This work uses an RCNN architecture to automatically detect suspicious (of being carcinogenic) regions in images of histopathological slides. It works for images at various zoom levels. The main challenges faced during this project was dealing with the large sizes of images (nearly 22000x37000) which we circumvented by dividing into multiple grids and stitching them back together for visualizing results. This project was carried out under the guidance of [Prof. T  K Srikanth](https://www.iiitb.ac.in/faculty_page.php?name=tksrikanth). The boxes denote suspicious regions.
<br>
<img src="/assets/img/roi-det.png" height="150" width="600">

8. **Scaling up Simhash**

   This is a dimensionality reduction algorithm that maintains an estimate of the cosine similarity between the original high-dimensional data points. This work was done in collaboration with [Dr. R Pratap](https://sites.google.com/site/prataprameshwaryadav/) and is currently under review at a top tier AI conference.


9. **Detection of star clusters using Pattern Analysis**

   This work was done with [Prof. Sarita Vig](https://www.iist.ac.in/ess/sarita) while I was an intern at the [Indian Institute of Space Sciene and Technology](https://www.iist.ac.in/) from May'17 to Aug'17. Worked on a direct application of pattern analysis techniques for a highly relevant problem statement in astrophysics. Used the K-Nearest Neighbor algorithm for density estimation and detection of star clusters. The images below show contour plots of a locus of simulated points with equal probability density. Highly dense regions correspond to star clusters.
<br>
<img src="/assets/img/iist.jpg" height="150" width="200"> <img src="/assets/img/iist2.jpg" height="150" width="200"> <img src="/assets/img/iist3.jpg" height="150" width="200">

<!-- 2. **Word Embeddings for the Medical Domain**

    This work is on generating word embeddings specifically for medical terms making use of hierarchical ontologies in
	medicine. This work was advised by [Prof. G S Raghavan](https://www.iiitb.ac.in/faculty_page.php?name=gsrinivasaraghavan). -->