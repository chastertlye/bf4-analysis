## Introduction
This research focuses on analyzing player behavior and performance patterns in **Battlefield 4**, a large-scale multiplayer first-person shooter developed by *DICE* and published by *Electronic Arts (EA)*. Released in 2013, the game is part of the long-running Battlefield franchise and is known for its combination of infantry combat, vehicle warfare, and destructible environments. 

Despite being over a decade old, Battlefield 4 remains one of the most data-rich shooters ever created, with deep player progression systems and extensive performance tracking. Players accumulate detailed statistics across weapons, classes, vehicles, and game modes, all of which are publicly accessible through *official and community-maintained APIs*. These aspects make Battlefield 4 an excellent source for data analysis, behavioral research, and machine learning experiments.


## 👾 Why was this particular game chosen?
**Battlefield 4** was selected as the focus of this project for several compelling reasons:
 1) 📅 **Rich and extensive data availability:** Released in 2013, Battlefield 4 has maintained an active player base for over a decade. This longevity has resulted in an huge volume of player data — providing an excellent foundation for large-scale statistical and behavioral analysis.
 2) 🌍 **Large and diverse player base:** Over the years, BF4 attracted players from all over the world and across all platforms. This diversity ensures that the data reflects a wide spectrum of skill levels, preferences, and play patterns, making it excellent for data-driven insights or machine learning models.
 3) 📡 **Open and Accessible API:** Battlefield 4 exposes a public API that allows anyone to securely and freely access detailed player statistics — including global performance, weapon usage, accuracy, vehicle activity, class distribution, and more. This transparency makes it possible to legally collect consistent and verifiable data without violating terms of service.

## 🎯 Project Goals

This project aims to:
- Analyze large-scale Battlefield 4 player statistics to uncover behavioral and performance trends.
- Compare gameplay characteristics between **regular players** and **verified cheaters**.
- Identify potential statistical indicators of cheating behavior using exploratory data analysis (EDA).

## 📖 Project Structure

01. [**Data Collection**](project/01_collection.md) - gathering player and cheater stats via open APIs
02. [**Data Cleaning**](project/02_cleaning.md) - merging datasets, handling missing values, and preparing features
03. [**Exploratory Data Analysis & Feature Engineering**](project/03_EDA.md) - statistical summaries and visual pattern discovery & designing behavioral indicators
## 🚀 Future Work

04. **Classification Approaches** - testing various methods for detecting cheaters
05. **Results** - summarizing findings and key patterns