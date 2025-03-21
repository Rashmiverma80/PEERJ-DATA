# PEERJ-DATA 
**Repository Location:** [https://github.com/Rashmiverma80/PEERJ-DATA]
This repository includes the implementation of the Software-Defined Multicloud Defense
Controller (SDMDC). The framework consists of:
● sdmdc-controller.ipynb: The main execution file that integrates Local IDS (LSTM),
Global IDS (CCTT Transformer), and policy optimization (Lemurs Optimizer).
● local-ids-using-lstm.ipynb: Implements a per-cloud Local IDS using LSTM for
anomaly detection in ingress and egress traffic.
● cctt-with-lo.ipynb: Implements the Global IDS using a Cross-Cloud Threat
Transformer (CCTT) with Lemurs Optimizer for dynamic policy adjustments.
● Datasets: The system is trained and evaluated using the Bot-IoT dataset
(/kaggle/input/bot-iot/) and the SDN-Augmented Dataset (/kaggle/input/sdn-
augmented-dataset/).

The models have been trained and evaluated using two datasets.

---

## 📂 Datasets Used

1. **CICIDS Dataset**
   - **Description:** A comprehensive dataset for intrusion detection including realistic network traffic and various attack scenarios.
   - **Kaggle Link:** [CICIDS Dataset](https://www.kaggle.com/rashmiverma80/cicids)

2. **Bot-IoT Dataset**
   - **Description:** IoT network traffic dataset designed to detect botnet attacks and anomalous activities.
   - **Kaggle Link:** [Bot-IoT Dataset](https://www.kaggle.com/datasets/vigneshvenkateswaran/bot-iot/data)

---

## 🚀 IDS Approaches

### 1. 🌐 Global IDS

- **Code Location:** [https://github.com/Rashmiverma80/PEERJ-DATA/tree/main/code/Global%20IDS  ]
  

### 2. 🏠 Local IDS

- **Code Location:**  [https://github.com/Rashmiverma80/PEERJ-DATA/tree/main/code/Local%20IDS]
  
### 3. SDMDC Controller Code Integrating LSTM Local IDS, CCTT Global IDS, and Lemurs Optimizer

- **Code Location:**  [https://github.com/Rashmiverma80/PEERJ-DATA/tree/main/code]
