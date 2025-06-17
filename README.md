# 🧠 Spinal Vision – CNN-Based Spinal Stenosis Detection

A deep learning web application for detecting spinal lumbar stenosis from MRI and CT scan images using Convolutional Neural Networks (CNNs). Built using Python, TensorFlow, and Flask.

---

## 📊 Dataset Description

The dataset is sourced from [Kaggle](https://www.kaggle.com/) and includes spinal MRI and CT scans labeled by stenosis severity. Preprocessing techniques included resizing, normalization, data augmentation (zoom, shear, flip), and splitting into training and testing sets.

Each image belongs to one of four classes:
- 🟢 Normal
- 🟡 Mild Stenosis
- 🟠 Moderate Stenosis
- 🔴 Severe Stenosis

---

## 🧠 Model Architecture

A custom CNN was trained to classify spinal images into 4 categories. The architecture was compared with popular CNN models like:
- LeNet
- GoogleNet
- ResNet
- Custom ManualNet

The final trained model (`spine_stenosis.h5`) achieved 90–95% accuracy across multiple test cases.

---

## 🛠️ Tech Stack

- **Language**: Python  
- **Framework**: Flask  
- **Deep Learning**: TensorFlow / Keras  
- **Data Preprocessing**: OpenCV, NumPy  
- **Visualization**: Matplotlib  
- **IDE**: Jupyter Notebook via Anaconda

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/thulasirahul/spinal-vision-cnn.git
   cd spinal-vision-cnn
   ```

2. **Create and activate virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask App**
   ```bash
   python app.py
   ```

5. **Access the App**
   Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

---

## 🚀 Project Features

- Upload MRI/CT image and get stenosis prediction instantly
- CNN-based detection and classification into 4 severity levels
- Simple and intuitive web interface using Flask
- Real-time results with model confidence
- Notebook included for training, experimentation, and evaluation

---

## 📈 Results

- ✅ Accuracy: 90–95%  
- ✅ Sensitivity: ~90%  
- ✅ Specificity: 85–90%  

The model generalizes well across unseen test images and outperforms traditional methods in terms of diagnostic precision.

---

## 🔮 Future Work

- Cloud deployment for hospital use
- Expand model to detect other spinal and bone conditions
- Integrate with real-time medical systems or PACS
- Add explainable AI features for doctors' interpretation

---

## 👨‍💻 Contributors

- **Thulasi Rahul J**  
- **Viswasai K P**  
- **Yellela Vaibhav Reddy**

---

## 📚 References

- Kaggle Dataset: Lumbar Spine MRI/CT Images  
- Stanford Coursera Deep Learning Specialization  
- AI & CNN research papers on spinal diagnosis  
