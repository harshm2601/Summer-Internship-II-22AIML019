# AI Internship Adventures: Tackling Computer Vision Frontiers

![Computer Vision Banner](https://img.shields.io/badge/Focus-Computer%20Vision-blueviolet) ![Projects](https://img.shields.io/badge/Projects-4-brightgreen) ![Duration](https://img.shields.io/badge/Duration-Summer%20Internship-orange)

Welcome to my showcase of an exhilarating summer internship in AI! I immersed myself in the dynamic realm of computer vision, developing innovative solutions for real-time detection and analysis. This repository highlights four key projects that pushed my skills in model training, optimization, and data handling. From safety gear spotting to airport logistics, these endeavors blended cutting-edge tech with practical problem-solving.

Whether you're a fellow AI enthusiast or just curious, dive in to explore the code snippets, insights, and lessons learned. Let's conquer vision challenges together! 🚀

## Table of Contents
- [Overview](#overview)
- [Projects](#projects)
  - [PPE Detection](#ppe-detection--safeguarding-environments-with-precision)
  - [Violence Detection](#violence-detection--unraveling-motion-patterns)
  - [Clothing and Age Classifier](#clothing-and-age-classifier--insightful-person-profiling)
  - [Airport Object Detection](#airport-object-detection--streamlining-aviation-operations)
- [Technologies Used](#technologies-used)
- [Challenges and Triumphs](#challenges-and-triumphs)
- [Key Takeaways](#key-takeaways)
- [Get Involved](#get-involved)

## Overview
During my internship, I focused on building AI models that address everyday challenges in safety, security, and efficiency. Each project involved experimenting with advanced architectures, curating datasets, and optimizing for real-world deployment. The journey was filled with iterations—from initial failures to polished prototypes—teaching me the art of resilient AI development.

## Projects

### PPE Detection — Safeguarding Environments with Precision
Aimed at identifying personal protective equipment in diverse settings to boost safety protocols.

**Tech Stack**:
- Python as the backbone.
- YOLOv8 and SigLIP for detection/classification.
- Zero-shot techniques (CLIP-inspired) for adaptability.
- Various open datasets for robust training.

**Development Flow**:
Began with standard detectors and classifiers, which struggled in variable conditions. Pivoted to zero-shot methods for flexibility, but latency crept in during validations. Fine-tuned with SigLIP for superior accuracy and rapid processing.

**Hurdles Cleared**: Managing trade-offs between responsiveness and reliability in unpredictable scenarios.

**Real-World Value**: Integrates effortlessly into monitoring systems, cutting down errors and supporting compliance in high-risk areas.

### Violence Detection — Unraveling Motion Patterns
This involved scrutinizing video streams to detect aggressive actions, emphasizing sequence analysis over static frames.

**Tech Stack**:
- Python with TensorFlow/Keras.
- Models: CNN-LSTM combos and 3D CNNs.
- Assorted open-source action datasets.

**Development Flow**:
Tested hybrid architectures for temporal insights, training on broad datasets. 3D CNN stood out for low false alerts, particularly distinguishing sports from threats amid vigorous movements.

**Hurdles Cleared**: Curbing over-detections in energetic contexts like athletics.

**Real-World Value**: Enhances surveillance for timely interventions in public venues, fostering safer communities.

### Clothing and Age Classifier — Insightful Person Profiling
Focused on recognizing apparel types (upper/lower) and categorizing people by age group, with applications in customization and oversight.

**Tech Stack**:
- YOLOv8 for precise bounding.
- Custom-annotated datasets for age.
- Depth estimation trials (monocular approaches).
- Python for data prep and training.

**Development Flow**:
Utilized a vast open dataset for clothing detection via YOLOv8, achieving solid performance. For age, bypassed simplistic box rules (ineffective at distances) and depth tools (too sluggish), opting for a richly labeled dataset from multiple viewpoints.

**Hurdles Cleared**: Overcoming scale and angle variances without site-specific setups.

**Real-World Value**: Powers personalized services, such as targeted ads or access controls, in a config-free manner.

### Airport Object Detection — Streamlining Aviation Operations
Targeted spotting specialized gear like refuelers, loaders, bridges, and aircraft in busy terminals.

**Tech Stack**:
- Hand-curated and labeled datasets.
- YOLO variants for multi-target tracking.
- Python pipelines for annotation and iteration.

**Development Flow**:
Due to sparse public data, built our own collection and trained models. Addressing overfitting: Performs great locally but falters elsewhere; expanding to global sources for better universality.

**Hurdles Cleared**: Combating data shortages and site-specific quirks.

**Real-World Value**: Optimizes ground ops and safety, automating tracking across international hubs.

## Technologies Used
- **Core Languages**: Python
- **Frameworks/Libraries**: YOLOv8, TensorFlow/Keras, SigLIP, CLIP
- **Architectures**: 3D CNNs, CNN-LSTM, Zero-Shot Learning
- **Data Tools**: Open-source datasets, manual labeling, depth estimators
- **Environments**: Focused on speed-optimized inference for deployment

## Challenges and Triumphs
- **PPE**: From sluggish zeros-shot to efficient SigLIP—boosted inference by 2x.
- **Violence**: 3D CNN slashed false positives in motion-heavy clips.
- **Clothing/Age**: Custom data trumped hardware-dependent fixes.
- **Airport**: Overfitting ongoing; aiming for worldwide robustness.
  
Overall: Navigated data scarcity, model tweaks, and performance balancing with iterative testing.

## Key Takeaways
- Gained proficiency in CV powerhouses like YOLO and 3D CNNs, plus dataset mastery.
- Embraced adaptability: Shifting from rigid models to versatile zero-shot paradigms.
- Deployment wisdom: Prioritize quick, generalizable solutions sans custom calibrations.
- Fueled my drive for AI that solves tangible problems in industries like safety and logistics. This experience was a launchpad for future innovations! 🌟

## Get Involved
Feel free to fork, star, or contribute ideas! If you have datasets or optimization tips, open an issue. Let's collaborate on advancing computer vision. Connect with me on [LinkedIn](https://linkedin.com) or [Twitter](https://twitter.com).

Thanks for checking out my internship portfolio! 📸
