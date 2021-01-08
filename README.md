# Predicting BTC Drawdowns

## Project Proposal

We are interested in using quantitative analysis to predict significant BTC price drawdowns exceeding 30%. We will fit an algorithm to combination of historical price, volatility, volume and sentiment data to develop a predictive model. 

## Data sources
To provide sufficient training data and capture previous boom and bust cycles our intent is to go back to at least mid-summer of 2017. As recently demonstrated, BTC price can significanly move within minutes/hours. Our intent is utilize hourly time series data for price, volatility, and volume datasets. Possible sources include:
* news api
* twitter api
* fear and greed indicator/indexes
* Kraken api
* Gemini api

## Data Preparation & Model Training
Three years of hourly data represents 1.5768M points per time series data metric. Of concern will be how to extract this much data from APIs, store it, and prepare it for modelling.

## Model Evaluation
Testing data split off the data set will be used to evaluate the model. Tables, charts, plots, or statistical analysis will be used to report the model performance.

## Predictions and Conclusions
Conclusions and predictions will be numerically summarized and presented visually.

>Summarize your conclusions and predictions. This should include a numerical summary (what data your model yielded), as well as visualizations of that summary (plots of the final model evaluation and predictions).

>Optionally, deploy the model as an interactive dashboard or interface (Lex or SageMaker).

>Be sure that your projects meet the [technical requirements](TechnicalRequirements.md).

## Presentation

>After you've tweaked your model to your satisfaction, you'll put together a presentation to show off your work, explain your process, and discuss your conclusions.

>This presentation will be delivered as a slideshow, and it should give your classmates and instructional staff an overview of your work. PowerPoint, Keynote, and Google Slides are all acceptable for building slides.

>As long as your slides meet the [presentation requirements](PresentationRequirements.md), you are free to structure the presentation however you wish, but students are often successful with the format laid out in the [presentation guidelines](PresentationGuidelines.md).
