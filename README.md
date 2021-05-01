<p align="center">  
   <h1 align="center">🚴‍♂️ Sydney Cyclability Analysis 🚴‍♂️</h1>
   <h5 align="center">DATA3406 ASSIGNMENT 2</h5>
</p>

Aim :mag_right:
----------------
To calculate a cyclability score for different neighbourhoods in Sydney. 

**What is a Cyclability score?**

Its a score that we define to assess how well a neighbourhood caters to cyclists. 

To calculate cyclability per neighbourhood, a formula was used that took all data sources with relevance to cyclability into consideration. The formula is as follows:

cyclability = z(population density)+ z(dwelling density)+ z(service balance)+ z(bikepod density)+ z(BikeParking)

Where z is z-score or "standard score" of a measure, which can be calculated using z(measure, x) = x − avg measure / stddev measure

Table of contents :clipboard:
------------------
1. [Analysis Code](data_and_analysis/analysis.ipynb)
2. [Final Report](Report.ipynb)
3. [Raw Data](data_and_analysis)


Overview of Schema
-------------------

<p align="center">
<img src="/imgs/schema.png" alt="schema.PNG" width="700"/>
</p>


Getting Started :file_folder:
--------------
**Short list of intructions for new collaborators to get up and running with the project.**

List of commands:

- `$ git clone https://github.com/abdullahsafi/Sydney_Cyclability_Analysis.git`
- `$ cd Sydney_Cyclability_Analysis`
- Here you can access the Source Code and Report in Jupter Notebooks.
- The Product Notebook can be opened through Google Colab:
   - Ensure you upload your copy of the repo onto your google drive
   - There is a path variable for you to link the data
- The Product Notebook can be opened through Jupyter Notebooks (recommened):
   - Ensure that modules and dependancies are downloaded

Data Origin and Summary :floppy_disk:
------------

**Origin of data**

Several CSV files with Statistical Area 2 (SA2) data from the Australian Bureau of Statistics (ABS), as well as some car-sharing data from Sydney.

populationdensitypopulation divided by neighbourhood’s land areaNeighbourhoods.csvdwellingdensitynumber of dwellings divided by neighbourhood land areaNeighbourhoods.csvservicebalancebalanceof selected business types in neighbourhoodBusinessStats.csvtransportdensitynumber of car-sharing pods per suburb divided by areaCarSharingPods.csv

Key Variables
---------
**Description of variables that are important throughout the Notebooks.**

| Key Variables | Description | 
|--------------|----------------|
| populationdensity          | population divided by neighbourhood’s land area |
| dwellingdensity           | number of dwellings divided by neighbourhood land area|
| servicebalance     | balance of selected business types in neighbourhood |
| transportdensity     | number of car-sharing pods per suburb divided by area |
