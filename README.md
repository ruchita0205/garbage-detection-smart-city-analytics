# Smart City Garbage Analytics Framework

## AI-Powered Waste Detection, Severity Assessment, Hotspot Analytics, and Municipal Decision Support

### Project Overview

This project presents a Smart City Garbage Analytics Framework that combines Artificial Intelligence, Computer Vision, Multi-Criteria Decision Analysis, and Spatial Analytics to support intelligent municipal waste management.

The framework integrates:

* YOLOv8-based garbage detection
* Smart Waste Severity Index (SWSI)
* AHP-based criteria weighting
* DBSCAN hotspot detection
* Municipal resource allocation planning
* Dashboard-based decision support
* Experimental and simulated validation

The objective is to help municipal authorities identify waste accumulation zones, prioritize cleanup activities, optimize resource allocation, and improve urban sanitation management.

---

## Research Contributions

### Contribution 1: YOLOv8 Waste Detection

A customized YOLOv8 model is used to detect garbage from images, videos, and surveillance feeds.

Features:

* Real-time waste detection
* Multi-object detection
* Confidence-based prediction
* Waste density estimation

---

### Contribution 2: Smart Waste Severity Index (SWSI)

A novel Smart Waste Severity Index is proposed to prioritize waste incidents.

The SWSI combines:

* Waste Count
* Waste Type Weight
* Location Sensitivity
* Historical Frequency

Final validated AHP weights:

| Criterion            | Weight |
| -------------------- | ------ |
| Waste Count          | 0.4658 |
| Waste Type Weight    | 0.2771 |
| Location Sensitivity | 0.1611 |
| Historical Frequency | 0.0960 |

---

### Contribution 3: AHP-Based Decision Weighting

The Analytic Hierarchy Process (AHP) was used to determine criterion importance.

Validation Results:

* λmax = 4.0310
* CI = 0.01035
* CR = 0.0115

Result:

CR < 0.10

The decision matrix is considered highly consistent.

---

### Contribution 4: DBSCAN Hotspot Analytics

DBSCAN clustering identifies waste accumulation hotspots.

Outputs include:

* High-priority waste zones
* Cluster density analysis
* Municipal cleanup prioritization
* Waste hotspot visualization

---

### Contribution 5: Municipal Resource Allocation Model

The framework converts severity scores into actionable municipal plans.

Generated recommendations include:

* Workforce allocation
* Vehicle deployment
* Cleanup scheduling
* Priority-based intervention planning

---

### Contribution 6: Dashboard-Based Decision Support

Interactive dashboards provide:

* Waste severity monitoring
* Hotspot visualization
* Resource allocation recommendations
* Operational decision support

---

## System Architecture

Input Data

↓

YOLOv8 Waste Detection

↓

Waste Analytics Engine

↓

Smart Waste Severity Index (SWSI)

↓

DBSCAN Hotspot Detection

↓

Resource Allocation Model

↓

Dashboard Decision Support

↓

Municipal Action Recommendations

---

## Experimental Validation

### Detection Performance

* Precision Evaluation
* Recall Evaluation
* F1 Score Analysis
* Confidence Threshold Analysis

### Severity Assessment Validation

* AHP Validation
* Expert Validation
* Sensitivity Analysis

### Hotspot Analytics Validation

* DBSCAN Parameter Validation
* Simulated Municipal Case Study

### Dashboard Validation

* Decision Support Verification
* Resource Allocation Validation

---

## Repository Structure

```text
Dataset/
Model_Training/
Baseline_Model_Comparison/
Methodology/
Validation_and_Experiments/
Dashboard_and_Decision_Support/
Research_Paper/
Literature_Review/
Project_Management/
Final_Deliverables/
```

---

## Technologies Used

* Python
* YOLOv8
* OpenCV
* Pandas
* NumPy
* Scikit-Learn
* DBSCAN
* Matplotlib
* Plotly
* Streamlit
* Jupyter Notebook

---

## Research Outputs

* Smart Waste Severity Index (SWSI)
* AHP Validation Framework
* DBSCAN Hotspot Detection Model
* Municipal Resource Allocation Model
* Dashboard Decision Support System
* Research Paper Draft v5

---

## Future Scope

* CCTV-based real-time deployment
* GIS integration
* Smart bin integration
* IoT-enabled waste monitoring
* Municipal command center deployment
* Smart city digital twin integration

---

## Author

Ruchita Kahane

AI-Based Smart City Garbage Analytics Framework

