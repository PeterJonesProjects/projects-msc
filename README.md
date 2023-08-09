# MSc Data Science Projects Outline
A collection of projects undertaken in MSc Data Science (Statistics).

7/8 projects completed with the masters still ongoing.

Each project below outlines the overall goal, project objective and methods used.

Due to concerns about potential plagiarism in future iterations of the course, I am unable to upload the code and folders for each project to my GitHub portfolio.

Four weeks total for a block. Each project was completed in parallel with another project during a single block, with a one-week learning period prior to beginning each project to understand the fundamentals behind the system or statistical process.

***

## Dissertation: Modelling Transfer Fees in Professional Football with an Emphasis on Bayesian Methods

| Content | Languages|Applications | Major Libraries |
|:----------------|:--------------:| -----------|----------|
|  **Project Goal:** Develop a transparent and equitable model for predicting football player transfer fees using Bayesian methods. <br><br> **Data:** Sources: TransferMarkt and Understat. Metrics Include: player_name, age, time_since_last_transfer, transfer_period, fee_cleaned, club_name, club_involved_name, league_name, general_position, mean_3yr_prev, mean_3yr_prev_sell, goals, shots, assists, xA, xG, key_passes, yellow, red, xGChain, xGBuildup, fee_cleaned_log. <br><br> **Objective:** To demystify the valuation of player transfers in professional football by leveraging the transparency of Bayesian approaches combined with the power to incorporate prior knowledge. <br><br> **Outcome:** <br> • The Bayesian approach was found to be effective in providing interpretability, handling uncertainty, and incorporating prior knowledge. <br> • Highlighted the significance of certain player metrics in relation to transfer fees. <br> • Identified data quality and external factors as potential challenges that need to be addressed for more accurate predictions. <br><br> **Theoretical:** <br> • Bayesian models offer an alternative to machine learning methods in sports analytics due to their transparent nature. <br> • The research emphasizes the importance of prior knowledge, transparency, and interpretability in the valuation of player transfers. | R <br> JAGS <br> css | Rstudio <br> Rmarkdown <br> Posit Cloud | rjags <br> conda <br> rticles <br> Posterdown |

***

## Bayesian Analysis of Cross Country Race Times: Predominantly Course Effects

| Content | Languages|Applications | Major Libraries |
|:----------------|:--------------:| -----------|----------|
|  __Project Goal:__ Utilise Bayesian methods to perform inference on data from a cross country racing league, in order to explain the variation in race times using other variables in the dataset.<br><br> __Data:__ Data concerning race times and other characteristics of the racers. ("NEHL Dataset").<br><br> __Objective:__ Use Markov chain Monte Carlo simulation to create statistical models for inference on the data, focusing on Bayesian methods.<br><br> __Outcome:__ Selection of the final statistical model, evaluated using diagnostics and reasoned comparison.<br><br> __Theoretical:__ Along with this project, 5 theoretical questions in Bayesian methodology were explored by implementing them both by hand and using Rjags. |R<br><br>JAGS|Rstudio<br><br>Rmarkdown | rjags<br><br>conda |

***

## Big Data Processing and Graph Analytics on NYC Taxi Rides Dataset

_The project involved analysing data from New York taxi trips, which were provided in both relational and graph formats. The tasks for each format were different, so they were approached separately._

### Scalable Data Engineering of NYC Taxi Rides Dataset with Spark

| Content | Languages|Applications | Major Libraries |
|:----------------|:--------------:| -----------|----------|
|  __Project Goal:__ To create a data processing pipeline using Spark on Microsoft Azure Databricks to engineer NYC taxi rides dataset and gain insights into the data.<br><br> __Data:__ NYC taxi rides dataset.<br><br> __Objective:__ To develop a scalable data processing pipeline in Spark using pyspark.api to explore the data, perform data cleaning and transformation, and extract insights.<br><br> __Outcome:__ Successful creation of a data processing pipeline using Spark on Azure Databricks, and insights gained into the NYC taxi rides dataset. Strong knowledge of parallel data processing, implicit parallelism, and scaling with input size gained. |Python |DataBricks <br><br> Apache spark | pyspark.api |

### Exploring Complex Relationships in NYC Taxi Rides Dataset with Neo4j

| Content | Languages|Applications | Major Libraries |
|:----------------|:--------------:| -----------|----------|
|  __Project Goal:__ To perform graph analytics on the NYC taxi rides dataset using Neo4j and Cypher query language.<br><br> __Data:__ NYC taxi rides dataset.<br><br> __Objective:__ To use Neo4j and Cypher query language to perform graph analytics on the dataset, including finding isolated nodes, computing the community cluster, centrality score, and finding the top centrality zones within each community.<br><br> __Outcome:__ Successful execution of different graph algorithms, such as the Louvain algorithm for community detection and Page Rank algorithm for centrality analysis, using the Neo4j Graph Data Science library. A deeper understanding of of complex dataset relationships and patterns was cemented. |Cypher Query Langauge |Neo4j  | Neo4j Graph Data Science library |
   
