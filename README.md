# MOBO_pub
Files relevant for the publication

## Repository Structure
### GSMs
Contains the GSMs used for this project, which are not part of the COBRApy toolbox.

### data
Contains the data used to create the Figures in the publication.

### figures
Contains the code to perform the Multi-Objective Bayesian Optimisation with which the results in data were generated alongside the code for the generation of the published figures.

## Usage
To generate the published figures, run everything in the corresponding Figure*_Main*.ipynb file except the section titled "Running the Optimisation & Plotting the Result". When loading the modified iJO1366 model, adjust for your own folder structure. When loading the data under the header "Only Plotting", use the corresponding data found in the data folder in this repository.

To run the full Multi-objective optimisation, potentially with your own model, run the desired Figure*_Main*.ipynb file and adapt the parameters, including medium composition, costs and bounds to your needs.
