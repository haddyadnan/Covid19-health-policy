# Covid19-health-policy
Change point analysis to quantify the impact of African government policy interventions to slow the spread of COVID-19

The main objective  is to quantify the statistical significance of a public health policy introduced by African governments to slow down the spread of COVID-19. This repo aim to concentrate on Egypt as case study.

# DATA

The Center for Systems Science and Engineering (CSSE) at Johns Hopkins University Covid19 project provides the necessary data to use. The python package that comes with the key code (Priesmann et al.) already contains a python API to easily download the relevant data from John Hopkins database.

# Analysis

This analysis is based on PYMC3 library and this work consist of combining Markov Chain Monte Carlo sampling with Bayesian Inference . The analysis is inspired by a similar work by Jonas Dehning et al, you can find the article to their research [here](https://arxiv.org/abs/2004.01105) and a link to their repository [here](https://github.com/Priesemann-Group/covid19_inference)
