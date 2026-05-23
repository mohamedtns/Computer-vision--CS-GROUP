# 🚢 Real-Time Maritime Surveillance — AI Computer Vision System

> **Defense R&D internship · March – August 2025 · South France**

[![Portfolio Page](https://img.shields.io/badge/🌐_View_Portfolio_Page-0a0c10?style=for-the-badge)](https://mohamedtns.github.io/Computer-vision--CS-GROUP/)

---

## 🔗 [→ Open the project page](https://mohamedtns.github.io/Computer-vision--CS-GROUP/)

---

## Overview

End-to-end AI pipeline for automated vessel **detection, classification, and tracking** from video feeds (infrared & visible), developed during a 5-month R&D internship in a defense-sector research lab.

The system processes raw video frames through a real-time multithreaded architecture and exports structured trajectory data for integration into command-and-control platforms.

---

## Pipeline

```
Video Input → [Detection] → [Classification] → [Tracking] → JSON Export
               YOLOv8        MobileNetV3 / ViT   Deep SORT
```

---

## Key Results

| Metric | Value |
|--------|-------|
| ViT classification accuracy (IR) | **97.18%** |
| MobileNetV3 accuracy (IR) | **96.43%** |
| YOLOv8x precision (IR) | **0.98** |
| YOLOv8x recall (IR) | **0.99** |
| GPU inference (YOLOv8x) | **34 ms/frame** |
| Full pipeline latency | **< 100 ms/frame** |

---

## Tech Stack

`Python` `YOLOv8` `Deep SORT` `MobileNetV3` `Vision Transformer (ViT)` `PyTorch` `TensorFlow` `OpenCV` `CUDA` `Tkinter` `Multithreading`

---

## Note

This project was conducted in a restricted defense R&D context. Implementation details, dataset specifics, and organizational information are intentionally omitted.

---

*Mohamed Boudhina — AI & Computer Vision Engineer · [LinkedIn](https://https://www.linkedin.com/in/mohamed-boudhina-a94a36265/) · [GitHub](https://https://github.com/mohamedtns)*
