<!-- Copyright (C)  Google, Runestone Interactive LLC
  This work is licensed under the Creative Commons Attribution-ShareAlike 4.0
  International License. To view a copy of this license, visit
  http://creativecommons.org/licenses/by-sa/4.0/. -->

Module C
========

Project Description
-------------------

In this project, you will complete a statistical analysis on a dataset,
then write a report summarizing your findings.

Here are the steps you'll need to complete. **Under each step are
sub-bullets detailing questions you need to answer in your report.**

**Step 1: Choosing a Dataset**

When selecting a database to use for this project, keep the following in
mind. Read through all of the instructions to ensure the selected
database contains enough data to be used for this project. Ensure that
the source is reliable if it is not one of the recommended databases to
choose from. Also, make sure that you are able to use this data. You can
check on the website to see if the dataset is licensed and what
restrictions there may be on using it. In most cases, using the data and
drawing conclusions from it is just fine, but republishing the data
itself is not allowed.

**To Do:**

-   Form a group of no more than 4 people. (You may want to form a group
    with people who are in a similar major or have similar interests as
    this may make dataset selection easier).
-   Find a dataset to analyze online. If you are unsure where to start
    looking, check out the hints section for some places to start. If
    you have questions about your dataset, ask an instructor before
    proceeding.
-   **Deliverable:** State and describe your dataset. Why did you choose
    this particular dataset?

*Hints:*

