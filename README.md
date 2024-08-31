# Air Quality and Climate Dynamics in California

This project is a part of the [Data Analytics Bootcamp](https://bigblue.academy/en/data-analytics-bootcamp) at [Big Blue Data Academy](https://bigblue.academy/en). 

## Project Members
- Angeliki Lagogianni, Data Analyst | Project Manager, https://github.com/alagogianni
- Stelios Vasilakis, Data Analyst | Smart Irrigation Systems Engineer, https://github.com/stlvas

## Project Status: [Completed]

## Table of Contents
- [Project Overview](#project-overview)
- [Project Description](#project-description)
- [Project Roadmap](#project-roadmap)
- [Data Sources](#data-sources)
- [Installation and Requirements](#installation-and-requirements)
  - [Prerequisites](#prerequisites)
  - [Dependencies](#dependencies)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Results and Findings](#results-and-findings)
- [Challenges and Limitations](#challenges-and-limitations)
- [Future Work](#future-work)
- [Project Presentation](#project-presentation)
- [BI Dashboard](#bi-dashboard)
- [License](#license)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Project Overview
The purpose of this project is to study air quality and climate dynamics in California and identify critical facts for insurance focus areas. 
By understanding the interplay between air quality trends and climate patterns, we aim to develop targeted insurance strategies that address the specific risks associated with poor air quality. This will enable insurance companies to adjust premiums, create specialized health coverage, predict claims more accurately, and offer incentives for clean energy solutions, ultimately improving risk management and support for policyholders in California.

## Project Description
We started searching for a good source to gather air quality data. We found EPA, U.S. Environmental Protection Agency. EPA establishes an AQI for five major air pollutants regulated by the Clean Air Act. Each of these pollutants has a national air quality standard set by EPA to protect public health:
- **ground-level ozone**
- **particle pollution** (also known as particulate matter, including PM2.5 and PM10)
- **carbon monoxide**
- **sulfur dioxide**
- **nitrogen dioxide** <br />

EPA also monitors weather parameters, winds, temperature, barometric pressure etc. So, our first step was to gather air quality and weather data, we collected daily data for the last 20 years, so we could study the air quality in US States throughout the years and identify our area of interest.

## Project Roadmap
- **Data Collection:** Gathered 20 years of air quality and weather data from the EPA.
- **Preliminary Analysis:** Cleaned and processed the data to identify states with the highest pollution levels.
- **Identify Areas of Interest:** Focused on states with high pollution and significant climatic variability.
- **Analyze Correlations:** Explored relationships between AQI, key pollutants, and weather data.
- **Heatwaves Analysis:** Examined the correlation between heatwaves, temperature spikes, and AQI.
- **Seasonal and Urban-Rural Analysis:** Studied AQI trends across different seasons and between urban and rural areas.
- **Implications for Insurance:** Provided recommendations for risk assessment and policy adjustments.

## Data Sources
- **EPA:** U.S. Environmental Protection Agency data for air quality and weather parameters. Historical data collected over 20 years, including pollutants like PM2.5, PM10, NO2, CO, SO2, O3, and weather parameters such as temperature and pressure.

## Installation and Requirements

### Prerequisites
- **Python 3.9:** Ensure Python 3.9+ is installed on your system.
- **Conda:** Conda package manager for environment management.
- **Git:** Version control system for cloning repositories.
- **Jupyter:** For running Jupyter notebooks, ensure Jupyter is installed.
- **Pandas, NumPy, Matplotlib, Seaborn:** Python libraries for data analysis and visualization.
- **Operating System:** Run on Windows.
- **Power BI:** Required for viewing and interacting with Power BI visualizations.

### Dependencies
To replicate the environment used in this project, follow these steps:

1. **Download the environment file:** [environment.yml](environment.yml)
2. **Create and activate the environment:**
    ```sh
    conda env create --file environment.yml
    conda activate aqi_project_env
    ```
3. **Install additional packages:**
    ```sh
    pip install pandas seaborn matplotlib
    ```

## Usage
1. **Clone the repository:**
    ```sh
    git clone git@github.com:alagogianni/Air-Quality-and-Weather-Analysis.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd Air-Quality-and-Weather-Analysis
    ```
3. **Run Jupyter Notebooks:** Start Jupyter Notebook or JupyterLab and open the notebooks located in the `Data_preprocessing`, `Data_merging`, and `Analysis` directories.

## Visualizations
Here are some key visualizations from the project:

- **AQI and Heatwaves:** ![AQI and Heatwaves](https://github.com/alagogianni/Air-Quality-and-Weather-Analysis/blob/main/Visualizations/AQI%20and%20Heatwaves.png)
- **Monthly and Seasonal AQI trends:** ![Monthly and Seasonal AQI trends](https://github.com/alagogianni/Air-Quality-and-Weather-Analysis/blob/main/Visualizations/Monthly%20and%20Seasonal%20AQI%20trends.png)
- **AQI in Urban vs Rural Areas:** ![AQI in Urban vs Rural Areas](https://github.com/alagogianni/Air-Quality-and-Weather-Analysis/blob/main/Visualizations/AQI%20%26%20Urban%20and%20Rural%20Areas.png)
- **Urban and Rural Key Pollutants:** ![Urban and Rural Key Pollutants](https://github.com/alagogianni/Air-Quality-and-Weather-Analysis/blob/main/Visualizations/Urban%20and%20Rural%20Key%20Pollutants.png)

## Results and Findings
Key insights from the analysis include:
- **States of Focus:** Utah, California, Maryland, Arizona, Mississippi.
- **California Hotspots:** San Bernardino, Riverside, Tulare, Kern, Fresno.
- **Temperature Effects:** High temperatures and heatwaves significantly impact AQI.
- **Key Pollutants:** O3, PM2.5, and PM10 are major contributors to poor air quality.
- **Seasonal Variations:** AQI trends show higher pollution in summer months; urban areas experience different patterns compared to rural areas.

## Challenges and Limitations
- **Outliers:** Some weather data had outliers, requiring cleaning.
- **Urban and Rural Areas Definition:** Distinguishing between rural and urban areas in California can be done using several approaches, each with its advantages and limitations.
- **Heatwave Definitions:** Varying definitions of heatwaves across counties.

## Future Work
- **Expand Analysis:** Extend to other highly polluted states (Utah) and explore other factors that affect AQI variations across counties (costal vs inland areas).
- **Machine Learning Models:** Predict future AQI trends based on climate data.
- **Integration with Insurance Data:** Incorporate health and insurance claims data for more accurate risk models.

## Project Presentation
- This is our [Air Quality and Climate Dynamics in California](https://github.com/alagogianni/Air-Quality-and-Weather-Analysis/blob/main/Presentation/Air%20Quality%20and%20Climate%20Dynamics%20in%20California_Critical%20Facts%20for%20Insurance%20Focus%20Areas.pdf) presentation.

## BI Dashboard
- This is our [PowerBI dashboard]()

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/alagogianni/Air-Quality-and-Weather-Analysis/blob/main/LICENSE) file for details.

## Acknowledgements
- Thanks to the **EPA** for providing the air quality data.
- Special thanks to the **Big Blue Data Academy** for guidance and mentorship.
  
## Contact
* Feel free to contact our team with any questions! 
