# AI-Based Triage System for Emergency Departments

![image](https://github.com/deonjoshua/AI_Based_Triage_ER/assets/117792685/483cf2cb-647d-4a8d-95f3-017fc7996fd5)

## Summary
The AI-Based Triage System for Emergency Departments project aims to develop an efficient system using machine learning algorithms to classify and prioritize patients in emergency departments based on the severity of their conditions. The project's objectives include improving efficiency, reducing waiting times, and enhancing patient outcomes by ensuring prompt attention to critical cases. The Korean Triage and Acuity Scale (KTAS) scoring system serves as the foundation for triage in this project.

## Project Overview

The goal of this project is to:

1. Improve efficiency in emergency departments.
2. Reduce waiting times for patients.
3. Enhance patient outcomes by promptly attending to critical cases.

## Data Preprocessing
The dataset used in this project includes vital signs, presenting symptoms, medical history, level of consciousness, and pain scale. The data preprocessing steps involve handling null values, identifying important variables for model training, distinguishing between categorical and numerical values, and scaling numerical values.

<img width="960" alt="image" src="https://github.com/deonjoshua/AI_Based_Triage_ER/assets/117792685/f42e2ce0-9c28-4de9-8d8f-b3c30ddbee3d">

## Machine Learning Models

Two primary machine learning models are utilized in this project:

1. Random Forest: This supervised learning model determines the best hyperplane for separating different classes of patients.

![Wiiner](https://github.com/deonjoshua/AI_Based_Triage_ER/assets/117792685/91049e1b-8210-47f5-b41b-258857cab514)

2. K-Nearest Neighbors (KNN): This supervised learning model classifies patients based on the similarity of their features to those in the training dataset.
![Picture 1](https://github.com/deonjoshua/AI_Based_Triage_ER/assets/117792685/65108a11-fa27-492d-9b5e-5fae121c9342)

## Output

The output of the AI-based triage system is displayed as follows:
<img width="1440" alt="Screenshot 2023-05-16 at 9 08 29 pm" src="https://github.com/deonjoshua/AI_Based_Triage_ER/assets/117792685/bbd8595b-010a-4a44-9f06-34107246f8dc">


## Running the Scripts

To run the application, follow these steps:

- Create a new conda environment specifically for this app using the following code:

```bash
conda create -n ai_triage_env python=3.7
```
- Activate this new environment:
```bash
conda activate ai_triage_env

# If issues arise, try the following command instead.
source activate ai_triage_env
```

- Install the libraries into your new environment:
```bash
pip install -r requirements.txt
```
- Make the run.sh file executable:
```bash
chmod a+x run.sh
```
Test the application by running the following command in your command line:
```bash
./run.sh
```
- Navigate to 127.0.0.1:5000 in your web browser to access the webpage and test the app locally.

Note: The provided starter code uses a .csv file as the database.
