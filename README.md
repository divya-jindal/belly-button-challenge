# Belly Button Biodiversity Dashboard

## Overview
This project visualizes the Belly Button Biodiversity dataset, providing insights into the types of bacteria found in human navels. The dashboard features an interactive interface where users can explore the dataset through demographic info, bar charts, and bubble charts.

## Files in the Repository
### 'app.js'
This JavaScript file contains the code to build the interactive features of the dashboard. It includes functions to:

* Fetch and display metadata for each sample.
* Build bar and bubble charts to visualize the bacterial data.
* Initialize the dashboard by populating the dropdown menu with sample IDs and displaying the initial charts and metadata.
* Update the charts and metadata panel when a new sample is selected.

### 'index.html'
This HTML file structures the layout of the dashboard. Key features include:

* A header section with the title and description of the dashboard.
* A dropdown menu for selecting different test subjects.
* A demographic info panel displaying metadata for the selected sample.
* A bar chart showing the top 10 bacterial cultures found in the sample.
* A bubble chart visualizing the bacterial cultures per sample.

### 'samples.json'
This JSON file contains the dataset used for the dashboard. It includes:

* metadata: An array of objects, each representing a test subject with their metadata.
* samples: An array of objects, each representing a test subject with their bacterial data.
* names: An array of test subject IDs.

## Dependencies
This project uses the following libraries:

* D3.js: For data manipulation and visualization.
* Plotly.js: For creating interactive charts.
* Bootstrap: For responsive design and styling.

## Usage

To run the dashboard, follow these steps:

1. Clone the repository to your local machine.
2. Open index.html in your web browser.

The dashboard will load, displaying the initial sample's metadata and visualizations. You can select different test subjects from the dropdown menu to explore their data.

You can also see the dashboard here:

https://divya-jindal.github.io/belly-button-challenge/
