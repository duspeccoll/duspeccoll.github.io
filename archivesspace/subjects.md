---
layout: default
category: ArchivesSpace
title: Managing Subject Headings
---

{% assign content = site.data.subjects %}

Subject headings are used in ArchivesSpace to link descriptive metadata records to terms bearing a topical, geographic, form, or other relationship to the items described by those records. Subject headings are managed separately from Agents, that is, named entities such as people or organizations. Common subject headings include the topic or subject of the item, its form or genre (e.g. "photograph," "map"), or the location of a photograph or geographic coverage of an audiovisual item.

## Fields for Subject Headings

{% include fields.html %}

## Deleting and Merging Subject Headings in ArchivesSpace

When two headings in ArchivesSpace are found to represent the same concept, it may be necessary to de-duplicate them. This may be done in one of two ways. If the heading contains no linked records, you may delete it. You can determine whether a heading is linked to any records in the database by viewing it; there will be a section of the record entitled “Linked Records” showing the records to which your heading is linked.

To delete the record, click on the red “Delete” button at the upper right of the pane. Note: You cannot un-delete a record once it has been deleted. If a record was deleted in error, alert the Archives Processing Librarian; they may be able to restore the record from backup.

If a heading contains links to other records, you should instead merge it into another record. To do this, navigate to the record for the heading you wish to keep, and click on the “Merge” dropdown, also at the upper right of the pane. A window will appear asking you to input the records you would like to merge into the current record.

You may enter the subject you wish to merge in one of two ways. You can do a search for it in the text box, as you would if you were attaching it to a record; or you may browse for it by clicking on the drop-down button, then selecting “Browse.” Once you have selected the heading you wish to merge, click on the “Merge” button.

In the background, this will detach any linked records from the heading you are merging, re-attach them to the heading into which it is being merged, then delete the original heading.
