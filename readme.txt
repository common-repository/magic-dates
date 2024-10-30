=== Magic Dates ===
Contributors: tsiger
Tags: dates, increase, ordinal, date, day, month
Requires at least: 5.0
Tested up to: 5.4.1
Stable tag: 1.3

Auto increased dates through the power of shortcodes and Magic Dates plugin!

== Description ==

If you are like me, you are probably responsible for updating content in (some) of your clients' sites. Have you ever had pieces of content like these:

1. "This is my 8th year in this industry [...]"
2. "Our little shop is up and running for 11 years [...]"
3. "9 years ago we decided to open our shop [...]"

Then, at some point next year your client calls and tells you to update the "11 years" to "12 years". Wouldn't be great if these number could be auto-increased?
And that's where "Magic Dates" comes to play.

How to use it:

Whenever you find yourself writing content in the editor, at the moment that you need an auto-increased number of years use the plugin like this:

(Example current year: 2020)

[magicdate]2005[/magicdate] => This will produce 15

If you want an ordinal number (1st, 2nd, 3rd etc) use it like this:

[magicdate ordinalize='true']2008[/magicdate] => This will produce 12th

Use the [magicdays]YYYY-mm-dd[/magicdays] shortcode to calculate the number of days between today and the given date

Easy eh?

== Installation ==

To install Magic Dates:

1. Upload the 'magic_dates.php' file into the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the shortcode [magicdate][/magicdate] in the editor to calculate the interval in years
4. Use the shortcode [magicdays][/magicdays] in the editor to calculate the interval in days

== Changelog ==

= 1.3 =
Add days interval calculations between today and a given date

= 1.2 =
Maintenance Release

= 1.1 =
Maintenance Release

= 1.0 =
Initial release