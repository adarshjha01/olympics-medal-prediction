# Olympic Medal Prediction

Live Dashboard: https://huggingface.co/spaces/adarshjha01/olympic-medal-prediction

## Overview
This project uses a **Linear Regression** model to predict the number of Olympic medals a team might win based on two key factors: the number of athletes in the team and the team's previous medal performance. The model is trained on historical Olympic data and is accessible through a **Gradio** interface.

## Features
- **Input**: Number of athletes and previous medals won by the team.
- **Output**: Predicted number of medals the team will win.
- **Technology**:
  - **pandas**: For data loading and preprocessing.
  - **sklearn**: For training the Linear Regression model.
  - **gradio**: For creating an interactive web interface for user input and prediction.

## How It Works
1. The data is preprocessed, cleaning up missing values and selecting relevant features.
2. The model is trained using data from years prior to 2012, with predictors being the number of athletes and previous medals.
3. A web interface allows users to input the number of athletes and past medals to predict the team’s future medal count.
