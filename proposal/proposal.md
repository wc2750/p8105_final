P8105 Final Project Proposal
================
Beibei Cao, Chenxi Liu, Renjie Wei, Weixi Chen
11/6/2020

## The group members

  - Beibei Cao: bc2918
  - Chenxi Liu: cl4044
  - Renjie Wei: rw2844
  - Weixi Chen: wc2750

## Tentative project title

Avocado Price Analysis and Prediction

## Motivation

Avocado has become a more preferable and healthy choice as a source of
fat nutrition source. According to USDA, U.S. demand for avocados has
increased steadily over the past two decades. Per capita consumption of
avocados has tripled since 2001 to 8 pounds per person in 2018. We
believe that by looking into influential factors and trends regarding
avocado prices, we could gain more insights into its consumption pattern
and further predict its impact on people’s life and health.

We want to perform EDA to the original data and implement a prediction
model of prices. The impact of GDP on local price and consumption of
avocado will also be assessed. We also intend to include interactive
visualization tool that will enable people to check on time-base or
region-base information purposefully.

## Intended final products

  - Quantified relationship between the size of an avocado and price
  - General trends of avocado volume and price (by regions) over time
  - Interactive maps of prices vs. volumes and prices vs. region of
    avocado in the U.S
  - The correlation of local GDP and avocado consumption (tentative)
  - Prediction model to accurately forecast avocado prices

The final product will be a well-formatted website, including a video
presentation, written report, and the display of our data analysis,
interactive visualization, and prediction model.

## Data sources

  - `Avocado price data`:
    [Kaggle](https://www.kaggle.com/neuromusic/avocado-prices)
      - The dataset, updated till March, 2018, was compiled by Justin
        Kiggins who obtained the data source from [Hass Avocado
        Board](https://hassavocadoboard.com/)
  - `State GDP data`:
    [Kaggle](https://www.kaggle.com/solorzano/gdp-per-capita-in-us-states?select=bea-gdp-by-state.csv)

## Planned analyses / visualizations / coding challenges

  - The data will be cleaned, manipulated and summarized through
    `tidyverse`, `stringr`, `forcat` and other neccessary packages.
  - Visualizations will be used to show the interested trends and
    associations of the variables through `ggplot`. In addition, the
    plots will be displayed for interactivity on websites through
    `plotly` and `shiny`. The `autoplot` library may be used because it
    allows us to see patterns between the different years.
  - Implementing several regression models based on our EDA and select
    the most accurate one for price prediction.

## Planned timeline

  - Milestone 1: Tidying Data (Nov 10 - Nov 15)
      - Proposal approved after review meeting
      - Date cleaning and data wrangling
  - Milestone 2: EDA (Nov 16 - Nov 22)
      - Initial data exploration/visualization
      - Further data visualizations/conclusions
  - Milestone 3: Building up deliverables (Nov 23 - Nov 30)
      - Interactive visualization
      - Report, website wrap-up and screencast
  - Milestone 4: Assembling (Dec 1 - Dec 4)
      - Finish up deliverables
      - Proofread
      - Done\!
