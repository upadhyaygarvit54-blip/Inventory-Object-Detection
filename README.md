# 📦 Inventory Object Detection and Product Counting using YOLOv5

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red)
![YOLOv5](https://img.shields.io/badge/YOLOv5-Object%20Detection-green)
![Dataset](https://img.shields.io/badge/Dataset-SKU110K-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📖 Overview

This project implements an automated inventory object detection and product counting system using **YOLOv5** and the **SKU110K retail dataset**.

The system detects products from retail shelf images and automatically estimates the number of products present in each image.

---

## 🚀 Features

* ✅ Product Detection
* ✅ Inventory Counting
* ✅ Bounding Box Visualization
* ✅ CSV Report Generation
* ✅ Statistical Analysis
* ✅ Histogram Visualization
* ✅ Top-10 Product Count Analysis

---

## 🛠 Technologies Used

* Python
* PyTorch
* YOLOv5
* OpenCV
* NumPy
* Pandas
* Matplotlib

---

## 📂 Dataset

**SKU110K Dataset**

* Training Images: 8233
* Validation Images: 588
* Test Images: 2941

---

## 📁 Project Structure

Inventory-Object-Detection/

├── notebook.ipynb

├── yolov5_inventory_counts.csv

├── README.md

├── report.pdf

├── presentation.pptx

├── output/

└── graphs/

---

## 📊 Results

The model successfully detects products from shelf images and generates inventory counts automatically.

### Sample CSV Output

| Image         | Objects Detected |
| ------------- | ---------------- |
| test_2110.jpg | 45               |
| test_2114.jpg | 37               |
| test_1743.jpg | 52               |

---

## 📈 Graphs

### Distribution of Detected Objects

![Histogram](graphs/histogram.png)

### Top 10 Images with Maximum Products

![Top10](graphs/top10.png)

---

## 🖼 Sample Detection Images

Add some sample images inside the `output/` folder and reference them:

```markdown
![Detection1](output/sample1.jpg)

![Detection2](output/sample2.jpg)

![Detection3](output/sample3.jpg)
```

---

## 🔄 Workflow

Input Image

⬇

YOLOv5 Model

⬇

Object Detection

⬇

Product Counting

⬇

CSV Generation

⬇

Visualization and Analysis

---

## 📌 Applications

* Retail Inventory Management
* Warehouse Automation
* Shelf Monitoring
* Smart Stores
* Product Analytics

---

## 📜 Conclusion

This project demonstrates how deep learning and computer vision can automate inventory monitoring and improve efficiency in retail environments.

---

## 👨‍💻 Author

Garvit Upadhyay

Computer Vision | Deep Learning | Machine Learning
