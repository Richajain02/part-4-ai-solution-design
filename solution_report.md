# Task 1:
Selected Domain: Healthcare

Healthcare is one of the most important industries where AI can improve speed, accuracy, and decision-making, especially in diagnosis and patient care.

# Task 2:
Business Problem - 

Hospitals and diagnostic centers often face delays in detecting diseases from medical images such as X-rays, CT scans, and MRI scans.
A common challenge is the early detection of pneumonia from chest X-ray images.
If pneumonia is not detected quickly, it can lead to severe complications, longer hospital stays, and even life-threatening situations.
The goal is to build an AI-based disease detection system using Computer Vision and Neural Networks to automatically identify signs of pneumonia in X-ray images.

The key stakeholders are:

* Doctors / Radiologists – Need fast and accurate diagnosis support.
* Hospitals / Clinics – Want to improve operational efficiency.
* Patients – Need faster treatment and better healthcare outcomes.
* Healthcare Management Teams – Want to reduce costs and improve service quality.

Currently, the process works like this:

1. Patient undergoes a chest X-ray.
2. The X-ray image is sent to a radiologist.
3. The radiologist manually examines the image.
4. Based on visual analysis, the doctor identifies whether pneumonia is present.
5. A diagnosis report is prepared and shared with the patient.

The traditional process has several challenges:
1. Time-Consuming - Radiologists may have to review hundreds of scans daily, which causes delays.

2. Human Error - Fatigue, workload, or subjective judgment can sometimes lead to missed diagnoses.

3. Limited Availability of Experts - In rural or underdeveloped areas, experienced radiologists may not always be available.

4. Higher Operational Costs - Manual diagnosis requires specialized experts, increasing healthcare costs.

5. Delayed Treatment - Late diagnosis can delay treatment, affecting patient recovery.

This creates a strong business case for an AI-powered solution using Convolutional Neural Networks (CNNs) for automated image classification.

## Task 3:
Selected AI Task Type: Image Classification

Medical X-ray images need to be analyzed to determine whether a patient has pneumonia or not. This is an image classification problem.

Image classification is suitable because:

* Input is image data - The system receives chest X-ray images as input.
* Output is category-based - The model predicts one of the predefined classes:  
                             1. Normal  
                             2. Pneumonia
* Deep learning performs well on medical imaging - Neural networks such as CNNs can automatically learn patterns like lung opacity, infection areas, and abnormal textures.
* Supports fast automated diagnosis - It reduces radiologists’ workload by quickly screening images.

A Convolutional Neural Network (CNN) is commonly used because it is designed to detect visual patterns in image data.
