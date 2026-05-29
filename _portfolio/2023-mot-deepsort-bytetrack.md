---
title: "Multi-object tracking with YOLO + DeepSORT / ByteTrack"
excerpt: "End-to-end MOT pipeline combining YOLOv5 detection with DeepSORT and ByteTrack, IOU matching, and ReID on GPU."
collection: portfolio
---

**Period:** Nov 2023 – Feb 2024 · **Lab:** IWIN-FINS, SJTU

Developed a **multi-object tracking (MOT)** system for video analytics:

- **YOLOv5** for frame-level detection  
- **DeepSORT** and **ByteTrack** for trajectory association and identity consistency  
- **IOU-based** matching and **ReID** appearance features to reduce ID switches  
- Full **GPU** pipeline for practical throughput

**Stack:** PyTorch, YOLOv5, DeepSORT, ByteTrack, CUDA
