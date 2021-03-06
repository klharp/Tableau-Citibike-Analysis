# Tableau - CitiBike Analysis

## Project Overview

Used Tableau for data exploration and visualizations of CitiBike data. The final dashboard is saved in Tableau Public account here: https://public.tableau.com/views/KH_Citibike_final/Story1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

![Citi-Bikes](images/header.png)

Each month Citi Bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

For a manageable dataset, the following conditions were selected to compare 2019 and 2020 data:

  * Used the summer peak month of July to reflect peak season.
  * Removed gender of "unknown" to have male and female only.
  * Split the date/time into separate date and time columns.
  * Calculated age from birth year.

  Languages and libraries used:
* Python
* Pandas
* OS
* Datetime
* HTML
* CSS
* Bootstrap
* Tableau

---

## Tableau Story

The dashboards and story in Tableau provides:

* An introduction to the project

* Overall station and usage map.

* Details of station usage

* Top 25 starting stations.

* Top 25 ending stations.

* Demographics of users.

* Summary which includes the observations:

  1. The number of stations increased nearly 26% in July of 2020 compared to July of 2019.

  2. The reduction in overall use in July of 2020 compared to July of 2019 was 7.64%. Beginning assumption was that this change would be greater.

  3. In July of 2020 the popular stations shifted from the lower Manhatten area to those areas bordering the water and Central Park. This reflects that bike usage was more in  open areas, avoiding more densely populated areas. This pattern is both in the start and the stop stations.

  4. Both female and male customers increased during the pandemic. Possibly reflecting the issue of people (non-subscribers) wanting to get outside and active. Though, female riders remain relatively low compared to male.

  5. Male subscribers was the only decrease (by almost 23%) comparing July 2019 to July 2020. Possibly reflecting the reduction CitiBike usage to go to work and other activities that were reduced or eliminated due to the pandemic.

  6. Trip duration increase slightly comparing July 2019 and July 2020, while the trip distances had little change.

---


Along with the direct link to the Tableau file, resources for this project are in this repository and include:

* The Jupyter Notebooks used to manipulate the datasets.
* An index.html page that contains the embedded Tableau code.
* The final .twbx file was too big to put in this repository.
* The initial and final CSVs were too big to put in this repository.