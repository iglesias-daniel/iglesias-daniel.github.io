---
title: "A dataset for detecting walking, grazing, and resting behaviors in free-grazing cattle using IoT collar IMU signals" 
date: 2025-08-28
tags: ["standardized dataset","behaviors","cattle","lameness","animal welfare","IoT","IMU"]
author: ["David Morales-Vargas","Miguel Guarda-Vera","Daniel Iglesias-Quilodrán","David Cancino-Baier","Carlos Muñoz-Poblete"]
description: "This paper was published in Frontiers in Veterinary Science in 2025." 
summary: "This study presents a publicly available dataset of 441 labeled dairy cow behaviors collected via IoT collars, including accelerometer and gyroscope data for lameness-related activity classification." 
# cover:
#     image: "paper3.png"
#     alt: "A dataset for detecting walking, grazing, and resting behaviors in free-grazing cattle using IoT collar IMU signals"
#     relative: true
editPost:
    URL: "https://www.frontiersin.org/journals/veterinary-science"
    Text: "Frontiers in Veterinary Science"

---

##### Abstract

In this study, we developed a dataset of behaviors associated with lameness in dairy cows. The data collection utilized IoT collars that were placed around the necks of 10 dairy cows. This publicly available dataset contains 441 labeled behaviors, amounting to over 7 h of recording time. It includes acceleration data referenced in both body and world frames, as well as gyroscope signals, which facilitated the extraction of 112 relevant features for classifying key behaviors such as walking, grazing, and resting through machine learning algorithms. To enhance model performance and reduce feature dimensionality, automatic feature selection techniques were applied before classification. The dataset's effectiveness was assessed using various classification models, including Support Vector Machines (SVM), Logistic Regression, Decision Trees, and Random Forests. Results indicated that signals referenced to the body frame yielded better behavior discrimination, achieving a maximum macro F1-score of 0.9625 with the SVM model. This public dataset can facilitate early lameness detection by enabling accurate classification of behavior patterns.

---

##### Links

+ [Paper](https://doi.org/10.3389/fvets.2025.1630083)
+ [Paper (PDF)](paper3.pdf)
+ [Data](https://github.com/WASP-lab/db-cow-walking)

---

##### Citation

Morales-Vargas D, Guarda-Vera M, Iglesias-Quilodrán D, Cancino-Baier D and Muñoz-Poblete C (2025) A dataset for detecting walking, grazing, and resting behaviors in free-grazing cattle using IoT collar IMU signals. Front. Vet. Sci. 12:1630083. doi: 10.3389/fvets.2025.1630083

```latex
@ARTICLE{10.3389/fvets.2025.1630083,
AUTHOR={Morales-Vargas, David  and Guarda-Vera, Miguel  and Iglesias-Quilodrán, Daniel  and Cancino-Baier, David  and Muñoz-Poblete, Carlos },     
TITLE={A dataset for detecting walking, grazing, and resting behaviors in free-grazing cattle using IoT collar IMU signals},  
JOURNAL={Frontiers in Veterinary Science},  
VOLUME={Volume 12 - 2025},
YEAR={2025},
URL={https://www.frontiersin.org/journals/veterinary-science/articles/10.3389/fvets.2025.1630083},
DOI={10.3389/fvets.2025.1630083},
ISSN={2297-1769}}
```
