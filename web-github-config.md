# Course website configuration and GitHub repositories

## GitHub repositories
This course uses several GitHub repositories to manage course materials. A list with their descriptions is below.

1. [https://github.com/IntroGM/](https://github.com/IntroGM/): This is the main GitHub organization for the course containing all course repositories.
2. [https://github.com/IntroGM/admin](https://github.com/IntroGM/admin): This admin repository is for notes about the course website configuration, changes in the course, plans, etc. You're viewing this file in the admin repository :open_mouth:.
3. [https://github.com/IntroGM/introgm.github.io](https://github.com/IntroGM/introgm.github.io): This repository exists solely to redirect users to the current version of the course page. In this way we can archive earlier versions and keep them available. We can also develop materials without having them live.

## Preparing to build course pages using Sphinx
We use Sphinx for the course website. With the default Anaconda installation we should be mostly ready to roll, but there are a few installations needed.

1. `conda install -c conda-forge nbsphinx` - Installs the sphinx extension needed to build Jupyter Notebooks
2. `conda install -c damianavila82 rise` - Installs RISE for converting Jupyter Notebooks to online presentations using reveal.js 
