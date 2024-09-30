# OCD-Patient-Dataset-Demographics-and-Clinical-Data-using-Python

## Overview
This project focuses on conducting an exploratory data analysis (EDA) on a dataset related to patients diagnosed with Obsessive-Compulsive Disorder (OCD). The analysis aims to uncover patterns and insights regarding patient demographics, symptom duration, previous diagnoses, and the types of obsessions and compulsions. By leveraging the Pandas library for data manipulation and visualization libraries such as Matplotlib and Seaborn, the project seeks to provide a deeper understanding of how various factors impact OCD diagnosis and treatment among different patient populations.

## Dataset
The dataset contains various attributes related to patients diagnosed with OCD, including:

- **Patient ID**: Unique identifier for each individual in the dataset.
- **Age**: Age of the patient at the time of data collection.
- **Gender**: Gender of the patient.
- **Ethnicity**: Ethnic background of the patient.
- **Marital Status**: Marital status of the patient.
- **Education Level**: Highest level of education completed by the patient.
- **OCD Diagnosis Date**: Date when the patient was diagnosed with OCD.
- **Duration of Symptoms (months)**: Number of months since the onset of OCD symptoms.
- **Previous Diagnoses**: Any previous psychiatric diagnoses or comorbidities.
- **Family History of OCD**: Indicates whether there is a family history of OCD in the patient's relatives.
- **Obsession Type**: Type of obsessions experienced by the patient.
- **Compulsion Type**: Type of compulsions exhibited by the patient.
- **Y-BOCS Score (Obsessions)**: Yale-Brown Obsessive Compulsive Scale score for obsessions.
- **Y-BOCS Score (Compulsions)**: Yale-Brown Obsessive Compulsive Scale score for compulsions.
- **Depression Diagnosis**: Diagnosis of depression (Yes or No).
- **Anxiety Diagnosis**: Diagnosis of anxiety (Yes or No).
- **Medications**: Type of medications used.

## Installation
Ensure that you have Python installed (preferably version 3.7 or later).

Install the required packages using pip:

```bash
pip install pandas matplotlib seaborn
```

## Usage
1. **Download the Dataset**: The link to download dataset is provided  in the project repository.
2. **Run the Jupyter Notebook**: Open and execute the `OCD_Patients_Demographic_and_Clinical.ipynb` notebook.
3. **Follow the Analysis Steps**: The notebook will guide you through data cleaning, exploratory analysis, and visualizations.

## Data Cleaning
The data cleaning process consists of several essential steps to ensure data integrity:

- **Handling Missing Values**: Identify and appropriately handle NaN values in the dataset.
- **Encoding Categorical Variables**: Convert categorical variables such as `Previous Diagnoses`, `Education Levels`, `Ethnicity`, and `Marital Status` into numerical values for analysis.
- **Data Formatting**: Standardize date formats and ensure all columns are correctly typed for further analysis.

## Data Analysis
Key analyses performed in this project include:

- **Distribution of Obsession Types**: Analyzing the prevalence of different types of obsessions across genders.
- **Obsession Type by Ethnicity**: Exploring how different ethnic backgrounds affect the types of obsessions reported.
- **Patient Marital Status**: Assessing the distribution of patients based on their marital status.
- **Obsession and Compulsion Types by Age**: Investigating the relationship between age and the types of obsessions and compulsions experienced.
- **Education Level Distribution**: Analyzing the education levels of patients diagnosed with OCD.
- **Scatterplot Analysis**: Visualizing the relationship between age and medication types used.
- **Depression and Anxiety Diagnoses by Gender**: Examining how depression and anxiety diagnoses differ between genders.
- **Ethnicity Distribution**: Assessing the diversity of the patient population in terms of ethnicity.

## Data Visualization
Visualizations created using Matplotlib and Seaborn to illustrate the insights gained from the data:

- **Bar Charts**: Show the distribution of obsession types across genders and ethnic backgrounds,Depression and Anxiety Diagnoses by Gender
- **Pie Charts**: Represent the distribution of patients ethnicity.
- **Scatter Plots**: Illustrate the relationship between patient age and medication types.
- **Count Plots**:Distribution of Patient's Marital Status, Obsession type by ethnicity.
- **Heat Map**:Distribution of Patient's Education Level
- **Swarm Plot**:Obsession and Compulsion type with reference To Age.

## Results
The analysis yields several key findings based on the visualizations:

- **Obsession and Compulsion Patterns**: The bar charts reveal distinct patterns in obsession types and compulsion behaviors, with notable variations observed across genders and ethnic backgrounds. For instance, certain obsession types are more prevalent among females, while others are predominantly reported by males. 

- **Depression and Anxiety Correlation**: The bar charts illustrating depression and anxiety diagnoses by gender indicate a higher incidence of comorbid conditions among females compared to males. This highlights the potential need for targeted interventions for female patients dealing with OCD.

- **Ethnicity Distribution**: The pie chart representing the distribution of patients by ethnicity shows a diverse patient population, with specific ethnic groups demonstrating a higher prevalence of OCD. This finding underscores the importance of culturally sensitive approaches in treatment and support.

- **Patient Age and Medication Types**: Scatter plots illustrate a varied relationship between patient age and the types of medications prescribed, indicating that younger patients may be more likely to receive specific medication classes. This trend suggests that treatment strategies could be tailored based on the patient's age demographic.

- **Marital Status Insights**: The count plots highlighting the distribution of patients’ marital status reveal that single patients constitute a significant portion of the dataset, raising considerations for support systems and social factors influencing OCD treatment outcomes.

- **Obsession Type by Ethnicity**: Count plots show that certain ethnic groups report distinct obsession types, indicating that cultural factors may influence the manifestation of OCD symptoms.

- **Education Level Distribution**: The heat map depicting the distribution of patients’ education levels suggests that lower educational attainment may correlate with higher OCD prevalence, pointing to the need for increased awareness and resources in educational settings.

- **Age-Related Trends in Symptoms**: The swarm plot showcases the relationship between age and the types of obsessions and compulsions experienced, revealing that younger patients tend to report a wider variety of obsession types. This finding highlights the necessity for age-appropriate therapeutic strategies.


## Acknowledgments
The dataset for this project was sourced from kaggle, contributing to a comprehensive understanding of Obsessive-Compulsive Disorder among various patient populations.

---

