# CSE438-Digital-Image-Processing-Lab-Project
# 🍎 Fruit Rot Detection Using CNN

A deep learning project that classifies fruit images into five categories based on the percentage of rot. This system helps automate fruit quality inspection in agriculture and retail, reducing waste and manual labor by providing fast, reliable predictions.

---

## 📖 Theory

Image classification is a fundamental problem in computer vision. Convolutional Neural Networks (CNNs) are particularly effective in capturing spatial hierarchies in images. This project uses a CNN model to classify fruit images into the following five categories based on the percentage of rot:

- 0% Rotten  
- 25% Rotten  
- 50% Rotten  
- 75% Rotten  
- 100% Rotten  

Such a model is beneficial in automating the detection of fruit degradation, which is critical in supply chains for maintaining quality.

---

## 🎯 Objectives

- Develop a CNN-based classifier to detect fruit rot percentage from images.
- Enable automatic fruit quality control for suppliers and retailers.
- Build a user-friendly and deployable model for real-world use.
- Reduce manual labor and subjective judgment in fruit inspection.
- Minimize human error in quality assessment.
- Provide a reliable model for practical use in food distribution systems.

---

## 🧰 Tools & Environment

- **Programming Language:** Python  
- **Development Platform:** Google Colab  
- **Libraries Used:**  
  - TensorFlow  
  - Keras  
  - OpenCV  
  - NumPy  
  - Matplotlib  
  - Seaborn  
- **Dataset Source:** Google Drive (images manually sorted into category folders)  
- **Image Preprocessing:** Resizing (100x100), normalization  
- **Hardware:** GPU runtime via Google Colab  

---

## 📊 Methodology

1. **Data Collection**  
   - Images stored in folders named by rot percentage: 0%, 25%, 50%, 75%, 100%.

2. **Preprocessing**  
   - Resize all images to 100x100 pixels.  
   - Normalize pixel values to the 0–1 range.

3. **Data Splitting**  
   - 70% of data for training  
   - 30% of data for testing

4. **Model Design**  
   - Simple CNN with convolutional, pooling, flatten, and dense layers.  
   - Optimizer: Adam  
   - Loss Function: Categorical Crossentropy  
   - Epochs: 5 (adjustable)

5. **Prediction**  
   - Users can upload new images and receive a predicted rot percentage with a visual output.

---

## 📈 Results

- **Accuracy Achieved:** ~85–90% on validation data  
- Clear visualization of model predictions  
- Effective train/test split to enhance generalization  
- Model predicts rot percentage reliably on unseen images  
- Simple interface for end users via image upload

---

## ⚠️ Limitations

- Limited dataset with low variation in background and lighting  
- Performance may degrade on complex or non-standard images  
- Fixed to five rot categories with no support for in-between or mixed states

---

## 🔮 Future Improvements

- Expand dataset with diverse fruits and varying lighting conditions  
- Deploy as a mobile or web application for farmers and suppliers  
- Add real-time video classification support for conveyor belt systems  
- Integrate with IoT tools for continuous monitoring  
- Extend support for additional fruit types and rot gradations

---

## 📚 References

1. [TensorFlow Documentation](https://www.tensorflow.org/)  
2. [Keras CNN Guide](https://keras.io/examples/vision/)  
3. [OpenCV Image Processing](https://docs.opencv.org/)  
4. Public fruit datasets and GitHub resources

---

## 🔗 GitHub Repository

[View Full Project Code and Assets](https://github.com/Sai1047/CSE438-Digital-Image-Processing-Lab-Project)
