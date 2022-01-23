# R4DS R Packages Book Club

Welcome to the R4DS R Packages Book Club!

We are working together to read [_R Packages_](https://r-pkgs.org/) by Hadley Wickham and Jenny Bryan (work-in-progress 2nd edition, copyright 2022).
Join the #book_club-rpkgs channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/rpkgs).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1 & 2 met using an old club style*

*Cohort 3: DAY-TBD, TIME-TBD CST/CDT*

<details>
  <summary> Past Meetings </summary>
  
(none yet)
</details>

- YYYY-MM-DD: Introduction - Collin Berke
- YYYY-MM-DD: Chapter 1 (TITLE) - Presenter TBD


<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI)
2. Fork this repository.
3. Create a New Project in RStudio using your fork.
4. Install dependencies for this book with `devtools::install_dev_deps()` (technically optional but it's nice to be able to rebuild the full book).
5. Create a New Branch in your fork for your work.
6. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Commit your changes.
9. Push your changes to your branch.
10. Open a Pull Request (PR) to let us know that your slides are ready.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/rpkgs).
