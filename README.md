# The Developmental Divide: Why is Burundi Lagging Behind Rwanda?

## Table of Contents
- [Project Overview](#project-overview)
- [Motivation and Objectives](#motivation-and-objectives)
- [Data Sources and Timeline](#data-sources-and-timeline)
- [Tools](#tools)
- [Steps Taken / Project Workflow](#steps-taken--project-workflow)
  - [Data Cleaning](#data-cleaning)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Correlation Analysis](#correlation-analysis)
  - [Data Visualization](#data-visualization)
- [Insights and Recommendations](#insights-and-recommendations)
  - [Key Findings](#key-findings)
  - [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Impact and Future Plans](#impact-and-future-plans)
- [References](#references)
- [Contact Information](#contact-information)

## Project Overview

This project looks at the economic, educational, and political factors that cause Burundi to lag behind Rwanda. Using data analysis, we aim to identify key challenges and provide clear recommendations for improving development in Burundi. Our goal is to help create positive changes that can enhance the quality of life for the people in Burundi.


## Motivation and Objectives

As a Burundian who has lived and studied in my country for many years, I have always wondered why Rwanda is growing faster than Burundi. This project aims to understand the key factors behind this difference. By looking at economic, educational, and political aspects, I hope to find insights that can help improve development in Burundi, create a better future for its people, and be part of the change-makers driving positive change.

![gdp comparison](https://github.com/user-attachments/assets/6fc12519-b854-45a2-b0ad-fa2035c0a371)

### Objectives
- **Economic Development Comparison:** Compare economic growth and performance metrics between Burundi and Rwanda.
- **Feature Correlations:** Perform a correlation analysis between different indicators against GDP growth rate.
- **Unemployment Analysis:** Examine the unemployment levels in each country and the causes.
- **Educational Analysis:** Examine educational outcomes, literacy rates, and the impact of education on economic growth.
- **Political Analysis:** Assess the impact of political stability on economic performance and growth.
- **Foreign Direct Investment (FDI) Analysis:** Evaluate FDI inflows and their relationship with economic growth in both countries.

## Data Sources and Timeline
**World Bank Database:** Accessed economic and educational indicators from the World Bank's comprehensive database. The data timeline spans from 2010 to 2022, ensuring a detailed analysis of trends over time. The link to the World Bank database is as follows: [World Bank Database](https://www.worldbank.org).

## Tools
- **Excel** for data organization.
- **Python** for data analysis (using libraries like Pandas, Numpy, Plotly, Seaborn, and Matplotlib).

## Steps Taken / Project Workflow
### Data Cleaning
- **Gathering Data:** Collected relevant datasets from various sources, ensuring the information was up-to-date and accurate.
- **Merging Data:** Combined multiple datasets into a single cohesive dataset to facilitate comprehensive analysis.
- **Restructuring Data:** Organized the dataset by creating appropriate columns and rows to improve usability and clarity.
- **Handling Missing Values:** Addressed gaps in the data through techniques such as imputation or removal, ensuring the dataset remained reliable.
- **Standardizing Formats:** Ensured consistency in data formats (e.g., date formats, currency) for ease of analysis.

### Exploratory Data Analysis
- Conducted initial analysis to understand the structure and characteristics of the dataset.
- Generated **summary statistics** (mean, median, mode, standard deviation) for key indicators.
- Created initial visualizations to identify patterns, trends, and outliers in the data.
- Explored relationships between different variables and their distributions.

### Correlation Analysis
- Analyzed relationships between various indicators, focusing on their **correlation with GDP growth rates**.
- Employed the **correlation matrix** to calculate and visualize correlations between different variables.
- Identified significant trends and relationships to support insights about economic performance.
- Documented findings to highlight key correlations and their implications for Burundi and Rwanda.
  
![correlation](https://github.com/user-attachments/assets/f5e0e55b-5461-4c6a-8c38-8cae7297a270)

### Data Visualization
- Developed visual representations of the data using tools like **Plotly**, **Seaborn**, and **Matplotlib**.
- Created charts and graphs (e.g., bar charts, scatter plots, heatmaps) to effectively communicate insights.
- Designed **interactive visualizations** to allow deeper exploration of the data.
- Included visual aids in the final report to enhance understanding and support key findings.

## Insights and Recommendations
### Key Findings
- **Economic Performance:** Rwanda has strong GDP growth and foreign direct investment (FDI), backed by a diverse economy and good governance. In contrast, Burundi faces challenges that slow its economic progress. **Burundi relies heavily on agriculture, with 85.1% of its workforce in this sector, while only 56% of Rwandans work in agriculture.** This heavy dependence on farming limits Burundi's economic diversity and growth potential.

![Employment distribution](https://github.com/user-attachments/assets/11c6c918-bfef-4226-bf35-20d299910ee9)

- **Government Spending on Education:** From 2010 to 2022, Burundi spent an average of **$147.34 million** on education each year, while Rwanda spent **$366.32 million** on average during the same period.

- **Investment and Growth Metrics:** Rwanda has a much higher average FDI of **$250.31 million** and a stronger average GDP growth rate of **6.71%**, compared to Burundi's lower average FDI of **$22.06 million** and GDP growth of **2.11%**. Furthermore, Rwanda’s maximum FDI is **$398.60 million**, highlighting its ability to attract foreign investment, which likely supports its higher GDP growth.

- **Educational Disparities:** Rwanda’s well-developed education system is linked to its economic growth, while Burundi struggles with low literacy rates and educational achievements, especially among those working in agriculture.

- **Political Stability:** Rwanda demonstrates better governance, with improvements in political stability and the rule of law shifting from negative to positive values on a scale of **-2.5 to 2.5** over the years. In contrast, Burundi has consistently negative political indicators, remaining below zero on this scale from 2010 to 2022, reflecting ongoing challenges with political instability. This instability hinders investment and sustainable growth opportunities, contributing to economic stagnation in Burundi.

![political stability](https://github.com/user-attachments/assets/f63e263b-9981-45c0-b025-a04aa8612c71)

- **Opportunities for Growth:** Identifying key areas for improvement—such as diversifying the economy, reforming education, and enhancing governance—can help Burundi improve its economic future and the overall quality of life for its people.

### Recommendations
- **Economic Diversification:**
    - Establish an **Agricultural Transformation Agency** similar to Ethiopia’s to modernize agriculture, focusing on high-potential sectors like coffee and tea production.
    - Promote **digital literacy programs** to prepare the workforce for emerging job markets and support innovation hubs to encourage entrepreneurship among youth.
    - **Promote tourism** as a means to diversify the economy, leveraging Burundi's natural beauty and cultural heritage to attract visitors and boost local businesses.

- **Strengthen Governance and Political Stability:**
    - Create independent bodies, such as an **anti-corruption commission**, to enhance transparency and accountability in government operations.
    - Implement **strict laws against corruption** and ensure regular audits of public finances to build trust in government institutions.
      
- **Enhance Education and Skill Development:**
    - Increase investment in **vocational training programs** to equip individuals with skills relevant to the job market, particularly in technology and trades.
    - Expand access to higher education and create incentives for teacher training to improve the quality of education across all levels.
    - Create programs to increase digital literacy at all educational levels to prepare the workforce for a technology-driven economy.


## Limitations
Data was gathered directly from the World Bank, which is a reliable source; however, challenges related to data availability and quality posed limitations in the analysis. Specifically, the World Bank provides estimates, and data beyond 2022 is not available. Additionally, there were gaps in some education indicators, such as literacy rates and enrollment rates.

To address these limitations, I utilized the available data for the same years for both countries and supplemented the main datasets with different tables for the indicators that had missing data. For example, I only included the literacy rate from 2022. Future research should aim to gather more comprehensive datasets, especially for education indicators, and explore additional sources to enhance the depth and accuracy of the findings.

## Impact and Future Plans

The insights from this project aim to guide policymakers and stakeholders in Burundi, helping to shape initiatives that foster sustainable development. This work has opened my eyes to the many challenges that Burundi faces and has motivated me to be part of the change-makers in the country. I am confident that it will also inspire more Burundians and others to contribute to positive change.

To enhance my efforts, I will focus on building more skills and improving my networking. By connecting with like-minded individuals and organizations, I hope to strengthen the impact of our initiatives and drive positive change in Burundi.

This will enable me to collaborate with local and international organizations to implement the recommendations effectively and create an official **interactive dashboard** to monitor Burundi's progress in economic, political, and educational outcomes. I also plan to expand the project to include other factors, allowing for data-driven decision-making.

Moreover, I intend to establish **TechBridge Burundi**, a program focused on enhancing digital literacy among the youth. By providing the necessary skills and resources, we can empower the next generation and promote innovation, ultimately contributing to Burundi’s economic growth and improved quality of life.

![TechBridge_Burundi](https://github.com/user-attachments/assets/a36c56b3-aa4d-4294-bb55-9e66623aaa1e)

## References
- World Bank Database: [World Bank](https://www.worldbank.org)
- UNESCO
- Stack Overflow: A platform for developers to ask and answer questions on various programming topics.
- Pandas Documentation: Official documentation for the Pandas library, providing guidelines and examples for data manipulation. [Pandas Documentation](https://pandas.pydata.org/docs/)
- ChatGPT: An AI language model used for generating text and assisting with coding and data analysis queries.

## Contact Information
For inquiries or collaboration, please contact me at [satalisonn@gmail.com](mailto:satalisonn@gmail.com).

# THANK YOU 
