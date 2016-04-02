# DocNow Notebooks

This repository contains various Jupyter notebooks used by the DocNow team
for sharing and testing out ideas and code. They are written to run under 
Anaconda's Python 3 environment.

To use them you'll need to:

* install [Anaconda] for Python 3
* create an environment: `conda create --name docnow-notebooks anaconda`
* activate it: `source activate docnow-notebooks`
* install dependencies: `pip install -r requirements.txt`
* start Jupyter: `jupyter notebook`
* voilà, your browser should open with a view of the notebooks

Some of the notebooks may be dependent on the Twitter API so you should go over
to [apps.twitter.com], create an app and set these environment variables using
your keys:

* CONSUMER_KEY
* CONSUMER_SECRET
* ACCESS_TOKEN
* ACCESS_TOKEN_SECRET

If you want you can set these [in your Anaconda environment] so you don't have
to remember to set them all the time.

[Anaconda]: https://www.continuum.io/downloads
[apps.twitter.com]: https://apps.twitter.com
[in your Anaconda environment]: http://conda.pydata.org/docs/using/envs.html#saved-environment-variables
