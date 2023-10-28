# Tweets Analytics using R

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

This repository contains R code for performing tweets analytics. The code uses various R libraries for data analysis, visualization, and natural language processing to gain insights from a dataset of tweets.

## Getting Started

To get started, make sure you have the following R libraries installed:

```R
library(readxl)
library(ggplot2)
library(RColorBrewer)
library(scales)
library(extrafont)
library(ggplot2)
library(tidyverse)
library(tidygraph)
library(wordcloud)
library(wordcloud2)
library(webshot)
library(tm)
library(igraph)
library(ggraph)
library(qgraph)
library(networkD3)
library(htmlwidgets)
library(htmltools)
library(IRdisplay)
library(glue)
library(cowplot)
library(magrittr)
library(plotly)
library(widyr)
library(hms)
library(lubridate)
library(dplyr)
library(tidytext)
library(sentimentr)
library(purrr)
library(magick)
library(plyr)
You can install these libraries using the install.packages() function in R.
```

## Data Loading
The code starts by loading tweet data from various CSV files (e.g., "Pendekar-Raw.csv", "PSHT-Raw.csv", "TAMSIS-Raw.csv"). It then combines the data from these sources into a single dataset, adding a keyword column for each source.

## Daily Line Chart
The code creates a line chart that displays the daily number of tweets. It converts the date format, counts the occurrences for each date, and plots the data using ggplot2. You can customize the chart's appearance and save it as an image.

## Heatmap
The code generates a heatmap to display the number of tweets per hour, aggregated by day and month. The heatmap provides insights into when tweets are most active. It also offers customization options for the heatmap's appearance.

## Network Diagrams
The code creates network diagrams to visualize relationships between bigrams in the tweet data. It calculates weights for the bigrams and allows you to set a threshold to control the visualization. It also generates interactive network diagrams using networkD3, allowing you to explore the relationships between bigrams with various customization options.

## Top Users Analysis
The code identifies and visualizes the top Twitter users based on their tweet counts. It generates a horizontal bar chart to display the top users and their tweet counts, allowing you to customize the chart's appearance and save it as an image.

## Word Cloud
The code generates a word cloud from the tweet text, providing a visual representation of the most frequent words used in the tweets. You can customize the appearance of the word cloud and save it as an image.

## Usage
Each section of the code is self-contained and can be run independently for specific analyses. You can modify the code and parameters to suit your specific dataset and research needs. Feel free to explore and adapt the code to your own tweet datasets and research requirements. For any questions or issues, please refer to the code comments or contact the author.

Enjoy analyzing tweets using R! 📊📈📋

If you have any questions or need assistance with this code, please don't hesitate to reach out to the author.
