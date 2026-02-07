---
title: "Cattle Localization in Free-Grazing System Using a Distance-Based GNSS/SINS Method" 
date: 2025-11-24
tags: ["Cattle localization","energy-efficient localization","GNSS","precision livestock farming","SINS"]
author: ["Cristian González-Aguirre","Daniel Iglesias-Quilodrán","Carlos Muñoz-Poblete"]
description: "This paper was published in IEEE Sensors Journal in 2025." 
summary: "This study proposes a hybrid SINS–GNSS localization system for cattle monitoring using IoT smart collars, reducing GNSS usage through distance-based update triggers while maintaining accuracy." 
cover:
    image: "paper4.png"
    alt: "Cattle Localization in Free-Grazing System Using a Distance-Based GNSS/SINS Method"
    relative: true
editPost:
    URL: "https://ieee-sensors.org/ieee-sensors-journal/"
    Text: "IEEE Sensors Journal"

---

##### Abstract

This study presents a localization system based on a hybrid algorithm that combines strapdown inertial navigation systems (SINSs) and Global Navigation Satellite Systems (GNSSs) to estimate the position and movement of cattle in a precision livestock farming (PLF) context. The system is applied to data collected from Internet of Things (IoT) smart collars worn by dairy cows in a freegrazing system, which includes inertial measurement units (IMUs) and global positioning system (GPS) modules. The proposed algorithm is a distance-based approach designed to reduce GNSS usage while maintaining acceptable localization accuracy. A Kalman filter is used to estimate the collar’s orientation from inertial data, enabling the transformation of accelerations from the body frame to the world frame. These corrected accelerations are then integrated to estimate the cow’s displacement. GNSS updates are triggered only when the accumulated distance exceeds a predefined threshold, limiting the drift of the inertial system with minimal energy consumption. The algorithm is compared against a baseline method using fixed-time GNSS updates and is evaluated in terms of localization error (relative to the original GNSS position) and energy consumption. The proposed system achieved an error of less than 43 m for 90% of the cases when using a 50-m distance-based update and reduced GNSS usage by 96.5%, which suggests a significant decrease in energy consumption. In addition, it outperformed the fixed-time method by achieving a lower 90th percentile error, particularly when GNSS updates were triggered by distance thresholds greater than 26 m.

---

##### Links

+ [Paper](https://doi.org/10.1109/jsen.2025.3633694)

---

##### Citation

González-Aguirre, C., Iglesias-Quilodrán, D., & Muñoz-Poblete, C. (2026). Cattle Localization in Free-Grazing System Using a Distance-Based GNSS/SINS Method. IEEE Sensors Journal, 26(1), 1011–1024. doi:10.1109/JSEN.2025.3633694

```latex
@ARTICLE{11266985,
  author={González-Aguirre, Cristian and Iglesias-Quilodrán, Daniel and Muñoz-Poblete, Carlos},
  journal={IEEE Sensors Journal}, 
  title={Cattle Localization in Free-Grazing System Using a Distance-Based GNSS/SINS Method}, 
  year={2026},
  volume={26},
  number={1},
  pages={1011-1024},
  keywords={Global navigation satellite system;Cows;Sensors;Location awareness;Global Positioning System;Energy consumption;Accuracy;Livestock;Inertial navigation;Data acquisition;Cattle localization;energy-efficient localization;Global Navigation Satellite System (GNSS);precision livestock farming (PLF);strapdown inertial navigation system (SINS)},
  doi={10.1109/JSEN.2025.3633694}}
```
