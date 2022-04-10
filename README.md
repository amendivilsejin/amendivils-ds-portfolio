### Intelligent prediction of real estate prices: from EDA and Feature Engineering to optimization of Advanced ML Models

### Description
   This project uses information collected by the real estate company [Properati](properati.com.ar/data/) until 2020, from advertisements published on its web platform by third parties in Argentina interested in promoting properties for sale. Based on the characteristics of the properties described in each advertisement, **the aim is to train data processing and machine learning pipelines so that they can later estimate the price of new properties, based on their characteristics and the state of the real estate market**; and thus be able to offer cadastral appraisal services.
   
   * Pipelines for preproccessing property features (data cleaning and imputation of missing data), and for price estimation, were developed using Random Forest models and Adaboost regressors optimized through Random Search.
   * Through the analysis of relationships between variables, supported by pairplots and correlation maps, relevant characteristics were identified for the estimation of real estate prices.
   * Through EDA, atypical values of property features were identified.
   * Through analysis of missing data mechanisms, determined the main factors for their occurrence.

### Dataset
You can download the dataset implemented here: 
  * [Buenos Aires Real State on sale (2020) | Properati Data](https://www.kaggle.com/datasets/alejandromendivil/bsas-realstate-on-sale)

### Tools needed
  * Python 3.6 | (You may as well import the project into Google Colab)
  * Python libraries: numpy (v1.21.5), pandas (v1.3.5), matplotlib (v3.2.2), seaborn (v0.11.2), sklearn (v1.0.2)
