# 🏖️ Sydney Swim Site Contamination Prediction

![Australian Flag](https://i.imgur.com/uBL1Z78.gif)

**Can we predict Enterococci contamination levels at Sydney swim sites using just a handful of publicly available features?**  
This project builds a machine learning pipeline to do exactly that — forecasting unsafe water conditions with real-world environmental and site data.

---



## Instructions

To replicate our analysis end-to-end, simply open an Rmd notebook and copy our code which can be found in the 'enterococci-forecasting.Rmd' file

EDA: From lines 1-1,310

Features Significance + Model Building 1,314 - 2,281

---

## Overview

Beach water pollution poses a significant public health risk. Enterococci, a bacteria found in fecal contamination, is used as the key indicator for swim safety in Sydney, Australia. However, many swim sites lack official forecasts. This project explores whether we can fill this gap using minimal but effective features like:

- **Location**
- **Date**
- **Rainfall**
- **Conductivity**
- **Air temperature**

The goal is to build a model that prioritizes **early warnings for unsafe conditions**, especially in sites that currently lack coverage.

---

## 📁 Data Sources

We used two primary datasets:

- **NSW Beachwatch**: water sample reports (Enterococci levels)
- **Open Meteo**: historical and current weather data

> ⚠️ The datasets are not stored locally — they are loaded via **URL links directly in the code**.
> Using these links:
> water_data<- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2025/2025-05-20/water_quality.csv')
> weather_data <- readr::read_csv('https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2025/2025-05-20/weather.csv')


---
