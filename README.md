Command line tools for expert searchers
==============================================================================

This is a demo site for teaching purposes. It contains a small collection of tools that I use. The tools itself are contained in the [bin/](bin/) folder. Some tools come from [this repository](https://github.com/knh11545/commandline4expertsearchers) where you can find more information on the philosophy. 

This repository can be made interactive by launching it in [mybinder.org](https://mybinder.org/). The tools can then be used in a terminal or in a [Jupyter notebook](https://jupyter.org/): 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/knh11545/cli4es/HEAD)

In addition, when launching this repository in [mybinder.org](https://mybinder.org/) the [Entrez Direct](https://www.ncbi.nlm.nih.gov/books/NBK179288/) tools from NLM are installed (see the [postBuild](.binder/postBuild) file). **Please, act responsible when using resources of mybinder.org and NLM and do obeye their usage guidelines!** For the Entrez API see [here](https://www.ncbi.nlm.nih.gov/books/NBK25497/#chapter2.Usage_Guidelines_and_Requiremen).

Currently, this is also a testbed on how to deploy a work environment.


## Fetching MeSH entry terms via API from the commandline

[This notebook](fetch_mesh_entry_terms.ipynb) is a demo of a tool used to fetch MeSH entry terms via API from the commandline. You can try it out.

Not (yet?) possible within Binder: Once you have the scripts installed on your local computer, it is possible to use the functionality directly from within a (better) text editor:

![Screencast: Use from within gvim editor](media/screencast_gvim.gif)

