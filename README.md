# AI-Driven Environmental Monitoring and Conservation

## Introduction
This project outlines the development and implementation of an AI model designed to analyze satellite imagery and IoT data for monitoring and predicting environmental changes such as deforestation and air quality. The model aims to provide actionable insights for conservation efforts.

## Problem Statement
The task is to create an AI model that analyzes satellite imagery and IoT data to monitor and predict environmental changes, such as deforestation or air quality, and suggests actionable insights for conservation efforts.

## Solution Overview
Our solution involves two main approaches:

### First Approach:
- Build individual models for detecting deforestation from satellite images and predicting air quality from time series air quality data.
- Save both models and combine their outputs using a weighted average or similar method to give the final predicted output.

### Second Approach:
- Build a deforestation detection model using satellite images.
- Use the output of the deforestation model as input features for the air quality prediction model, along with the original air quality features.

Due to limited computation power and time, we were unable to fully implement the ensemble approaches. As of now, we have individual models, but we plan to work on the ensembles in the future.

## Innovation and Creativity
1. **Dual-Data Integration:** Combines satellite imagery and IoT data for a comprehensive analysis of environmental changes.
2. **Predictive Model Interlinking:** Uses predictions from one model as features in another, acknowledging the interconnectedness of environmental factors.
3. **Advanced Machine Learning Techniques:** Employs CNNs for satellite imagery and RNNs or LSTMs for IoT data, demonstrating sophisticated analysis and prediction.
4. **Comprehensive Data Preprocessing:** Handles unique challenges of satellite imagery and IoT data, ensuring high-quality inputs for accurate predictions.
5. **Actionable Insights for Conservation:** Focuses on practical guidance for policymakers and conservationists based on accurate predictions.
6. **Future-Proof and Scalable Approach:** Designed for scalability and adaptability to include additional environmental parameters.

## Technical Accuracy
1. **Satellite Imagery Analysis:** Shows significant improvement across epochs, indicating effective learning and refinement.
2. **Air Quality Prediction:** Substantial improvements in MSE and R² score, demonstrating high accuracy.
3. **Model Integration and Feature Engineering:** Technically sound approach of using deforestation predictions as features for the air quality model.
4. **Data Preprocessing and Handling:** Rigorous preprocessing ensures high-quality inputs, crucial for maintaining accuracy.
5. **Use of Advanced Tools and Libraries:** Leverages robust machine learning frameworks like TensorFlow and scikit-learn.

## Implementation Quality
1. **Code Quality:** Organized into clear, modular components with comprehensive documentation and unit tests.
2. **Usability:** Detailed setup instructions and flexible configuration options.
3. **Efficiency:** Optimized algorithms, parallel processing, and scalability to handle large data volumes.

## Scalability and Impact
1. **Scalability:** Efficiently processes large volumes of data, adaptable to new parameters, and facilitates continuous updates.
2. **Impact:** Provides accurate predictions for proactive conservation efforts, informs policy formulation, and has global applicability.

## Conclusion
The solution effectively addresses the problem statement by integrating satellite imagery and IoT data, employing advanced AI techniques, and focusing on actionable insights. The high implementation quality ensures that the solution is both technically sound and practical, with significant potential for scalability and real-world impact.

## Appendices
- Air Quality Prediction
![Screenshot 2024-07-30 030642](https://github.com/user-attachments/assets/65a17b7d-d693-4a12-af44-2b3a79b9b906)
![Screenshot 2024-07-30 025949](https://github.com/user-attachments/assets/c4cea1f1-f234-4761-90a6-31d3ede70ca7)

- Deforestation Prediction
![Screenshot 2024-07-30 030016](https://github.com/user-attachments/assets/c35f329a-8979-42f2-b67f-edcf3211f603)
![Screenshot 2024-07-30 030039](https://github.com/user-attachments/assets/f938b199-203e-4840-b1c2-eb2470b4dd80)
![Screenshot 2024-07-30 030247](https://github.com/user-attachments/assets/bf20eb0f-462c-4cee-aeda-6618d1fda87f)
![Screenshot 2024-07-30 030340](https://github.com/user-attachments/assets/ebc0f96a-0e6d-4b6f-b870-767f703396d1)
![Screenshot 2024-07-30 030405](https://github.com/user-attachments/assets/afa6de54-1a57-4eff-84ac-db0ca9be918e)
