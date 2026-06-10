# AI-Based Smart City Garbage Detection and Analytics System Using YOLOv8

## Project Overview

This project proposes an AI-powered Smart City Waste Analytics and Decision-Support System using YOLOv8 for garbage detection, severity assessment, hotspot identification, and municipal resource allocation.

The system analyzes images, videos, CCTV feeds, and geospatial information to identify waste objects, calculate waste severity, detect hotspot zones, generate municipal analytics, and support data-driven waste management decisions.

The project extends traditional waste detection systems by integrating Smart Waste Severity Index (SWSI), DBSCAN-based hotspot analytics, and municipal decision-support mechanisms into a unified Smart City Garbage Analytics Framework.

---

# Objectives

* Detect garbage using YOLOv8
* Classify waste categories
* Generate garbage counts
* Calculate Smart Waste Severity Index (SWSI)
* Identify waste hotspots using DBSCAN clustering
* Generate municipal priority rankings
* Recommend resource allocation strategies
* Provide ward-wise and camera-wise analytics
* Support municipal decision-making through dashboards
* Enable data-driven smart city waste management

---

# Dataset

### Dataset Used

**TACO (Trash Annotations in Context)**

The dataset was not uploaded to this repository due to size limitations.

### Download Instructions

1. Visit the official TACO Dataset repository.
2. Download images and annotations.
3. Convert annotations to YOLO format.
4. Organize into train, validation, and test folders.

### Classes Used

* Aluminum Can
* Glass Bottle
* HDPEM
* PET

---

# Model Information

### Primary Model

YOLOv8n

### Comparative Models

* YOLOv8s
* YOLOv5s (Planned)
* YOLOv7 (Planned)
* SSD (Planned)
* Faster R-CNN (Planned)

### Task

Garbage Detection and Classification

---

# Experimental Results

## YOLOv8n Performance

| Metric    | Value  |
| --------- | ------ |
| Precision | 97.48% |
| Recall    | 98.24% |
| mAP@50    | 98.98% |
| mAP@50-95 | 84.87% |

## YOLOv8s Performance

| Metric    | Value  |
| --------- | ------ |
| Precision | 96.99% |
| Recall    | 98.98% |
| mAP@50    | 99.00% |
| mAP@50-95 | 85.11% |

---

# Smart City Analytics Features

## Waste Detection Module

* Waste Detection
* Waste Classification
* Garbage Counting
* Bounding Box Generation
* Confidence Score Analysis

## Smart Waste Severity Index (SWSI)

Severity Score Formula:

SWSI = 0.35(WC) + 0.30(WTW) + 0.20(LS) + 0.15(HF)

Where:

* WC = Waste Count
* WTW = Waste Type Weight
* LS = Location Sensitivity
* HF = Historical Frequency

Severity Levels:

* Low
* Moderate
* High
* Critical

---

## Hotspot Detection Module

Method Used:

**DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**

Inputs:

* GPS Coordinates
* Waste Count
* SWSI Score

Outputs:

* Waste Hotspots
* Cluster Density
* Priority Zones

---

## Municipal Resource Allocation Module

Provides:

* Worker Allocation Recommendations
* Vehicle Allocation Recommendations
* Supervisor Alerts
* Cleanup Scheduling
* Priority Ranking

---

## Dashboard Analytics

* Real-Time Waste Monitoring
* Severity Analytics
* Hotspot Visualization
* Ward-Wise Analytics
* Camera-Wise Analytics
* Historical Trends
* Resource Recommendations
* Municipal Decision Support

---

# Research Contributions

This project introduces:

1. YOLOv8-based waste detection framework.
2. Smart Waste Severity Index (SWSI) for waste prioritization.
3. DBSCAN-based hotspot analytics framework.
4. Municipal resource allocation recommendation engine.
5. Dashboard-based decision-support system.
6. Integrated Smart City Garbage Analytics Framework with feedback-driven monitoring.

---

# Project Status

## Completed

✔ Dataset Preparation Completed

✔ Dataset Verification Completed

✔ YOLOv8n Training Completed

✔ YOLOv8s Training Completed

✔ Model Evaluation Completed

✔ Error Analysis Completed

✔ Smart Waste Severity Index (SWSI) Developed

✔ DBSCAN Hotspot Detection Methodology Developed

✔ Municipal Resource Allocation Framework Developed

✔ Baseline Model Comparison Completed

✔ Quantitative Ablation Study Plan Completed

✔ Research Gap Matrix Completed

✔ Literature Review Matrix (50 Papers) Completed

✔ Research Paper Draft v3 Completed

✔ Revised System Architecture Diagram Completed

---

## In Progress

* Dashboard Development
* Hotspot Visualization
* Decision-Support Integration

---

## Future Work

* YOLOv5s Benchmark Evaluation
* YOLOv7 Benchmark Evaluation
* SSD Benchmark Evaluation
* Faster R-CNN Benchmark Evaluation
* Vehicle Routing Optimization
* Workforce Optimization
* Real-Time CCTV Integration
* Edge AI Deployment
* Smart City Command Center Integration

---

# Research Significance

Most existing waste management studies focus only on waste detection or smart bin monitoring. This project extends beyond detection by integrating severity assessment, hotspot analytics, resource allocation, and municipal decision support into a single framework.

The proposed framework aims to support smarter, faster, and more efficient municipal waste management operations in future smart cities.

---

# Author

**Ruchita Kahane**
