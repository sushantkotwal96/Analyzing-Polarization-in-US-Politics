# Analyzing-Polarization-in-US-Politics

## Overview
This project visualizes the political polarization in the US Congress from 1989 to 2014 using Multidimensional Scaling (MDS). The project processes and analyzes voting data of senators, recodes their votes, calculates the cosine similarity between their voting patterns, and then uses MDS to plot the distances between senators based on their voting behavior.

## Requirements
The project requires the following R libraries:
- `magrittr`
- `tidyverse`
- `ggbiplot`
- `ggrepel`
- `plyr`
- `lsa`
- `flexclust`

## Data
The project utilizes the voting records and member information from the US Congress for the years 1989 to 2014. The data files should be organized in the following structure:
```
congress/
    ├── 1989/
    │   ├── members.csv
    │   └── votes.csv
    ├── 1990/
    │   ├── members.csv
    │   └── votes.csv
    ├── ...
    └── 2014/
        ├── members.csv
        └── votes.csv
```

### Data Description

- **Bills Data:** Records of all bills passed, including information on senators who supported or opposed each bill.
- **Senators Data:** Information on senators, particularly their party affiliations.
- **Time Frame:** 1989 to 2014.

### Methodology

The analysis is divided into three parts:

#### 1. Comparison of Voting Results (1989 vs. 2014)

- **Objective:** Determine how senators' ideologies and voting patterns have changed from 1989 to 2014.
- **Approach:** 
  - **Multi-dimensional Scaling (MDS):** Used to project voting patterns onto an n-dimensional plane, allowing for the visualization of similarities and clusters among senators.
  - **Clustering:** Identified how senators grouped based on their ideologies in 1989 and 2014.

### Analysis Process

1. **Data Collection and Preparation:**
   - Gathered records of bills passed and senators' voting patterns.
   - Extracted relevant data for the years 1989 and 2014.

2. **Multi-dimensional Scaling (MDS):**
   - Applied MDS to project senators' voting patterns onto a plane.
   - Visualized the distances and clusters to understand ideological similarities and differences.

3. **Clustering Analysis:**
   - Analyzed the clusters formed by senators based on their voting patterns.
   - Compared clusters from 1989 and 2014 to observe changes in political polarization.

### Results

- **Polarization Trends:** The analysis revealed significant changes in the clustering of senators' ideologies between 1989 and 2014, indicating an increase in political polarization over time.
- **Ideological Shifts:** Clear shifts in the voting patterns and ideological stances of senators were observed, reflecting the evolving political landscape in the US.

### Conclusion

This project provides a comprehensive analysis of political polarization in US politics over a 25-year period. By examining the voting patterns and ideological shifts of senators, it highlights the increasing divide in political opinions and the resulting impact on governance.


## Author
Sushant Kotwal

