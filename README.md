# DSI-Team-16-p-1
# Infrastructure & Transportation Project: US Accident Data

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Key Questions](#key-questions)
- [Workflow and Rules of Engagement](#workflow-and-rules-of-engagement)
- [Implementation](#implementation)
- [Deliverables](#deliverables)
- [Project Structure](#project-structure)
- [File Structure](#file-structure)
- [Team Members](#team-members)
- [Video Presentations](#video-presentations)

## Project Overview
This project leverages the US Accident Data from Kaggle to analyze road accidents across the United States, with a focus on predicting the number of car accidents in Los Angeles based on weather conditions. By examining data over seven years, we aim to identify patterns and insights that can inform infrastructure improvements and enhance transportation safety. Our goal is to understand how weather conditions impact accident rates in Los Angeles, thereby aiding in the development of better public safety measures and preparedness for adverse weather.

## Data
In this project, the US Accident Data from Kaggle is used, which provides detailed information on accidents, their locations, weather conditions, and impacts. The dataset has been simplified to focus exclusively on car accidents in Los Angeles.

### Dataset Details
- **Source**: [Kaggle](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents?resource=download)
- **Coverage**: March 22, 2016 to March 31, 2023
- **Features**:
   - Weather conditions (temperature, humidity, precipitation, wind speed, etc.)
   - Number of car accidents per day in Los Angeles

## Key Questions
1. (Primary) How does weather impact accident rates?
2. (Secondary) What are the most common causes of accidents?
3. (Secondary) What times of day are most accidents likely to occur?

## Workflow and Rules of Engagement
The project workload was distributed among the team as follows:
- Dmytro Bonislavskyi - work with repository(create project, update, and resolving conflicts), create map visualisation.
- Yihui	Zhu - prepare cross validation method.
- Ibrahim Assi - implement regression model analysis.
- Mario	Klaes - prepare the DataFrame to be used in the model
- Kostiantyn Koval - create and fill in README file

## Implementation
1. **Data Exploration**:
   - Understand the structure and primary focus of the dataset.
   - Identify potential relationships in the data.

2. **Analysis and Modeling**:
   - Answer selected questions using exploratory data analysis (EDA) and regression models.
   - Document findings and insights.

3. **Collaboration**:
   - Use GitHub for version control and collaboration.
   - Create and merge pull requests.
   - Write detailed pull request descriptions.

## Deliverables
- **Exploratory Data Analysis (EDA)**
- **Regression Models**
- **Pull Requests (PRs)**
- **README file**
- **Individual Learning Videos**

## Project Structure
The project is divided into two sprints:

### Sprint 1: Propose and Select Dataset
1. **Propose a dataset**: Each team member suggests a dataset for the project.
2. **Define one dataset to work on**: Review proposed datasets and select the most suitable one (US Accident Data).

### Sprint 2: Explore Dataset and Define Scope
1. **Explore the dataset**:
   - **Primary focus**: Understand the main focus of the dataset.
   - **Explore relationships**: Identify and document potential relationships in the data.
   - **Prepare Data**: Simplify the dataset to focus on Los Angeles.
2. **Model Development**:
   - **Select appropriate regression models**
   - **Split data into training and testing sets.**
   - **Train models and tune hyperparameters.**
3. **Model Evaluation**
   - **Evaluate models using relevant metrics (MAE, MSE, R²).**
   - **Compare model performance and select the best model.**

## File Structure

- **team_project/**: Root folder of the project
  - **data/**: Contains all the datasets used in the project.
    - **raw/**: Original datasets.
      - **Filtered_US_Accidents_CA.csv**: dataset that contain gps data needed for visualisation
      - **Visualization.ipynb**: map with all accidents marked
    - **processed/**: Processed datasets for analysis.
      - **Los_Angeles_Accidents_2016_2023.csv**: prepared dataset to be used in the model 
      - **projec_process.ipynb**: prepares data to be used in the model
  - **Catherine.ipynb**: cross-validation model
  - **project_regression.ipynb**: regression model
  - **README.md**: info about the project

## Team Members
- Mario	Klaes	
- Dmytro Bonislavskyi	
- Ibrahim Assi	
- Yihui	Zhu	
- Kostiantyn Koval	

## Video Presentations (Project 1)
- Mario	Klaes: [Link to video](https://drive.google.com/drive/folders/18qlROMeoctgqyvcRID3QZaMIwwFjAdy4?usp=sharing)
- Dmytro Bonislavskyi: [Link to video](https://drive.google.com/file/d/1uyA7UrDtwuNZbuEx5-96M27VAoFoDW22/view?usp=sharing)
- Ibrahim Assi: [Link to video](https://drive.google.com/file/d/19pSBsEf6iRjc8oyOMNAnHxtT83Qh0z1J/view?usp=sharing)
- Yihui	Zhu: [Link to video](https://drive.google.com/file/d/11Q5KD9LheuuaCGjciBFDE_aBw0QwuNl2/view?usp=sharing)
- Kostiantyn Koval: [Link to video](https://drive.google.com/file/d/1SUGuGANHnDHDXsH2qrr0JavMQ5ydbIJ8/view?usp=sharing)

## Video Presentations (Project 2)
- Mario	Klaes: [Link to video](https://drive.google.com/drive/folders/1afjtVXDJHdqQb0FWYnuBA-LSsKd6J-QQ?usp=sharing)
- Dmytro Bonislavskyi: [Link to video]()
- Ibrahim Assi: [Link to video]()
- Yihui	Zhu: [Link to video](https://drive.google.com/file/d/1Xt4-4pRKgonygnagrWE5wF3E8ZQg3RFd/view?usp=sharing)
- Kostiantyn Koval: [Link to video]()