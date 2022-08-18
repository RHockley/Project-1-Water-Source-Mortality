# Project-1-Water-Source-Mortality
Files for project 1 dealing with water availability and mortality

This repository was created for the use of Robbie, Danny, and Vanessa to collaborate in creating a study of deaths related to diarrohea and a country's wealth between the years 2015-2019. This is project 1 for the Data Analytics bootcamp created by Trilogy Education through the University of Western Australia.

Data was downloaded in csv format from https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?locations=G8 and https://ourworldindata.org/diarrheal-diseases for country GDP per capita and diarrheal deaths respectively. There was some data cleaning needed in excel to remove unnecessary columns and find the mean of the country's GDP per capita over the target years.

Below is an image that shows a heatmap of the total deaths per country in 2019 that are attributed to diarrohea. The markers deonte the top 5 and bottom 5 countries based on average GDP per capita over the years 2015-2019. The data included world regions which needed to be excluded.

<img width="1080" alt="Heat_map_with_markers" src="https://user-images.githubusercontent.com/66938245/185377895-c4ad166e-8f8b-4977-ae62-c8c91ff0831b.png">

The data was further cleaned and manipulated using jupyter notebooks to create images to further prove that a country's wealth has a direct influence over the number fo deaths related to unsafe water sources.

The line graph below clearly shows that a stark difference between the top 5 and bottom 5 GDP per capita countries in terms of diarrheal deaths between 2015-2019

<img width="537" alt="top_and_bottom_GDP_totals" src="https://user-images.githubusercontent.com/66938245/185379947-52ea8fcc-aece-4901-9349-7e68eb953adc.png">

This histogram of total deaths during 2015-2019 due to unsafe water sanitation across all countries shows a highly left-skewed plot. There are very few occasions where the total deaths is above 500,000.

![unsafe_sanit](https://user-images.githubusercontent.com/66938245/185379861-95e0e337-a60f-446e-8bab-abb780bb589c.png)

Below is a scatterplot that clearly shows the higher nuber of deaths comes solely from the countries with a lower GDP per capita.

![unsafe_watervGDPreg](https://user-images.githubusercontent.com/66938245/185379762-b172ab42-f4e1-486c-abed-7bb205161fb0.png)

From the analysis, even though it is normally thought to be obvious, there is a clear distinction between the richer and poorer countries in terms of deaths related to diarrhoea caused by unsafe water sources.

Robbie Hockley, Danny Bruzzese, Vanessa Kemp. 2022




