# cl_sq_demo-binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/cl_sq_demo-binder/master?filepath=index.ipynb)


*tl;dr:*  
Click any `launch binder` badge on this page to use the demonstrations inside your browser.

------


***cl_sq_demo-binder:  Jupyter notebook environment for demonstrating some sequence work resources.***

A launchable, working Jupyter-based environment that has a collection of demonstrations of useful resources on command line, or also accessible in Jupyter sessions, for manipulating sequence files.

Meant to be self-contained and ready-to-go. No installations or copying of notebooks is necessary if `launch binder` is clicked. Everything will just work. Of course, static versions of the notebooks can also be used. I recommend rendering the static versions by placing the URLs into the [nbviewer](https://nbviewer.jupyter.org/). The views provided by [nbviewer](https://nbviewer.jupyter.org/) look best and Github's rendering often times out (your mileage may vary).

**Note: THIS REPO WAS STARTED AFTER SEVERAL OTHER DEMO NOTEBOOKS (many meant to be static) WERE MADE FOR MY SEQUENCE SCRIPTs, and so don't expect all demos availables to be here yet. I hope to move those (slowly) here as well in order to be available in active form. Until then pointers for those scripts will continue to point to the unmoved, static demos. In other words, it is always best to consult the description page for any of my scripts first. The demos are only meant to expand on that information.**


## Attributions

I tried to include attributions for each resource when they were not mine; however, let me know if you catch an oversight or you'd like to suggest an improvement.

## Related

- [blast-binder](https://github.com/fomightez/blast-binder)
- [patmatch-binder](https://github.com/fomightez/patmatch-binder)
- [circos-binder](https://github.com/fomightez/circos-binder)
- [hhsuite3-binder](https://github.com/fomightez/hhsuite3-binder)
- [mscscan-binder](https://github.com/fomightez/mcscan-binder)

Plus, see [here](https://github.com/fomightez/structurework#related-binderized-utilities) for a listing of resources in a similar vein yet targeted to macromolecular structure data. In particular, see [cl_demo-binder](https://github.com/fomightez/cl_demo-binder) for the companion set to this one.



## Technical notes

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.


**Currently (November 2020), the `get_protein_seq_as_FASTA.py` and presumably other scripts that use yeastmine/intermine from [my YeastMine repository](https://github.com/fomightez/yeastmine) work here.**  The issue was that the current version of the `intermine` package installed by conda and pip is outdated at present time. The current development version fixes an issue with using templates and perhaps other things in the current Python version, and so is preferably the one to use at this time, see [here](https://github.com/intermine/intermine-ws-python/issues/40). Note that to get the development branch of the intermine webservice installed, this repository was updated as shown [here](https://github.com/fomightez/cl_sq_demo-binder/commit/59d6d3e61abf0d43dbaad71445d41f552b741496). That approach should be easily applied to other repositories or run `%pip install https://github.com/intermine/intermine-ws-python/archive/dev.zip` in a cell in a notebook in a session. (I haven't yet checked whether the used of `%pip install https://github.com/intermine/intermine-ws-python/archive/dev.zip` is compatible with having installed `intermine` from the traditional sources, which presently give an older version, prior.)


Click `launch binder` below to start using the demonstrations.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/cl_sq_demo-binder/master?filepath=index.ipynb)
