# RobinJangam-Airline-Demand-Seasonal-Trend-Analysis

# Basic Airline Passenger Trend Analysis (2022)

This project performs a basic exploratory data analysis of an airline passenger dataset limited to the year 2022. The goal is to understand fundamental patterns in passenger traffic and flight characteristics within this specific year.

**Dataset:**

The analysis is based on the provided "Airline Dataset.csv" file, which contains information about individual airline passengers and their flights in 2022.

**Analysis Performed:**

The project includes the following steps:

1.  **Data Loading and Cleaning:** The raw CSV data is loaded using pandas, and basic data cleaning is performed to handle missing values and ensure appropriate data types (e.g., converting 'Age' to numeric and 'Departure Date' to datetime).
2.  **Key Data Summaries:** Provides an overview of the dataset's structure, data types, descriptive statistics, and missing values.
3.  **Monthly Passenger Trends:** Analyzes and visualizes the total number of passengers for each month in 2022 using a line plot. Identifies the peak and off-peak months based on passenger volume within the year.
4.  **Passenger Trends by Day of Week:** Analyzes and visualizes passenger counts for each day of the week using a bar plot to identify weekly patterns.
5.  **Flight Status Distribution by Month:** Uses a stacked bar chart to show the distribution of flight statuses (e.g., on time, cancelled, delayed) across each month of 2022.
6.  **Distribution of Top Airports:** Visualizes the top 20 airports by the number of flights using a bar plot.
7.  **Distribution of Top Countries:** Visualizes the top 15 countries by the number of flights using a bar plot.
8.  **Age Distribution by Flight Status:** Uses a box plot to explore the distribution of passenger ages for different flight statuses.

**Key Findings (Based on 2022 Data):**

*   Monthly passenger volume shows variations throughout the year, with specific peak and off-peak months identified within 2022.
*   Passenger counts also exhibit patterns based on the day of the week.
*   The distribution of flight statuses can be observed monthly, providing insights into operational consistency.
*   The analysis highlights the busiest airports and countries represented in the dataset.
*   Preliminary exploration suggests potential differences in age distribution based on flight status.

**Limitations:**

It's important to note that this analysis is based on data from a single year (2022). Drawing robust conclusions about long-term seasonal trends or predicting future demand would require data spanning multiple years.

**How to Run the Code:**

1.  Upload the `Airline Dataset.csv` file to your Google Colab environment.
2.  Open the `[Your_Notebook_Name].ipynb` file in Google Colab.
3.  Run the code cells sequentially.

**Technologies Used:**

*   Python
*   pandas
*   matplotlib
*   seaborn
*   Google Colab

---
