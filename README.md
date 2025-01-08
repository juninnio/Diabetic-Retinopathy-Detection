Diabetic Retinopathy Detection using Transfer Learning (ResNet50)
This project leverages deep learning and transfer learning to classify diabetic retinopathy severity using a ResNet50 model pre-trained on ImageNet. The dataset comprises retina fundus images annotated with levels of diabetic retinopathy. The goal is to create a robust, efficient model to assist in early diagnosis and treatment planning. This is still an ongoing project and I am researching for ways to imporve the accuracy.

# 📂 Project Structure
Data Preprocessing: Images are resized, normalized, and augmented using techniques like Gaussian blurring and weighted adjustments to enhance contrast.<br>
Model Architecture: ResNet50 (pre-trained) is used as the backbone, with additional layers for classification of 5 severity levels of diabetic retinopathy.<br>
Training and Validation: The model is trained with augmented data and validated on a subset of the training set.<br>
Evaluation: The model is evaluated on a separate test set to measure accuracy and performance.<br>

# 🗂 Dataset
Source: Diabetic Retinopathy Detection Dataset<br>
Classes:<br>
0: No retinopathy<br>
1: Mild non-proliferative diabetic retinopathy (NPDR)<br>
2: Moderate NPDR<br>
3: Severe NPDR<br>
4: Proliferative diabetic retinopathy (PDR)<br>

# ⚙️ Technologies Used
Programming Language: Python<br>
Deep Learning Framework: TensorFlow/Keras<br>
Preprocessing Tools: OpenCV, NumPy, Pandas<br>
Visualization: Matplotlib<br>
Data Augmentation: ImageDataGenerator<br>
Model Architecture: ResNet50 (Transfer Learning)

# 📊 Model Performance
Final Accuracy on Test Set: 74%

# 🖼 Image Preprocessing
Enhancement: Gaussian blur and contrast adjustments.<br>
Normalization: All pixel values are scaled to [0, 1].<br>
Augmentation:
- Rotation
- Zoom
- Horizontal Flip

# 🔧 Key Features
Transfer Learning: Utilized ResNet50 for faster convergence and improved performance.<br>
Data Augmentation: Improved model robustness with extensive augmentation techniques.<br>
Custom Preprocessing: Enhanced input images for better model accuracy.<br>

# 🔬 Future Improvements
- Experiment with other pre-trained architectures like EfficientNet.
- Integrate explainability tools such as Grad-CAM for model interpretability.
- Fine-tune ResNet50 layers to improve performance further.

Dataset from kaggle: [https://www.kaggle.com/datasets/tanlikesmath/diabetic-retinopathy-resized/data?select=resized_train](url)
