This project focuses on automated brain tumor segmentation and classification using a 3D U-Net deep neural network. The system processes multi-modal MRI scans to accurately identify tumor regions such as edema, tumor core, and enhancing tumor. It helps improve medical diagnosis by reducing manual effort and increasing segmentation accuracy.
🚀 Features
Brain tumor detection from MRI images
3D MRI volumetric segmentation
Tumor classification using deep learning
Data preprocessing and augmentation
Visualization of segmented tumor regions
Web interface for prediction and analysis
🧠 Technologies Used
Python
Deep Learning
3D U-Net
CNN
TensorFlow / PyTorch
OpenCV
Flask
NumPy
Pandas
Matplotlib
📂 Dataset
BraTS (Brain Tumor Segmentation Challenge) Dataset
Multi-modal MRI scans: T1, T1c, T2, and FLAIR
⚙️ Methodology
Data preprocessing
Skull stripping
Intensity normalization
Resizing and augmentation
Model building
3D U-Net architecture
Encoder-decoder structure with skip connections
Training and evaluation
Dice Loss and Cross-Entropy Loss
Metrics: Dice Score, IoU, Accuracy, Precision, Recall
📊 Results
The model achieved accurate tumor segmentation and reliable classification performance on MRI datasets, improving boundary detection and reducing false positives compared to traditional methods.
💻 Installation
Bash
git clone <repository-link>
cd brain-tumor-3dunet
pip install -r requirements.txt
python app.py
▶️ Usage
Upload MRI brain scan dataset
Preprocess dataset
Train model
Predict and classify tumor type
View segmentation results
🔮 Future Scope
Integration with hospital PACS systems
Attention-based 3D U-Net models
Cloud deployment for real-time diagnosis
Improved multi-modal MRI fusion
👩‍💻 Team Members
Renuka Reddy
Vempati Rajkumar
Pillagulla Vasantha
Kota Venkat Ramana
📚 References
U-Net: Convolutional Networks for Biomedical Image Segmentation
3D U-Net: Learning Dense Volumetric Segmentation from Sparse Annotation
BraTS Brain Tumor Segmentation Challenge
