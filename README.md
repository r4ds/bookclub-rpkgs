# R4DS R Packages Book Club

Welcome to the R4DS R Packages Book Club!

We are working together to read [_R Packages_](https://r-pkgs.org/) by Hadley Wickham and Jenny Bryan (work-in-progress 2nd edition, copyright 2022).
Join the [#book_club-rpkgs](https://rfordatascience.slack.com/archives/C014C9F4DRS) channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/rpkgs).

## Meeting Schedule

If you would like to present, please see the sign-up sheet for your cohort (linked below, and pinned in the [#book_club-rpkgs](https://rfordatascience.slack.com/archives/C014C9F4DRS) channel on Slack)!

- Cohort 1 (started 2020-09-29, ended 2020-12-15): [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGiXMln8bxY7e0XgA5z1cp-8)
- Cohort 2 (started 2021-03-13, ended 2021-06-05): [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGhRtG2Oj1aI9mWTGY6KKUJB)
- [Cohort 3](https://docs.google.com/spreadsheets/d/188z71TbrgTtAWMAtKcwNXvtBhvCwqCvLO5F3hSYI1tM/edit?usp=sharing) (started 2022-03-30): [Wednesdays, 8:00pm CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20220331T010000&p1=24) | [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGi8NcKmNxw_Hk4-leUsivZv)

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_Happy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} `install.packages("usethis")`
3. `usethis::create_from_github("r4ds/bookclub-rpkgs")` (cleanly creates your own copy of this repository).
4. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion).
5. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
9. Commit your changes (either through the command line or using Rstudio's Git tab).
10. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
11. (If we request changes, make them)
12. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/rpkgs).

## Images

If any static files are used in the `.Rmd` for a chapter, please add them into the directory `./images/<chapter_number>-<title_stub>/`. For example, to include images for the "02-the-whole-game" chapter, please place them in `./images/02-the-whole-game/`. Name files in a manner that is informative on what the image represents. 
