# Parkinson’s Disease Classification Using Speech Under Data-Constrained Regime

This repository contains our paper **“Parkinson’s Disease Classification Using Speech Under a Data-Constrained Regime.”**

## Abstract

Speech-based detection of Parkinson’s disease (PD) provides a promising pathway for early and noninvasive diagnosis using everyday devices. Motor impairment associated with PD affects the muscles responsible for controlling the vocal folds and articulators, leading to measurable changes in speech.  This work presents a complete pipeline for PD detection using two types of speech samples: sustained /aa/ phonation and reading speech, collected from a dataset with a limited number of speakers. Acoustic features were extracted using the ComParE 2016 feature set, including functional and low-level descriptor (LLD) features. For functional features, the mRMR algorithm was used to select predictors, with each audio sample segmented into 3s clips and evaluated using traditional machine learning classifiers. For LLD features, 60ms frames were extracted from both speech types and used to train deep learning models. Experiments show that reading speech provides more discriminative cues for PD classification, with traditional ML models performing best on reading speech and deep learning models performing best on sustained /aa/ phonation. Baseline classifiers trained on handcrafted features were also evaluated, but the proposed pipeline outperformed them.

## Citation

**Mayurakshi Mukherji\***, **Hrithik Mhatre†**, **Vamshika Sutar†**, **Nirmal Punjabi\***, **Ganesh Ramakrishnan‡**  
\*Koita Center for Digital Health, IIT Bombay  
†Department of Civil Engineering, IIT Bombay  
‡Department of Computer Science and Engineering, IIT Bombay

