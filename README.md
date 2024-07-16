# EMU 2023 Agreement for Performance of Work with WHO Western Pacific Regional Office

Notebooks illustrate various epidemiological processes using the `summer2` platform.

To run these over Google Colab, follow the links below and the instructions in the first cell.

## Colab notebook links

1. [Simple SEIR model](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/01-seir-model.ipynb)

2. [Stratification](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/02-stratification.ipynb)

3. [Calibration](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/03-basic-calibration.ipynb)

4. [Heterogeneous mixing](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/04-hetero-mix.ipynb)

5. [Serial latent compartments](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/05-serial-latent-comps.ipynb)

6. [Tracking model outputs](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/06-tracking-model-outputs.ipynb)

7. [Multiple strains](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/07-multi-strain.ipynb)

8. [Post-immunity dynamics](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/08-immunity.ipynb)

9. [Renewal introduction](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/09-renewal.ipynb)

10. [Renewal implementation](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/10-renewal-app.ipynb)

11. [Tuberculosis](https://colab.research.google.com/github/monash-emu/WPROEpiModellingTraining/blob/main/notebooks/11-tb.ipynb)

## Local installation
To interact with the code from this repository on your local computer, you would need to undertake the following steps:
- [Git clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) the repository
```
git clone https://github.com/monash-emu/WPROEpiModellingTraining.git
```
- Install [conda](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html), and set up an environment
```
conda create -n summertraining python=3.10
conda activate summertraining
```
- Install the requirements into the active environment (this can take several minutes)
```
pip install -r requirements.txt
```
- Use an IDE with integrated notebook support like [Visual Studio Code](https://code.visualstudio.com/download), or [install jupyter](https://jupyter.org/install)

## Other resources
The notebooks listed above provide a brief introduction to participants in the 2023/2024 capacity building program.

Further resources are available through the Monash EMU 
[homepage](https://monash-emu.github.io).
In particular, we draw your attention to:
- Full online [documentation](https://summer2.readthedocs.io/en/latest/) of the `summer` platform
- [Textbook](https://github.com/monash-emu/summer-textbook) of infectious disease modelling using `summer`

## Notes on the manual
The PDF of the training manual is generated from the supplied notebook file using [Quarto](https://quarto.org)
```
quarto render .\WPRO_WHO_Capacity_Training_Manual.ipynb --to pdf --toc
```
