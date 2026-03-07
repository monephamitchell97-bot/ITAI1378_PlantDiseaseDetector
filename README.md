# Plant Disease Detector

**Student:** Monepha Mitchell  
**Course:** ITAI 1378 – Computer Vision and AI  
**Tier:** Tier 1 – Image Classification

## Problem Statement
Many farmers and home gardeners struggle to identify plant diseases early. Incorrect diagnosis can lead to crop loss, poor treatment decisions, and wasted time.

## Solution Overview
This project will build a computer vision model that classifies plant diseases from leaf images. A user will upload a plant leaf image, and the system will predict the disease category.

## Technical Approach
- **Technique:** Image Classification
- **Model:** ResNet18 / CNN
- **Framework:** PyTorch

## Dataset Plan
- **Source:** PlantVillage dataset
- **Size:** Approximately 50,000 images
- **Labels:** Healthy and multiple plant disease categories
- **Preparation:** Resize, normalize, train/test split

## Metrics
- **Primary Metric:** Accuracy ≥ 92%
- **Secondary Metric:** Inference time < 1 second per image

## Week-by-Week Plan
- **Week 10:** Set up repo and dataset
- **Week 11:** Train first model
- **Week 12:** Improve accuracy
- **Week 13:** Create demo notebook
- **Week 14:** Final testing and documentation
- **Week 15:** Final presentation

## Resources Needed
- Google Colab
- PyTorch
- Kaggle dataset
- Cost: Free

## Risks and Mitigation

| Risk | Probability | Mitigation |
|------|-------------|------------|
| Low accuracy | Medium | Use transfer learning and augmentation |
| Missing data issues | Low | Use a smaller cleaned subset |
| Training too slow | Medium | Use Colab GPU |

## AI Usage Log
- ChatGPT: Helped brainstorm project scope, README outline, and proposal structure
