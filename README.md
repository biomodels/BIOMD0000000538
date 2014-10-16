# BIOMD0000000538: MODEL1408070000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000538.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000538.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000538 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Clarke2000 - One-hit model of cell death in neuronal degenerations

This one-hit model fits different neuronal-death associated diseases for
different animal models.

This model is described in the article:

[A one-hit model of cell death in inherited neuronal
degenerations.](http://identifiers.org/pubmed/10910361)

Clarke G, Collins RA, Leavitt BR, Andrews DF, Hayden MR, Lumsden CJ, McInnes
RR.

Nature 2000 Jul; 406(6792): 195-199

Abstract:

In genetic disorders associated with premature neuronal death, symptoms may
not appear for years or decades. This delay in clinical onset is often assumed
to reflect the occurrence of age-dependent cumulative damage. For example, it
has been suggested that oxidative stress disrupts metabolism in neurological
degenerative disorders by the cumulative damage of essential macromolecules. A
prediction of the cumulative damage hypothesis is that the probability of cell
death will increase over time. Here we show in contrast that the kinetics of
neuronal death in 12 models of photoreceptor degeneration, hippocampal neurons
undergoing excitotoxic cell death, a mouse model of cerebellar degeneration
and Parkinson's and Huntington's diseases are all exponential and better
explained by mathematical models in which the risk of cell death remains
constant or decreases exponentially with age. These kinetics argue against the
cumulative damage hypothesis; instead, the time of death of any neuron is
random. Our findings are most simply accommodated by a 'one-hit' biochemical
model in which mutation imposes a mutant steady state on the neuron and a
single event randomly initiates cell death. This model appears to be common to
many forms of neurodegeneration and has implications for therapeutic
strategies.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000538](http://identifiers.org/biomodels.db/BIOMD0000000538).

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024).

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


