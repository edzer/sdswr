# Spatial Data Science with R, MSc course, 2017

### Goals

The goals of this course are to get familiar with data science,
with spatial data in data science problem, with techniques and
tricks to using R for solving smaller problems, and with programming
R to solve larger problems. The final assignment is writing an R
package for solving a particular spatial data science problem that
passes all checks cleanly, and that contains one or more vignettes
illustrating the problem(s) solved.

### Motivation

Carrying out a proper scientific data analysis exercise involves
not only understanding appropriate statistical methods, but also
understanding the data, of the domain from which the data and
the research question originate, and familiarity with tools that
are needed or that still need to be developed to carry out the
analysis. Ideally, the analysis should be carried out such that
the report does not only give full insight in all details of the
analysis, but also makes it relatively effortless to reproduce
or modify the complete analysis, and by that recreate the report
itself, or modify it. The combinations of all these skills can be
called data science.

Spatial data science is a flavor of data science where spatial
locations play a role, not only to hold records togehter, but also
to compute and analyse distances, consider spatial autocorrelation,
or compute spatial relationships between features with different
geometry types, such as distances from points to linestrings. Quite
often, temporal considerations play a role too when considering
spatial properties. 

R is a language and environment for statistical computing that
plays a large role in data science, because it is open source, it
is easily extendible, and it used a lot by non-computer programmers
to carry out programming tasks.


### Course organisation

The course will be organized along the following topics:

1. R and the CRAN package ecosystem; other ecosystems: bioconductor, github
2. R basics: vectors, arrays, lists, data.frames, factor, NA, subset
3. R programming basics: functions, methods, creating generics, S3, S4, R6
4. Writing packages: package organisation, writing R extensions, NAMESPACE, roxygen
5. R looping: for, apply, lapply, sapply, rapply, ...
6. R models, formula, lm, predict, plot, summary,
7. R plotting: base plot, grid, lattice, ggplot
8. Tidyverse: tidy data, tidy tools manifesto, dplyr, pipes
9. Extending R: C, C++, Fortran, Java, JavaScript, 
10. Time in R: POSIXlt, POSIXct, zoo, xts
11. Spatial and spatiotemporal packages: sp, spacetime, raster, sf
12. Programming challenges
 

### References

* John Chambers, 2016. Extending R. CRC Press.

* Hadley Wickham, Advanced R. http://adv-r.had.co.nz/

* Hadley Wickham, R Packages. http://r-pkgs.had.co.nz/

* Hadley Wickham and Gareth Grolemund, R for Data Science, http://r4ds.had.co.nz/

* Roger Bivand, Edzer Pebesma, Virgilio Gomez-Rubio, Applied Spatial Data Analysis with R. Springer, NY.; http://www.asdar-book.org/
