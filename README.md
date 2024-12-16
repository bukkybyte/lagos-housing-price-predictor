# Lagos Housing Price Predictor

This project aims to predict housing prices in Lagos based on various factors like neighborhood, property type (flat or duplex), and the number of bedrooms. It provides an interactive web-based interface for users to input their preferences and get an estimated property price.

## Features:
- Predict housing prices based on:
  - Neighborhood
  - Property type (Flat or Duplex)
  - Number of Bedrooms
- Real-time updates with dynamic predictions based on input values.
- Simple user interface built with **ipywidgets**.
  
## Prerequisites:
To run this project, you need the following:
- Python 3.x
- Jupyter Notebook or JupyterLab
- The following Python packages:
  - `ipywidgets`
  - `pandas`
  - `scikit-learn` (for model predictions)

You can install the required packages using `pip`:

```bash
pip install ipywidgets pandas scikit-learn
```

## How to Run:
1. Clone this repository to your local machine:

```bash
git clone https://github.com/bukkybyte/lagos-housing-price-predictor.git
```

2. Navigate to the project directory and open the notebook:

```bash
cd lagos-housing-price-predictor
jupyter notebook
```

3. Open the `housing_prices_and_size.ipynb` notebook and run the cells.

4. Use the interactive widgets to select your desired neighborhood, property type, and number of bedrooms to predict the house price.

## Conclusion:
The **Lagos Housing Price Predictor** provides users with an easy-to-use tool to estimate house prices based on specific input features. Future improvements can include adding more data, using advanced machine learning algorithms, and refining the model for better accuracy.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