*** 


## Time Series Analysis & Forecasting of Monthly Product Sales
| Content | Languages|Applications | Major Libraries |
|:----------------|:--------------:| -----------|----------|
|  __Project goal:__ To analyse and forecast monthly sales data for a product over a period of ten years and identify the best statistical model for predicting future sales based on historical sales data.<br><br>__Data:__ Monthly sales data for a product over a period of ten years.<br><br>__Objective:__ To identify the most accurate statistical model for predicting future sales by fitting several models to the sales data, including ARIMA models, time series regression models, and dynamic linear models (DLMs), and evaluating the performance of these models using various error metrics.<br><br> __Outcome:__ Identification of the 'best' prediction model and using this to forecast the next 6 months of data. <br><br> __Theoretical:__ Two mathematical questions related to time series theory. These questions added an academic component to the project and allowed for a deeper understanding of the statistical models used in the analysis. | R |Rstudio <br><br>   Rmarkdown | bestglm<br><br>glmnet<br><br>MASS |
   
*** 


## Application of Learning Analytics to 'Massive Online Open Course' Data

 Content | Languages|Applications | Major Libraries 
:----------------|:--------------:| -----------|----------
|  __Project goal:__ Gain insights that could help course providers make improvements to the course content and delivery.<br><br>__Data:__ Cytological characteristics data from breast tissue samples.<br><br>__Objective:__ Utilise the **CRISP-DM** process to complete two cycles of data analysis, applying a wide range of skills learned from dplyr and ggplot2 to gain insights from the MOOC data set. Develop a comprehensive understanding of the data, analyse it, and derive insights that can improve the course content and delivery. Ensure that the project is reproducible by using Project Template and sharing the code and documentation.<br><br> __Outcome:__ A reprodcuible report providing strong insights into the MOOC dataset. | R |Rstudio <br><br> Rmarkdown | dlm|

   
*** 


## Classification of Breast Tissue Samples using Statistical Methods

| Content | Languages|Applications | Major Libraries |
|:----------------|:--------------:| -----------|----------|
|  __Project goal:__ Developing classifiers for predicting cancer presence in breast tissue samples using cytological characteristics data.<br><br>__Data:__ Cytological characteristics data from breast tissue samples.<br><br>__Objective:__ Building classifiers using statistical methods such as logistic regression and linear discriminant analysis (LDA) and evaluating their performance through cross-validation.<br><br> __Outcome:__ The project successfully developed classifiers to predict breast cancer presence using statistical methods, and demonstrated the effectiveness of these methods in identifying predictors of cancer presence. <br><br> __Theoretical:__ A mathemcatical question relating to logistic regression and linear discriminant analysis was also answered. | R |Rstudio <br><br>   Rmarkdown | bestglm<br><br>glmnet<br><br>MASS |


   
*** 


## Stock Management & Billing Application


| Content | Languages | Applications|Major Libraries|
| ---------------- |:----------------:|--------------|--------------|
|      __Project goal:__ An introduction to software engineering. Develop a user-friendly stock management system to efficiently manage inventory and produce receipts.<br><br>  __Data:__   The system reads in a CSV file of items and their details and converts it to a list.<br><br> __Features:__ Full user input, no need to run any code. Six functions available, including full stock list and creating receipts. Search function returns a list of matching items and their details. <br><br>__Programming practices:__ Emphasizes object orientation, unit testing, and exception handling. Clear code documentation and naming conventions. <br><br>__Outcome:__ An excellent tool for businesses to efficiently manage their inventory. Provides multiple functions to suit different inventory management needs. Well-designed and easy to modify/update inventory as needed.| Python |PyCharm |abc<br>Numpy<br>unittest<br>os
   
*** 

## Visualisation of Epidemic Data


| Content |  Applications|
|----------------|:--------------|
|   __Project goal:__ Visualizing the impact of an airborne disease outbreak through simulations.<br><br>__Data:__ Results from simulations of the outbreak area modeled as a grid of cells, including cell population, infected count, and uncertainty statistics.<br><br>__Objective:__ Creating interactive dashboards to visualize the uncertainty and impact of the outbreak for a single simulation and arbitrary number of simulations.<br><br> __Outcome:__ Effective visualization of the outbreak impact and uncertainty. Easily understandable for those not statistically literate.|PowerBI 

