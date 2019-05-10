Reproducible Science
====================

Forked from: https://github.com/mkrapp/cookiecutter-reproducible-science
A boilerplate for reproducible and transparent science with close resemblances to the philosophy of [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science): *A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.*

Requirements
------------
Install `cookiecutter` command line: `pip install cookiecutter`    

Usage
-----
To start a new science project:

`cookiecutter gh:Huite/cookiecutter-reproducible-project`

Project Structure
-----------------

```
.
├── AUTHORS.md
├── LICENSE
├── README.md
├── bin                 <- Your compiled model code can be stored here (not tracked by git)
├── config              <- Configuration files, e.g., for doxygen or for your model if needed
├── data                
│   ├── 1_external      <- Data external to the project.
│   ├── 2_interim       <- Intermediate data that has been altered.
│   ├── 3_input         <- The processed data sets, ready for modeling.
│   ├── 4_output        <- Data dump from the model.
│   └── 5_visualization <- Post-processed data, ready for visualisation.
├── docs                <- Documentation, e.g., doxygen or scientific papers (not tracked by git)
├── notebooks           <- Jupyter notebooks
├── reports             <- For a manuscript source, e.g., LaTeX, Markdown, etc., or any project reports
│   └── figures         <- Figures for the manuscript or reports
└── src                 <- Source code for this project
    ├── 0_setup         <- Install necessary software, dependencies, pull other git projects, etc.
    ├── 1_prepare       <- Scripts and programs to process data, from 1_external to 2_interim.
    ├── 2_build         <- Scripts to create model specific inputm from 2_interim to 3_input. 
    ├── 3_model         <- Scripts to run model and convert/compress model results, from 3_input to 4_output.
    ├── 4_analyze       <- Scripts to post-process model results, from 4_output to 5_visualization.
    └── 5_visualize     <- Scripts for visualisation of your results, e.g., matplotlib, ggplot2 related.
```

License
-------
This project is licensed under the terms of the [BSD License](/LICENSE)
