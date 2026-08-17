Navigation Sensor Dataset (Multi-sensor Configuration)

### CSIR - Central Mechanical Engineering Research Institute (CSIR-CMERI), Durgapur, India

---

## 📌 Overview

This repository hosts a Navigation Sensor Dataset (Multi-sensor configuration) collected and maintained by the **CSIR – Central Mechanical Engineering Research Institute (CSIR-CMERI), Durgapur, India**. 

The dataset has been developed to support research and development in sensor fusion, navigation, robotics, autonomous systems, and state estimation. It contains synchronized measurements from multiple navigation sensors acquired under controlled experimental conditions. 

This specific release organizes the data based on different motion trajectories performed during data acquisition, making it suitable for trajectory-specific algorithm development and validation.

---

## 🎯 Applications

The dataset can be used for research in areas including, but not limited to:

- Multi-sensor data fusion
- Inertial Navigation Systems (INS)
- Extended Kalman Filter (EKF) and Unscented Kalman Filter (UKF)
- Factor Graph Optimization
- SLAM and Localization
- Autonomous Surface and Underwater Navigation
- Machine Learning for Navigation
- State Estimation and Sensor Calibration
- Navigation Algorithm Benchmarking

---

## 🧰 Dataset Contents (Sensors)

The repository includes data collected from multiple navigation sensors, such as:

- Inertial Measurement Unit (IMU)
- Global Navigation Satellite System (GNSS/GPS)
- Doppler Velocity Log (DVL)
- Attitude and Heading Reference System (AHRS)
- Magnetometer

All sensor measurements are **time-synchronized** and organized for ease of analysis and algorithm development.

---

## 🗂️ Repository Structure (Trajectory Folders)

The data is organized into subfolders based on the trajectory pattern followed during acquisition:

| Folder      | Trajectory Description                     |
|-------------|--------------------------------------------|
| `Arrow`     | Linear path with a sharp directional turn  |
| `Eight`     | Figure-8 (infinity) looping pattern        |
| `F_shape`   | Path resembling the letter 'F'             |
| `Lawnmower` | Raster scanning / back-and-forth motion    |
| `Spiral`    | Outward/inward spiral path                 |
| `Straight`  | Straight-line linear motion                |
| `Triangle`  | Triangular closed-loop path                |
| `Triangle2` | Variant of the triangular trajectory       |

Each folder contains multiple `.csv` files with timestamped sensor readings.

---

## 📄 File Format

- **Type:** Comma Separated Values (`.csv`)
- **Encoding:** UTF-8
- **Structure:** Rows represent sequential data points; columns denote individual sensor channels (specifics may vary per experiment).

---

## 🎓 Intended Use

This dataset is provided for:

- Academic research
- Educational purposes
- Algorithm development
- Performance comparison and validation of sensor fusion techniques

---

## ⚖️ Copyright, Ownership & Access

**© CSIR, India. All Rights Reserved.**

This dataset is the intellectual property of **CSIR-CMERI**. All data, documentation, and associated materials are protected under applicable copyright laws.

### 🔒 Access & Permissions
This repository is **Private** and strictly reserved for authorized research purposes.

- **Unauthorized access, duplication, redistribution, commercial use, or modification without prior written permission from CSIR-CMERI is strictly prohibited.**
- External researchers / collaborators may request access via GitHub's **"Request Access"** feature. All requests must be approved by the repository owner and are subject to institutional review.

---

## 📬 Request for Additional Data

The dataset provided in this repository represents only a portion of the complete data collection. Researchers requiring additional datasets or extended recordings for academic or collaborative research are requested to contact:

**Head of Underwater Robotics and Autonomous Systems Group (URASG) Department**  
CSIR – Central Mechanical Engineering Research Institute (CSIR-CMERI)  
Durgapur, West Bengal, India  

**Requests should include:**
- Name and affiliation
- Purpose of the research
- Intended use of the dataset
- Relevant project or publication details (if applicable)

---

## 📝 Citation

If you use this dataset in your research, please acknowledge **CSIR-CMERI** as the source of the dataset.

---

## ⚠️ Disclaimer

The dataset is provided **"as is"** without any express or implied warranty. While every effort has been made to ensure data quality and integrity, CSIR-CMERI assumes no responsibility for any loss, damage, or consequences arising from the use of this dataset. Users are solely responsible for validating the suitability of the data for their specific applications.

---

## 📞 Contact

For technical queries, collaboration opportunities, or requests for additional datasets, please contact the **URASG Department, CSIR-CMERI, Durgapur**.

---

**Last Updated:** July 2026
