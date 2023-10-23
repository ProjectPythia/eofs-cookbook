<img src="notebooks/images/nh-slp-eofs.png" alt="thumbnail" width="800"/>

# EOFs Cookbook

[![nightly-build](https://github.com/ProjectPythia/eofs-cookbook/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/eofs-cookbook/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/eofs-cookbook/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/656765685.svg)](https://zenodo.org/badge/latestdoi/656765685)

This Project Pythia Cookbook covers empirical orthogonal function analysis and its application to climate data.

## Motivation


## Authors

[Robert Ford](https://github.com/r-ford)

### Contributors

<a href="https://github.com/ProjectPythia/eofs-cookbook/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ProjectPythia/eofs-cookbook" />
</a>

## Structure


### Foundations



### Applications



## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through
[Binder](https://binder.projectpythia.org/), which enables the execution of a
[Jupyter Book](https://jupyterbook.org) in the cloud. The details of how this works are not
important for now. All you need to know is how to launch a Pythia
Cookbooks chapter via Binder. Simply navigate your mouse to
the top right corner of the book chapter you are viewing and click
on the rocket ship icon, (see figure below), and be sure to select
“launch Binder”. After a moment you should be presented with a
notebook that you can interact with. I.e. you’ll be able to execute
and even change the example programs. You’ll see that the code cells
have no output at first, until you execute them by pressing
{kbd}`Shift`\+{kbd}`Enter`. Complete details on how to interact with
a live Jupyter notebook are described in [Getting Started with
Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter.html).

### Running on Your Own Machine

If you are interested in running this material locally on your computer, you will need to follow this workflow:

1. Clone the `https://github.com/ProjectPythia/eofs-cookbook` repository:

   ```bash
    git clone https://github.com/ProjectPythia/eofs-cookbook.git
   ```

1. Move into the `eofs-cookbook` directory
   ```bash
   cd eofs-cookbook
   ```
1. Create and activate your conda environment from the `environment.yml` file
   ```bash
   conda env create -f environment.yml
   conda activate eofs-cookbook-dev
   ```
1. Move into the `notebooks` directory and start up Jupyterlab
   ```bash
   cd notebooks/
   jupyter lab
   ```
