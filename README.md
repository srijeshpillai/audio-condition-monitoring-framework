# A Machine Learning Framework for Audio-Based Equipment Condition Monitoring

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains the Jupyter Notebooks and supporting code for the paper accepted at the **2025 Advances in Science and Engineering Technology International Conferences (ASET)**.

**Authors:** Srijesh Pillai, Yodhin Agarwal, Zaheeruddin Ahmed  
**Paper Link:** https://arxiv.org/abs/2509.11075

---

## Abstract
> Audio-based equipment condition monitoring suffers from a lack of standardized methodologies for algorithm selection, hindering reproducible research.
> This paper addresses this gap by introducing a comprehensive framework for the systematic and statistically rigorous evaluation of machine learning models.
> Leveraging a rich 127-feature set, our methodology is validated on both synthetic and real-world datasets. Results demonstrate that an ensemble method achieves superior performance (94.2% accuracy), with statistical testing confirming its significant outperformance of individual algorithms.
> This work provides a validated benchmarking protocol for selecting robust monitoring solutions in industrial settings.

---

## Key Results

Our framework systematically evaluates six machine learning algorithms across multiple performance dimensions. The ensemble method consistently demonstrates superior accuracy and robustness to noise.

| Overall Performance (Accuracy, Precision, Recall) | Noise Robustness Analysis (F1-Score) |
| :---: | :---: |
| <img src="outputs/performance_metrics.png" width="400"> | <img src="outputs/Noise Robustness F1 Scores.png" width="400"> |

---

## The Evaluation Framework

This project proposes and implements a complete, end-to-end pipeline for the fair and reproducible benchmarking of classification algorithms for audio-based fault detection.

![Framework Flowchart](outputs/framework_flowchart.png)

---

## How to Reproduce the Analysis

### 1. Setup

Clone this repository to your local machine:
```bash
git clone https://github.com/YOUR_USERNAME/audio-condition-monitoring-framework.git
cd audio-condition-monitoring-framework
