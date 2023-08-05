### Heart Stroke Risk Prediction using Machine Learning and Explainable AI
This repository contains **Python** code for predicting the likelihood of a heart stroke among patients using various machine learning models. After evaluating the performance of multiple models, **Random Forest** is chosen as the best-performing one, thereby using it for the main predictions. The code then provides a web-based dashboard, developed using **Dash** (whose link is provided later in the document), for users to input the identified important features and get the likelihood of stroke prediction for a new patient. Additionally, the project incorporates Explainable AI techniques to enhance model interpretability using the SHAP (SHapley Additive exPlanations) package.

## Motivation
The world stroke organization stated in 2022 that Stroke remains the second-leading cause of death and the third-leading cause of death and disability combined in the world. 
> According to the National Institute of Health, NIH: “Having a stroke is just as serious as having a heart attack”!

Stroke risk increases with age, but strokes can — and do — occur at any age. Some risk factors for stroke, such as age, race and ethnicity, and family history, can’t be controlled. But there are ways to help lower risk, or prevent stroke. **Our idea is to train models to determine the likelihood of stroke in a person based on some basic and easily available attributes.**

## Dataset
The dataset used for this project contains information about heart stroke occurrences among multiple patients. It includes various features related to id,	gender,	age, hypertension,	heart disease,	average glucose level, BMI, smoking status, marriage status, work and residence type.

![image](https://github.com/ACM40960/project-vaishnavi-mohan/assets/113624086/e6eca1d0-6964-482c-af9b-1cff9b2799d9)

## Machine Learning models
The Python code in this repository leverages **scikit-learn** and other relevant libraries to implement and evaluate several machine learning models, including:

- Logistic Regression
- Multi layer perceptron (MLP)
- Gaussian Naive Bayes
- Random Forest CLassifier (selected as the best-performing model)
- AdaBoost classifier

  The code provides a comprehensive evaluation of each model's performance using various metrics like accuracy, precision, recall, and F1-score.

  ## Usage
1. Download this Jupyter Notebook to your local machine.
2. Install the required dependencies mentioned below.
3. Run the notebook cells step-by-step to
      - perform EDA
      - pre-process the data to achieve required format
      - fit ML model, evaluate and compare them
      - use the best-performing model for **RISK STRATIFICATION**
      - build a web-based dashboard.
4. The dashboard will be accessible at [this URL](http://127.0.0.1:8051/)

You will majorly need the following Python libraries to run this notebook:
```pip install matplotlib.pyplot scikit-learn shap dash```

## Explainable AI
The project incorporates Explainable AI techniques to enhance model interpretability. It utilizes techniques such as:

- Feature Importance: To highlight which features are most influential in making predictions.
- SHAP (SHapley Additive exPlanations): To provide individual-level feature attributions for better insights into each prediction.

The explainable AI part of the project aims to provide transparency and understanding of the Random Forest model's decision-making process.

## Contribution
Contributions to this repository are welcome! If you find any issues or want to add more machine learning models, improve the dashboard, or enhance Explainable AI techniques, feel free to open a pull request.

Please make sure to adhere to the existing code style and follow best practices for machine learning model evaluation, web development, and explainable AI.

## License
This project is licensed under the MIT License

## Credits
This project is in collaboration with [Monica J raju](https://github.com/ACM40960/project-22200376)


Thank you for using this Jupyter Notebook for heart stroke prediction and incorporating Explainable AI to better understand the model's decisions. If you have any questions or need further assistance, please feel free to reach out to the repository maintainers. Happy predicting and helping save lives!
