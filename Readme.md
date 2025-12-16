# PCA-Based Mandala Art Generation Using Python 🎨🧠

This project explores the creative intersection of **machine learning, computer vision, and generative art**.  
It transforms an input image into a **symmetrical mandala-style artwork** using **Principal Component Analysis (PCA)** and geometric rotations.

---

## ✨ Project Overview

The pipeline follows three main stages:

1. **Image Processing**
   - Load and resize an image
   - Convert color space from BGR to RGB

2. **Dimensionality Reduction with PCA**
   - Flatten image pixels into feature vectors
   - Apply PCA to reduce color dimensionality
   - Reconstruct the image using reduced components

3. **Mandala Symmetry Generation**
   - Apply rotational symmetry
   - Enhance brightness, contrast, and saturation
   - Add artistic gamma correction

The result is a visually rich mandala derived from the original image structure.

---

## 🛠️ Technologies Used

- **Python**
- **NumPy** – numerical computations
- **OpenCV** – image processing
- **scikit-learn** – PCA implementation
- **Matplotlib** – visualization

---

## 🧪 How It Works

- PCA reduces the RGB color space to two principal components
- The reconstructed image retains structure while smoothing details
- Multiple rotated copies of the image are averaged
- Color and brightness adjustments enhance artistic appeal

---

## ▶️ How to Run

1. Clone the repository:
   git clone https://github.com/your-username/pca-mandala-art.git

2. Install dependencies:
   pip install numpy opencv-python matplotlib scikit-learn


3. Update the image path in the script:
   img = cv2.imread("path/to/your/image.jpg")

4. Run the script:
   python mandala_pca.py

---

## 📊 Output

The program displays:

* Original Image
* PCA Reconstructed Image
* Final Mandala Artwork

---

## 💡 Applications

* Generative & computational art
* Creative AI experiments
* Image compression visualization
* Digital art installations

---

## 🚀 Future Enhancements

* Adjustable PCA components via user input
* Interactive sliders for symmetry and color controls
* Real-time webcam mandala generation
* Export high-resolution artwork

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository, open issues, or submit pull requests.

