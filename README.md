
# Visualization of Tree Planting Data in San Francisco

![image](https://github.com/ZRQ-rikkie/Information-Visualization/blob/main/tree.gif)

## Dataset Overview

This project utilizes data from San Francisco's open data portal, focusing on the city's diverse tree population. The dataset includes a variety of tree species, each with unique characteristics, offering insights into the ecological diversity of San Francisco’s urban landscape. Key attributes include species, location, planting date, diameter at breast height (DBH), and legal status, among others.

## Preliminary Data Processing with Python

### Data Loading and Initial Processing
- Imported and analyzed the dataset using the pandas library in Python.
- Counted the unique tree species to understand the dataset's diversity.

### Date Conversion and Tree Age Calculation
- Standardized planting dates and calculated the age of each tree.

### Data Cleaning
- Removed incomplete entries and irrelevant data.
- Filtered out specific non-contributing entries.

### Species Stratification and Sampling
- Focused on the top 8 species for simplicity.
- Applied stratified sampling for manageable data representation.

### Geospatial Filtering
- Integrated tree data with geospatial information of San Francisco's neighborhoods.

### Final Dataset Preparation
- Prepared and saved the refined dataset for visualization.

## Design Considerations

![image](https://github.com/ZRQ-rikkie/Information-Visualization/assets/74203373/516d1d0d-1be8-4735-a4c1-d545465693de)
### Geographical Distribution Map
- **Design:** A Mercator projection map with two layers: base layer for neighborhoods and tree layer for individual trees.
- **Rationale:** Offers a familiar and intuitive spatial distribution of trees with age-coded markers.
- **Alternatives Considered:** Heat maps were considered but not chosen due to detail limitations.

### Bar Chart (Species and Age Range)
- **Design:** Horizontal bar chart categorizing trees by species and age range, using color encoding and calculated transformations.
- **Rationale:** Enhances readability and comparison across species and age ranges.
- **Alternatives Considered:** Vertical bars and pie charts were options but not selected for clarity reasons.

### Scatter Plot and Line Chart (Tree Age and DBH)
- **Design:** Combines scatter plot and line chart to explore tree age and DBH relationships.
- **Rationale:** Allows for detailed analysis of growth patterns and individual tree characteristics.
- **Alternatives Considered:** Standalone scatter plot or line chart, but a combined approach was chosen for comprehensive analysis.

## Interaction Approaches
![image](https://github.com/ZRQ-rikkie/Information-Visualization/assets/74203373/a2f85de0-bfbe-4da2-9770-ab3fa34b34d9)
### Cross-Filtering with Toggle Selection
- Enables dynamic visualization updates based on species selection.

### Point Selection and Brushing on Scatter Plot
- Allows for detailed analysis of specific trees and planting trends over time.

### Tooltip Information
- Provides detailed information on the map, bar chart, and scatter plot.

## Overall Quality and Attention to Detail
- Careful design with clear titles, labels, and legends.
- Accurate and relevant data transformation and aggregation.
- User-friendly encodings and interactions for insightful data exploration.

## Conclusion

The tool provides an interactive platform for analyzing San Francisco's urban forest landscape, valuable for urban planners, environmentalists, and the public. Continued improvements and data updates could further enhance its utility for decision-making and educational purposes.


