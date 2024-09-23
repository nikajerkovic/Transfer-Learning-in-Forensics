# Transfer-Learning-in-Forensics

This repository contains the code and materials for the research conducted as part of the Master's thesis "Application of Transfer Learning in the Field of Forensics." The study was carried out in collaboration with the University Department of Forensic Sciences, University of Split.

Data scarcity is a significant issue in fields like forensics due to the sensitive nature of the data involved. This research tackles the challenge by exploring various techniques, focusing on sex classification using 220 skull images obtained through 3D reconstructions from MSCT scans.

Key strategies discussed in this study include:

  -  Classical data augmentation (rotation, lighting adjustments)
  -  Synthetic methods
  -  Transfer learning using pre-trained models, specifically ResNet50.
    
The best-performing approach combines traditional augmentation techniques and transfer learning, achieving a model accuracy of 92.54% through majority voting across different skull views (lateral, frontal, and occipital).
