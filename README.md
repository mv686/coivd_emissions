# Air Emissions Analysis around COVID-19 Dates

## Requirements

- Python 3.8.6 (the project was developed and tested with this version)
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

## Installation

This project was developed and thoroughly tested using Python 3.8.6. While it is designed to work with this version, there's a good chance it will also be compatible with other Python 3.x versions. You can download it from the [official Python website](https://www.python.org/downloads/). 

To install the required libraries, run the following command in your terminal or command prompt:

```bash
pip install jupyter pandas matplotlib seaborn
```

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/mv686/coivd_emissions.git
    ```
2. Navigate to the project directory

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
    ```

4. Open the covid_emissions.ipynb notebook in your browser.

5. Follow the instructions in the notebook to execute the code cells and visualize the data.

## Introduction

Climate change, primarily caused by the burning of fossil fuels such as oil, gas, and coal, poses a significant threat to our planet. The release of carbon dioxide (CO2) into the atmosphere from these activities contributes to global warming. The COVID-19 pandemic, leading to shifts in work patterns and reduced travel, offers a unique opportunity to study the impact of these changes on global emissions. This project aims to analyze data related to global CO2 emissions and other polluting gases to understand the variations in emissions before and after the pandemic.

## Data Sources

The project utilizes data from [ourworldindata.org](https://ourworldindata.org/), a reputable source providing information on CO2 emissions, greenhouse gases, population, energy consumption, and other calculated values for major countries spanning over 100 years. Additionally, an emission by sector dataset from the same source is used to analyze CO2 emission distribution trends. While these datasets contain valuable information, dealing with missing values and dataset cleaning was essential for accurate analysis.

## Conclusion

### Achievements

- **Global Decline:** The pandemic led to a noticeable global decline in CO2 emissions and energy usage, primarily due to altered work patterns and reduced travel.
  
- **Correlation:** A strong correlation between CO2 emissions and energy consumption emphasizes the importance of addressing both factors in combating pollution.

- **Regional Variations:** Different countries exhibited diverse patterns, highlighting the need for tailored interventions. While some nations, like Germany, showed promising progress, others, including China and Qatar, faced challenges in emission reduction.

### Limitations

- **Data Availability:** Access to comprehensive and detailed datasets, especially for specific sectors, remains a challenge. Many datasets contain missing values, requiring thorough filtering and cleaning.

### Future Work

- **Localized Studies:** Future research should focus on detailed investigations into individual countries, regions, and cities to identify localized factors contributing to emissions.

- **Commuting Patterns:** Exploring the impact of changes in commuting patterns, including various modes of transport, during the pandemic period can provide valuable insights.

By understanding these patterns and challenges, further efforts can be directed towards mitigating the impact of human activities on the environment and slowing down the progression of climate change.
