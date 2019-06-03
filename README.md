# Spatial Data Science with R, MSc course, 2019

### Goals

The goals of this course are to get familiar with data science,
with spatial data in data science problem, with techniques and
tricks to using R for solving smaller problems, and with programming
R to solve larger problems. The final assignment is one of:
* writing an R package for solving a particular spatial data science problem that passes all checks cleanly, and that contains one or more vignettes illustrating the problem(s) solved.
* develop a worked out spatial data science case study, wrapped as R markdown file, submitted in a fully reproducible manner

### Motivation

Carrying out a proper scientific data analysis exercise involves
not only understanding appropriate statistical methods, but also
understanding the data, of the domain from which the data and
the research question originate, and familiarity with tools that
are needed or that still need to be developed to carry out the
analysis. Ideally, the analysis should be carried out such that
the report does not only give full insight in all details of the
analysis, but also _minimises_ the effort to reproduce or modify the
complete analysis, and by that inviting to recreate the report
itself, or modify it. The combinations of all these skills can be
called data science.

Spatial data science is a flavor of data science where spatial
locations play a role, not only to hold records together
(which IDs also could do), but also play an explicit role in the
analysis, e.g. to compute and analyse distances, consider spatial
autocorrelation, or compute spatial relationships between features
with different geometry types, such as distances from points to
linestrings. Quite often, temporal considerations play a role too
when considering spatial properties.

R is a language and environment for statistical computing that
plays a large role in data science, because it is open source, it
is easily extendible, and it used a lot by non-computer programmers
to carry out programming tasks.

### Course organisation

The course will be organized along the following topics:

1. (Apr 8) R and its package ecosystem; CRAN; other ecosystems: bioconductor, github; flavors of R, IDEs, rstudio [questions](meeting1.md)
2. (Apr 15) R basics: objects, vectors, arrays, lists, `NULL`, attributes; data.frames
3. (Apr 22) (no class) (Apr 25) (no class) 
4. (Apr 29) R models, formula, lm, predict, plot, summary, subset, NA, factor
5. (May 3) R spatial basics: history, packages, sys reqs, simple features
6. (May 6) Vector geometric operations, DE-9-IM
7. (May 13) Attributes, attribute-to-geometry relations
8. (May 20) Raster, vector-raster conversion, arrays 
9. (May 27) R plotting: base plot, grid, lattice, ggplot2
10. (Jun 3) Tidyverse basics: tidy data, tidy tools manifesto, dplyr, pipes 
11. (Jun 17) R programming: functions, methods, S3, S4, R6
12. (Jun 24) R looping: for, apply, lapply, purr
13. (Jul 1) Extending R: foreign language interfaces; R markdown; Writing R packages

### References

* [JC] John Chambers, 2016. Extending R. CRC Press.

* [AR] Hadley Wickham, Advanced R. http://adv-r.had.co.nz/

* [RP] Hadley Wickham, R Packages. http://r-pkgs.had.co.nz/

* [RDS] Hadley Wickham and Gareth Grolemund, R for Data Science, http://r4ds.had.co.nz/

* [ASDAR] Roger Bivand, Edzer Pebesma, Virgilio Gomez-Rubio, Applied Spatial Data Analysis with R. Springer, NY.; http://www.asdar-book.org/

* [IR] R Core Team, 2017, [An Introduction to R](https://cran.r-project.org/doc/manuals/r-release/R-intro.html)
