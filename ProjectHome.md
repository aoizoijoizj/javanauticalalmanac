# Calculates Nautical Almanac. #
Written in Java, based on **Jean Meeus Algorithms**, and the work done by **Henning Umland**.
Works for Sun, Moon, main planets, and stars.
It generates an XML file that can then be transformed and published, like with FOP for example (other project takes care of that part).
The delta T parameter is part of the data to feed the program with.
Needs the GeomUtil class defined in the [Java NMEA Parser](http://javanauticalalmanac.googlecode.com/) project (in Google Code as well).
<br><br>
This project is part of the Navigation Desktop project. Build it from <a href='http://code.google.com/p/oliv-soft-project-builder/'>there</a>.