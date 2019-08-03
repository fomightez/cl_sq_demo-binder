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

See [here](https://github.com/fomightez/structurework#related-binderized-utilities) for a listing of resources in a similar vein yet targeted to macromolecular structure data. In particular, see [cl_demo-binder](https://github.com/fomightez/cl_demo-binder) for the companion set to this one.

## Technical notes

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

**TO DO:**  
August 3, 2019, I pinned version of Matplotlib to 3.0.3 because that allowed heatmap used in [this demo](https://github.com/fomightez/cl_sq_demo-binder/blob/master/notebooks/Demo%20of%20script%20to%20calculate%20differences%20between%20sequences%20in%20multiFASTA%20file.ipynb) notebook to work. Unpin when 3.1.12 released ---> see https://github.com/matplotlib/matplotlib/issues/14675 . Current version as of writing this is 3.1.11 and it has the heatmaps cutoff.  
TEST ANY [NEW RELEASE](https://github.com/matplotlib/matplotlib/releases) AND UNPIN IN `environment.yml.`


Click `launch binder` below to start using the demonstrations.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/cl_sq_demo-binder/master?filepath=index.ipynb)
