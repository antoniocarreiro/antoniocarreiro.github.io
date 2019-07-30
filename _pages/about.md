---
permalink: /
title: "Abstract"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Breast cancer is the leading cause of cancer in women worldwide and so it is important to empower the patients and improve the communication between them and the physician. Therefore, the use ultrasound imaging for study, evaluation and development of different techniques for anatomical landmark segmentation of the different structures and lesions of the female breast can play a significant role.
Bearing this in mind, our goal is to develop an algorithm for automated segmentation of several anatomical structures as well as lesions of the female breast using ultrasound imaging.
In this dissertation, we investigate the use of six different methods for lesion segmentation - K-means clustering, Mean shift clustering, Watershed segmentation, Region growing, Active contour model (Snakes) and Bi-polar minimum path; and three for anatomical structures segmentation - K-means clustering, Mean shift clustering and Watershed segmentation, all of them followed by a shortest path algorithm to connect one margin to the other. To assess the results we compare them with manually delineated annotations by a radiologist using Pixel-Area and Contour-wise metrics.
Our results indicate that contour-based and region-based methods have a better performance than clustering-based and watershed-based methods for lesion segmentation. Furthermore, Active contour model was the most successful of the methods tested for the task at hands. On the other hand, our results also suggest that clustering-based methods perform better than watershed-based segmentation methods for anatomical structures segmentation. Moreover, K-means clustering revealed to be the most fruitful of the methods tested for this type of segmentation.
