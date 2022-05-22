# R4DS HTTP testing in R Book Club

FIND/REPLACE httptestr, HTTP testing in R, https://books.ropensci.org/http-testing/, Scott Chamberlain and Maëlle Salmon, BOOKDAYS, and BOOKTIMECST THEN DELETE THIS SENTENCE.

ALSO UPDATE THE MEETING TIME INFO BELOW AND DELETE THIS SENTENCE.

ALSO ADD PLACEHOLDERS FOR ALL CHAPTERS BY COPYING 01.Rmd (IDEALLY ALSO UPDATE TITLES WITHIN THE FILES), THEN DELETE THIS SENTENCE.

Welcome to the R4DS HTTP testing in R Book Club!

We are working together to read [_HTTP testing in R_](https://books.ropensci.org/http-testing/) by Scott Chamberlain and Maëlle Salmon.
Join the #book_club-httptestr channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/httptestr).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: DAY TBD, TIME TBD CST/CDT*

<details>
  <summary> Past Meetings </summary>
  
(none yet)
</details>

- 2022-MM-DD: Introduction (Chapters 1-4) - Jon Harmon
- 2022-MM-DD: Use vcr & webmockr (Chapters 5-6) - Presenter TBD
- 2022-MM-DD: Use httptest (Chapter 7) - Presenter TBD
- 2022-MM-DD: vcr and httptest (Chapter 8) - Presenter TBD
- 2022-MM-DD: Use httptest2 & Use webfakes (Chapters 9-10) - Presenter TBD
- 2022-MM-DD: vcr (& webmockr), httptest, webfakes (Chapter 11) - Presenter TBD
- 2022-MM-DD: Advanced Topics Part 1 (Chapters 12-13) - Presenter TBD
- 2022-MM-DD: Advanced Topics Part 2 (Chapters 14-16) - Presenter TBD
- 2022-MM-DD: Conclusion & Future Plans (Chapter 17) - Presenter TBD

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
