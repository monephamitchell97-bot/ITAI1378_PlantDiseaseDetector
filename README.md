# Plant Disease Detector

**Student:** Monepha Mitchell  
**Course:** ITAI 1378 – Computer Vision and AI  
**Tier:** Tier 1 – Image Classification

## Problem Statement
Many farmers and home gardeners struggle to identify plant diseases early. Incorrect diagnosis can lead to crop loss, poor treatment decisions, and wasted time. This creates a need for an automated and reliable solution.

## Solution Overview
This project builds a computer vision model that classifies plant diseases from leaf images. Users can upload a plant leaf image, and the system predicts whether the leaf is healthy or identifies the type of disease. This project was originally proposed during the midterm and has been fully implemented and improved for the final submission.

## Technical Approach
- **Technique:** Image Classification  
- **Model:** ResNet18 / CNN  
- **Framework:** PyTorch  
- **Enhancements:** Model training, prediction testing, and result visualization added for final version  

## Dataset Plan
- **Source:** PlantVillage dataset  
- **Size:** Approximately 50,000 images  
- **Labels:** Healthy and multiple plant disease categories  
- **Preparation:** Images resized, normalized, and split into training and testing datasets  

## Metrics
- **Primary Metric:** Accuracy (target ≥ 92%)  
- **Secondary Metric:** Inference time (< 1 second per image)  

## Results
The model was successfully trained to classify plant leaf images. Sample predictions and performance outputs are included in the `results/` folder. The system demonstrates the ability to identify plant health conditions using image classification techniques.

## Project Structure
ITAI1378_PlantDiseaseDetector/
├── data/
├── notebooks/
│ └── plant_disease_detector.ipynb
├── results/
│ ├── sample_prediction_1.png
│ ├── sample_prediction_2.png
│ └── accuracy_chart.png
├── docs/
│ ├── AI_usage_log.md
│ └── presentation.pdf
├── README.md
├── requirements.txt
└── .gitignore

## Demo Video
Paste your demo video link here:  
[ADD LINK HERE]

## Week-by-Week Plan (Completed)
- **Week 10:** Repository and dataset setup completed  
- **Week 11:** Initial model training completed  
- **Week 12:** Model accuracy improved through tuning  
- **Week 13:** Demo notebook created  
- **Week 14:** Final testing and results collected  
- **Week 15:** Final presentation and documentation completed  

## Resources Used
- Google Colab  
- PyTorch  
- PlantVillage dataset (Kaggle)  
- Free GPU resources  

## Risks and Mitigation

| Risk | Probability | Mitigation |
|------|-------------|------------|
| Low accuracy | Medium | Used transfer learning and tuning |
| Missing data issues | Low | Used cleaned dataset subset |
| Training too slow | Medium | Used GPU acceleration in Colab |

## AI Usage
AI tools (ChatGPT) were used to assist with:
- Project planning and structure  
- Debugging and explanations  
- README improvements  
- Presentation preparation  

Full log available in `docs/AI_usage_log.md`.

## Future Improvements
- Increase dataset size and diversity  
- Improve model accuracy with advanced architectures  
- Deploy as a web or mobile application  
- Add real-time plant disease detection  

## Conclusion
This project demonstrates how computer vision can be used to detect plant diseases efficiently. It highlights the potential of AI to assist in agriculture by improving early diagnosis and decision-making.
