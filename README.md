Synopsis
========

This is a metadata add-on for [Kodi/XBMC](http://kodi.tv/) which scrapes movie information from [Filmweb.pl](http://www.filmweb.pl/) (a Polish movie database) and fills the missing data using [IMDB](http://www.imdb.com/). It also downloads fanarts from [TheMovieDB](http://www.themoviedb.org/).

Background
==========

Filmweb's website structure gets updated every once in a while and at a point I got tired of waiting for a new release of [smuto's Filmweb add-on](http://kodi.wiki/view/Add-on:Filmweb) included in the official Kodi add-on repository. I decided to write a new add-on from scratch with two main objectives on my mind: extensive commenting and adhering to the KISS principle (wishful thinking...).

I dubbed the project *Filmweb+* to avoid confusion with smuto's add-on and allow the two to happily coexist in a single Kodi installation.

Installation
============

For now, the steps are:

1. Download the [latest version](https://github.com/kempniu/metadata.movies.filmwebplus/archive/master.zip).
2. In Kodi, navigate to *System* > *Settings* > *Add-ons* > *Install from zip file*.
3. Browse for the downloaded zip file and click *OK*.

Compatibility
=============

The following Kodi/XBMC versions are supported:

* Kodi 15 *Isengard*
* Kodi 14 *Helix*
* XBMC 13 *Gotham*
* XBMC 12 *Frodo*
* XBMC 11 *Eden*

Disclaimer
==========

Feel free to report any issues with the scraper, though any feature requests will probably remain unheard. The main point of this project was to create a relatively simple scraper for my own personal use, without the intention of creating a full-blown project. I was also hoping the XML file would have some educational value for newbie scraper developers like myself.
