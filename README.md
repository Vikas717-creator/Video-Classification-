# 🎥 Video Classification using CNN-LSTM

A deep learning project for **classifying videos** by extracting temporal and spatial features using a **CNN-LSTM model**. This project is built to understand sequences of frames and recognize patterns across time, enabling accurate video-level predictions. Features saved into Csv file.

---

## 🌟 Features

- 🎞️ Extracts frames from videos and processes them sequentially  
- 🧠 Uses **CNN for spatial feature extraction** and **LSTM for temporal analysis**  
- 📈 Achieved **R² = 0.88** and **MSE = 0.11** on test data  
- 🔁 Automates video-to-frame extraction and preprocessing pipeline  
- 💾 Trained on a labeled video dataset (custom or public)

---

## 🧠 Model Info

- ✅ **Architecture:** CNN + LSTM  
- 📥 **Input:** Video files (mp4/avi)  
- 🧪 **Evaluation:**  
  - R² Score: 0.88  
  - MSE: 0.11  
- 🔀 Output: Video class or score based on learned patterns

---

## ⚙️ Getting Started

### 🔧 To Run Locally:

1. Clone the repository:
git clone https://github.com/Vikas717-creator/video-classification.git cd video-classification

markdown
Copy
Edit

2. Install required packages:
pip install -r requirements.txt

csharp
Copy
Edit

3. Extract frames from videos:
python frame_extractor.py
store in .npy file
features saved in csv file
markdown
Copy
Edit

5. Train the model:
python train.py

yaml
Copy
Edit

---

## 📊 Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy / Pandas  
- Matplotlib *(optional for visualization)*

---
## Screenshots
![image](https://github.com/user-attachments/assets/7f6dc2ee-9685-46dc-af07-cdc8ae6a4ef5)
![image](https://github.com/user-attachments/assets/48c0df61-f26f-45ce-91db-4421f4dd0529)





## 🔮 Future Enhancements

- ⏩ Use 3D-CNN for direct spatiotemporal feature learning  
- 🧪 Add support for multi-class video classification  
- 🌐 Build a Streamlit-based frontend for demoing predictions  
- 📥 Use transfer learning for better accuracy on smaller datasets

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork and submit pull requests.

---
## 🔗 Connect with Me

- GitHub: [@Vikas717-creator](https://github.com/Vikas717-creator)  
- LinkedIn: [Vikas Thakur](https://www.linkedin.com/in/vikas-thakur-2304a6261/)

## Screenshots


