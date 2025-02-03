# Object Matching using SIFT 🔎📦

## 📌 Introduction
This project implements **Object Detection and Matching** using **Scale-Invariant Feature Transform (SIFT)**. The goal is to match an object from a reference image with its instance in a scene image using feature extraction and homography estimation.

## 🚀 Features
- **Feature Extraction**: Detecting keypoints and computing descriptors using **SIFT**.
- **Feature Matching**: Utilizing **Brute-Force Matcher (BFMatcher)** with L2 norm and KNN matching.
- **Outlier Filtering**: Lowe’s Ratio Test (0.75) to filter weak matches.
- **Homography Estimation**: Computing perspective transformation if sufficient matches exist.
- **Outlier Visualization**: Highlighting unmatched keypoints in red for analysis.

## 📂 Project Structure
```
📦 Object-Matching-SIFT
├── 📜 machine_vision.ipynb   # Jupyter Notebook with full implementation
├── 📜 Box_In_Scene.png       # Scene image containing the object
├── 📜 Box.png                # Object image to be detected
├── 📜 README.md              # Project documentation
```



## 📌 How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook machine_vision.ipynb
   ```
2. Run all cells sequentially to execute keypoint detection, matching, and homography estimation.

## 📊 Results Analysis
- **Keypoint Detection**: Visualization of detected keypoints in both object and scene images.
- **Feature Matching**: Displaying the best-matching keypoints.
- **Homography & Localization**: Highlighting the detected object within the scene (if successful).
- **Outlier Analysis**: Identifying false matches and visualizing them in red.

## 📧 Contact
For any inquiries or collaboration opportunities, reach out to:
📩 Email: emad.k50000@gmail.com.com

## ⭐ Contribute
Feel free to fork this repository, report issues, or submit pull requests to improve the project.

🔹 **Developed by [Emad k] | Open Source & Research-Oriented**

