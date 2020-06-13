## 3.0.1 / 2020-06-13 (jknight)
==================
  * Updated to 60/40 split

3.0.0 / 2020-06-12 (jknight)
==================

  * Moved all code into osacript (it was previously calling out to layouts.scpt
  * Removed all grunt/dist/lib/etc files in favor of single workflow file
  * Removed friendly named positions ("top", "middle") etc to simplify code
  * Updated lookup for current window - it was previously failing to position some applications (Slack, Mathematica, various open source apps)
  * Updated positions to give slightly larger left-side work area
  * Updated key shorcuts to give a more natural pairs feel:
    * 1 / 2: left / right
    * 3 / 4: left / right tops
    * 5 / 6: left / right bottoms

2.1.0 / 2013-05-03 
==================

  * [grunt] runTest task
  * [displays] factor in dock size
  * Merge branch 'feature/workflow'

2.0.0 / 2013-04-17 
==================

  * removed site submodule
  * [alfred] allow custom layout
  * [alfred] updated workflow
  * [grunt] added banner on top of applescript file
  * [alfred] build with version in description, script for zipping workflow
  * [alfred] updated workflow
  * added custom size example to alfred, added notifications
  * allow for passing in custom size
  * changed alfred bundle id
  * complete rewrite and initial work on alfred workflow
  * updated site

0.0.5 / 2012-04-19 
==================

  * updated makefile and added DS_store to gitignore
  * updated alfred template
  * updated docs
  * cache screen size and fix if only one monitor

Older Releases
==============

  * fixed some issues with multi monitors
  * updated site
  * fixed escaping chars in alfred extension
  * multi monitor support
  * moved TODO file into docs
  * 0.0.2 - fixed bottom
  * updated docs
  * fixed paths for docs
