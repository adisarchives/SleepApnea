ABSTRACT

Obstructive Sleep Apnea (OSA) occurs when the airway is repeatedly obstructed during sleep due to relaxation of the tongue and airway muscles. Indicators of OSA include snoring, poor sleep quality, and waking up unrefreshed. OSA diagnosis is costly, leading to many undiagnosed cases. Previous research links facial morphology with OSA. This project investigates using deep learning on facial depth maps for OSA diagnosis, achieving around 69% validation accuracy using transfer learning.
Introduction – Aim, Objective, Scope
Aim: To develop a deep learning model for predicting OSA using facial depth maps.

Objective:
- To apply deep learning techniques on facial depth maps.
- To improve the accuracy of OSA prediction.
- To compare the new method with existing diagnostic techniques.

Scope: This study focuses on the correlation between facial morphology and OSA, using depth maps for more detailed analysis compared to 2D images.
#Existing System and its limitations
Existing System:
- Uses imaging techniques like MRI and dental X-rays to assess upper airway structures.
- Employs volumetric analysis and tomography for craniofacial measurements.

Limitations:
- Low accuracy and efficiency.
- Manual landmark detection is time-consuming and dependent on the operator's expertise.
#Proposed System and its advantages
Proposed System:
- Utilizes pre-trained CNN models (e.g., VGGFace, Pose-Aware CNN Models) for transfer learning with facial depth maps.
- Fine-tunes networks for end-to-end classification of OSA from facial depth maps.

Advantages:
- Higher accuracy and efficiency.
- Automates landmark detection, reducing time and dependency on manual expertise.
Software Architecture
Block Diagram of CNN models (VGG19, AlexNet)
UML Diagrams including Use Case, Class, Sequence, and Collaboration diagrams.

Modules:
- Upload OSA face dataset
- Preprocess dataset
- Build VGG19 model
- Upload test data & predict OSA
- Accuracy comparison graph



