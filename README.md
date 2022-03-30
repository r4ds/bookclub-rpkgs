# R4DS R Packages Book Club

Welcome to the R4DS R Packages Book Club!

We are working together to read [_R Packages_](https://r-pkgs.org/) by Hadley Wickham and Jenny Bryan (work-in-progress 2nd edition, copyright 2022).
Join the #book_club-rpkgs channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/rpkgs).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1 & 2 met using an old club style*

*Cohort 3: Wednesdays, 8:00pm CDT*

<details>
  <summary> Past Meetings </summary>
  
(none yet)
</details>

- 2022-03-29: Introduction; git; Chapter 1 (Introduction) - Collin Berke
- 2022-04-06: Chapter 2 (The whole game) - Presenter TBD
- 2022-04-13: Chapter 3 (System setup) & 4 (Package structure and state) - Presenter TBD
- 2022-04-20: Chapter 5 (Fundamental development workflows) - Presenter TBD
- 2022-04-27: Chapter 6 (The package within) - Presenter TBD
- 2022-05-04: Chapter 7 (R code) - Presenter TBD
- 2022-05-11: Chapter 8 (Package metadata) - Presenter TBD
- 2022-05-18: Chapter 9 (Licensing) - Presenter TBD
- 2022-05-25: Chapter 10 (Object documentation) - Presenter TBD
- 2022-06-01: Chapter 11 (Vignettes: long-form documentation) - Presenter TBD
- 2022-06-08: Chapter 12 (Testing) - Presenter TBD
- 2022-06-15: Chapter 13 (Namespace) - Presenter TBD
- 2022-06-22: Chapter 15 (Compiled code) - Presenter TBD
- 2022-06-29: Chapter 14 (External data), Chapter 16 (Installed files), & Chapter 17 (Other components) - Presenter TBD
- 2022-07-06: Chapter 18 (Git and GitHub) - Presenter TBD
- 2022-07-13: Chapter 19 (Automated checking) - Presenter TBD
- 2022-07-20: Chapter 20 (Releasing a package) - Presenter TBD

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
