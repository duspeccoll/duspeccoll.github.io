---
layout: default
category: ArchivesSpace
title: Dates
---

{% assign content=site.data.dates %}

The Dates sub-form in ArchivesSpace manages information about various types of dates relating to all other data models within the system. The Dates sub-form is consistent across all ArchivesSpace metadata editing forms in which it appears.

When adding Dates in ArchivesSpace, be sure to consult the instructions for the specific component level of the record you are adding, as there may be additional rules specific to that component level not mentioned here.

When adding Expressions to a date, there are certain conventions we follow in instances where the date is unknown or cannot be determined with certainty. These mainly affect how machine-readable date fields (those labeled 'Begin' and 'End,' which appear when the user selects a Type in the Dates sub-form) are populated. Our conventions are as follows:

* **When a date range is definitively known:** Enter the expression as two DACS-compliant dates, separated by a hyphen, e.g. "1937-1993," "1945 June 1-August 31." In the 'Begin' field, enter the first date in the range, in machine-readable form; in the 'End' field, enter the last date in the range in the same way.
* **When a single date is known with some degree of uncertainty:** Enter the expression using the keyword 'circa,' e.g. "circa 1955." Assign the date a type of 'inclusive,' the 'Begin' field a date equal to five years prior to the known single date, and the 'End' field a date equal to five years after the known single date.
* **When a single date is known with certainty to fall within a range:** Enter the expression using the keyword 'between,' e.g. "between 1939-1949." Assign the date a type of 'inclusive,' the 'Begin' field the first date in the range, and the 'End' date the last date in the range.

## Field guidelines for Dates

{% include fields.html %}
