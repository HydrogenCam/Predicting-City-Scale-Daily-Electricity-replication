# City-Scale Electricity Use Prediction

This is the official repository that implements the following paper:

> *Wang, Z., Hong, T., Li, H. and Piette, M.A., 2021. Predicting City-Scale Daily Electricity Consumption Using Data-Driven Models. Advances in Applied Energy, p.100025.*

[[paper_submitted]](docs/paper_submitted.pdf)[[paper_online]](https://doi.org/10.1016/j.adapen.2021.100025)




# Code Usage


### Set up the environment 
Set up the virtual environment with your preferred environment/package manager.

The instruction here is based on **conda**. ([Install conda](https://docs.anaconda.com/anaconda/install/))
```
conda create --name cityEleEnv python=3.9 -y
conda activate cityEleEnv
```
requirements: numpy pandas matplotlib seaborn scikit-learn pystan scipy lightgbm prophet( instead of old version fbprophet from original paper)

### Repository structure
``bin``: Runnable programs, including Python scripts and Jupyter Notebooks

``data``: Raw data, including city-level electricity consumption and weather data

``results``: Cleaned-up data, generated figures and tables


### Running
You can replicate our experiments, generate figures and tables used in the manuscript using the Jupyter notebooks saved in ``bin``: `section3.1 EDA.ipynb`, `section3.2 linear model.ipynb`, `section3.3 time-series model.ipynb`, `section3.4 tabular data model.ipynb`, `section4.1 model comparison.ipynb`, `section4.2 heat wave.ipynb`, `section4.3 convid.ipynb`

### Notes
Some 



### Citation


```
Wang, Z., Hong, T., Li, H. and Piette, M.A., 2021. Predicting City-Scale Daily Electricity Consumption Using Data-Driven Models. Advances in Applied Energy, p.100025.

@article{wang2021predicting,
  title={Predicting City-Scale Daily Electricity Consumption Using Data-Driven Models},
  author={Wang, Zhe and Hong, Tianzhen and Li, Han and Piette, Mary Ann},
  journal={Advances in Applied Energy},
  pages={100025},
  year={2021},
  publisher={Elsevier}
}
```
