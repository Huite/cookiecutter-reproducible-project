{{cookiecutter.project_slug}}
==============================

{{cookiecutter.project_short_description}}

Project Organization
--------------------

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
        ├── 3_model         <- Scripts to run model and convert or compress model results, from 3_input to 4_output.
        ├── 4_analyze       <- Scripts to post-process model results, from 4_output to 5_visualization.
        └── 5_visualize     <- Scripts for visualisation of your results, e.g., matplotlib related. From 5_visualization to ./report/figures.