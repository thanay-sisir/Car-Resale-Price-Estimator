# Car-Resale-Price-Estimator Summary <br>
## Overview
This project is a Flask-based web application that predicts the resale price of a car based on various input features, such as the year of the car, fuel type, number of previous owners, and other attributes . The application uses a pre-trained Random Forest Regressor model to make predictions. The model is trained on a dataset of car details and integrates user inputs through a web form to provide predictions.
## Project Structure
* app.py::Main Flask application handling routes and logic.
* rfrm.pkl:Pre-trained Random Forest Regressor model.
* templates/:Folder containing HTML file index.html
* my_dataset.csv: Dataset used for training the model.

* ## Installation and Setup
└── Car-Resale-Price-Estimator &nbsp;   /  #foldername <br>
├── FlaskValuator.py &nbsp;  # Your Flask application <br> 
├── RANDOM_FOREST.pkl&nbsp;  # Your model file <br>
├── mydataset.csv &nbsp;  # Your CSV file <br>
└── templates/ <br>
       &nbsp; └── index.html   # Your HTML template file


# Dataset Overview
 This dataset contains valuable information about used cars, including the car's name, year, selling price, kilometers driven, fuel type, seller type, transmission type, and the number of previous owners.
 ## The dataset Characteristics:<br>

 **Year**:&nbsp; Ranges from cars manufactured between 1992 to 2020. <br>
 <br>
 **Selling Price**: &nbsp;The selling price ranges from approximately ₹20,000 to ₹90,00,000 <br>
 <br>
 **Owner**: &nbsp;65% of the cars are first-owner vehicles, with second-owner and third or more owners accounting for a smaller percentage. <br>
 <br>
 **Seller Type**: &nbsp;75% of cars are sold by individuals, and 23% are from dealers.<br>
 <br>
 **Kilometers Driven**:&nbsp; Values range from 1,000 km to over 800,000 km.<br>

 # Final Output: <br>

![Screenshot 2025-01-05 224639](https://github.com/user-attachments/assets/509cebc1-8660-47b6-82a0-d1ab63477419)  <br>
![result1](https://github.com/user-attachments/assets/152d60a9-ea4d-44a8-ad26-9bf8cc3b9ace)


 
 
 
 
