# BIOMD0000000088: Maeda2006_MyosinPhosphorylation

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000088.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000088.git@20140916`


# Model Notes


The model reproduces Fig 2B, D, F, and 2H. The dynamics correspond to a
stimulus of 1 U/ml of thrombin which is equal to 0.01 uM. Phosphorylated MLC
is the sum of pMLC (s359) and ppMLC (s360). A slight discrepancy in peak
values of species between the figure in the paper and simulation result might
be due to different initial conditions in the two sets. The model was
successfully tested on MathSBML. It is possible to simulate the model on other
software that do not support "Events" at this time by removing the
"listOfEvents" and substituting a value of 0.01 for thrombin (s2). This does
not change the model very much. With the latter format, the model was also
successfully tested on Copasi.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


