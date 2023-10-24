---
editor: visual
---

# Data Source Description

The data we will use come from the 2021 [General Social Survey](https://gss.norc.org/About-The-GSS) (GSS), which is a nationally representative survey of adults in the United States, conducted every two years, by the National Opinion Research Council. The GSS is primarily concerned with trends in opinions, attitudes, and behaviors.

From the full data, I have extracted and recoded the following variables for our use as an analytical dataset. To load this dataset in R, you just need to run the setup code chunk in the full_report.qmd quarto document. The name of the dataset in R is `gss`.

-   **active_enviro**: This variable is a composite variable based on responses to four separate questions on environmental activism. This variable is the key dependent variable. The variable is simply the count of "yes" responses provided by the respondent across all four questions. Those questions were:

    -   In the last five years, have you signed a petition about an environmental issue?
    -   In the last five years, have you taken part in a protest or demonstration about an environmental issue?
    -   Are you a member of any group whose aim is to preserve or protect the environment?
    -   In the last five years, have you given money to an environmental group?

-   **income_quintile**: This variable measures roughly the quintile (20% percentile groups) of family income to which the respondent belongs. The higher the quintile, the higher this person's income. This variable is the key independent variable.

-   **age**: The respondent's age in years.

-   **gender**: The respondent's reported gender. The only available choices in this survey were male or female.

-   **educ**: The respondent's years of education.

-   **race**: The respondent's self-reported racial identification as White, Latino, Black, American Indian/Alaska Native, Asian/Pacific Islander, Other, or Multiple.

-   **marital**: The respondent's current marital status.

-   **region**: The respondent's current region of the country with the choices being Northeast, Midwest, South, or West.
