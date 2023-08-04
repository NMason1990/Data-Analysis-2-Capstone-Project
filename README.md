# FaB TCG Analysis/CodeLouisvilleData2

[A Capstone Project for the Python Data Analysis 2 Bootcamp ]

## Table of Contents
- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)


## Project Description

[1. I will be taking Data in from the fabdb.net API, from the cards endpoint - Done in api-data-exploded.ipynb
Then scraping data from TCGPlayer.net that will show more cards, current market price and potentially other insights to make this data wider. - TCGPlayer_Scraper.ipynb

2. I will be mnerging my data with pandas merge, manipulating and removing any empty values, finding a way to fix the duplicate entries from the two data sets, and filtering to only show columns that I need for my end goal - Done in Merged_Data.ipynb

3. For The Visualization Requirement of this project, I made two pivot tables in pandas using the 'market price' column for the x axis, 'rarity' on one, and 'set' on the other for the y axis. I made the pivot tables so that the unique values in the columns on the y axis would be compared to the 'market price'. I made the pivot tables calculate the Min, Max, Sum, and Mean for all of the columns and rows involved. From there I used numpy to use logarithmic scaling I saw in pluralsite on the data for further analysis once I can grow these data sets over time so I can do predictions. I then visualized the two pivot tables with seaborn in bar graphs. 

4. For this Requirement I used an anaconda environment to make my code. 

5. I will be using a Jupyter notebook for annotation and to inerpret the data  ]

## Installation


## Usage

[Provide instructions on how to use your project. Explain the basic usage and any important features or functionalities. Include examples or code snippets if applicable.]

## Features

[Web scraping, API Calls, Using Pandas to clean the data,merged the data make pivot tables, and analyze. Bar charts made with seaborn..]

## Contributing

[If you would like to contribute to this project I would like to make the web scraper more in depth and actually select each card and then get the prices of sales in the past so that in the future maybe some machine learning can be used to predict future prices.]


## Contact

[Natanielmason90@gmail.com,]
