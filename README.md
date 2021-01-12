# Peace Agreements visualization
The [Peace Agreements database](https://www.peaceagreements.org) or PA-X, its a database that holds 1868 peace agreements generated during 157 peace processes dating from 1990 to 2020.
In this visualization the original dataset has been used to generate a new dataset throughout a set of transformations allowing to properly and easily visualize the topics and subtopics mentioned in those peace agreements.

![Example Viz](https://github.com/boschmateo/peaceagreements/viz_example.png?raw=true)
## Project files

* `pax_all_agreements_data.xlsx`: Original dataset downloaded from the official [website](https://www.peaceagreements.org/search).
* `PEACE AGREEMENTS DATABASE AND DATASET V3.pdf`: Original description of the dataset.
* `peace_agreements_analysis.ipynb`: Jupyter Notebook that holds the first contact with the data. It also includes the necessary transformations to obtain the modified dataset.
* `aggrements_long.xlsx`: Transformed dataset obtained by running the Jupyter Notebook file.
* `country.csv`: File containing ISO codes of the countries and additional information used.
* `peaceagreements_viz.twb`: Visualization created using Tableau Desktop.

## Requirements

* Python3 and its dependencies in `requirements.txt`.
* Tableau Desktop.
