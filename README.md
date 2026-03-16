
# Istanbul Air Quality Analysis: District-Based Pollution Investigation to Support SDG 3 and SDG 11

## 1) Overview
This project investigates the air quality in various districts of Istanbul using data visualization and Exploratory Data Analysis (EDA) techniques. The study is a long-term AI project aiming to directly support **Sustainable Development Goal 3 (Good Health and Well-being)** by addressing health risks associated with air pollution, and **Sustainable Development Goal 11 (Sustainable Cities and Communities)** by promoting data-driven urban environmental management.

Our primary objective is to analyze the concentration of key air pollutants (PM10, PM2.5, NO2, etc.) across different districts of Istanbul and to determine spatial and temporal trends. By visualizing these patterns, we aim to uncover how local dynamics, such as traffic density or the presence of industry, can impact district-level air quality.

Through EDA techniques such as descriptive statistics and time series visualizations, this project will highlight critical risk zones, missing values, and pollution trends. These insights will demonstrate how the dataset supports the project's objectives and will assist local authorities in making data-driven decisions.

## 2) Background
Air quality is a critical factor affecting public health and urban sustainability. In a rapidly growing and densely populated metropolis like Istanbul, environmental challenges such as vehicle emissions, industrial production, and residential heating severely impact the air citizens breathe.

Traditional environmental monitoring systems generally provide raw data that is difficult for the public or local authorities to interpret effectively. To solve this problem, it is necessary to start by finding open-source or publicly available datasets that align with the project's objectives. By cleaning and analyzing this data, we can transform raw pollution metrics into actionable insights.

## 3) Key Objectives / Business Objectives

### a) Research Questions:
* What is the overall distribution of air pollutants across Istanbul districts?
* Which districts consistently record the highest and lowest levels of air pollution?
* Are there observable seasonal or monthly trends in air quality deterioration?
* How do different pollutants in the dataset (e.g., PM10 and NO2, or PM2.5 and NO2) correlate with each other?

### b) Key Steps:
* Identify and collect open-source datasets containing air quality metrics for Istanbul districts, suitable for AI-based analysis.
* Clean and preprocess the dataset.
* Apply descriptive statistics to visualize underlying trends and identify missing values or patterns.
* Provide insights into how the dataset supports the project's goals.

## 4) Methods and Workflow

### a) Datasets
To conduct our analysis in this project, we used current air quality data for Istanbul districts obtained from the Air Quality Data Bank provided by the National Air Quality Monitoring Network (UHKİA) of the Ministry of Environment, Urbanization and Climate Change.

### b) Data Cleaning and Preprocessing
To focus on the project's scope, the dataset was first filtered to isolate only specific Istanbul districts. Subsequently, the collected air quality values were converted into numerical formats suitable for analysis, and inconsistent entries in the data were cleaned. Date and time formats were standardized to conduct an accurate temporal analysis. Finally, rows where values for our target feature (PM2.5) were missing were completely removed from the dataset, and other null values that could cause issues during analysis were cleaned, making the dataset ready for Exploratory Data Analysis (EDA).

### c) Exploratory Data Analysis (EDA)
The analysis process began by calculating the basic statistical metrics of pollutants on a per-district basis on the cleaned dataset. Various visualizations, such as time series graphs, were utilized to observe daily and seasonal fluctuations in pollution levels. Additionally, by examining the relationships between different particulate matters and gases in the air (e.g., PM2.5 and NO2), patterns and correlations regarding the pollution profiles of the districts were identified.

### d) Deliverables
The main deliverables of the project include a structured Concept Note, prepared in PDF format in accordance with the specified guidelines, summarizing the project selection, dataset details, and the applied analysis. Additionally, a comprehensive presentation material that will convey the project's objectives, the rationale behind the dataset selection, the applied Exploratory Data Analysis (EDA) results, and key takeaways.

## Team Members
* Mehmetcan Yılmaz - 21061031
* Ibrahim Rzazade - 23061904
* Oğuzhan Ketenci - 20069703
* Zümra Buse Uyur - 21069607
