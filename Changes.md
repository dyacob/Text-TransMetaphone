# Revision History for the Text::Transmetaphone Perl Distribution

## 0.08 Sun Mar  2 19:46:24 EST 2025
	- Migration to a Build.PL & GitHub system.
	- Pure Perl implementation of the `en_US` Double Metaphone algorithm.
	- Removing PerlXS and C code.

## 0.07 Sat Aug 12 12:59:32 EDT 2006
	- fixed installation problems
	- masked all unsigned chars to chars for stdlib string functions
          to make gcc 4.0.3 happy.  This could be hazardous.
	- tested with perl v5.8.7, on Ubuntu 6.06

## 0.06 Sat Apr 12 21:23:09 EDT 2003
	- fixes in am.pm.
	- am.pm resynced with Regexp::Ethiopic.

## 0.05a Mon Mar 24 07:28:19 EST 2003
	- minor documentation fixes.

## 0.05 Sat Mar 22 20:41:44 EST 2003
	- initial release.
