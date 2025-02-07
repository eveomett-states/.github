# Post-2020 Census States

This organization contains a repository for most states (we hope to eventually have one for each state).  The repository for a state contains a json file that has the following data at the precinct level: congressional, state house, and state senate map data; election data for several years of elections; and population data.  The json is ready to be used in the [Metric Geometry Gerrymandering Group](https://mggg.org/) (MGGG)'s [gerrychain](https://github.com/mggg/GerryChain/releases) python library.  The json shared for each state was made using the jupyter notebook shared in that state's repository, and the cited data.  The data used is all taken from the [Redistricting Data Hub](https://redistrictingdatahub.org/) (RDH), and election data is the [Voting and Election Science Team](https://election.lab.ufl.edu/precinct-data/) (VEST) data that is shared on RDH.  We used the MGGG's [maup](https://github.com/mggg/maup) python library to clean and coalesce the data.

*Please note that this data is **not** guaranteed to be "correct" in any legal sense, and is not intended to be used for litigation purposes.*  This data, and the notebooks used to create it, are intended for researchers studying redistricting and wanting maps that were created after the 2020 census.  Please see a state's notebook and README for details, as well as the [maup](https://github.com/mggg/maup) documentation.  If a state's shapefile was small enough, we zipped and added that to the repository as well.  You can run the jupyter notebook for a state to create the shapefile, if it is not already in the repository.

This project has several contributors, most Computer Science students at the University of San Francisco (directed by Dr. Ellen Veomett).  Contributors are:

Ananya Agarwal<br>
Arbie Hsu<br>
Alusi<br>
Ellen Veomett
<br>
<br>
Special thanks to Jeanne Clelland, for her feedback and advice regarding maup and its `smart_repair` function in particular.

# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)
