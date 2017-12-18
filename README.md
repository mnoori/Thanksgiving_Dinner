# Thanksgiving_Dinner

The dataset contains 1058 responses to an online survey about what Americans eat for Thanksgiving dinner (https://github.com/fivethirtyeight/data/tree/master/thanksgiving-2015). Each survey respondent was asked questions about what they typically eat for Thanksgiving, along with some demographic questions, like their gender, income, and location. This dataset will allow us to discover regional and income-based patterns in what Americans eat for Thanksgiving dinner.

The dataset has 65 columns, and 1058 rows. Most of the column names are questions, and most of the column values are string responses to the questions. Most of the columns are categorical, as a survey respondent had to select one of a few options. For example, one of the first column names is What is typically the main dish at your Thanksgiving dinner?. The potential responses are:

Turkey
Other (please specify)
Ham/Pork
Tofurkey
Chicken
Roast beef
I don't know
Turducken

We won't enumerate every single column now, but here are descriptions of some of the most important:

RespondentID -- a unique ID of the respondent to the survey.
Do you celebrate Thanksgiving? -- a Yes/No reponse to the question.
How would you describe where you live? -- responses are Suburban, Urban, and Rural.
Age -- resposes are one of several categories, such as 18-29, and 30-44.
How much total combined money did all members of your HOUSEHOLD earn last year? -- one of several categories, such as $75,000 to $99,999.
