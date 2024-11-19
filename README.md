<h1> Evaluating Support for Cannabis Legalization: 2020 Referendum Analysis </h1>



<h2>Description</h2>

This project analyzes data from the 2020 Cannabis Referendum in New Zealand to help the Green Party determine if it is worth pursuing a citizen-initiated referendum in the next election cycle. 
A cannabis referendum is a public vote where people decide whether cannabis (marijuana) should be legalized or not. People voted either "Yes" (to legalize) or "No" (to keep it illegal).

#### Objectives
1. Identify the proportion of support for cannabis legalization within the sample.
2. Analyze demographic trends (age, gender, etc.) to understand who supported legalization.
3. Address missing data using basic imputation techniques, as a considerable amount of data was missing, especially from younger respondents.

<b> Refrendum: </b> The referendum was a way for the government to understand public opinion on the issue and decide whether to change the law based on the results.

<b> The Cannabis Legalisation and Control Bill:</b> This Bill was proposed in New Zealand to legalize and regulate recreational cannabis use. In the 2020 referendum, 50.7% of voters opposed the bill, resulting in its rejection. Consequently, recreational cannabis remains illegal in New Zealand. However, medicinal cannabis is legal under the Misuse of Drugs (Medicinal Cannabis) Amendment Act 2018, allowing access for patients with specific medical conditions. 

   



<br />

### Key Functions Used
- ggplot(): Creates plots using the ggplot2 package for data visualization.
- geom_histogram(): Adds a histogram layer to display the distribution of continuous data.
- facet_wrap(): Splits the plot into multiple smaller plots based on a categorical variable.
- mutate(): Creates or modifies columns in a dataset.
- recode(): Changes values in a column according to specified rules.
- summarize(): Calculates summary statistics such as mean, count, etc.
- filter(): Filters data based on specified conditions.
- complete(): Converts imputed datasets into a complete dataset after handling missing values.
- pool(): Combines results from multiple imputed datasets into one result.
- tidy(): Converts model outputs into a clean and readable format (data frame).
- kable(): Formats a data frame into a well-organized table for reports.

### Tools and Libraries Used

- dplyr: Helps to manipulate data easily by allowing you to filter, select, and modify data.
- tidyverse: A collection of R packages for data science that includes tools like dplyr (for data manipulation) and ggplot2 (for data visualization).
- kableExtra: Makes tables look better and more presentable in reports by adding styles like borders and colors.
- broom: Converts complex model outputs into tidy and easy-to-read data frames for better understanding and analysis.
- mice: Stands for Multiple Imputation by Chained Equations, handles missing data by filling in the missing values with estimated ones using a method called imputation.


