# Housing Prices Prediction

## Overview
This project focuses on predicting housing prices in California using neural networks. The aim is to utilize socioeconomic and demographic data to provide accurate and reliable price predictions that can help in real estate decision-making.

## Data Description
The dataset contains various attributes related to California housing, including:
- **MedInc**: Median income in the block
- **HouseAge**: Median house age in the block
- **AveRooms**: Average number of rooms
- **AveBedrms**: Average number of bedrooms
- **Population**: Block population
- **AveOccup**: Average house occupancy
- **Latitude**: Block latitude
- **Longitude**: Block longitude

## Features
- Extensive data preprocessing includes scaling features and encoding categorical variables.
- Feature engineering to derive new informative attributes and remove redundant data.

## Prerequisites
Required libraries to run the project:
```bash
pip install numpy pandas matplotlib tensorflow scikit-learn
```
## Setup
To execute the project:
1. Clone the repository to your local environment.
2. Install the required dependencies listed above.
3. Run the Jupyter notebook to train the neural network model and visualize the results.
## Model Training and Evaluation
The project uses a neural network model optimized through hyperparameter tuning.
Performance is evaluated based on metrics like Mean Squared Error (MSE) and R-squared (R²) to measure accuracy.
## Results
The trained model demonstrates strong predictive capability with high accuracy, validated through various metrics and visual data exploration.

## Contributing
Contributions to improve the model or extend the dataset are welcome. Please fork the repository, commit your updates, and submit a pull request.
