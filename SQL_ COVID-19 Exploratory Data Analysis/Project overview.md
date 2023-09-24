# SQL COVID-19 Exploratory Data Analysis

# 1. Aims, objectives and background

## 1.1 Description
In the wake of a global pandemic that reshaped our world, I embarked on a data-driven journey to understand the dynamics of COVID-19 infections and vaccinations across the globe, and in Mexico, my country. This project is a testament to the power of SQL in uncovering valuable insights from vast datasets.

## 1.2 Aims and Objectives
My analysis encompasses various critical metrics that shed light on the pandemic's progression over time based on the following questions:
- What is the percentage of deaths in relation each country's population?
- What percentage of the population was infected with the virus in each country?
- Which were the countries with the highest infection and death rates per capita?
- Which continents beared the heaviest COVID-19 burdens?

## 1.3 Methodology
I followed the following steps to understand how did the infection and mortality rates over COVID-19 evolved over time:
1. Downloading the data from Our World in Data [[1]](https://ourworldindata.org/coronavirus) and importing it into SQL.
2. Data Exploration.
3. Sharing findings and conclusion in the following Tableau dashboard [[2]](https://public.tableau.com/app/profile/alberto.mart.nez6422/viz/COVID-19DashboardLastUpdatedApril2023/Dashboard1).

## 1.4 Impact and Contribution
COVID-19 was not just a health crisis; it was a defining moment in our history. Analyzing its data was a matter of life and death, and it allowed us to comprehend the world's response to an unprecedented challenge. This project allowed me to gain a comprehensive understanding of the pandemic's trends, and I chose to share my insights to contribute to the broader discourse surrounding this critical issue. This project holds a personal connection as it aligns with my undergraduate thesis, where I studied how diplomatic authorities in Mexico navigated the global arena to secure vaccine access.

## 1.5 Limitations
The dataset I used for the project is publicly available in Our World in Data [[1]](https://ourworldindata.org/coronavirus). Since the data was downloaded from Our World in Data, it relies on the quality and accuracy of the source from which it was originally compiled. Additionally, I decided to take information up until May 5, 2023 because that is the date when the World Health Organization (WHO) director general, Dr Tedros Adhanom Ghebreyesus, downgraded COVID-19 from being a public health emergency of international concern (PHEIC) [[3]](https://www.who.int/news/item/05-05-2023-statement-on-the-fifteenth-meeting-of-the-international-health-regulations-(2005)-emergency-committee-regarding-the-coronavirus-disease-(covid-19)-pandemic). This means it does not include information after that date, this limitation could affect the analysis of recent trends of the virus.

## 1.6 Acknowledgements
I extend my gratitude to 'Alex the Analyst' for his invaluable guidance, which served as a cornerstone for this project. I drew inspiration from his video titled 'Data Analyst Portfolio Project | SQL Data Exploration | Project 1/4' [[4]](https://www.youtube.com/watch?v=qfyynHBFOsM&list=PLUaB-1hjhk8H48Pj32z4GZgGWyylqv85f&index=1&ab_channel=AlexTheAnalyst). I used his code as a foundation for my Data Analysis project. However, I have made considerable modifications and enhancements to tailor the analysis to my specific goals and requirements. While the initial code provided valuable insights, I have adapted it to suit the unique aspects of my project.

Additionally, credit is duly attributed to both datasets' source, Edouard Mathieu et al. (2020), which can be accessed on Our World in Data [[1]](https://ourworldindata.org/coronavirus).

## 1.7 References
[1] Mathieu, E., Ritchie, H., Rodés-Guirao, L., Appel, C., Giattino, C., Hasell, J., Macdonald, B., Dattani, S., Beltekian, D., Ortiz-Ospina, E. & Roser, M. (2020). Coronavirus Pandemic (COVID-19). *OurWorldInData.org*. https://ourworldindata.org/coronavirus

[2] Martinez-Garcia, A. (2023). COVID-19 Dashboard (Last Updated April 2023). *Tableau* [Dashboard]. https://public.tableau.com/app/profile/alberto.mart.nez6422/viz/COVID-19DashboardLastUpdatedApril2023/Dashboard1

[3] Statement on the fifteenth meeting of the IHR (2005) Emergency Committee on the COVID-19 pandemic. *World Health Organization* [Public statement]. https://www.who.int/news/item/05-05-2023-statement-on-the-fifteenth-meeting-of-the-international-health-regulations-(2005)-emergency-committee-regarding-the-coronavirus-disease-(covid-19)-pandemic

[4] Alex The Analyst. (2021, May 4th). Data Analyst Portfolio Project | SQL Data Exploration | Project 1/4 [Video]. *Youtube*. https://www.youtube.com/watch?v=qfyynHBFOsM&list=PLUaB-1hjhk8H48Pj32z4GZgGWyylqv85f&index=1&ab_channel=AlexTheAnalyst
