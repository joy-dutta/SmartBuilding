# SmartBuilding

The term "smart building" refers to a building that makes optimal use of its resources in a cost-effective manner, all while ensuring the safety and comfort of its residents. In addition to incorporating a variety of current technology, smart buildings are built or modified in a manner that makes it easy to include any future innovations. Sensors connected to the Internet of Things (IoT), building management systems, artificial intelligence (AI), and augmented reality (AR) are some of the technologies that might be used to regulate and enhance the efficiency of a smart building.

## Download Smart Building Dataset: [Click Here](https://github.com/joy-dutta/SmartBuilding/blob/master/SmartBuildingXAI.csv)

### Dataset Descriptions 

This is a synthetic dataset that was generated by considering real-world data from our previous work experience. We used the smart building context and associated data for preparing this dataset to identify sensitivity of the data, with our primary focus being indoor data. For measuring the indoor condition, the following eight features were considered: temperature, humidity, air quality index (AQI), noise, occupancy, carbon monoxide (CO), carbon dioxide (CO2), and flame data, according to References 1, 2, and 3. We have used this synthetic dataset (having the eight mentioned features and one target class, 'data sensitivity') already for our research publication (Reference 4).

Hence, this dataset has 1000000 instances with eight training features and one target feature. You can use this dataset to test your multiclass-classification (0, 1, and 2) machine learning model, where the target feature class value '0' represents a normal situation, '1' represents a sensitive situation, and '2' represents a critical situation for a smart building. If you are using this dataset, kindly cite any of the references mentioned below that helped us generate this data.


### References for the Dataset
#### 1. J. Dutta, S. Roy, “OccupancySense: Context-Based Indoor Occupancy Detection & Prediction using CatBoost Model”, Applied Soft Computing, Elsevier, 2022, DOI: [https://doi.org/10.1016/j.asoc.2022.108536](https://doi.org/10.1016/j.asoc.2022.108536)

#### 2. J. Dutta, S. Roy, “IndoorSense: Context Based Indoor Pollutant Prediction using SARIMAX Model", Multimedia Tools and Applications, Springer, Electronic ISSN: 1573-7721, Print ISSN: 1380-7501, 2021, DOI: [https://doi.org/10.1007/s11042-021-10666-w](https://doi.org/10.1007/s11042-021-10666-w)

#### 3. J. Dutta, S. Roy, “IoT-fog-cloud Based Architecture For Smart City: Prototype Of A Smart Building”, Proceedings of the 7th International Conference on Cloud Computing, Data Science & Engineering, CONFLUENCE 2017, Noida, Uttar Pradesh, India (IEEE), 2017, DOI: [https://doi.org/10.1109/CONFLUENCE.2017.7943156](https://doi.org/10.1109/CONFLUENCE.2017.7943156)

#### 4. J. Dutta, D. Puthal and E. Damiani, "AI-based Block Identification and Classification in the Blockchain Integrated IoT," 2022 OITS International Conference on Information Technology (OCIT), Bhubaneswar, India, 2022, pp. 415-421, DOI: [10.1109/OCIT56763.2022.00084](https://ieeexplore.ieee.org/document/10053810)