-   Places to find free datasets: [World Bank Open
    Data](https://data.worldbank.org/),
    [FiveThirtyEight](https://data.fivethirtyeight.com/),
    [Kaggle](https://www.kaggle.com/datasets).
-   [Additional list of websites to find
    datasets](https://www.dataquest.io/blog/free-datasets-for-projects/).

**Step 2: Clean Your Dataset**

Only rarely will datasets ever be ready for analysis right away.
Therefore, you will need to prepare your dataset to make useful
observations. Don't worry if it seems overwhelming at first. You want to
remove outliers that may skew your dataset, while still maintaining the
integrity of your data. Some steps have been provided to help with this
process. Once you clean your dataset, you should be able to find
sections of the data that are interesting and find relevant
relationships.

**To Do:**

-   First look at your data and see if you can spot any inconsistencies.
-   Filter out unwanted outliers.
-   Check for missing or incorrect data (check for data types and
    nulls).
-   **Deliverable:** Summarize your data cleaning process and make sure
    to answer the following questions.
    -   Are there any ethical issues with the way you cleaned the data?
        What are they?
    -   Did you make any trade-offs as you were cleaning? What were
        these tradeoffs and why did you make this decision?

*Hints:*

   -   For a more in-depth explanation of data cleaning [read
        this.](https://elitedatascience.com/data-cleaning)

**Step 3: Join Tables**

By joining tables across the database you can answer questions and
analyze data with a different perspective. For resources, refer back to
the [section on joining tables](../sql/joining.md) earlier in
the textbook.

**To Do:**

-   Think of 2-3 interesting questions you would like to answer using
    the database. These should involve joining the tables using SQL in
    order to link variables from different tables.
-   Using the joined dataset, find summary statistics for the
    population.
-   **Deliverables:** Answer the following questions in the Joining
    section of your report.
    -   What were the questions you chose and why?
    -   Which datasets did you have to join?
    -   What are the primary keys on which you join?
    -   What type of JOIN was applicable for your questions?

**Step 4: Analyze**

For your research, think of 2-3 interesting statistical questions you
would like to answer using these datasets. These should involve
calculating the mean, median, and standard deviation using SQL. Also, in
your analysis, select a categorical variable to focus on.

**To Do:**

-   Calculate the mean, median, and standard deviation using SQL.
    -   For example:
        -   Compare the mean and standard deviation for two different
            variables.
        -   Compare the mean and median for a single variable.
-   Choose a categorical variable that you predict will have an
    interesting relationship with the other variables in the dataset.
    -   Why did you choose this variable?
    -   What led you to predict this variable would have an interesting
        relationship with the other variables?
-   Using SQL, find summary statistics for the main groups within the
    dataset based on your chosen categorical variable.
    -   For groups of interest, what are the mean, median, variance,
        standard deviation within the group?
    -   Is the sample size enough within each group?
-   Formulate a new question about how the relationship identified above
    may be influenced by another categorical variable.
    -   Using Sheets, create scatter plots and regression lines for each
        category (using either multiple graphs or multiple colors).
    -   In a short paragraph, compare and contrast how the regression
        analysis varies between these groups.
-   **Deliverables:** Answer the questions in each of the above sections
    in the summary statistics section of your report. Add a paragraph
    that compares and contrasts the variation of the regression analysis
    as specified above.

**Step 5: Visualize**

As discussed in the textbook, visualizations are important to convey
your findings. You will create visualizations in Sheets of your results.
Keep in mind
[accessibility guidelines](../introduction_to_visualizations/creating_visualizations_checklist.md) when creating your visualizations.

**To Do:**

-   Export grouped data from the SQL server to sheets.
-   **Deliverable:** Using sheets, create a visualization for (what you
    consider to be) the most interesting results from your summary
    statistics.
    -   Why did you choose these visualizations? Be specific as to the
        types of visualization.
    -   Discuss how center and spread are impacted by the categorical
        variable.

**Step 6: Regression**

Determine two quantitative variables that have either a strong or an
interesting relationship.

**To Do:**

-   Determine two quantitative variables that have either a strong or an
    interesting relationship. Using Sheets, fit a regression on the
    data.
    -   How did you determine that this relationship was particularly
        interesting?
    -   Identify any potential lurking variables. How did you find them?
    -   What is the equation for the line of best fit, and does the line
        of best fit fit the data well? If not, why not?
    -   If you are getting surprising results, what is surprising and
        why?
-   **Deliverable:** Answer the above questions.

**Step 7: Conclude and reflect**

The power of data science is that you can get meaningful takeaways from
statistics that can help you make a positive impact on society. Now that
you've done data analysis, take a moment to reflect on your findings and
think about the broader implications.

**To Do:**

-   Include a conclusion summarizing your findings.
    -   Who does this affect?
    -   What did you learn?
-   Proofread your report.
-   **Deliverable:** Write the conclusion section of your paper. Submit
    your report and your sheets reflecting your analysis by \[Due
    Date\].

**Optional** (faculty can decide whether to include or not): After
completing and submitting your project, complete the group work self
assessment and group assessment.

**Optional** (faculty can choose whether to include or not): [Here](https://drive.google.com/open?id=1lYx1vIQsdeL3OUpYn2L1tZBLykFlgvwl)
is an example project.

Grading Rubric
--------------

|                                                 | Excellent                                                                                                                                                                                                                                                                                                                                                                                            | Developing                                                                                                                                                                                                                                                        | Beginning                                                                                                                                                                                                                                           | NA/Not Present                                                                                            |
|-------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Dataset (2)                                     |                                                                                                                                                       The report contains a sufficiently in-depth discussion as to why the dataset was chosen.                                                                                                                                                       | The report contains a discussion as to why the dataset was chosen, but it lacks details.                                                                                                                                                                          |                                                                                                                                                                                                                                                     | The report does not state why dataset was chosen.                                                         |
| Data Cleaning (8)                               |                                                                                                          All missing/unclean data is found and accounted for in a way that makes sense. The report references data types, any ethical tradeoffs, and outlines what steps were taken and why.                                                                                                         | Some crucial steps are not taken. Steps outlined to clean the data are ambiguous.                                                                                                                                                                                 | There is an attempt at data cleaning, but it does not get far. Large chunks of missing/unclean data are untreated. Key steps of cleaning process were not reported.                                                                                 | Report does not include any reference to data cleaning (independently of whether data cleaning was done). |
| Joining (4)                                     |                                             At least 2 questions were chosen and explanation was given as to why. These questions involve using JOIN. The correct JOIN was used and implemented to answer the stated questions. The merged dataset was verified for correctness. The report includes a correct discussion on the different types of JOIN.                                            | Technical implementation of the JOIN is done correctly, but the discussion in the report lacks the sufficient detail.                                                                                                                                             | Questions may be lacking in complexity. The incorrect JOIN or join key was chosen/used. There is inadequate discussion on why the type and key of the JOIN are chosen.                                                                              | There is no attempt at using JOIN.                                                                        |
| Questions Answered Using Summary Statistics (4) | At least 2 questions were chosen and explanation was given as to why. These questions involve calculating summary statistics. The summary statistics are accurately calculated, and used to answer the stated questions. There is some comment on what these values mean for the distribution.                                                                                                       | At least 2 questions were chosen and explanation was given as to why. These questions involve calculating summary statistics. There is an attempt at calculating summary statistics, but it produces minor errors. The discussion in the report lacks some depth. | Questions may be lacking in complexity. There is an attempt at calculating summary statistics, but they are incorrect, not relevant to the stated question, or not referenced in the report.                                                        | There is no question or attempt to answer the question via calculating the population summary statistics. |
| Grouped Summary Statistics (8)                  | GROUP BY was used to calculate relevant summary statistics per group. The query result is presented in the report in a clean way. There is some other visualization showing some important summary statistics. There is some mention of sample size within groups, as well as why the specific grouping was chosen. There is a working attempt at using GROUP BY, and it is presented in the report. | Not all statistics are accurate, or there is no extra visualization. There is some mention of sample size within groups.                                                                                                                                          | There is an attempt at a GROUP BY, but it uses the wrong dimensions or measures. The grouped summary statistics are incorrect or non-existent.                                                                                                      | There is no attempt at a GROUP BY.                                                                        |
| Visualization (8)                               | There are multiple visualizations comparing summary statistics across groups to answer the questions posed. There is some comparison of center or spread across groups.                                                                                                                                                                                                                              | There are multiple visualizations, but they have issues, for example they do not directly address the questions posed.                                                                                                                                            | There is at least one visualization comparing summary statistics across groups attempting to address the questions posed.                                                                                                                           | There are no visualizations comparing summary statistics across groups.                                   |
| Regression (8)                                  | Report includes both the scatter plot and the line-of-best-fit equation, and these values are (close to) correct. The report includes a discussion of why the particular variables were chosen, the meaning of the coefficients, and correlation versus causation. There is some mention of whether regression is appropriate for the sample size.                                                   | The line of best fit is not completely correct. The scatter plot is missing from or wrongly formatted in the report. The discussion on variable selection, coefficient interpretation, and correlation vs. causation is not sufficiently detailed or accurate.    | There is some attempt at a line of best fit, but the values are completely wrong. The scatter plot or the equation are not included. There is no proper discussion on variable selection, coefficient interpretation, or correlation vs. causation. | There is no attempt at fitting a regression.                                                              |
| Categorical Variable Regression (10)            | Suitable variables are chosen, with justification presented. The regression and scatter plots are well presented in the report, and the appropriate conclusions are reached. There is a paragraph comparing the regression with and without the influence of the categorical variable.                                                                                                               | There are some inaccuracies or some poor presentation in the regression and scatter plots. There is a paragraph comparing the regressions but it misses key points.                                                                                               | Inappropriate (e.g. all quantitative) variables were chosen. The regression and scatter plots were not done correctly. There is no paragraph comparing the regressions.                                                                             | There is no attempt at regression on a categorical variable.                                              |
| Conclusion (4)                                  | The report contains a conclusion section summarizing key findings from other rubric areas. It is concise and complete.                                                                                                                                                                                                                                                                               | The report contains a conclusion section, but either contains minor inconsistencies with previous findings, or omits relevant findings.                                                                                                                           | The report contains a conclusion section, but it is incomplete or doesn’t accurately reflect previous findings.                                                                                                                                     | The report does not contain a conclusion section.                                                         |
| Readability (4)                                 | The report is structured by section, with appropriate headings. The report has very few spelling/grammar errors.                                                                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                   | The report’s structure lacks clarity or is otherwise difficult to read. The report has several spelling/grammar errors.                                                                                                                             | There is no report.                                                                                       |
