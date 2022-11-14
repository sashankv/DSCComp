# Optum Data Science Competition

This is team H2Coder's repository for the Optum Data Science Competition. In this competition, we were asked to use the publicly avaiable County Health Rankings Dataset to determine the factors which contribute the most to preventable hospitalizations.

A pdf of our final presentation and analysis code is found under the presentation folder. The file presentation/correlation.ipynb includes our team's preprocessing of data, correlation analysis and visualizations.
 
### What we used for this Project
**Language**: Python (Jupiter Notebook)  
**Pandas**: An open source data analysis and manipulation library  
**Numpy**: Scientific computing library  
**Seaborn**: Data visualization library 

**presentation/requirements.txt** contains all the dependencies for our project.

### Data Files
For this competition we are using data from the publicly available [County Health Rankings Dataset]()
Our datasets are included in the data folder.

**2022 County Health Rankings Data.xlsx**: This is a data dictionary of all the health measures for 2022. It includes a rank list of multiple health and social factors for all US counties. It allows comparison within a state. It is very well formatted for rapid Exploratory Data Analysis [Click here to see the Documentation](https://www.countyhealthrankings.org/sites/default/files/media/document/DataDictionary_2022.pdf)

**chr_analytic_data2022.csv**: This data is similar to that above but it is in csv form. Furthermore it is in a raw formatting so data transformation will be needed. [Click here to see the Documentation](https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation#:~:text=2022%20CHR%20CSV/SAS%20Analytic%20Data%20Documentation)

**chr_trends_csv_2022.csv**: This data provides the trends in the health measures year over year across all counties. [Click here to see the Documentation](https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation#:~:text=2021%20CHR%20Trends%20Data%20Documentation)

For our analysis and visualization, we mainly used the **chr_analytic_data2022.csv** file.

### Miscellaneous  
**LICENSE**: We will be using the open source Apache 2.0 License for this competition. [Click here to learn more](https://choosealicense.com/licenses/apache-2.0/)
