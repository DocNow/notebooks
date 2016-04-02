# DocNow Notebooks

This repository contains various Jupyter notebooks used by the DocNow team
for sharing and testing out ideas and code. They are written to run under 
Anaconda's Python 3 environment.

To use them you'll need to:

* install [Anaconda] for Python 3
* create the environment: `conda create --name docnow-notebooks --file environment.yml`
* activate it: `source activate docnow-notebooks`
* start Jupyter: `jupyter notebook`
* voilà, your browser should open with a view of the notebooks

Some of the notebooks may be dependent on the Twitter API so you should go over
to [apps.twitter.com], create an app and set these environment variables using
your application's keys:

* CONSUMER_KEY
* CONSUMER_SECRET
* ACCESS_TOKEN
* ACCESS_TOKEN_SECRET

You may want to set these [in your Anaconda environment] so you don't have
to remember to set them all the time.

If you want to try out functionality in the notebooks that is not dependent on
the Twitter API you also can launch them in the cloud at Binder:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/docnow/notebooks)

[Anaconda]: https://www.continuum.io/downloads
[apps.twitter.com]: https://apps.twitter.com
[in your Anaconda environment]: http://conda.pydata.org/docs/using/envs.html#saved-environment-variables
