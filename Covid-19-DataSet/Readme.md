# Experiment 19 , 20 - Covid Data Analysis

## Introduction:

The emergence of the Coronavirus Disease 2019 (COVID-19), caused by the SARS-CoV-2 virus, precipitated one of the most significant public health crises in modern history. First identified in December 2019, the virus was declared a Global Pandemic by the World Health Organization (WHO) on March 11, 2020.

Beyond the immediate medical challenges, the pandemic triggered profound socio-economic disruptions, straining healthcare infrastructures and impacting global supply chains. As governments and health organizations worldwide struggled to contain the spread, the role of data-driven decision-making became paramount. Accurate tracking of infection rates, recovery statistics, and mortality data provided the essential foundation for public health policy and resource allocation.

## Libraries and Functions Used:

* **Python:** The core programming language for data manipulation.
* **Pandas & NumPy:** Utilized for data loading, cleaning, feature engineering, and statistical aggregation.
* **Plotly Express:** Employed for generating interactive, high-fidelity geospatial visualizations (choropleth maps).
* **GeoJSON:** Used to map geographical boundaries for regional state-level plotting in India.

## Dataset Overview

The dataset utilized for this COVID-19 analysis is a comprehensive collection of pandemic records sourced from the World Health Organization (WHO), spanning from early 2020 through May 2021.

The raw dataset contains 306,429 entries organized into 8 initial columns

<img width="1719" height="811" alt="image" src="https://github.com/user-attachments/assets/3a5cd4d6-7ed0-42c2-b7bb-5626d0690faa" />

## Methodologies and Functional Implementation

In the data analysis performed unique methodologies and functions were implemented as follows:

* Data Loading: Used functions from the pandas library to load over 3,00,000 entries and perform data preprocessing in them.

* Data Cleaning: The .drop() command was used to delete unwanted column such as SNo, Last Update to reduce the memory load

* Data Transformation: the pd.to_datetime function was used to convert string based data into temporal objects, which enables us to perform Time Series Analysis

* Heirarchial Aggregation: The .groupby() function was used in columns such as Country/Region or Province/State which allows us to perform statistical operations on such massive data


## Experiment - 19: Global Data Visualization


To evaluate the current state of the pandemic globally, the dataset was filtered to extract the latest available observation date using the max() function, which returned May 29, 2021.

### Geospatial Visualization

Using plotly.express, a choropleth map was generated of the world which shows a visual context with the intensity of color corresponding to the most and least affected countries.

<img width="1736" height="748" alt="image" src="https://github.com/user-attachments/assets/dd99e024-df8a-4a88-a308-8005b5090a88" />

According to the above graph the Top 10 affected countries were:

<img width="598" height="413" alt="image" src="https://github.com/user-attachments/assets/cb3e9edb-c599-493a-8674-7fa3ea5a2737" />

## Experiment - 20: India Specific COVID Data Analysis

In this Experiment the Data analysis was done for done for Indian Specific Data by creating a separate Data Frame of data entries having Country/Region as **India**. This localized analysis is particularly poignant, as May 2021 coincided with the peak of India's devastating "second wave" of infections.

The data revealed that cases were tracked across 38 distinct entities, encompassing all states and union territories. Grouping the data by Province/State for the latest observation date allowed us to see exactly where the virus was most concentrated.

<img width="1131" height="889" alt="image" src="https://github.com/user-attachments/assets/28fb0bfe-3e19-4f02-b674-1f2723e66774" />

The Top states or Provinces affected in India are:

<img width="439" height="419" alt="image" src="https://github.com/user-attachments/assets/fcd4ebad-f6cc-4d94-9d86-34d1770fcf2d" />

## Key Insights and Inferences:

* Maharashtra and some southern states had the nation's heaviest initial impact, where Maharashtra alone contributed over 20% of India's cases

* Despite high infection rates Kerala maintained significantly lower death rate when compared to regions like Delhi. This highlights their robust public health infrastructure

* Choropleth maps transformed abstract numbers into a visual blueprint of neighborhoods and borders in crisis. These visualizations allowed for real-time logistical planning, ensuring oxygen and vaccines reached the communities where they were needed most.

## Conclusion:

This project successfully demonstrates the end-to-end process of data analysis using Python. By cleaning, engineering, and visualizing the covid_19_data.csv dataset, we were able to quantify the massive scale of the pandemic up to May 2021. The global analysis confirmed the US, India, and Brazil as the epicenters of the outbreak. Furthermore, the localized mapping of India using GeoJSON boundaries provided a clear, data-driven picture of the regional crises unfolding across states like Maharashtra and Karnataka. Ultimately, this experiment underscores the vital role of data science in tracking, understanding, and communicating the realities of global public health emergencies.

