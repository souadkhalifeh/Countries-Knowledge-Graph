# Countries Knowledge Graph

This project creates a knowledge graph using country-related data, specifically linking **countries**, their **capitals**, and to which **region** they belong.

## Dataset 
The project uses a country dataset from Kaggle: https://www.kaggle.com/datasets/mexwell/countries-states-and-cities-around-the-world?utm_source=chatgpt.com
- Used only the countries.csv file
- Extracted only the name, capital, and region
- Samples 10 random countries
  

## Features
- Extracts and builds relationships as knowledge triples:
  **Country → has_capital → Capital**
  **Country → in_region → Region**
- Constructs a directed graph using **NetworkX**
- Adds edges with labeled relations: has_capital and in_region
- Visualizes the graph using:
 **Skyblue nodes**: Countries  
 **Lightgreen nodes**: Capitals  
 **Lightcoral nodes**: Regions
  
  ## Libraries used
  - pandas
  - matplotlib
  - networkx

  This project was developed on **Google** **Colab**

## Example Output 
<img width="2020" height="1444" alt="image" src="https://github.com/user-attachments/assets/99aa22b0-5db3-4338-b57e-bc34a3598416" />

