# Biodiversity Analysis (Species and Sightings Data)

## Project Overview
This project aims to analyze the relationship between different animal species and their sightings in various national parks. Two datasets are used to explore species taxonomy categories, conservation status, and the distribution of sightings, focusing on identifying insights from the data.

## Dataset
The project uses the following datasets:

- **species_info.csv**: Contains detailed information about various animal species, including:
  - **Category**: The taxonomic category of the species (Mammal, Bird, Reptile, etc.).
  - **Scientific Name**: The scientific name of the species.
  - **Common Name**: The common name of the species.
  - **Conservation Status**: The conservation status of the species (Endangered, Vulnerable, Secure, etc.).

- **observations.csv**: Records sightings of species in different national parks, including:
  - **Park Name**: The name of the park where the sighting occurred.
  - **Scientific Name**: The scientific name of the species sighted.
  - **Observations**: The number of sightings of the species in the park.

## Key Questions
This project addresses the following key questions:

1. **What is the distribution of conservation status among species?**  
   The analysis examines how species are distributed across different conservation statuses, identifying trends and areas of concern.

2. **How does the conservation status relate to the number of observations?**  
   This explores whether species with different conservation statuses are observed more or less frequently in national parks.

3. **What is the distribution of species categories?**  
   The project analyzes how species are distributed across various taxonomic categories, providing insight into the diversity of life forms in the dataset.

4. **How are endangered species distributed across national parks?**  
   The analysis identifies which parks have a higher presence of endangered species, shedding light on critical areas for conservation efforts.

## Visualizations
The project includes several visualizations to illustrate trends and correlations:

- **Bar charts** to show the distribution of species by conservation status and taxonomic category.
- **Pie charts** to visualize the distribution of species categories.

## Technologies Used
- **Python**: Data analysis and visualization.
- **Pandas**: Data manipulation.
- **Numpy**: Numerical calculations.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: Data normalization and preprocessing.

## Installation
To run this project, ensure you have Python installed along with the required libraries:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
