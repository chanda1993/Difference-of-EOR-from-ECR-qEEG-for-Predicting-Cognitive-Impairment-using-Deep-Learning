# Difference of EOR from ECR qEEG for Predicting Cognitive Impairment using Deep Learning
# Abstract

# Purpose
Electroencephalography (EEG) is a method that offers detailed observations of electrical activities occurring in the brain’s cerebral cortex. The EEG-derived brain signals can serve as a neurophysiological indicator for the early detection of dementia through quantitative EEG (qEEG) analysis. This study introduces a deep learning (DL)-based classification approach trained with subtracting qEEG time-frequency (TF) images of eyes-open resting (EOR) from eyes-closed resting (ECR) state EGG for the detection of mild cognitive impairment (MCI) and Alzheimer’s disease (AD) among subjects.

# Methods and Participants
The dataset comprised 16,910 TF images from 890 subjects, including 269 normal controls (NC), 356 with MCI, and 265 diagnosed with AD. The artifacts free of traditional EEG signals were converted into qEEG TF images using the Fast Fourier Transform (FFT), which captured various event-related alterations within the five (delta, theta, alpha, beta, gamma) EEG frequency sub-bands. EEG data was preprocessed using the EEGlab toolbox version 2022 within the MATLAB R2024a software environment. The preprocessed TF images were then utilized in a DL algorithm convolutional neural network (CNN) classification with age as the input variable.

# Results
The performance metrics of the trained models for EOR - ECR in differentiating NC vs. MCI, NC vs. AD, and NC vs. cognitive impairment (CI) (MCI + AD) classes were assessed using the test dataset from the subjects. The model NC vs. CI yielded the best area under the curve (AUC), accuracy, sensitivity, and specificity with 0.95, 0.93, 0.97, and 0.92; NC vs. AD was 0.88, 0.88, 0.89, and 0.86; and NC vs. MCI was 0.85, 0.83, 0.9, and 0.81, respectively.

# Conclusion
The findings suggest subtracting EOR from the ECR qEEG state can be another practical approach to detecting cognitive impairment in dementia research with DL. The trained models could also serve as a reference to assist physicians in clinical sectors for the early diagnosis of cognitive impairment.

Keywords: neurodegenerative diseases, electroencephalography, supervised deep learning, classification

# Study Framework

![image](https://github.com/user-attachments/assets/2f979c2b-5de4-4d1d-99fa-c9ce1458d293)

