![HeaderBanner](https://raw.githubusercontent.com/Rohan-Dawar/ML-Wine-Price-Prediction/main/wineML.png)

# Machine Learning Wine Price Prediction Models
## Author [Rohan Dawar](https://www.rohandawar.com/)
---
### In this project I have built some machine learning models to predict the price of wine based on [zynicide's web scraped data](https://github.com/zackthoutt/wine-deep-learning) from [WineEnthusiast](https://www.winemag.com/)
---
### [Kaggle Page](https://www.kaggle.com/zynicide/wine-reviews) where you will find the raw datasets used in my notebook. Credit to [zynicide](https://www.kaggle.com/zynicide) for this web-scraper.
---
### [Check out my blog post on this project](https://www.rohandawar.com/post/predicting-wine-prices-with-machine-learning)!
---
##### *Note:* GitHub has an issue with displaying the plotly graph outputs in the Jupyter Notebook, if you cannot see the plotly graphs, please try opening the .ipynb in Google Colab.
---
### Getting Started
1. Open ```Machine_Learning_Models_Predicting_Wine_Prices_Rohan_Dawar.ipynb (10.5 MB)``` in a Jupyter Notebook environment (Google Colab recommended).
2. Run the notebook inputing your [Kaggle Api Key](https://www.kaggle.com/docs/api) when prompted, if you don't have an API key you can manually upload the CSV ```winemag-data_first150k.csv (49.78 MB)``` from the [Kaggle Page](https://www.kaggle.com/zynicide/wine-reviews).
3. The code will perform input engineering, data analysis and regression model fitting. Once the models are created they are saved as joblib files and you can run predictions by calling ```mode.predict(inputs)```.

### Built With
* [SciKit Learn](https://scikit-learn.org/stable/)
* [XGBoost](https://xgboost.readthedocs.io/en/stable/)
* [Pandas](https://pandas.pydata.org/)
* [Plotly Express](https://plotly.com/python/plotly-express/)

### License
The software and output models in this project are licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
