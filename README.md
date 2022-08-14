# Employment in California: An analysis on the trends of employment and wages

### Meet the team
<hr/>
<ol>
<li>Neha Bhagavandas</li>
<li>Raunak Dua</li>
<li>Himanshu Mann</li>
<li>Vaibhav Singh</li>
</ol>

### Introduction
<hr/>

<p>The goal of this project is to analyze the trends of employment across various ownerships and their relative wages From 2004 till Sept 2021 for California-Statewide, County, U.S. The subject of this analysis is two datasets. The first is quarterly employment data for the state of California, USA only. This data is provided quarterly by the U.S. Department of Labor’s Bureau of Labor Statistics. Whereas the second dataset is from Current Employment Statistics provided by EDD - Labor Market Information Division</p>

> The Quarterly Census of Employment and Wages (QCEW) Program is a Federal-State cooperative program between the U.S. Department of Labor’s Bureau of Labor Statistics (BLS) and the California EDD’s Labor Market Information Division (LMID). The QCEW program produces a comprehensive tabulation of employment and wage information for workers covered by California Unemployment Insurance (UI) laws and Federal workers covered by the Unemployment Compensation for Federal Employees (UCFE) program.
>
> -- <cite>Quarterly Census of Employment and Wages</cite>

> Current Employment by Industry (CES) data reflect jobs by "place of work." It does not include the self-employed, unpaid family workers, and private household employees. Jobs located in the county or the metropolitan area that pay wages and salaries are counted although workers may live outside the area. Jobs are counted regardless of the number of hours worked. 
>
> -- <cite>Current Employment by Industry</cite>
>

### Data sources
<hr/>

The data of this study can be found at [State of California, Employment Development Department](https://data.edd.ca.gov/Industry-Information-/Quarterly-Census-of-Employment-and-Wages-QCEW-/fisq-v939) website.

Whereas the second dataset can be found at [California open data portal](https://data.ca.gov/dataset/current-employment-statistics-ces) website.

The dataset files for this study are CSV files which can be downloaded from below links <br/>
Dataset 1:  [Quarterly Census of Employment and Wages (QCEW)](https://data.edd.ca.gov/api/views/fisq-v939/rows.csv?accessType=DOWNLOAD)<br/>
Dataset 2: [Current Employment Statistics (CES)](https://data.edd.ca.gov/api/views/r4zm-kdcg/rows.csv?accessType=DOWNLOAD)


### Methods used
<hr/>

<p>For analysis purpose we are using the</p>
<ol>
<li>Linear Regression</li>
<li>Kmeans Clustering</li>
<li>Plotting</li>
<li>T statistical tests</li>
</ol>

### How to run?
<hr/>

Download the Jupyters [Notebook](https://github.com/MQCOMP2200-S2-2021/group-project-group-17/blob/main/DSGroupProject_Group_17.ipynb) file. Then place the two CSV files which can be downloaded under **Data Sources** section and put them inside a 'files' directory and run the cells to execute the project.