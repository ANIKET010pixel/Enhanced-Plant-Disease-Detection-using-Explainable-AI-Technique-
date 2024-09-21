# Enhanced-Plant-Disease-Detection-using-Explainable-AI-Technique-

- **Technologies:** Deep Learning, CNN, Explainable AI (XAI), Python

**Purpose:**  
I initiated this project to address a critical issue in agriculture—plant disease detection. In many rural areas, farmers struggle to identify crop diseases in time, which often leads to significant crop loss and decreased yields. Traditional methods of detection can be slow, costly, and prone to human error. By integrating Explainable AI (XAI) with deep learning, my goal was to create an accurate, fast, and transparent system that could assist farmers in identifying diseases early and take corrective actions promptly.  

**Real-Life Application:**  
This AI-driven solution can be deployed as a mobile or web application, allowing farmers to upload images of their crops and receive instant feedback on potential diseases. With the Explainable AI component, farmers can not only get a prediction but also understand why the model is suggesting a particular disease, helping them to trust and act on the system's recommendations. This approach has the potential to prevent large-scale crop failure, reduce the need for expert diagnosis, and promote healthier agricultural practices.

**Challenges Faced:**  
1. **Data Collection:** One of the biggest hurdles was gathering a reliable dataset of plant disease images. Existing datasets were limited, so I worked to collect and label data directly from farms, which took significant time and effort.  
2. **Model Accuracy:** Achieving high accuracy with limited data required experimenting with different deep learning architectures and techniques, such as CNN, data augmentation, and transfer learning.  
3. **Explainability:** Incorporating Explainable AI (XAI) using Layer-wise Relevance Propagation (LRP) to not only predict but also explain the model's decisions posed another challenge. Balancing accuracy and interpretability required careful tuning of the model’s layers.

**Outcome:**  
The final model achieved an accuracy of 90% in detecting various plant diseases. The Explainable AI component provided visual feedback to users, helping farmers see which parts of the plant the model identified as diseased. This transparency built trust and allowed farmers to understand and accept the AI-driven results. The model has the potential to be scaled and integrated into agricultural advisory services, reducing crop losses by at least 10% in early implementations.
