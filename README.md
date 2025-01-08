Diabetic Retinopathy Detection using Transfer Learning (ResNet50)
This project leverages deep learning and transfer learning to classify diabetic retinopathy severity using a ResNet50 model pre-trained on ImageNet. The dataset comprises retina fundus images annotated with levels of diabetic retinopathy. The goal is to create a robust, efficient model to assist in early diagnosis and treatment planning.

#📂 Project Structure
Data Preprocessing: Images are resized, normalized, and augmented using techniques like Gaussian blurring and weighted adjustments to enhance contrast.
Model Architecture: ResNet50 (pre-trained) is used as the backbone, with additional layers for classification of 5 severity levels of diabetic retinopathy.
Training and Validation: The model is trained with augmented data and validated on a subset of the training set.
Evaluation: The model is evaluated on a separate test set to measure accuracy and performance.

#🗂 Dataset
Source: Diabetic Retinopathy Detection Dataset
Classes:
0: No retinopathy
1: Mild non-proliferative diabetic retinopathy (NPDR)
2: Moderate NPDR
3: Severe NPDR
4: Proliferative diabetic retinopathy (PDR)

#⚙️ Technologies Used
Programming Language: Python
Deep Learning Framework: TensorFlow/Keras
Preprocessing Tools: OpenCV, NumPy, Pandas
Visualization: Matplotlib
Data Augmentation: ImageDataGenerator
Model Architecture: ResNet50 (Transfer Learning)

#📊 Model Performance
Final Accuracy on Test Set: 74%

#🖼 Image Preprocessing
Enhancement: Gaussian blur and contrast adjustments.
Normalization: All pixel values are scaled to [0, 1].
Augmentation:
Rotation
Zoom
Horizontal Flip

#🔧 Key Features
Transfer Learning: Utilized ResNet50 for faster convergence and improved performance.
Data Augmentation: Improved model robustness with extensive augmentation techniques.
Custom Preprocessing: Enhanced input images for better model accuracy.

#🔬 Future Improvements
- Experiment with other pre-trained architectures like EfficientNet.
- Integrate explainability tools such as Grad-CAM for model interpretability.
- Fine-tune ResNet50 layers to improve performance further.

Dataset from kaggle: [https://www.kaggle.com/datasets/tanlikesmath/diabetic-retinopathy-resized/data?select=resized_train](url)
<br>
This project is an ongoing project.
