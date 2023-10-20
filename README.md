# CHIEF - Clinical Histopathology Imaging Evaluation Foundation Model


### A Generalizable Foundation Model for Quantitative Pathology Image Analyses 

Wang X., et al.

#### ABSTRACT 
Histopathology image evaluation is indispensable for cancer diagnoses and subtype evaluation. Standard artificial intelligence (AI) methods for histopathology image analyses focused on optimizing specialized models for each diagnostic task. Although such methods attained some success, they often have limited generalizability to images generated by different digitization protocols or samples collected from different populations. To address this challenge, we devised the Clinical Histopathology Imaging Evaluation Foundation Model (CHIEF), a weakly supervised machine learning framework trained with 60,530 whole-slide images (WSIs) spanning 19 distinct cancer types. CHIEF leverages two complementary pretraining methods to extract diverse pathology representations: unsupervised pretraining for tile-level feature identification and weakly supervised pretraining for whole-slide pattern recognition. Through pretraining on 44 terabytes of high-resolution histopathology imaging datasets, CHIEF extracted pathology imaging representations useful for cancer detection, tumor origin identification, molecular profile characterization, and survival outcome prediction. We successfully validated CHIEF using 24,765 whole-slide images of 38 independent slide sets collected from 24 hospitals and cohorts internationally. CHIEF consistently outperformed conventional models for digital pathology analyses, showing its ability to address domain shifts observed in samples from diverse populations and processed by different slide preparation methods. CHIEF provides a generalizable foundation for efficient digital pathology evaluation for cancer patients.

![main figure](https://github.com/hms-dbmi/CHIEF/assets/31292151/022b0829-6e3c-4ffa-92a0-645622949fab)


