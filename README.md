**AI Image Enhancer**

The AI Image Enhancer is a deep learning-based project designed to sharpen and enhance blurry images using a simple Convolutional Neural Network (CNN). It simulates a teacher-student model where the "teacher" applies a blur to an image and the "student" (CNN) learns to reverse this effect and recover the original sharp version. This project is great for beginners looking to understand: Image enhancement techniques Basic CNN architecture in PyTorch Real-world image preprocessing with OpenCV How to build a front-end using Streamlit

**🚀 Demo**
http://192.168.29.231:8501

**🧐 Features**
Here're some of the project's best features:
✅ AI-Powered Image Sharpening: Enhances blurry or low-quality images using a trained Convolutional Neural Network (CNN).
🧠 Student-Teacher Learning Model: Implements a simplified Knowledge Distillation approach where a CNN (Student) learns from a basic image filter (Teacher).
🖼️ Automatic Image Preprocessing: Handles image resizing color conversion and normalization using OpenCV.
💾 Model Training and Testing: Includes full training and testing pipeline using PyTorch
📁 Organized File Structure: Clean and modular Python scripts (train.py test.py utils.py student_model.py) for easy understanding.
🌐 Streamlit Web Interface (Optional): Upload and enhance your images in a browser with a simple user interface.

**🛠️ Installation Steps:**
 Install the required libraries using:
**pip install torch torchvision opencv-python numpy streamlit**

**❓ How to use **

Step 1: Train the Model Put 256x256 images in the images/ folder then run:
**python train.py**

🧪 Step 2: Test the Model Put a test image in the images/ folder (e.g. test.jpg) then run: bash Copy Edit
**python test.py**

🌐 Optional: Run the Web App
**streamlit run app.py**

**💻 Built with**
Technologies used in the project:

Python Core programming language used for the whole project
PyTorch Deep learning framework used to build and train the CNN model
OpenCV For loading resizing and processing images
NumPy To handle numerical operations and image arrays
Streamlit (optional) To create a simple and interactive web interface (frontend)
