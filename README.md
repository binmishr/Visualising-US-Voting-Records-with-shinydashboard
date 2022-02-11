# Visualising-US-Voting-Records-with-shinydashboard

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

Adavis Package - A Brief Introduction
======================================

A visual exploration of the Americans for Democratic Action (ADA) Voting Scores. 

Description
============
        Utilizes about 36,000 US legislator voting scores originally collected by the Americans for Democratic Action (ADA) foundation between 1947 and 2015
        "[Annual voting records] served as the standard measure of political liberalism. Combining 20 key votes on a wide range of social and economic issues, both domestic and international, the Liberal Quotient (LQ) provides a basic overall picture of an elected official's political position"
        Actual data compiled by Justin Briggs Blog post | .xlsx file
        Uses both nominal and adjusted ADA scores Procedure
        Data can be grouped by year, state, chamber, and party
        Data visualizations using statebins, plotly, ggExtra and base R

Features
==========
State of the Union

    Charts a single Year > Chamber > Party combination on a first-level political (administrative) division map displaying either nominal or adjusted LQ score (averaged by state):
![image](https://user-images.githubusercontent.com/26252963/149285338-f63bd2d1-3cf4-4e04-904a-8f80a36ec53b.png)


Change from Last Year

    Plots LQ score change from previous year (state-level). Hover info offers the precise amount in percentages:
![image](https://user-images.githubusercontent.com/26252963/149285458-ae769f4e-2109-44de-baaa-c2f031973e86.png)

Head-to-Head

    Allows the user to select two states and compare their voting scores in a specified timeframe. Works under the C/P constraint; i.e. it compares representatives from the same party/chamber:
![image](https://user-images.githubusercontent.com/26252963/149285514-20e2dd3a-8607-4ddc-b3b1-2ed956f07886.png)

Representatives

    Enables looking up specific representatives (3,371 in total) found in the dataset; offers descriptives on Year, Congress, District and plots their LQ scores, mean, and plus/minus one standard deviation:
![image](https://user-images.githubusercontent.com/26252963/149285594-0e3c8994-f5cf-4d01-a0b5-dc397382ed35.png)

Design

    Users can change viridis colour palettes (viridis, plasma, inferno, and magma) and direction (whether higher values are light or dark) throughout the app:

![image](https://user-images.githubusercontent.com/26252963/149285632-580662ed-e537-4144-8c5f-6a3ca0eb522c.png)


