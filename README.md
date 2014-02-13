###dateformatjs - Meteor Smart Package

JavaScript date format package for Meteor 

This a tiny (~100 lines) piece of [date/time formatting](http://blog.stevenlevithan.com/archives/date-time-format) code
by [xregexp author Steven Levithan](https://github.com/slevithan), repackaged for Meteor. It hasn't been maintained since 2009.

###How to use?

1. Install [meteorite](https://github.com/oortcloud/meteorite)
2. `mrt add date-formatjs`

Check out the [dateformat docs](http://blog.stevenlevithan.com/archives/date-time-format) for more details.

### Example:

	dateFormat(new Date().getTime(), "dddd, mmmm dS, yyyy, h:MM TT");

