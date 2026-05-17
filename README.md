# A Novel Methodology for Health Assessment in Printed Circuit Boards

The demand for Printed circuit boards (PCBs) has increased due to the rapid change in technology in recent years. Consequently, PCBs health assessment and fault detection 
play an important role in improving productivity. This study proposed a novel method which focused on feature engineering for health assessment in PCBs. The performance 
of the proposed method has been validated using data obtained from PHM Europe 2022 data challenge. In this data challenge, PCBs health assessment needs to be performed 
with data from the Solder Paste Inspection (SPI) and the Automated Optical Inspection (AOI) machine. The challenge has three tasks: 1) Predict the labels of the AOI machine using 
the SPI data. 2) Using both the SPI and AOI machine data, predict the operator's verification that the AOI machine correctly detected a defect. 3) With the SPI and AOI data, 
predict the classification of the defective PCBs as either repairable or unrepairable. The component level features are extracted from the original SPI and AOI data which contain 
the pin level features to solve these tasks. Two machine learning-based classification models, i.e., Light Gradient Boosting Machine (LightGBM) and eXtreme Gradient 
Boosting (XGBoost), have been used for classification purposes. Training data given by the organizer was divided into 70% training and 30% validation. Based on the 
validation data, the highest F1-score was observed with LightGBM in Tasks 1 and 2, whereas, in Task 3, the highest F1-score was observed with the XGBoost model. Hence, the 
LightGBM model has been used in Tasks 1 and 2, and the XGBoost model was developed for Task 3.

DOI: https://doi.org/10.36001/phme.2022.v7i1.3308
