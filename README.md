<h1 align="center">Impact of coalition governments on key country metrics</h1>
Creator of the repository: Ilias Samathrakis

<p align="center">
  <img src="https://github.com/isamathr/coalition-governments/assets/134223309/d23d1e73-4384-4426-8c0a-523c0d9e1920" width="400">
</p>

# Table of contents

* [Description](#description)
* [Data Collection](#collection)
* [Data Analysis](#analysis)
* [Findings](#findings)


## Description <a name="description"></a>

**Scientific Question**: Are countries with coalition governments performing better than their single party government counterparts?

In this project, I perform hypothesis testing to further investigate the question using three different metrics:

1. gross domestic product per capita (GDP) 
2. corruption index (CPI)
3. world press freedom index (WPFI)

In conclusion, this project sheds light on the relationship between government types and key country metrics, suggesting that coalition governments may have a positive impact on transparency (i.e. CPI) and press freedom (i.e. WPFI), but their influence on economic performance (i.e. GDP) is less clear.

## Data Collection <a name="collection"></a>

The process of collecting the necessary data is described in this [Jupyter Notebook](https://github.com/isamathr/coalition-governments/blob/main/process/Collecting_datasets.ipynb).
Some further cleaning is required to get the final version of the files

## Data Analysis <a name="analysis"></a>

Files 
1. Data.csv
2. Elections.csv

are necessary for the analysis. You can find them in the [process](https://github.com/isamathr/coalition-governments/blob/main/process/) folder.
The statistical analysis of datasets is described in this [Jupyter Notebook](https://github.com/isamathr/coalition-governments/blob/main/process/analyzing_datasets.ipynb).

## Findings <a name="findings"></a>

It is found that for the corruption index (CPI) as well as the world press freedom index (WPFI), the null hypothesis is rejected for all years, demonstrating a significant difference between the 'upper' and the 'lower' group of countries. On the other hand, the gross domestic product per capita (GDP) does not have the same behaviour. A particular example for the year 2019 is shown on the graph below.

![bernoulli_distr](https://github.com/isamathr/coalition-governments/assets/134223309/28c2abe4-3cd0-459c-a6fc-f2eb44119086)

Find more detailed explanation in [Jupyter Notebook](https://github.com/isamathr/coalition-governments/blob/main/process/analyzing_datasets.ipynb).
