
<!-- README.md is generated from README.Rmd. Please edit that file -->

# DSAIRM <img src="man/figures/logo.png" align="right" alt="" width="120" />

<!-- badges: start -->

[![R-CMD-check](https://github.com/ahgroup/DSAIRM/workflows/R-CMD-check/badge.svg)](https://github.com/ahgroup/DSAIRM/actions)
[![Coverage
status](https://codecov.io/gh/ahgroup/DSAIRM/branch/master/graph/badge.svg?token=OGO3sVEcPD)](https://codecov.io/gh/ahgroup/DSAIRM)
[![test-coverage](https://github.com/ahgroup/DSAIRM/workflows/test-coverage/badge.svg)](https://github.com/ahgroup/DSAIRM/actions)
[![CRAN
status](https://www.r-pkg.org/badges/version/DSAIRM)](https://cran.r-project.org/package=DSAIRM)
[![CRAN
checks](https://cranchecks.info/badges/summary/DSAIRM)](https://cran.r-project.org/web/checks/check_results_DSAIRM.html)
[![metacran monthly
downloads](http://cranlogs.r-pkg.org/badges/DSAIRM)](https://cran.r-project.org/package=DSAIRM)
[![metacran
downloads](http://cranlogs.r-pkg.org/badges/grand-total/DSAIRM?color=ff69b4)](https://cran.r-project.org/package=DSAIRM)
<!-- badges: end -->

**DSAIRM - Dynamical Systems Approach to Immune Response Modeling**

## Description

DSAIRM is an R package containing a set of simulation models (apps) that
teach within-host infection dynamics and immune response modeling from a
dynamical system perspective.

All models can be explored through a graphical user interface, no
reading or writing code is required. Each app comes with documentation
and instructions which teach important concepts of within-host and
immune response modeling, and how to use simulation models to understand
such concepts.

It is also possible to go beyond the graphical interface and directly
access and modify all simulations to adapt them to your needs.

## Getting Started

While the main idea is to install the R package and use it locally, if
you want to get a quick glimpse at the package to see if this package is
for you, you can give it [a quick try online, without having to install
it](https://shiny.ovpr.uga.edu/DSAIRM/). If you like what you see, you
can install it and start using it with these 3 commands:

    install.packages('DSAIRM')
    library('DSAIRM')
    dsairmmenu()

For an introduction to the package, step-by-step instructions on getting
started, and more information on the different ways you can use the
package [see the *Get Started* tutorial
(vignette)](https://ahgroup.github.io/DSAIRM/articles/DSAIRM.html).

## Further information

-   The [package tutorial
    (vignette)](https://ahgroup.github.io/DSAIRM/articles/DSAIRM.html)
    contains detailed instructions on the different ways the package can
    be used.
-   [I published a paper describing the
    package](https://doi.org/10.1186/s12865-019-0321-0). The package has
    since been updated and changed, but the paper still describes the
    overall idea and context well.  
-   I teach an annual workshop with my colleague Paul Thomas at
    [SISMID](https://si.biostat.washington.edu/suminst/sismid) where we
    cover some of the topics you can learn about in DSAIRM (and we use
    the package). Workshop materials [are freely available
    online](https://andreashandel.github.io/SMIcourse/).
-   I have full solutions and quiz sheets for all of the **What to do**
    tasks for each app. If you are an instructor using this package as
    part of a class, email me if you are interested in having access to
    the materials.
-   Contributions to the package are very welcome! If you want to take a
    deeper look at the package, see [this Markdown
    file](https://github.com/ahgroup/DSAIRM/blob/master/auxiliary/docsfordevelopers/documentation.md)
    which provides further information on the details of the package
    structure. I’d be excited to receive any contributions from
    individuals who want to help improve the package. If you plan to
    develop new apps, or make other substantial contributions, it might
    be best to get in touch with me first.
-   A companion package to this one, called *Dynamical Systems
    Approaches to Infectious Disease Epidemiology (DSAIDE)*, focuses on
    models at the population level. It has the same structure as DSAIRM.
    [See the DSAIDE site for more
    information.](https://ahgroup.github.io/DSAIDE/)
-   I send out a monthly newsletter in which I announce any noteworthy
    updates to my R packages. If you want to stay updated, [you can sign
    up here](https://www.andreashandel.com/susbscribe/).

## Citation and Contributors

If the package does in any way help you with your work such that it
warrants citing it, please cite [this publication in BMC
Immunology](https://doi.org/10.1186/s12865-019-0321-0). This R package
is developed and maintained by [Andreas
Handel](https://www.andreashandel.com/). A full list of contributors and
a Bibtex entry for the citation [can be found
here](https://ahgroup.github.io/DSAIRM/authors.html).

This project was/is partially supported by NIH grants U19AI117891,
U01AI150747, R25AI147391 and R25GM089694.
