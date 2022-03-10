<!-- PROJECT SHIELDS -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/george-matevosyants-621b9651/
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
![Image Test](images/ML.jpeg)

## Table of Contents
1. [About the Project](https://github.com/gmatevos/Machine_Learning#about-the-project)
2. [Repository Contents](https://github.com/gmatevos/Machine_Learning#repository-contents)
3. [Getting Started](https://github.com/gmatevos/Machine_Learning#getting-started)
4. [References](https://github.com/gmatevos/Machine_Learning#references)


## About the Project
During my Petroleum Engineering days I was always dealing with data analytics, but at some point I ran out of tools from my toolbox.  I decided to learn data science on my own time and started with reading books referenced at the end.  The biggest challenge for me was lack of structured examples that capture modeling process from start to finish :raised_eyebrow:.

I started organizing the material and putting the pieces of the puzzle together during the learning process :thinking:.  I'm hoping people that are facing the same challanges can utilize this repository to answer some of their own questions.  Don't be afraid to start, the biggest hurdle is usually self-doubt.

<ins>Topics covered within this repo:</ins>
1. EDA
2. Preprocessing
3. Feature selection / extraction
4. Modeling
5. Evaluations and improvements


<b>P.S. There are sections with repetitive code that can be easily placed inside a function.  Since repetition is the best path to learning (cross-validation would concur), this was done intentionally.</b>


## Repository Contents
Below is a brief description of what's in each folder.  More detailed information can be found within each project.

<b>Folders</b>
1. [Craigslist Car Pricing](https://github.com/gmatevos/Machine_Learning/tree/main/Craigslist_Car_Price_Predictions) - regression model that predicts car posting price.
2. [Credit Score Classification](https://github.com/gmatevos/Machine_Learning/tree/main/Credit_Score_Classification) - classification of people with good/bad credit.
3. [Maunaloa Volcano CO2 Levels](https://github.com/gmatevos/Machine_Learning/tree/main/Maunaloa_Volcano_CO2_Levels_Forecast) - time series forecasting.  Sourced from A. Muller [lectures](https://github.com/gmatevos/Machine_Learning#references)
4. [US Population Income](https://github.com/gmatevos/Machine_Learning/tree/main/US_Population_Income_Classifications) - classification model for prediction people making >$50k.
5. [Wine Ratings](https://github.com/gmatevos/Machine_Learning/tree/main/Wine_Rating_Predictions) - predicting wine ratings from free text reviews.

<b>Files</b>
1. [ML Cheat Sheet](https://github.com/gmatevos/Machine_Learning/blob/main/ML%20Cheat%20Sheet.docx) - summary of models, theory and assumptions.


## Getting Started
Datasets are not attached, but could be downloaded by following links mentioned within each project.  Below are libraries and IDE used in each project.

### Prerequsites
<ins>IDE</ins>
* [Jupyter Notebook](https://jupyter.org)

<ins>Libraries</ins>
* Sklearn
* Numpy
* Matplotlib
* Pandas
* Scipy
* Statsmodels
* Category_encoders
* Seaborn
* Math
* Skopt

Libraries can be installed with pip through terminal/command line
```
pip install numpy
```
If all mentioned packages are installed, you don't need anything else, time to download the notebooks and get going! :rocket:

## References
I've referenced the following books to learn statistics, python and ML algorithms.  They should suffice to get started with ML, with rare supplemental Google searches.
1. [Probability & Statistics for Engineers & Scientists](https://www.amazon.com/Probability-Statistics-Engineers-Scientists-Update/dp/0134115856)
2. [Learning Python](https://www.amazon.com/Learning-Python-5th-Mark-Lutz/dp/1449355730)
3. [Introduction to Computation and Programming Using Python](https://www.amazon.com/Introduction-Computation-Programming-Using-Python/dp/0262529629)
4. [Applied Predictive Modeling](https://www.amazon.com/Applied-Predictive-Modeling-Max-Kuhn/dp/1461468485)
5. [Introduction to Machine Learning with Python, A Guide for Data Scientists](https://www.amazon.com/Introduction-Machine-Learning-Python-Scientists/dp/1449369413)
6. [Andreas Muller Columbia Data Science Institute Lecture Series](https://www.youtube.com/playlist?list=PL_pVmAaAnxIRnSw6wiCpSvshFyCREZmlM)
