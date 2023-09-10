Business Intelligence Project
================
Clarice Muthoni Gitonga
07/09/2023

- [Student Details](#student-details)
- [Setup Chunk](#setup-chunk)
- [Understanding the Dataset (Exploratory Data Analysis
  (EDA))](#understanding-the-dataset-exploratory-data-analysis-eda)
  - [Loading the Dataset](#loading-the-dataset)
    - [Source:](#source)
    - [Reference:](#reference)
      - [Karlan, A., Dean; Wood, S., Daniel H., (2017), “The Effect of
        Effectiveness: Donor Response to Aid Effectiveness in a Direct
        Mail Fundraising Experiment”,
        https://doi.org/10.7910/DVN/RDHJQZ, Harvard Dataverse, (Version
        1),](#karlan-a-dean-wood-s-daniel-h-2017-the-effect-of-effectiveness-donor-response-to-aid-effectiveness-in-a-direct-mail-fundraising-experiment-httpsdoiorg107910dvnrdhjqz-harvard-dataverse-version-1)

# Student Details

|                                              |                 |
|----------------------------------------------|-----------------|
| **Student ID Number**                        | 127707          |
| **Student Name**                             | Clarice Gitonga |
| **BBIT 4.2 Group**                           | 4.2B            |
| **BI Project Group Name/ID (if applicable)** | Champions       |

# Setup Chunk

**Note:** the following KnitR options have been set as the global
defaults: <BR>
`knitr::opts_chunk$set(echo = TRUE, warning = FALSE, eval = TRUE, collapse = FALSE, tidy = TRUE)`.

More KnitR options are documented here
<https://bookdown.org/yihui/rmarkdown-cookbook/chunk-options.html> and
here <https://yihui.org/knitr/options/>.

# Understanding the Dataset (Exploratory Data Analysis (EDA))

## Loading the Dataset

### Source:

The dataset that was used can be downloaded here:
<https://www.kaggle.com/datasets/nancyalaswad90/finding-donors-for-charityml>\*

### Reference:

\*\<Cite the dataset here using APA\>  
Refer to the APA 7th edition manual for rules on how to cite datasets:
<https://apastyle.apa.org/style-grammar-guidelines/references/examples/data-set-references>

#### Karlan, A., Dean; Wood, S., Daniel H., (2017), “The Effect of Effectiveness: Donor Response to Aid Effectiveness in a Direct Mail Fundraising Experiment”, <https://doi.org/10.7910/DVN/RDHJQZ>, Harvard Dataverse, (Version 1),

``` r
library(readr)
census <- read_csv("../data/census.csv")
```

    ## Rows: 45222 Columns: 14
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (9): workclass, education_level, marital-status, occupation, relationshi...
    ## dbl (5): age, education-num, capital-gain, capital-loss, hours-per-week
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
View(census)


# Provide the executable R code inside the various code chunks as guided by the lab work.
```

…to be continued
