# IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies

This repository documents the capstone project completed during the **IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies**. This program is a collaborative initiative by the **Edunet Foundation**, **AICTE**, and **IBM SkillsBuild**.

The internship's primary goal is to provide hands-on experience in emerging technologies, enhancing employability and confidence by solving real-world challenges using the IBM SkillsBuild and IBM Cloud platforms.

## 📝 Table of Contents
- [Intern Details](#intern-details)
- [About the Internship](#about-the-internship)
- [Project: Intelligent Classification of PMGSY Schemes](#project-intelligent-classification-of-pmgsy-schemes)
  - [Problem Statement](#problem-statement)
  - [Solution Overview](#solution-overview)
- [⚙️ Technology Stack](#️-technology-stack)
- [🚀 Project Workflow](#-project-workflow)
- [📊 Results](#-results)


## 👨‍💻 Intern Details
-   **Name:** Nihal DR
-   **College:** CMR institute of technology 
-   **Duration:** 4 Weeks (15th July 2025 to 7th August 2025)

## 📖 About the Internship
This 4-week program focused on providing practical skills in AI and Cloud Computing. The internship was structured with weekly virtual sessions, mentor guidance, and hands-on labs. The curriculum included:
-   **Week 1:** Internship Orientation, IBM Cloud Registration, Artificial Intelligence.
-   **Week 2:** Data Analytics concepts, Hands-On Labs, and Cloud EDA.
-   **Week 3 & 4:** Building a Chat Bot, AI/ML experiments on the cloud, and a deep dive into AutoAI experiments on IBM Cloud.

Successful completion required active participation, completion of at least two courses on IBM SkillsBuild, and the submission of a final project presentation. This internship was offered with no stipend.

## 💡 Project: Intelligent Classification of PMGSY Schemes

### Problem Statement
Create a robust network intrusion detection system (NIDS) using machine learning. The 
system should be capable of analyzing network traffic data to identify and classify various 
types of cyber-attacks (e.g., DoS, Probe, R2L, U2R) and distinguish them from normal 
network activity. The goal is to build a model that can effectively secure communication 
networks by providing an early warning of malicious activities. 

### Solution Overview
An end-to-end machine learning solution was developed to automate the classification of network intrusion class. The system uses a project's physical and financial data to predict the class it belongs to i.e anomoly or not anomoly. The final, trained model was deployed as a real-time web service on the IBM Cloud platform.

## ⚙️ Technology Stack
-   **Cloud Platform:** IBM Cloud 
-   **AI/ML Service:** IBM watsonx.ai Studio
-   **Automated ML Tool:** IBM AutoAI
-   **Core Language & Libraries:**
    -   Python
    -   `scikit-learn`
    -   `pandas`
    -   `XGBoost`
    -   `ibm-watsonx-ai`

## 🚀 Project Workflow
1.  **Data Ingestion:** The kaggle dataset was uploaded to an IBM Cloud project.
2.  **Automated Model Building:** An AutoAI experiment was configured in watsonx.ai. This powerful tool automated the entire machine learning pipeline, including data preprocessing, feature engineering, model selection, and hyperparameter optimization.
3.  **Model Selection:** AutoAI trained and ranked multiple classification algorithms. The **Binary classification** was identified as the best-performing model based on accuracy.
4.  **Deployment:** The top-performing pipeline was saved as a model asset and deployed as an **Online Web Service** within a Deployment Space on IBM Watsonx.ai, which provides a REST API for real-time predictions.
5.  **Testing:** The deployed API endpoint was successfully tested with sample data to validate its real-time classification capabilities.

## 📊 Results
The deployed model demonstrated high accuracy in classifying infrastructure projects, proving the effectiveness of using automated AI tools for rapid development and deployment. The project successfully met all requirements for the final evaluation and submission.

<img width="1920" height="1080" alt="Screenshot (543)" src="https://github.com/user-attachments/assets/de3bd361-e149-45c1-8998-46beb698756a" />
<img width="1920" height="1080" alt="Screenshot (544)" src="https://github.com/user-attachments/assets/f144c0e1-95a1-4d54-8ea7-1a03f4606bdd" />
<img width="1920" height="1080" alt="Screenshot (547)" src="https://github.com/user-attachments/assets/96b6d65a-90e2-4e60-91c7-38a160f736cd" />
<img width="1920" height="1080" alt="Screenshot (562)" src="https://github.com/user-attachments/assets/9ced6554-342a-491b-bf13-5870049e2750" />
<img width="1920" height="1080" alt="Screenshot (563)" src="https://github.com/user-attachments/assets/bab26089-2ff7-4b5e-ab9f-fae8d4e0418c" />


