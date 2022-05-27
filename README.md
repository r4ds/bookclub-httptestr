# R4DS HTTP testing in R Book Club

FIND/REPLACE BOOKDAYS, BOOKTIMECST, and TIMEANDDATEURL THEN DELETE THIS SENTENCE.

Welcome to the R4DS HTTP testing in R Book Club!

We are working together to read [_HTTP testing in R_](https://books.ropensci.org/http-testing/) by Scott Chamberlain and Maëlle Salmon.
Join the [#book_club-httptestr](https://rfordatascience.slack.com/archives/C03G5P13A1Z) channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/httptestr).

## Meeting Schedule

If you would like to present, please see the sign-up sheet for your cohort (linked below, and pinned in the [#book_club-httptestr](https://rfordatascience.slack.com/archives/C03G5P13A1Z) channel on Slack)!

- [Cohort 1](https://docs.google.com/spreadsheets/d/1kKBnJ-e2cZCcBAOnF3NHT9iXzXmUTQGwN7eFPrLDsyQ/edit?usp=sharing) (started TBD): [BOOKDAYS, BOOKTIMECST CST/CDT](TIMEANDDATEURL) | [meeting videos](https://www.youtube.com/playlist?list=PL3x6DOfs2NGjbhtOKn_p-M-bfqTb6zx4H)

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_Happy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} `install.packages("usethis")`
3. `usethis::create_from_github("r4ds/bookclub-httptestr")` (cleanly creates your own copy of this repository).
4. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion).
5. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
9. Commit your changes (either through the command line or using Rstudio's Git tab).
10. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
11. (If we request changes, make them)
12. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/httptestr).