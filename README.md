# EY-Open-Data-Challenge-2023
Rice Crop Classification using Satellite Data

**Introduction:**

The study focuses on classifying rice crops using satellite imagery from Sentinel-1 and Sentinel-2, essential for agricultural planning and global food security.

**Data Analysis:**

*  Outliers in Sentinel-1 VV and VH data were identified and managed.
* Time series data revealed distinguishable patterns between rice and non-rice areas.

**Methodology:**

*  Data from Sentinel-1 and Sentinel-2 satellites was collected between 2021-11-01 and 2022-12-01.
*  Cleaning involved handling missing values and outlier detection using the IQR method.
*  Feature engineering encompassed deriving vegetation indices, including NDVI, SAVI, NDWI, EVI, GCI, LAI, and RVI, among others.
*  Model development used a train-test split, explored various algorithms, and settled on a RandomForestClassifier optimized through hyperparameter tuning.

**Innovations:**

*  Comprehensive data cleaning and correlation analysis.
*  Extensive feature engineering and extraction from satellite data.
*  Integrated anomaly detection and oversampling techniques to enhance model performance.
*  Developed a robust evaluation and comparison process to identify the best performing model.

**Results:**

*  The optimized random forest model achieved exceptional accuracy, showing resilience against multicollinearity.
*  Key model parameters are presented, with RVI indices, VV, and VH as top-performing features.

**Challenges:**

Difficulties arose in dealing with complex, noisy satellite data and time-consuming data acquisition.

**Real-world Impact:**

*  The solution can guide precision agriculture, enhancing crop management.
*  Potential scalability of the method can impact global food security, environmental conservation, and economic development, especially in developing regions.

**Conclusion:**

The research delivers a precise methodology for rice crop classification using Sentinel satellite data, highlighting the potential for improved agricultural practices, heightened food security, and broader environmental benefits.
