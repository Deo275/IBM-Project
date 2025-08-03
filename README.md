# Network Intrusion Detection System (NIDS) 🚨

This project is a **Machine Learning-based Network Intrusion Detection System** designed to identify and classify cyber-attacks such as **DoS, Probe, R2L, and U2R** in real-time. Built using **IBM Watsonx.ai** and deployed on **IBM Cloud**, it leverages supervised learning models to enhance network security.

## 🧠 Problem Statement

With the exponential growth of internet-based services, networks are increasingly vulnerable to cyber threats. Early detection of malicious activity is crucial to prevent severe damages. This system aims to detect and classify various types of intrusions from network traffic patterns.

## ✅ Features

- Real-time detection of network attacks
- Support for multiple attack types (DoS, Probe, R2L, U2R)
- Cloud-based deployment on IBM Cloud
- Easy-to-train ML models using Watsonx.ai Studio
- Evaluation using test datasets

## 🛠️ Technologies & Tools

- IBM Watsonx.ai Studio
- IBM Cloud Object Storage
- Python (via Watson Studio Runtime)
- Kaggle Datasets
- REST API for deployment & inference

## 🗃️ Dataset

We used a publicly available dataset from Kaggle:

- [Network Intrusion Detection Dataset](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)
  - `Train_data.csv`
  - `Test_data.csv`

## 🧪 Workflow

1. **Data Collection**:
   - Downloaded from Kaggle and split into train/test datasets.
   
2. **Preprocessing & Training**:
   - Uploaded `Train_data.csv` to Watsonx.ai Studio.
   - Auto-generated ML models evaluated by accuracy.

3. **Model Evaluation**:
   - Tested on `Test_data.csv`.
   - Accuracy-based model selection.

4. **Deployment**:
   - Deployed model via Watsonx.ai.
   - Stored in IBM Cloud Object Storage for inference.

## 📊 Result

- Successfully predicted types of attacks on test data.
- Visual prediction results were generated within Watson Studio.

## 🎯 Conclusion

The system effectively detects and classifies network intrusions using machine learning. It provides scalable, cloud-based, and real-time intrusion detection capabilities—enhancing the security of communication networks.

## 🔮 Future Scope

- Integrate live network stream for real-time prediction.
- Add deep learning (LSTM, autoencoders) for complex patterns.
- Enable adaptive learning from new attacks.
- Develop a visualization dashboard.
- Multi-cloud support for wider deployment.
- Combine anomaly and signature-based detection.

## 📚 References

- [Kaggle Dataset - Network Intrusion Detection](https://www.kaggle.com/datasets/sampadab17/network-intrusion-detection)
- [IBM Cloud Documentation](https://cloud.ibm.com/docs)

## 👨‍💻 Author

**Deyon Tomy Joseph**  
B.Tech in Computer Engineering  
Fr. C. Rodrigues Institute of Technology

---

