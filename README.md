# IoT Based System for Early Detection and Monitoring of Mosquito Breeding Sites

## Introduction
This project is an IoT-powered solution designed to combat the spread of dengue by identifying and analyzing potential mosquito breeding grounds and predicting dengue outbreak risks. The system integrates hardware, data analytics, and user engagement to provide a proactive, data-driven approach to dengue prevention in vulnerable communities.

## Architecture Diagram
![Architecture Diagram](https://github.com/R25-063/.github/blob/main/Overall%20System%20Diagram.png?raw=true)


## Project & Repositories

- [Project](https://github.com/R25-063)
- [Model Repository](https://github.com/R25-063/Dengue-model)
- [Backend Repository](https://github.com/R25-063/Dengue-backend)
- [Frontend Repository](https://github.com/R25-063/Dengue-frontend)

---

## Supervisor

- **Supervisor**: [Ms. Uthpala Samarakoon]
- **Co-Supervisor**: [Mr. Nelum Amarasena]

## Team Members

| Member           | IT Number  | Sub-Objective                                        | Tasks                                                                             |
| ---------------- | ---------- | ---------------------------------------------------- | --------------------------------------------------------------------------------- |
| [Thathsara B.M.L](https://github.com/it21277986)   | IT21277986 | Develop IoT Sensor & Callibration                  | IoT sensor deployment, data collection & Callibration System        |
| [Thennakoon K.T.A.T](https://github.com/thimalkat38)    | IT21817526 | Identify Mosquito using Wingbeat                | Capture wingbeat & Detect Mosquito Types        |
| [Rajapaksha R.M.K.P](https://github.com/IT21804892-Kavindu)   | IT21804892 | Realtime Data Processing and Prediction       | Data Aggregation & Future Prediction        |
| [Sanjana P.M.B](https://github.com/bingers00)  | IT21826122 | Develop Mobile App & Identify Risky Areas                  |   Localized Risk- Level Display & Alert and Notification system      |

## Features

## 1.Collecting Realtime Data & Callibration System:

## 2.Capture Wingbeats, Mosquito Image & Identify Type of Mosquitos:

## 3.Future Predication using Historycal Data & Realtime data:

## 4.Mobile App for Genaral Community:


## Objectives

### Main Objective

To design and implement an integrated IoT-based system that identifies potential dengue mosquito breeding sites and classifies mosquito species using wingbeat analysis, predicts dengue risk levels using geospatial heatmaps, and delivers real-time alerts and preventive guidance through a user-friendly mobile application, thereby enabling early detection, risk mitigation, and community awareness for effective dengue control.

### Sub-Objectives

- **IoT-Based Breeding Site Detection**:
Develop and deploy IoT-enabled sensors and camera modules to monitor environmental conditions and identify potential Aedes mosquito breeding grounds such as stagnant water areas.

- **Mosquito Species Identification via Wingbeat Analysis**: 
Implement an audio-based mosquito classification system using wingbeat frequency data and machine learning to detect and distinguish dengue-transmitting mosquito species.

- **Dengue Risk Prediction through Heatmaps**: 
Analyze environmental, sensor, and mosquito data using GIS and machine learning techniques to generate dynamic heatmaps indicating high-risk dengue zones.

- **Mobile Application Development**:
Design a mobile application to provide users with real-time dengue risk alerts, educational content, and interactive tools for reporting breeding sites and symptoms.

- **Data Integration and Visualization**:
Build a centralized dashboard for researchers and health officials to visualize sensor data, mosquito detection logs, and risk predictions for informed decision-making.

---

## Technology Stack

### Programming Languages

- **Frontend**: React.js, ReactNative
- **Backend**: Node.js
- **Machine Learning**: Python
- **Database**: MongoDB

### Frameworks

- **Frontend**: React.js, Vite
- **Backend**: Node.js

### Machine Learning Frameworks

- TensorFlow.js
- OpenCV.js
- Keras

### Tools

- Figma
- Postman
- GitHub
- Arduino

---

## References

1. A. Sarlan et al., “Aedes Breeding Habitat Localization System,” Int. J. Eng. Technol., vol. 7, no. 4, pp. 45–49, Nov. 2018. – Describes an IoT-based “ABLD” trap that uses sensors to locate standing water and collect data on potential Aedes breeding areas; the system greatly reduced data-collection time and helped forecast dengue patterns​
researchgate.net

2. J. Aira et al., “MosquIoT: A System Based on IoT and Machine Learning for the Monitoring of Aedes aegypti,” arXiv:2401.16258, 2024. – Proposes an IoT ovitrap equipped with image sensors and TinyML to automatically detect and count Ae. aegypti eggs, sending real-time data via LoRaWAN​
arxiv.org

3. B. Aguinaldo and A. Sicam, “Design and implementation of an IoT-based Orvicidal-Larvicidal trap for community-based dengue early warning system,” J. Biodiv. Environ. Sci., vol. 26, no. 3, pp. 81–87, 2025. – Presents an IoT trap (Raspberry Pi + camera) using a CNN to detect and enumerate Ae. aegypti eggs with 99.5% accuracy; integrates environmental and case data into a cloud dashboard for early outbreak warning​
innspub.net

4. M. S. Fernandes et al., “Detecting Aedes aegypti mosquitoes through audio classification with convolutional neural networks,” Comput. Biol. Med., vol. 129, 2021, Art. 104152. – Uses smartphone audio of mosquito wingbeat to train a CNN classifier; achieves ~97% accuracy in identifying Ae. aegypti vs. other species​
pubmed.ncbi.nlm.nih.gov

5. A. Supratak et al., “MosquitoSong+: A noise-robust deep learning model for mosquito classification from wingbeat sounds,” PLOS One, vol. 19, no. 10, e0310121, 2024. – Introduces a 1D-CNN model that classifies mosquito species/sex from wingbeat audio even in noisy environments, obtaining >80% accuracy on various datasets (93.3% accuracy for species+sex)​
pmc.ncbi.nlm.nih.gov

6. M. Javaid et al., “WebGIS-Based Real-Time Surveillance and Response System for Vector-Borne Infectious Diseases,” Int. J. Environ. Res. Public Health, vol. 22, no. 4, p. 499, 2025. – Develops a GIS-integrated ML platform for dengue (and other VBDs) that uses climate factors to predict breeding sites; a Random Forest model reached 93.97% accuracy, and a web-based GIS dashboard visualizes risk areas​
pmc.ncbi.nlm.nih.gov

7. W. Luo et al., “Unraveling varying spatiotemporal patterns of Dengue Fever and associated exposure–response relationships with environmental variables in three Southeast Asian countries before and during COVID-19,” PLoS Negl. Trop. Dis., vol. 19, Apr. 2025. – Analyzes dengue case data in SE Asia using time-series decomposition and spatial heatmaps to identify high-risk subregions; employs heatmaps to depict infection trends and examines climate–dengue exposure relationships​
journals.plos.org

8. X. Chen and P. Moraga, “Forecasting dengue across Brazil with LSTM neural networks and SHAP-driven lagged climate and spatial effects,” BMC Public Health, vol. 25, 2025. – Builds an LSTM-based forecast model for Brazilian dengue that incorporates lagged meteorological and spatial features (e.g. neighboring region cases); demonstrates robust nationwide dengue incidence prediction by integrating climate and connectivity data​
bmcpublichealth.biomedcentral.com

9. A. Mahotra et al., “Feasibility of NepaDengue mobile application for dengue prevention and control: user and stakeholder perspectives in Nepal,” BMJ Public Health, 2024. – Reports on the development and pilot testing of “NepaDengue,” a smartphone app with health-awareness content, symptom checker, reminders and breeding-site reporting; found high user acceptability (perceived as useful and easy to use) among community and health workers​
pmc.ncbi.nlm.nih.gov

10. K. Watanabe et al., “An Integrated mHealth App for Dengue Reporting and Mapping, Health Communication, and Behavior Modification: Development and Assessment of Mozzify,” JMIR Form. Res., vol. 4, no. 1, e16424, 2020. – Describes “Mozzify,” an Android app that features real-time dengue case reporting and mapping, news/forum updates, symptom checkers, reminders, and educational content; user surveys rated it highly for usability and information quality​
formative.jmir.org
