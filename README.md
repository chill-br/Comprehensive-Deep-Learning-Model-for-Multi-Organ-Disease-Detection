**Comprehensive Deep Learning Model for Multi-Organ Disease Detection**
This project presents a deep learning-based solution for multi-organ disease detection using medical imaging data such as X-rays, MRI, and CT scans. It leverages state-of-the-art CNN architectures like ResNet, 
VGG16, and DenseNet to accurately detect diseases such as brain tumors, lung cancer, breast cancer, oral diseases, and kidney conditions. The system integrates multiple pre-trained models into a Streamlit web 
application, allowing real-time medical image classification through a simple and intuitive interface.

Key Features
* Multi-Organ and Multi-Modal Support: Detects diseases across multiple organs using different types of imaging modalities.
* High Accuracy: Achieved up to 95% overall accuracy across all disease categories.
* Real-Time Predictions: Predicts disease presence within 2 seconds per image.
* User-Friendly Interface: Simple web app for uploading medical images and receiving diagnostic results.
* Explainable AI: Integrates Grad-CAM visualizations to highlight important regions in medical images.
* Scalability: Easily expandable to add new diseases and imaging modalities.
* Secure: Designed to ensure patient data privacy and secure storage.

Technologies Used
* Python
* TensorFlow/Keras
* Streamlit (for Web Interface)
* OpenCV (for image preprocessing)
* MySQL (for data storage)

Project Workflow
* Upload medical images via the web interface.
* Images are preprocessed (resizing, normalization, augmentation).
* Processed images are fed to trained deep learning models.
* Disease prediction along with confidence scores and heatmaps are displayed to the user.
* Results are stored securely for further analysis.

Future Enhancements
* Expand support to more diseases (e.g., liver, heart diseases).
* Mobile application development for broader access.
* Implement federated learning for privacy-preserving model training.
* Real-time video-based diagnostic support.
* Improved model explainability for better clinical adoption.

Output
![image](https://github.com/user-attachments/assets/24dd07dd-7f17-47ac-abce-fe72915902b2)
![image](https://github.com/user-attachments/assets/a8d33125-0890-4503-8b50-52d0bb4c3ee4)
