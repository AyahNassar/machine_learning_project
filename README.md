# Indoor Localization Using WLAN Fingerprinting
## Project Overview
- This project utilizes the UJIIndoorLoc dataset to develop machine learning and deep learning models for accurate indoor localization using WLAN fingerprinting. Our models demonstrate high accuracy in predicting unique indoor positions and geographic coordinates, offering potential improvements in indoor navigation, asset tracking, and emergency response services.

## Team Members
- Ayah Nassar – 60101805
- Sumaya Al-Hamdan – 60105006

## Dataset
- The UJIIndoorLoc dataset contains over 19,000 training instances and 1,111 validation instances, covering WiFi fingerprints across three buildings. This rich dataset provides a complex challenge for indoor localization.



## Methodology
- Deep Dataset Understanding: In-depth analysis of the dataset structure and features.
- Robust Data Preprocessing: Includes handling missing values, feature scaling, categorical encoding, and feature reduction.
- Missing values in signal strengths were replaced with a standard minimum value.
- Signal strength values were normalized to ensure balanced input feature influence.
- Categorical variables like Building ID and Space ID were encoded into numerical values.
- Features not contributing to localization accuracy, such as TIMESTAMP, USERID, and PHONEID, were removed.
- Introduced 'UNIQUELOCATION' as a composite feature to encapsulate specific indoor locations.
## Model Development:
- Basic Machine Learning Model: Random Forest Classifier and Regressor for predicting 'UNIQUELOCATION' and geographic coordinates.
- Deep Learning Model: Feed-forward neural networks (FNNs) for enhanced accuracy in spatial localization. The model predicts the 'UNIQUELOCATION' and geographical coordinates using layers designed to recognize intricate signal patterns.
## Results
- Random Forest Classifier: Achieved an accuracy of approximately 86.25% on training data and 94.17% on validation data.
- Deep Learning Model: Maintained accuracy of about 82.17% on validation data, with high precision in predicting geographic coordinates.

## Limitations
- The performance is heavily dependent on the quality and granularity of WLAN fingerprinting data.
- Further testing is needed in more varied and less controlled environments to assess real-world applicability.
## Future Work
- Explore integration with other sensor technologies to enhance localization accuracy.
- Address computational efficiency and privacy concerns for real-world applications.
## Acknowledgments
- Special thanks to Dr. Bekir Sait Ciftler for his guidance and support throughout this project.
