# Crop-Health-Monitoring-System using Drone
Drone-based Crop Health Monitoring System with Deep Learning disease detection, HSV severity estimation, MATLAB prototype &amp; Android app 

**M.Tech Project** | IIITDM Kurnool  
**Author:** S MD Parvez (Roll No: 224EC2003)  
**Guide:** Dr. K. Krishna Naik  
**Year:** 2024–2026

---

## Overview

A complete system for monitoring crop health using **drone images**, **deep learning**, and a **mobile app**.

The system can:
- Verify the crop type
- Detect diseases in 10 crops
- Calculate disease severity using HSV method
- Compare before and after pesticide spray
- Show health progress graphs over days

Available as:
1. MATLAB GUI Prototype
2. Android App (works offline using ONNX)

---

## Supported Crops

| Crop       | Diseases |
|------------|----------|
| Chilli     | Bacterial Spot, Cercospora Leaf Spot, Leaf Curl Virus, White Spot, Nutrition Deficiency, Healthy |
| Onion      | Alternaria, Bulb Blight, Fusarium, Virosis, Healthy |
| Wheat      | Leaf Rust, Stem Rust, Stripe Rust, Loose Smut, Powdery Mildew, Healthy |
| Tomato     | Early Blight, Late Blight, Bacterial Spot, Mosaic Virus, Healthy |
| Sugarcane  | Red Rot, Smut, Mosaic, Wilt, Yellow Leaf, Healthy |
| Cotton     | Bacterial Blight, Leaf Curl, Healthy |
| Corn/Maize | Common Rust, Northern Leaf Blight, Gray Leaf Spot, Healthy |
| Paddy      | Leaf Blast, Bacterial Leaf Blight, Brown Spot, Healthy |
| Coconut    | Bud Rot, Leaf Spot, Healthy |

---

## Key Features

- Crop Verification Model → **99.27%** accuracy
- Disease Detection Models → **89% to 99.46%** accuracy (Average ≈ 94%)
- DenseNet-201 deep learning model
- HSV-based severity calculation
- Before / After spray comparison
- Day-wise health trend graphs
- Works offline on Android

---

## Results

| S. No. | Model            | Accuracy (%) |
|--------|------------------|--------------|
| 1      | Chilli           | 99.46        |
| 2      | Coconut          | 98.79        |
| 3      | Corn             | 96.68        |
| 4      | Cotton           | 94.17        |
| 5      | Maize            | 89.00        |
| 6      | Onion            | 92.17        |
| 7      | Paddy            | 95.91        |
| 8      | Sugarcane        | 94.52        |
| 9      | Tomatoes         | 98.72        |
| 10     | Wheat            | 93.67        |
| 11     | **Crop Verifier**| **99.27**    |

- Average Accuracy ≈ **94%**
- Real drone testing accuracy: **88% – 92%**
- Inference time: **60 – 110 ms**

---

## How to Run (MATLAB)

1. Open MATLAB
2. Go to the `code/matlab` folder
3. Run:
```matlab
CropHealthMonitoringGUI
4. Select crop → Upload image → Select region → Analyze

---

##Future Work
- Add more crops and diseases
- Use Vision Transformers for better accuracy
- Add multispectral / hyperspectral drone images
- Cloud storage and analytics
- Weather prediction + soil monitoring using IoT
- Multilingual support and voice interaction
- Fully automatic drone monitoring

##Project report
Full report is available in the docs folder:

##Important Note
This is an experimental academic prototype.

Always verify the results physically with an agriculture expert.

##Citation
S MD Parvez, Dr. K. Krishna Naik,
"Crop Health Monitoring System using Drone",
M.Tech. Project Report, IIITDM Kurnool, 2026.

##License
This project is under the MIT License.
