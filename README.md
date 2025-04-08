# Diverse Sports Activity Recognition Using Custom Convolutional Neural Networks (CNNs) for Complex Athletic Movements
 deep learning-based solution for real-time classification and recognition of athletic movements across multiple sports disciplines using custom CNN and LSTM architectures.

# Dataset 📈

UCF Sports Action Dataset

Link: UCF Sports Action Dataset

Training Size: 8185

Test Size: 1456

# Objective

To automate the recognition of complex athletic movements (e.g., running, kicking, swinging) from videos/images using deep learning, improving the efficiency, accuracy, and speed of performance analysis in sports, healthcare, and fitness.

👥 Target Audience

Sports analytics companies

Coaches and trainers

Physical therapists and rehab specialists

Sports broadcasters and media outlets

Wearable tech developers

# Problem Statement ❗

Manual observation of sports activities is time-consuming, prone to error, and lacks real-time feedback. This solution aims to overcome these challenges by offering an automated, scalable, and accurate action recognition system using deep learning models trained on a diverse dataset.

# Proposed Solution ✅ 

A deep learning pipeline that leverages:

Custom CNN for spatial feature extraction

LSTM for modeling temporal sequences in videos

Fully Connected Layers for final action classification

Trained on the UCF Sports Action Dataset with real-time deployment capabilities

# Model Architecture 🧠

Preprocessing:

Extract video frames using OpenCV

Resize and augment data

Extract features using a fine-tuned ResNet50

Model Structure:

CNN layers for spatial feature extraction

LSTM layer for capturing sequential dependencies

Fully connected layers for classification

Training:

Loss: Categorical Cross Entropy

Optimizer: Adam

Accuracy: 81.11%

Precision: 0.7547

Recall: 0.8111

F1-Score: 0.7779

Training Time: ~30-35 minutes

Memory Used: 1127.83 MB

Memory Reserved: 1382.00 MB

# Technology Stack🧰

Python

PyTorch

TorchVision

OpenCV

CUDA Toolkit (GPU acceleration)

Scikit-learn (Evaluation)

Transfer Learning (ResNet50)

# Demo Requirements ⚙️ 

Hardware:

GPU-enabled system with CUDA support (e.g., NVIDIA GPU)

Software:

PyTorch

TorchVision

OpenCV

CUDA Toolkit

Jupyter Notebook / VSCode

📈 Future Enhancements

Add support for additional sports actions

Incorporate 3D CNNs for improved temporal modeling

Integrate with pose estimation systems for more granular motion analysis

Deploy model in edge devices or mobile apps
