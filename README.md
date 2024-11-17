### **PLANT DISEASE CLASSIFICATION & CURE PREDICTION USING CONVOLUTIONAL NEURAL NETWORK (CNN)** 

--- 
**Overview**

The early detection and prevention of plant diseases are crucial for increasing agricultural yield and preventing economic losses.
This project uses Convolutional Neural Networks (CNN) to automatically classify plant diseases based on leaf images.
It also provides prevention and cure suggestions for the detected diseases, enabling timely action.

#### **Features**

**Image Classification**: Detects 38 plant conditions, including healthy and diseased classes.

**Prevention and Cure Suggestions**: Offers actionable insights for disease management.

**Deep Learning Model**: Implements a CNN architecture for accurate disease classification.

**High Accuracy**: Achieves a validation accuracy of ~89%.

---

**Dataset**
The dataset contains images of healthy and diseased plants, along with a CSV file mapping diseases to their prevention and cure information.

---

**Project Steps**

1. Importing Libraries
Includes TensorFlow, Keras, NumPy, Pandas, and Matplotlib for data handling, model building, and visualization.

2. Data Preparation
Data is split into training and validation sets.
Data augmentation techniques are applied to improve model robustness.

4. CNN Model Architecture
The model includes:
Convolutional Layers: Feature extraction from images.
Pooling Layers: Reducing dimensionality.
Fully Connected Layers: Classification into categories.

4. Training
The CNN is trained using the Adam optimizer and categorical cross-entropy loss over 10 epochs.

5. Disease Prediction
The model takes a plant leaf image, predicts the disease, and provides prevention and cure information.

6. Model Evaluation
Validation Accuracy: ~89%

---

**Usage**
**Prerequisites**
Python 3.7 or above
Libraries: TensorFlow, Keras, NumPy, Pandas, Matplotlib

---

**Outputs**

**Example Output:**

**Predicted Class:** Tomato Yellow Curl Virus

**Prevention:** Control whitefly populations with insecticides or natural predators. Remove infected plants.

**Cure:** No specific cure exists. Focus on prevention and whitefly control.

---

**Future Enhancements**

Real-Time Detection: Integrate real-time disease detection via mobile or IoT devices.

Dataset Expansion: Incorporate more plant species and disease classes.

Deployment: Develop a user-friendly web or mobile app.

---

**Contributing**
Contributions are welcome! Feel free to open an issue or submit a pull request.


Contributions are welcome! Feel free to open an issue or submit a pull request.


