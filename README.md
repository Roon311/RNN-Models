# RNN Models for Temperature Prediction

This repository contains Python code for predicting the temperature 1 hour into the future using two different Recurrent Neural Network (RNN) models: one with simple vanilla RNN cells and the other with Gated Recurrent Unit (GRU) cells. The models are trained and evaluated using the "jena_climate_2009_2016" dataset.

## Dataset

The temperature prediction models are trained and evaluated using the "jena_climate_2009_2016" dataset. This dataset contains weather measurements recorded at the Weather Station in Jena, Germany, from 2009 to 2016.

To use this dataset, follow these steps:

1. Download the dataset from the following source link: [jena_climate_2009_2016.csv.zip](https://storage.googleapis.com/tensorflow/tf-keras-datasets/jena_climate_2009_2016.csv.zip).

2. Extract the contents of the zip file.

3. The dataset file should be named "jena_climate_2009_2016.csv".

4. Place the "jena_climate_2009_2016.csv" file in the project's root directory.

## Requirements

Make sure you have the following dependencies installed:

- NumPy
- Matplotlib
- scikit-learn
- TensorFlow
- Pandas
- Seaborn
- pandas-profiling

You can install the dependencies using the following command:

```bash
pip install numpy matplotlib scikit-learn tensorflow pandas seaborn pandas-profiling
```

## Usage

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Roon311/RNN-Models.git
   ```

2. Navigate to the project directory:

   ```bash
   cd RNN-Models
   ```

3. Run the Jupyter Notebook `Temperature_Prediction.ipynb` to train and evaluate the RNN models for temperature prediction.

4. Follow the instructions and code provided in the notebook to understand and execute the temperature prediction process using both vanilla RNN and GRU models.

5. Experiment with different hyperparameters, architectures, or preprocessing techniques to improve the model's performance.

## Contact

For any questions or inquiries, please contact [s-noureldin.hamed@zewailcity.edu.eg].

Feel free to customize this README file according to your specific project details. Good luck with your temperature prediction models!
