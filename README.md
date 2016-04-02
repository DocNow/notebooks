This repository contains various Jupyter notebooks used for sharing ideas
and testing things out. They are written to run under Anaconda's Python 3
environment.

To run these you'll need to:

* install [anaconda] for Python 3
* create an environment: `conda create --name docnow-notebooks anaconda`
* activate it: `source activate docnow-notebooks`
* install dependencies: `pip install -r requirements.txt`
* start jupyter: `jupyter notebook`
* your browser should open with a view of the notebooks

Some of the notebooks may be dependent on the Twitter API so you should go over
to [apps.twitter.com], create an app and set these environment variables using
your keys:

* CONSUMER_KEY
* CONSUMER_SECRET
* ACCESS_TOKEN
* ACCESS_TOKEN_SECRET

If you want you can set these [in your anaconda environment] so you don't have
to remember to set them all the time.

[anaconda]: https://www.continuum.io/downloads
[apps.twitter.com]: https://apps.twitter.com
[in your anaconda environment]: http://conda.pydata.org/docs/using/envs.html#saved-environment-variables
