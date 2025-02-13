puckfetcher
===========

A simple command-line podcatcher.

GitHub Project: (https://github.com/lunemercove/puckfetcher)

Supports Python 3.6+. Please report any issues on the GitHub project or reach out over email.

| You’ll need setuptools (https://pypi.python.org/pypi/setuptools) to run this in its current
| state. Go get it, clone this repo, and you can run the below commands. Should work on OSX and
| Linux, from the command line. You’ll want a default config file, name it config.yaml and look at
| example\_config.yaml to see how it should be structured.

Directory for config file:

-  OSX: /Users/[USERNAME]/Application Support/puckfetcher/config.yaml
-  Linux: /home/[USERNAME]/.config/puckfetcher/config.yaml

Build + Install:

::

    python3 setup.py install

Test:

::

    python3 setup.py test

Features
--------
-  Download any podcast with an RSS URL.
-  Download newest episodes on demand.
-  Download any episode from a podcast's backlog.
-  Respects podcast authors' websites - rate limits, checks when feed was last updated when trying
   to refresh.
-  Provides progress on downloads.
-  Provides summary of recently-downloaded podcasts per-session, as well as summary of
   recently-downloaded episodes per-podcast.
-  Add MP3 tag support to clean up tags based on feed information if it’s messy.

Ideas for Future Releases
-------------------------
-  Text-based progress for other time-consuming actions.
-  Support PyPy (when it supports 3.6+).
-  Allow parallel downloading.
