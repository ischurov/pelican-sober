# pelican-sober-iv #

Pelican-sober-iv is a modification of the original
[pelican-sober](https://github.com/fle/pelican-sober) theme.

Key differences are:

- Theme translated to Russian
- List of tags added to side panel
- Main page consists of article summaries
- Added Facebook Comments integration (have to add `PELICAN_SOBER_IV_FACEBOOK_APP_ID` config variable)
- Fixed some issues with social icons

This theme is used in [my blog](http://ischurov.github.io).

Below is README of the original Pelican-sober

# sober #

Pelican-sober is a very light theme focused on readability :

* Integration of [TinyTypo](http://tinytypo.tetue.net)
* Utilisation of the font Source Sans Pro
* Option to fade out sidebar to focus on article reading

This theme provides also classical features like Google Analytics, Twitter, Disqus and Pygments integration.


## Screenshot ##

![screenshot](screenshot.png)

## Sidebar options ##

* ``PELICAN_SOBER_ABOUT = "My name is Brian" `` option allows you to add a short *About* block in sidebar
* ``PELICAN_SOBER_STICKY_SIDEBAR = True | False `` option allows you to set the sidebar fixed (following scroll and fading out)

![screenshot2](screenshot2.png)


## Twitter cards ##

[Twitter card metadata](https://dev.twitter.com/docs/cards/types/summary-card) are useful to provides a better overview of your post
when a tweet point to it.

If you provide one of the two settings below, twitter card metadata will be automatically added for each post.

* ``PELICAN_SOBER_TWITTER_CARD_CREATOR = '__fle__' `` (author twitter account)
* ``PELICAN_SOBER_TWITTER_CARD_SITE = '__company__' `` (website/company twitter account)


## Credits ##

* Icons by [Jorge Calvo](http://dribbble.com/shots/1074961-Flat-Icons-EPS), slightly adapted by [Ingrid Hamard](http://ingrid.hamard.free.fr)

