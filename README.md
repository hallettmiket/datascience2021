[![Netlify Status](https://api.netlify.com/api/v1/badges/5593d0f5-bec7-41b1-bbe6-53aed0f28f2e/deploy-status)](https://app.netlify.com/sites/hallett-biology-datascience/deploys)

# General


 
The general structure of this website was modified from dataviz.andrewheiss.com

This repository contains the code for generating [this course](https://hallett-biology-datascience.netlify.app/).

## Theme  

This site customed the [`ath-tufte-hugo` theme](https://github.com/andrewheiss/ath-tufte-hugo) from Andrew Heiss.

When cloning for the first time, use this command to get the theme too:

    git clone --recursive https://github.com/hallettmiket/ath-tufte-hugo.git

To get the theme later, use this command:

    git submodule add \
      https://github.com/hallettmiket/ath-tufte-hugo.git \
      themes/ath-tufte-hugo

To update to the latest version of the theme, use:

    git submodule update --recursive --remote

