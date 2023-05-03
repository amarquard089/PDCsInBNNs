# Eine empirische Analyse von Prior-Daten Konflikten in Bayesianischen neuronalen Netzen
This Repository contains the necessary code to reproduce the results from the bachelors thesis "Eine empirische Analyse von Prior-Daten Konflikte in Bayesianischen neuronalen Netzen".

## Contents
- bilder: Contains the pictures used in the bachelor thesis
- simple_BNN.ipynb: Contains the code for the analysis in chapter 4.1
- deep_BNN_fix_first_two_layers.ipynb: Contains the code for the analysis in chapter 4.2.1
- deep_BNN_full.ipynb: Contains the code for the analysis in chapter 4.2.2


## Usage
To create the environment run
```bash
conda env create -f requirements.yml
```
and
```bash
conda activate pdcsinbnns
```
After that you can just use jupyter-lab / jupyter-notebook or VSCode with the appropriate extensions in order to run the notebooks.
<br>
The pictures in the folder "bilder" where modified using sips, e.g.
```bash
sips -z 800 1600 bilder/LM_10.png
```
Analogous they can be modified folderwise as
```bash
for filename in ./*png; do
    sips -z 800 1600 $filename
done
```
