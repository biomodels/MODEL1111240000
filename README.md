# MODEL1111240000: Huthmacher2010_MetabolicNetwork_Pfalciparum

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1111240000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1111240000.git@20140916`

## Usage

Importing the model package.

`import MODEL1111240000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Antimalarial drug targets in Plasmodium falciparum predicted by stage-specific metabolic network analysis.**   
Huthmacher C, Hoppe A, Bulik S, Holzhütter HG. _BMC Syst Biol._ 2010 Aug
31;4:120. [20807400](http://www.ncbi.nlm.nih.gov/pubmed/20807400) ,  
**Abstract:**   
BACKGROUND: Despite enormous efforts to combat malaria the disease still
afflicts up to half a billion people each year of which more than one million
die. Currently no approved vaccine is available and resistances to
antimalarials are widely spread. Hence, new antimalarial drugs are urgently
needed. RESULTS: Here, we present a computational analysis of the metabolism
of Plasmodium falciparum, the deadliest malaria pathogen. We assembled a
compartmentalized metabolic model and predicted life cycle stage specific
metabolism with the help of a flux balance approach that integrates gene
expression data. Predicted metabolite exchanges between parasite and host were
found to be in good accordance with experimental findings when the parasite's
metabolic network was embedded into that of its host (erythrocyte). Knock-out
simulations identified 307 indispensable metabolic reactions within the
parasite. 35 out of 57 experimentally demonstrated essential enzymes were
recovered and another 16 enzymes, if additionally the assumption was made that
nutrient uptake from the host cell is limited and all reactions catalyzed by
the inhibited enzyme are blocked. This predicted set of putative drug targets,
shown to be enriched with true targets by a factor of at least 2.75, was
further analyzed with respect to homology to human enzymes, functional
similarity to therapeutic targets in other organisms and their predicted
potency for prophylaxis and disease treatment. CONCLUSIONS: The results
suggest that the set of essential enzymes predicted by our flux balance
approach represents a promising starting point for further drug development.

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


