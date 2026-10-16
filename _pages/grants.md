---
title: "Grant Projects"
layout: textlay
excerpt: "Grant projects"
sitemap: false
permalink: /research/grants
---

<style>
  h1 { font-size: 30px; }
  h2 { font-size: 22px; margin-top: 35px; color: #1b3a5c; }
  .grant-meta { color: #555; margin-bottom: 15px; }
</style>

# Grant Projects

## Intelligent 3D Reconstruction Framework for Chronic Wound Monitoring and Healing Assessment

<p class="grant-meta"><i>National Research Program for Universities (NRPU), Higher Education Commission of Pakistan, 2026–2027</i><br>
<b>Principal Investigator:</b> Dr. Usman Amjad</p>

A device-independent, marker-calibrated 3D reconstruction and measurement framework for chronic wounds, built on multi-view smartphone photography. Clinical data collection, longitudinal monitoring and outcome association focus on diabetic foot ulcers (DFUs) during the project period.

**Motivation**

Chronic wounds, including diabetic foot ulcers, need objective assessment for safe documentation and follow-up. Routine practice still relies on 2D ruler measurements, which cannot capture depth or volume and can be misleading when infection, systemic toxicity or ischemia are present.

**Approach**

Using multi-view smartphone photos and an ArUco plus colour-patch marker, the pipeline will:

1. Enforce a standard capture procedure (SOP) with automated quality gating
2. Calibrate scale, and optionally lens distortion and colour
3. Segment the wound boundary using AI, with a manual audit trail
4. Run segmentation-guided Structure-from-Motion and dense reconstruction to produce a metrically scaled 3D mesh

**Outputs**

- 3D wound biomarkers (area, perimeter, mean and maximum depth, volume) with uncertainty estimates
- Longitudinal alignment across visits, with 3D change maps and rates of change
- A minimal, standards-aligned documentation bundle covering infection severity (including systemic red flags), perfusion or ischemia status, neuropathy, offloading, ulcer duration, and care-gap and discordance flags

**Validation**

Accuracy and repeatability will be measured on synthetic meshes of known geometry, 3D-printed phantoms and clinic follow-up data. The project will also test whether depth and volume trajectories add value beyond area-only baselines.

**Deliverables**

Capture SOP and quality-control report; calibrated image packages with metadata; boundary masks; scaled meshes and camera poses; biomarker and trajectory reports; the documentation bundle; and validation and association summaries.

*The system supports wound monitoring only and does not provide diagnosis or treatment recommendations.*


<hr>

## Real-Time Post-Floods Disease Detection, Management and Response System

<p class="grant-meta"><i>Sindh Higher Education Commission (SHEC) Research Grant, 2024-2025</i><br>
<b>Principal Investigator:</b> Dr. Usman Amjad</p>

An AI and IoT-based diagnostic system designed for the healthcare needs of rural and disaster-affected regions, such as post-flood Sindh, where internet connectivity and clinical infrastructure are limited.

**Motivation**

After the 2022–2023 floods, Sindh reported outbreaks of conjunctivitis, leishmaniasis, dengue and acute respiratory infections (ARI). Large populations living in overcrowded shelters with poor sanitation and limited healthcare access made early detection and coordinated response difficult, and conventional healthcare arrangements struggled to cope. This exposed a clear need for systems that can detect disease early and support the management of large-scale outbreaks.

**Approach**

- Runs AI diagnostic models on the NVIDIA Jetson Nano edge computing device, so diagnosis works without continuous internet connectivity
- Analyses patient blood samples using devices that detect disease biomarkers
- Uses camera-equipped IoT devices to support remote diagnosis
- Delivers results in real time at the point of care

**Impact**

- **Healthcare:** early detection and faster response to disease outbreaks in underserved areas
- **Social:** brings diagnostic testing to neglected and low-income communities, improving equity of access
- **Governance:** shares health information securely with authorities such as the Sindh Health Department, enabling rapid outbreak response, and reduces dependence on foreign infrastructure

