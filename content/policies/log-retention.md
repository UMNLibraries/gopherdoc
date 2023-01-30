---
title: Log Retention Policy
date: "2022-09-12"
description: "Web Development Log Retention Policy"
slug: log-retention
---

|||
|:----|:----|
| Author | Cody Hanson |
| Date | 2014-02-20 |
| Last Reviewed | 2022-09-14 | 
| Original | [Google Drive](https://docs.google.com/document/d/1dFpspQ4gP-csUwFO-7ejyoqw-nh1ubNe4L4cT1yG3QQ/edit?usp=sharing) |

Unless otherwise noted, the Web Development department will retain log files for applications under the department’s purview for a maximum total of two calendar years past the year of logging, and will purge three-year old logs at the beginning of each calendar year.


e.g. Logs generated during calendar year 2013 will be retained through the end of 2015, and purged at the beginning of 2016.


This policy is intended to ensure that log data is destroyed after a reasonable time period has elapsed, and describes the longest possible period we will retain such data. Our commitment to retain log data no longer than three years does not constitute a promise to retain all log data for this same period. The default configuration of some of our applications (such as MySQL) will use rolling logs that are steadily purged, and at any moment may contain only a few hours or days of logs. Where possible, Web Development will use the OIT standards for log retention to determine minimum retention periods (http://www.oit.umn.edu/security/security-framework/log-management/).


If there is a demonstrated need elsewhere in the libraries for retention of logs beyond this period, Web Development will turn over logs to the appropriate department or individual at the end of the retention period provided the department or individual can make available to Web Development the retention policy under which the logs will be subsequently managed. Further, Web Development has a strong preference that logs retained beyond the standard two-year period be subject to deidentification.


Among the applications affected by this policy:

- Apache (for www.lib and hsl.lib domains)
- EZProxy
- Drupal (www.lib and hsl.lib)


Upon approval of this draft policy by the appropriate Libraries bodies (D&T Directors? Cabinet?) we propose to put this policy into place immediately by purging logs dating from 2011 and earlier.
