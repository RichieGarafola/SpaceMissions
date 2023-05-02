# Space Missions Analysis
This repository contains an analysis of a dataset containing information about space missions. The dataset includes information about space missions from 1957 to 2020. Including the mission name, the date of launch, the rocket company, and the mission status.

![](./Images/astro.jpg)
---

##  Introduction

The field of space exploration has been an area of great interest and innovation for decades. With each new mission, we learn more about the universe and our place in it. The Space Race of the mid-20th century between the United States and the Soviet Union spurred some of the greatest advancements in space exploration, including the first manned missions and the first moon landing. Since then, numerous countries and private companies have entered the field, with the goal of expanding our knowledge of the universe and, in some cases, commercializing space travel.

In this project, we will be analyzing a dataset of space missions to gain insights into the trends and patterns in space exploration. We will be using Python and various data analysis libraries, such as Pandas and Matplotlib, to clean and manipulate the data and generate visualizations to aid in our analysis. Some of the questions we will be exploring include the success rate of rocket launches for different companies, the number of space missions launched each year, and the most common types of missions for each company. Through this analysis, we hope to gain a deeper understanding of the history and current state of space exploration.

---

## About the data

**Company** - Company responsible for the space mission

**Location** - Location of the launch

**Date** - Date of the launch

**Time** - Time of the launch (UTC)

**Rocket** - Name of the rocket used for the mission

**Mission** - Name of the space mission (or missions)

**RocketStatus** - Status of the rocket as of August 2022 (Active or Inactive)

**Price** - Cost of the rocket in millions of US dollars

**MissionStatus** - Status of the mission (Success, Failure, Partial Failure, Prelaunch Failure)

---

## Installation
To run the analysis, you need to have Python 3 and the following libraries installed:

    pandas
    matplotlib
    seaborn

---

## Data Cleaning
Before performing any analysis, the data was cleaned by:

- Converting the date column to a datetime data type.

- Removing the commas from the price column.

- Converting the price column to a numeric data type.

- Dropping the entire price column because the majority of the data is missing.

- Dropping rows with missing values.

- Dropping duplicated rows.

---

## Analysis
The analysis includes the following:

- Analyzing the success rate of rocket launches for different companies.

- Plotting the number of missions by year to see how the frequency of space launches has changed over time.

- Counting the number of missions by year and computing the year with the most and the least amount of missions to date.

- Counting the number of successful and failed missions and computing the success and failure rates.

- Creating a pie chart to visualize the distribution of mission statuses.

- Calculating the most common mission types for each company.

- Analyzing the success rate of missions by company.

---

## Conclusion
The analysis provides insights into the success rate of rocket launches for different companies and the number of space missions over time. It also highlights the most common mission types for each company and the success rate of missions by company. The analysis can be used to inform decision-making related to space exploration and investment in space-related industries.

---

## Images

![](./Images/DistributionMissionStatuses.png)

![](./Images/MisionPricesByCompany.png)

![](./Images/MissionsByCompany.png)

![](./Images/MissionsPerCompany.png)

![](./Images/MissionStatusesProportionByCompany.png)

![](./Images/MissionStatusLaunchDate.png)

![](./Images/NASAMissionSuccess.png)

![](./Images/SpaceMissionsByYear.png)

![](./Images/SpaceXMissions.png)

![](./Images/SuccessfulAndFailedMissionsCompany.png)

![](./Images/SuccessRateYear.png)

![](./Images/TopSuccessfulMissionsByCompany.png)
