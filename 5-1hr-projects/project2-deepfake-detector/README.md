# 🧠 Project 2: Deepfake Detector (Image-based)

## ⏱️ Duration: ~1 Hour  

Use basic image forensics techniques to detect if an image may have been manipulated using deepfake methods.

---

## 📌 Goals

- Load and analyze images
- Extract facial landmarks (optional)
- Detect inconsistencies (e.g., head shape, shadows, eyes)
- Use image filters and FFT for forensics

---

## 🧰 Tools & Libraries

- Python
- OpenCV
- NumPy
- dlib / face_recognition
- Matplotlib

---

## 📸 Dataset

You can start with sample images:

- [Real Faces Dataset](https://www.kaggle.com/datasets/dansbecker/5-celebrity-faces-dataset)
- [Deepfake Examples](https://www.kaggle.com/datasets/rozumdenis/fakefaces)

---

## 🔧 Steps

1. **Load an image (real/fake)**  
2. **Convert to grayscale** and apply filters  
3. **Use FFT to detect noise/resampling patterns**  
4. **Detect face and extract features** using `face_recognition`  
5. **Visualize and compare** against real faces

---

## 📊 Output Sample

Image 1: High resampling artifacts → ⚠️ Possibly fake Image 2: Face landmarks inconsistent → ⚠️ Possibly fake

---

## 💡 Ideas to Extend

- Use a CNN for real vs. fake classification
- Add video deepfake detection
- Train on DeepFake Detection Challenge dataset

---

## 🔗 Resources

- [Detect Deepfakes with Python](https://www.analyticsvidhya.com/blog/2021/06/detecting-deepfake-images-using-python/)
- [FFT in Image Forensics](https://pyimagesearch.com/2020/03/30/opencv-fast-fourier-transform-fft-for-image-processing/)
