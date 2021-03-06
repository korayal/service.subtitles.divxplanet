PlanetDP Kodi Subtitle Addon
======================

This is an unofficial Kodi Subtitle Addon to be able to easily download subtitles from planetdp.org


# Changelog
**0.2.0**
* Since divxplanet.com / altyazi.org is powered down, plugin now is adapted for
  PlanetDP.org which is it's successor
* Added support to select the title when it's not possible to select the correct title
* Added support for season packs

**0.1.1**
* Set default encoding to utf8
* Normalized file names before using them

**0.1.0**
* Upgraded versions for modules used in the addon
* Replaced usage of `mechanize` with `requests` module for simpler scraping
* [Issue #4] Fixed an issue with unicode handling on file names
* Year detail added to search for better filtering
* Some code refactoring

**0.0.12**
* [Issue #3] Better file extraction handling

**0.0.11**
* Fixed searches for series that has the same name with a movie

**0.0.10**
* Fixed searches for series with year value in their titles

**0.0.9**
* Fixed another typo
* Search from Google removed because of some restrictions

**0.0.8**
* Fixed the typo made on previous version

**0.0.7**
* Domain used for search replaced from **divxplanet.com** to **altyazi.org**

**0.0.6**
* Downloaded file handling improved [emreuygur]
* Movie year may differ from the original one [emreuygur]

**0.0.5**
* filename encoding handling changed

**0.0.4**
* fixed downloaded filename encoding
* fixed subtitle description text encoding

**0.0.3**
* added tags required for XBMC addon database
* removed dummy translations
* removed print statements

**0.0.2**
* fixed empty year search on tv shows
* fixed empty result crash
* normalized saved filenames
* cleaned up text in parantheses in tv show titles

**0.0.1**
* move the service out of XBMC Subtitles
