---
title: multiMonthTitleFormat
since_version: 6.1.0
---

In [multiMonth view](multimonth-view), the format of the text above each month.

<div class='spec' markdown='1'>
[format string](date-formatting-string)
</div>

If the calendar spans a single year, the default is `{ month: 'long' }` (ex: `"January"`).

If the calendar spans *multiple* years, the default is `{ month: 'long', year: 'numeric' }` (ex: `"January 2023"`).