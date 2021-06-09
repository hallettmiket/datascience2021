# General

The structure of this website was modified from dataviz.andrewheiss.com

This repository contains the code for generating [datascience.mikehallett.science](https://datascience.mikehallett.science).

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
