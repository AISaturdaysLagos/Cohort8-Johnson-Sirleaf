# Table of Contents

- Project title
- Project description
- Data Sources
- Data Cleaning and Preprocessing
- Modeling
- Model Deployment
- Getting Started Locally
- Acknowledgments
- Support and Contact

## Project Title

### Machine Learning Approach to Predicting Diabetes Risk

## Project description

The project aims to develop a machine learning-based predictive model for assessing the risk of diabetes in individuals. By leveraging historical health data, the goal is to create an accurate tool that can identify individuals at high risk of developing diabetes, enabling early intervention and personalized healthcare. The ultimate goal is to facilitate early intervention and enable personalized healthcare strategies.

The significance of our project lies in its potential to revolutionize diabetes prevention and management through:

1. **Early Detection:** Identifying individuals at risk before symptoms manifest allows for timely interventions and lifestyle modifications.

2. **Personalized Healthcare:** The machine learning model will provide personalized risk assessments, enabling healthcare professionals to tailor interventions based on individual profiles.

3. **Resource Optimization:** Efficient allocation of healthcare resources by targeting interventions toward individuals at the highest risk.

4. **Improved Patient Outcomes:** Timely interventions and personalized care can lead to better health outcomes and a reduced risk of complications associated with diabetes.

5. **Public Health Impact:** Contributing to public health goals by reducing the prevalence of diabetes and associated healthcare burdens.

6. **Technological Innovation:** Showcasing the integration of advanced technologies into healthcare for accurate risk prediction.

## Data Sources

The dataset used was obtained from Kaggle. The dataset can be accessed with this [link](https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset). This dataset contains demographic data from patients as well as their diabetes status.

## Data Cleaning and Preprocessing

1. Data Inspection:
   a. Identified the types of data (numerical, categorical).
   b. Identified potential hanging values or outliers.
   c. Conversion of Non-Numerical Values:

2. Map categorical values to numerical representations.
   a. Used techniques like one-hot encoding for nominal variables.
   b. Handled Missing Values:

3. Identify and fill or remove missing values.
   a. Outlier Detection and Removal:

4. Normalization or Standardization:
   a. Scale numerical features to a common range to ensure fair comparisons.

## Modeling

We used Linear Regression + Polynomial Regression Model, Random Forest Model and XGBoost Model for training and testing.

## Model Deployment

Both the model and API was deployed using render and the frontend was deployed using netlify.

## Getting Started Locally and Remote

Follow this steps to run the project on your machine.

### Installation

a. Make sure you have docker installed on your machine from [here](https://www.docker.com/products/docker-desktop/)

b. Clone the repository

```shell
git clone https://github.com/AISaturdaysLagos/Cohort8-Johnson-Sirleaf.git`
```

c. Change directory into the repository

```shell
cd Cohort8-Johnson-Sirleaf
```

d. Run the command to start both the frontend and backend applications

```shell
make start
```

e. Run the command to stop both the frontend and backend applications

```shell
make stop
```

d. visit this links on your browsers for local testing.

- <http://localhost:5000> for backend service
- <http://localhost:8080> for frontend service

f. visit this links on your browsers to test the deployed application

- visit [here](https://tranquil-llama-c1669d.netlify.app)

## Acknowledgments

We would like to acknowledge the outstanding contributions of :
Olawale Abimbbola - Your guidance and valuable feedback played a pivotal role in steering the course of this research. Your patience and positive encouragement provided steadfast support during the hurdles we encountered.
**Email** - [abimbolaolawale41@gmail.com](abimbolaolawale41@gmail.com)
**Github** - [https://github.com/olawale0254](https://github.com/olawale0254)
**Linkedin** - [https://www.linkedin.com/in/bimbolawale](https://www.linkedin.com/in/bimbolawale)

## Support and Contact

**Name** - Oluwafemi Akinode
**Linkedin** - [linkedin.com/in](https://www.linkedin.com/in/oluwafemi-akinode-572459148)

**Name** - Buraimoh Glory
**Linkedin** - [linkedin.com/in](https://www.linkedin.com/in/gloryburaimoh)

**Name** - Dolamu Oludare
**Linkedin** - [linkedin.com/in](https://www.linkedin.com/in/dolamu-oludare-76097b133/)

**Name** - Usman Daudu
**Linkedin** - [linkedin.com/in](https://www.linkedin.com/in/usmanadaudu)

**Name** - Stanley Oguazu
**Linkedin** - [linkedin.com/in](https://www.linkedin.com/in/chinedu-oguazu-bba88440/)
