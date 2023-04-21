# Top 10 CO2 Emitters Over 50 Years
This code will analyze the top 10 countries with the most CO2 emissions and their developments over 50 years (1971-2020).
I will be using the data from [*Our World in Data*](https://github.com/owid/co2-data) in order to complete this lab. I downloaded it from the link entitled owid-co2-data.csv on March 29, 2023.

## Requirements

I will be using the Colaboratory system, created by Google, to code with Python for this project. In it, I have imported the following softwares: Pandas, Numpy, Mathplotlib.Pyplot, Seaborn, and Missingno. Pandas is being used to effectively analyze, manipulate, and clean up data throughout the code. Numpy provides the code with multiple mathmatical operations to use on the data. Mathplotlib.Pyplot allows me to plot any data or equation and make changes to the plot's figure if necessary. Seaborn creates easily-readable graphs to assist with statistical analysis. Finally, Missingno is used to visualize the data to better check for its completeness.

## Data

The data used in this lab is from *Our World in Data*. It is a recording of all Greenhouse Gas and CO2 Emissions in the world, organized by country, continent, and world. It is updated regularly, as needed, and keeps a well-rounded collection of each country's contributon to harmful emissions in the atmosphere. It also organizes the emissions by their source. For example, CO2 is given generally, but also as CO2 per Capita, CO2 per GDP, etc.

I used [owid-co2-data.csv](https://raw.githubusercontent.com/owid/co2-data/master/owid-co2-data.csv) for the data analyzed in this lab. This [codebook](https://github.com/owid/co2-data/blob/master/owid-co2-codebook.csv), also linked in the lab, provides information about each category, complete with its title and description. I used this as a reference point to analyze what variables are measured continuously, as objects, etc.

## Data Processing

The software listed in the Requirements section were used to clean and process the data. The results of this new, streamlined depiction of *Our World in Data*'s csv, given by owid-co2-data.csv, is presented and analyzed in the lab, coded in [Colab](https://github.com/KianaLaBella/co2emissions/blob/main/Kiana%20LaBella%20MATH%202315%20Lab%201.ipynb).

The data in the owid-co2-data.csv file also needed cleaning before my analysis, as it contained data from the world, regions, countries, and continents. For the purpose of this lab, I needed to isolate the countries from the rest of the data. I did this by defining all of the non-country variables and removing them from the data (see the *Import and set up the data* section in the Colab notebook).

## Author

This lab was done by Kiana LaBella, a Civil Engineering student at Seattle University. She is also pursuing minors in Mathematics and Writing Studies. She hopes that the data analysis depicted in this repository will be useful for understanding how different countries contribute to excessive CO2 emissions in the atmosphere.

[LinkedIn](https://www.linkedin.com/in/kiana-labella)

## License

The data analysis in this lab is open access for all to use and reference, with credit to both the author and *Our World in Data* (see their license for more information on how to cite). 
