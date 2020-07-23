# Accessing National Library of Estonia Collections workshop

This repository presents simple tools and a workflow to access the Digitized Newspaper Collections at the National Library of Estonia. The collection currently includes 386,950 issues from 2200 periodical publications (including journals, magazines and newspapers). This amounts to a total of 3,635,503 pages of text and 6,298,369 articles segmented from this. Some of these texts are free to access, others need to follow some access restrictions due to copyright and other legal requirements. This workflow connects to the freely accessible issues in the collection that have been segmented, amounting to ~3,833,000 articles.

NB! These texts have the licence: Free access - restricted use. This publication's copyright protection has expired but the rights of works contained in the publication may be protected. The works may be used for private purposes or study and research purposes. In other cases please ascertain that the copyright term has expired.

The workflow can be followed in Jupyter or RStudio, to run them click on the following links.

Jupyter+R: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/peeter-t2/RR_GLAMlab_pilot/master)

RStudio: [![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/peeter-t2/RR_GLAMlab_pilot/master?urlpath=rstudio)


## Usage

There are three script files currently in this repository.
- *data_overview.Rmd* - gives an overview of the collection and allows further exploration of the metadata.
- *access_data.Rmd* - link to the archived full-text files on [data.digar.ee](data.digar.ee)
- *search_and_concordance.Rmd* - a simple workflow to search texts and export concordances for later study.

The Notebooks are currently run in a [MyBinder environment](https://mybinder.org/) which has memory limitations, allowing at least 1Gb of RAM, but no more than 2Gb (if memory is exceeded the system is restarted). For this, it is recommended to work with no more than 200 data files at the same time. Binder is meant for short term usage. It will automatically shut down user sessions that have more than 10 minutes of inactivity (if you leave your window open, this will be counted as “activity”) and can be expected to reliably work for 12 hours.

However the script files can easily be used on your own computer (just install [R](https://cran.r-project.org/) and then [RStudio](https://rstudio.com/products/rstudio/download/)), and you are welcome to work with any and all texts locally. Download the whole Github repository [here](https://github.com/peeter-t2/RR_GLAMlab_pilot/archive/master.zip).

## License

The workflow has been built keeping in mind the principles of Open Science in scientific computing [Wilson et al. 2017](https://doi.org/10.1371/journal.pcbi.1005510), aiming for a maximally transparent and simple interface. 
The code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license, and is free to use for whatever purpose.

The workflow is registered at Zenodo, and can be cited as

- Tinits, Peeter (2020). Rahvusraamatukogu digilabori tööriistad tekstimaterjali ligipääsuks ja töötlemiseks. Zenodo. http://doi.org/10.5281/zenodo.3953795
- Tinits, Peeter (2020). GLAMlab toolkit to access and analyse texts at the National Library of Estonia. Zenodo. http://doi.org/10.5281/zenodo.3953795

Stable location now at [https://github.com/peeter-t2/RR_GLAMlab_pilot/](https://github.com/peeter-t2/RR_GLAMlab_pilot/).
