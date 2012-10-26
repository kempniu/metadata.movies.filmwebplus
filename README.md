Synopsis
========

This is a metadata add-on for [XBMC](http://www.xbmc.org/) which scrapes movie information from [Filmweb.pl](http://www.filmweb.pl/) (a Polish movie database) and fills the missing data using [IMDB](http://www.imdb.com/). It also downloads fanarts from [TheMovieDB](http://www.themoviedb.org/).

Background
==========

Filmweb's website structure gets updated every once in a while and at a point I got tired of waiting for a new release of [smuto's Filmweb add-on](http://wiki.xbmc.org/index.php?title=Add-on:Filmweb) included in the official XBMC add-on repository. I decided to write a new add-on from scratch with two main objectives on my mind: extensive commenting and adhering to the KISS principle (wishful thinking...).

I dubbed the project *Filmweb+* to avoid confusion with smuto's add-on and allow the two to happily coexist in a single XBMC installation.

Installation
============

For now, the steps are:

1. Download the [latest version](https://github.com/kempniu/metadata.movies.filmwebplus/downloads).
2. In XBMC, navigate to *System* > *Settings* > *Add-ons* > *Install from zip file*.
3. Browse for the downloaded zip file and click *OK*.

Compatibility
=============

Only XBMC v11.0 (*Eden*) is supported at this time.

Disclaimer
==========

Feel free to report any issues with the scraper, though any feature requests will probably remain unheard. The main point of this project was to create a relatively simple scraper for my own personal use, without the intention of creating a full-blown project. I was also hoping the XML file would have some educational value for newbie scraper developers like myself.
