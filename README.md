Jekyll 301 Redirects Generator
========================

A Jekyll generator to create redirects for all old urls to a new structure

This plugin creates a list of 301 redirects from old Wordpress urls to new ones.
It currently only supports one source url structure and one target structure:

  source:    <olddomain>/year/month/day/postname

  target:    <newdomain>/postname

Whenever you use Jekyll generate or preview, the redirects file will be created in the source folder. The default file name is "htaccess_redirects"

Author
======

Mathieu Davy :: hello@ekynoxe.com :: [@ekynoxe](http://twitter.com/ekynoxe)


Copyright
=========

Copyright (c) 2014 Mathieu Davy. See [Licence](https://github.com/ekynoxe/JekyllRedirectsGenerator/blob/master/LICENCE) for details.