1.3.0 / X-X-X (not released)
==================

  * Added modifier methods firstOfMonth(), lastOfMonth(), nthOfMonth(), next(), previous(), and so on
  * Added modifiers startOfWeek() and endOfWeek()
  * Added testing helpers to allow mocking of new Carbon(), new Carbon('now') and Carbon::now()
  * Added formatLocalized() to format a string using strftime() with the current locale
  * Improved diffInSeconds()
  * Improved [add|sub][Years|Months|Days|Hours|Minutes|Seconds|Weeks]
  * Docblocks everywhere ;(
  * General Code cleanup

1.2.0 / 2012-10-14
==================

  * Added history.md
  * Implemented __isset() (thanks @flevour)
  * Simplified tomorrow()/yesterday() to rely on today()... more DRY
  * Simplified __set() and fixed exception text
  * Updated readme

1.1.0 / 2012-09-16
==================

  * Updated composer.json
  * Added better error messaging for failed readme generation
  * Fixed readme typos
  * Added static helpers `today()`, `tomorrow()`, `yesterday()`
  * Simplified `now()` code

1.0.1 / 2012-09-10
==================

  * Added travis-ci.org

1.0.0 / 2012-09-10
==================

  * Initial release
