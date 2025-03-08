# Belly Button Biodiversity Dashboard

This project involves building an interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels. The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs) were present in more than 70% of people, while the rest were relatively rare.

## Overview

The interactive dashboard allows users to visualize the top 10 OTUs found in an individual's navel and explore various aspects of the dataset through bar and bubble charts. Additionally, users can view metadata information about the individuals.

## Features

- **Horizontal Bar Chart**: Displays the top 10 OTUs found in an individual with sample values as the values for the bar chart, otu_ids as the labels, and otu_labels as the hovertext.
![hw01](https://github.com/user-attachments/assets/3089fb4e-07b5-4ea2-96ef-38c45a732fbe)

- **Bubble Chart**: Visualizes each sample with otu_ids for the x values, sample_values for the y values and marker size, and otu_labels for the text values.
![bubble_chart](https://github.com/user-attachments/assets/4f5bc402-55a2-4b2e-921f-a814d79be0dd)

- **Demographic Info Panel**: Displays an individual's demographic information by looping through key-value pairs from the metadata JSON object.
![hw03](https://github.com/user-attachments/assets/faba1587-e36b-42b8-89b2-2e721afa773b)

- **Dynamic Updates**: Updates all plots when a new sample is selected from the dropdown menu.
![hw02](https://github.com/user-attachments/assets/0de77f45-3777-4dee-af55-92e37a85cb0a)


## Technologies Used

- D3.js
- Plotly.js
- HTML/CSS
- JavaScript

