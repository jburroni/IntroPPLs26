# Notebooks

A Pyro tutorial for *Intro to Probabilistic Programming*: a variational autoencoder with
a normalizing-flow prior (trained on MNIST), plus a short activity on importance sampling
from the guide. Open the notebook in Google Colab and run it top to bottom; the first cell
installs the dependencies.

Adapted (and modified) from the Pyro tutorial [Variational Autoencoder with a Normalizing Flow prior](https://pyro.ai/examples/vae_flow_prior.html).

## Activity 7: Variational autoencoder with a normalizing-flow prior

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jburroni/IntroPPLs26/blob/main/notebooks/Jul-01/activity-7-vae-flow-students.ipynb)

## Running locally

Install the dependencies and launch Jupyter:

```bash
pip install pyro-ppl zuko
jupyter lab
```

A GPU speeds up training, but it is not required.
