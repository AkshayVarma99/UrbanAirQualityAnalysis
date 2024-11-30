# Assessing Urban Air Quality in Major English Cities Using Geospatial Analysis and Python

This project leverages Python and geospatial technologies to assess and visualize air quality in major English cities (London, Manchester, Birmingham, and Bristol). The analysis identifies pollution hotspots, examines trends over time, and highlights factors influencing air quality, helping to inform urban planning and policy decisions.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [How to Run the Code](#how-to-run-the-code)
- [Results](#results)
  - [Spatial Distribution](#spatial-distribution)
  - [Statistical Analysis](#statistical-analysis)
  - [Trends Over Time](#trends-over-time)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

---

## Project Overview

This dissertation explores the integration of geospatial technologies and Python to analyze urban air quality. Key objectives include:
- Data cleaning and formatting.
- Spatial mapping and analysis using **GeoPandas**.
- Data visualization with **Matplotlib** and **Folium**.
- Regression analysis for understanding pollution dynamics.

---

## Technologies Used

- **Python** (GeoPandas, Matplotlib, Folium)
- **NumPy** & **Pandas** (Data manipulation)
- **Scikit-learn** (Regression analysis)
- **Jupyter Notebooks** (Interactive code execution)

---

## Data Description

The dataset contains air quality measurements (CO, NOx, NO2) and weather parameters for major English cities. It includes geospatial coordinates to help map pollutant concentrations.

---

## How to Run the Code

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AkshayVarma99/urban-air-quality-analysis.git
   cd urban-air-quality-analysis
   ```
2. **Install dependencies**:
   ```bash
   pip install geopandas matplotlib folium pandas scikit-learn
   ```
3. **Place the air quality data file in the data/ folder.**
 
4. **Run the script:**:
   ```bash
   jupyter notebook Air_Quality_Analysis_Dissertation.ipynb
   ```
   This will launch Jupyter, where you can run the cells interactively. The notebook processes the data, performs spatial analysis, and generates visualizations (interactive maps and static plots).

---

## Results

  ## Spatial Distribution: 
  The spatial analysis reveals significant variations in air quality across cities. Pollution hotspots were identified in urban centers, with the highest concentrations of CO and NOx in densely populated areas.
  
  ![Pollution Map](images/Air%20Quality%20Map.png)
  
  *Screenshot 1: Air Quality Map.*
  


 ![Summary of Spatial Regression](images/Summary%20of%20Spatial%20Regression.png)
 
 *Screenshot 2: Summary of Spatial Regression.*

  ## Statistical Analysis: 
  The OLS regression model produced an R-squared value of 1.000, indicating a perfect fit. However, issues like multicollinearity and a low Durbin-Watson statistic suggest potential violations of model   
  assumptions.
  
  ![OLS Regression Summary](images/OLS%20Regression%Summary.png)
  
  *Screenshot 3: OLS Regression Summary.*
  

  ## Trends Over Time: 
  Air quality data shows fluctuations in CO levels throughout the day, with noticeable decreases at night.

---

## Conclusion

This project demonstrates the power of combining geospatial analysis and Python for urban air quality assessment. Key insights include:
- Geospatial tools (GeoPandas, Folium) effectively map pollutant concentrations.
- Statistical models (OLS regression) reveal factors influencing air quality.
- Interactive maps and visualizations simplify communication of findings.
- 
![Geospatial Patterns of CO(GT) and C6H6(GT) in High Air Pollution Cities](images/Geospatial%20Patterns%20of%20CO%20and%20C6H6.png)

*Screenshot 4: Geospatial Patterns of CO(GT) and C6H6(GT) in High Air Pollution Cities.*
  
**Key Takeaways**:
- Geospatial technologies help identify pollution hotspots and understand spatial patterns.
- Statistical models reveal relationships between traffic, population, and pollution.
- Interactive maps make it easy to engage with the data and inform decision-making.

---

## Recommendations

1. **Urban Planning**: Focus on areas with high pollution concentrations. Prioritize interventions such as green spaces and enhanced public transport.
2. **Policy Advocacy**: Advocate for stronger air quality monitoring and regulations in pollution hotspots.
3. **Further Study**: Increase monitoring station density for more accurate and granular data on air quality.
