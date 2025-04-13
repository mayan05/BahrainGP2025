# Bahrain GP Prediction

This project aims to predict the winner of the Bahrain Grand Prix using historical race data and machine learning techniques. The analysis is performed using Python and several data science libraries.

## Project Structure

- `main.ipynb`: The Jupyter Notebook containing the data analysis and prediction model.
- `requirements.txt`: A file listing the Python dependencies required to run the project.
- `f1_cache/`: A directory used to store cached data for faster data retrieval.

## Installation

To run this project, you need to have Python installed on your system. You can install the required dependencies using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the `main.ipynb` notebook in Jupyter Notebook or Jupyter Lab.
2. Run the cells sequentially to load the data, process it, and make predictions.
3. The notebook will output the predicted race times and the predicted winner of the 2025 Bahrain GP.

## Dependencies

The project requires the following Python packages:

- `fastf1==3.3.5`
- `pandas==2.1.0`
- `numpy==1.24.3`
- `scikit-learn==1.3.0`
- `matplotlib==3.7.2`
- `seaborn==0.12.2`

## Data

The data for this project is sourced from the FastF1 library, which provides access to Formula 1 race data. The data is cached locally in the `f1_cache/` directory to improve performance.

## Model

The prediction model is built using a Random Forest Regressor from the `scikit-learn` library. The model is trained on historical lap times and sector times to predict the race outcome.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [FastF1](https://theoehrly.github.io/Fast-F1/) for providing access to Formula 1 data.
- The open-source community for the development of the libraries used in this project.