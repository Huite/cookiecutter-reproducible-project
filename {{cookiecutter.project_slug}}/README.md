{{cookiecutter.project_slug}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------

    .
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md
    ├── bin                <- Compiled model code can be stored here (not tracked by git)
    ├── config             <- Configuration files, e.g., for doxygen or for your model if needed
    ├── data
    │   ├── 0_external     <- Data external to the project.
    │   ├── 1_interim      <- Intermediate data that has been altered.
    │   ├── 2_input        <- Model input.
    │   ├── 3_raw          <- Raw data dump from the model.
    │   └── 4_processed    <- Final data, ready for visualisation.
    ├── docs               <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
    ├── notebooks          <- Jupyter notebooks
    ├── reports            <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
    │   └── figures        <- Figures for the manuscript or reports
    └── src                <- Source code for this project
        ├── data           <- scripts and programs to process data
        ├── external       <- Any external source code, e.g., pull other git projects, or external libraries
        ├── models         <- Source code for your own model
        ├── tools          <- Any helper scripts go here
        └── visualization  <- Scripts for visualisation of your results, e.g., matplotlib, ggplot2 related.
