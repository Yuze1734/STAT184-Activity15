---
editor_options: 
  markdown: 
    wrap: 72
---

# Plan for Version Control

## Goal:

Create a GitHub repository using the features learned in class
containing the .qmd file, the .pdf, and the plan from activity #14.

## Needs:

GitHub.com, GitHub desktop, Rstudio, Activity 14.qmd, Activity-14.pdf

## Instructions:

1.  Create the new GitHub repository on GitHub.com

2.  Give the new repo a descriptive name and summary

3.  Clone the repo onto my local machine

4.  Create a developer branch within the repo

5.  Create a .rproj to view everything in with Rstudio

6.  Create a plan file within the developer branch, commit and push
    changes

7.  Update the README file describing the goal of the repo, where the
    data is coming from, the current plan, how the repo is organized,
    and contact info. commit and push changes in the developer branch

8.  Import files from activity #14 within the developer branch, commit
    and push changes

    a.  The issues feature should be used here

9.  Import the plan from activity #14 within the developer branch

10. Merge all things committed to the developer branch with the main
    branch

# Plan for Activity #14

## Goal:

Create a quarto file that successfully generate a pdf file that contains
activities from a few previous activities (#10, #8, #13, #4). The quarto
file should have a code appendix at the end detailing the creation of
all data visualization created:

```         
Frequency table of pay grades and gender in Navy
Popularity of Names of My Roommates Over Time
Plot of Box Volume With Variable Excess
```

The generated pdf should also contain a section reflecting on what I've
learned so far in the course.

## Needs:

Activity #8.R, Activity #10.R, Activity #4.R, Activity #13.R, Rstudio,
Tidyverse Quarto

## Instructions:

1.  Create a Quarto file that outputs type pdf

2.  Write in a YAML header that including:

    a.  Include title, author, date, and date modified

    b.  Include format (pdf), no table of contents, and 1 inch margins

    c.  Set echo to false, warning to false, error to false

3.  Create section Armed Forces Data Wrangling Redux

    a.  Describe the data scraping in activity #8

    b.  Copy and paste the data scraping code in a code chunk, create a
        label

    c.  Describe the data wrangling in activity #8

    d.  Copy and paste the data wrangling code in a code chunk, create a
        label

    e.  Describe creating the kableExtra table with scraped and wrangled
        data

    f.  Copy and paste the table creation code that will excute and
        display the table, label the code chunk to have "tbl-"

    g.  Give the table a caption (tbl-cap)

    h.  Write narrative text describing what is going on in the table

4.  Create section Popularity of Baby Names

    a. Copy and paste the visualization creation code in a code chunk that 
    will execute and display the line graph, label the code chunk to have 
    "fig-"
    
    b. Give the figure a caption (fig-cap)
    
    c. Write narrative text describing what is going on in the figure
    
5. Create section Plotting a Mathematical Function

    a. Copy and paste the function definition and plotting code in a code chunk
    that will execute and display the graphical interruptation of the function,
    label the code chunk to have "fig-"
    
    b. Give the figure a caption (fig-cap)
    
    c. Write narrative text describing the interruptation of the graph with
    relation to the context
    
6. Write in reflection for section What You Feel You've Learned So Far

7. Create a code appendix detailed in the quarto crash course
