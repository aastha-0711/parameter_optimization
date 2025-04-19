# 🏠 Room Occupancy Estimation using Environmental Sensors

This project aims to estimate the **number of occupants in a room** using multiple **non-intrusive environmental sensors**. The approach leverages machine learning techniques to classify occupancy levels based on various environmental features.

---

## 📊 Dataset

The dataset used in this project is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation).

- **Type:** Multivariate Classification  
- **Number of Instances:** 10,129  
- **Number of Attributes:** 16  
- **Sensors Used:**
  - Temperature
  - Light
  - Sound
  - CO₂
  - PIR (Passive Infrared Sensor)

These features provide an indirect and privacy-preserving means of occupancy detection.

---

## 📈 Result

### 📸 Sample Visualization

*Best performing configuration (Sample 9)*  
- **Accuracy:** 0.97  
- **Kernel:** Poly  
- **Nu:** 1.27  
- **Epsilon:** 6.87  

The following graph illustrates the performance of different models:


---

## 🧠 Conclusion

From the above graph, it is evident that:

- The **training and cross-validation curves are closely aligned**, indicating that the model is not overfitting.
- The **parameters have been effectively optimized**.
- **Sample 9** achieved the best performance with an accuracy of **0.97** using the specified hyperparameters.

This model shows promise for real-time room occupancy estimation in smart buildings or energy-efficient HVAC systems.

---

## 📝 Requirements

- Python 3.x  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

