# 🧠 Real-Time Human Identification System

A real-time human detection and person re-identification system using **YOLOv6** for object detection and **OSNet** (via **Torchreid**) for feature extraction and matching. Evaluated on public datasets with **MOTChallenge** metrics.

## 🚀 Overview

This project performs:
- **Human detection** in video streams using **YOLOv6**.
- **Feature extraction** using pretrained **OSNet** models.
- **Human-to-human matching** with **cosine similarity**.
- **Real-time tracking and identity assignment** across frames.

## 📦 Technologies Used

| Purpose                     | Tools & Libraries                     |
|----------------------------|----------------------------------------|
| Object Detection           | YOLOv6, PyTorch                        |
| Re-Identification (ReID)   | Torchreid, OSNet                       |
| Real-Time Video Processing | OpenCV, imutils                        |
| Feature Similarity         | Cosine Similarity (NumPy, Torch)       |
| Evaluation                 | MOTChallenge (MOTA, IDF1 metrics)      |

## 📈 Achievements

- 🧠 Built a custom **feature extractor** using pretrained **OSNet**.
- 🧍 Detected humans in video using **YOLOv6**.
- 🔁 Matched identities using **cosine similarity**.
- 🎯 Achieved **MOTA 63.8** and **IDF1 62.4**, ranked **95/100** on benchmark results.


