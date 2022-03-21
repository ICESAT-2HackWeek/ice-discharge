Antarctic Ice Discharge Project - ICESat-2 Hackweek 2022

This is as an example on how teams can structure their project repositories. Thanks to Lindsey Heagey and Joachim Meyer for the template, provided originally for Geohackweek.


    .gitignore
    Globally ignored files by git for the project.
    environment.yml
    conda environment description needed to run this project.
    README.md
    Description of the project. 
    Create an open source work flow to measure catchment scale solid ice discharge in Antarctica using ICESat-2 altimetry, landsat/sentinel based velocity tracking, and subglacial topography. By tracking grounding line migration, flux gates ca nbe assigned to calculate Gt discharge and help estimate contributions to sea level rise. Ideally, this work could then be automated and applied across all antarctic catchments to contribute to global sea level rise rates. Exact location(s) for study TBD.

Folders
contributors
Mark Hehlen
Lizzie Hebel
Lawrence Bird
Julia Andreasen
Hui Gao
Emily Glazer
Bryony Freer

Each team member has it's own folder under contributors, where he/she can work on their contribution. Having a dedicated folder for one-self helps to prevent conflicts when merging with master.
notebooks

Notebooks that are considered delivered results for the project are contained in:
scripts

Helper utilities that are shared with the team
