Changelog
=========

## Version 0.5.1
_2020-04-30_
* Add option to force server-side media scan
* Change to local artist sorting (case-insensitive)
* Fix crash while offline (#25)
* Fix read timeout not being respected
* Fix switching to playlist on app resume

## Version 0.5.0
_2020-01-15_
* Add 24kbps and 48kbps options
* Add adaptive icon
* Add support for p= authentication
* Change to MediaStyle playback notification
* Fix SSID selection
* Fix keyboard being visible when switching to now playing
* Fix now playing icon when using light theme

## Version 0.4.1
_2019-12-28_
* Revert attempt to fix infinite loop as it sometimes deleted valid files.

## Version 0.4.0
_2019-12-22_
* Add support for .opus files
* Fix HTTP support
* Fix infinite loop when playing contains only invalid files
* Overhaul themes
* Replace raster images with vector images

## Version 0.3.3
_2019-03-17_
* Fix [Funkwhale](https://funkwhale.audio/) (Subsonic API) support
* Use query parameters instead of body
* Disable most "now playing" swipe gestures - too sensitive and often
  accidentally triggered.
  Only swipe left/right to change track ramains.


## Version 0.3.2
_2018-07-05_
* Prevent now playing from closing upon resuming
* Only show save and delete playlist functions in menu
* Stop hiding playlist on resume


## Version 0.3.1
_2018-06-03_
* Fix crash on now playing & playlist while in landscape


## Version 0.3.0
_2018-05-12_
* Center cover art on now playing screen
* Use blurred cover art to fill empty space on now playing screen
* Fix extra whitespace on now playing while offline


## Version 0.2.5
_2018-03-24_
* Fix pausing playback on disconnect on API 26+
* Allow testing connection in settings while offline


## Version 0.2.4
_2018-03-24_
* Fix launch crash on Lollipop and earlier (added READ_PHONE_STATE for API <= 22) [#23](https://github.com/nvllsvm/Audinaut/issues/23)


## Version 0.2.3
_2018-02-27_
* Fix notifications on API 26+
* Target SDK 27
* Dependency updates


## Version 0.2.2
_2017-06-11_
* Use black background when loading application (previously white)
* Begin transition to Kotlin
* Target SDK 26
* Dependency updates
* Cleanup


## Version 0.2.1
_2017-04-13_
* Form correct REST path. Fixes #7


## Version 0.2.0
_2017-03-14_
* Use OkHttp for all HTTP calls
* Dependency upgrade and cleanup
* Bug fixes
* Cleanup


## Version 0.1.2
_2017-03-04_
* Forgot to bump the app version in tag 0.1.1, so now it's 0.1.2.
* By default, hide music from other apps.
* Change account type to be specific to Audinaut.


## Version 0.1.1
_2017-02-27_
* Merge ServerProxy into Audinaut
* Update Kryo to 4.0.0


## Version 0.1.0
_2017-12-18_
* Initial release.
