---
layout: default
title: Description of Archival Materials
---

This document contains description guidelines for Resource and Archival Objects. In Special Collections and Archives, each archival collection should be assigned a description level, on a scale from 1 to 3. Level 3 represents the highest level of description a collection may receive; Level 1 is the lowest.

To view specific data entry instructions for ArchivesSpace records, click [here](archivesspace).

## Level 1 Description

At Level 1, the Resource should contain the following metadata properties...

* A title
* A local classification number, to uniquely identify the Resource within its collection area
* A level of description (required by ArchivesSpace)
* A date of creation of the records, if known
* The extent of the records (this can be calculated by ArchivesSpace if the resource's container records have container profiles)
* An Abstract note
* An agent link identifying the creator or immediate source of the collection materials, if known
* At minimum, three subject terms or headings of any type

At Level 1, the Resource components should be described as follows...

* One Top Container record per barcoded physical item, with the following information attached:
  * Barcode
  * Component ID
  * Container Profile (for calculating extent)
* Sufficient arrangement and description to link these Top Containers to their constituent archival resources. In the simplest form, this is done by creating one Archival Object for each container, then linking the Top Containers to that.

## Level 2 Description

At Level 2, in addition to the specifications from the levels above, the Resource should contain the following metadata properties...

* A Scope/Contents note
* A Biographical/Historical note

At Level 2, in addition to the specifications from the levels above, the Resource components should be described to the folder level, containing the following metadata properties...

* A title
* A local identifier, according to the [Special Collections and Archives guidelines](arrangement)
* Creation dates, if known
* Attribution information (Linked Agents with roles of "Creator" and/or "Source"), if known

## Level 3 Description

There are no additional required metadata properties for Resources at Level 3, beyond those required for Level 2 description.

At Level 3, in addition to the specifications from the levels above, Resource components should be described to the item level, to a degree suitable for MODS export and ingest in the digital repository.

## Specific Instructions

* [Instructions for Resources](archivesspace/resources)
* [Instructions for Archival Objects](archivesspace/archival_objects)
