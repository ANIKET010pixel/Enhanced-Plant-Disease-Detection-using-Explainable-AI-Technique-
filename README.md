## 🌿 Enhanced-Plant-Disease-Detection-using-Explainable-AI-Technique
**Technologies:** Convolutional Neural Networks (CNN), Explainable AI (LIME), Python

### 🎯 Purpose
I created this project to tackle a real-world agricultural challenge: the **early and accurate detection of plant diseases**. Many farmers, especially in remote or under-resourced areas, lack access to timely expert diagnosis, which often results in misdiagnosis or delayed treatments. These delays can severely impact crop yield and quality. My aim was to develop a **machine learning solution that is not only accurate but also interpretable**, enabling farmers to trust the system’s predictions and act confidently.

### 🌍 Real-Life Application
This solution can be embedded into a mobile or web-based application where farmers simply upload a picture of a diseased plant leaf. The system will return the predicted disease class **along with a visual explanation**—thanks to the LIME framework. By highlighting the image regions that contributed most to the prediction, the model builds **trust and transparency**. This real-time AI assistant could empower farmers to take immediate action, reduce dependency on expert consultations, and ultimately safeguard their crops.

### 🧷 Challenges Faced
- **Model Simplicity vs. Accuracy:** Designing a lightweight CNN that could run effectively without high-end GPUs while still delivering high accuracy was a key challenge. I had to experiment with various model architectures and fine-tune hyperparameters to strike the right balance.  
- **Visual Interpretability:** Integrating LIME with image classification models was non-trivial. Ensuring that explanations were both **intuitive and reliable** required deep understanding of how local surrogate models behave.  
- **Deployment Readiness:** Creating an interface using Streamlit that could allow for both predictions and explanation outputs involved UI/UX planning and backend optimization. The app had to be fast, responsive, and farmer-friendly.

### ✅ Outcome
- Developed a **custom CNN model** that achieved ~98% validation accuracy on plant disease classification.
- Successfully integrated **LIME** to provide pixel-level explanations for each prediction.
- Gained a deeper understanding of the trade-offs between **accuracy and interpretability**, making the model not just performant, but also **human-centric**.

This project demonstrated how AI can go beyond predictions to foster **trust, usability, and real-world impact**—especially in critical domains like agriculture.

