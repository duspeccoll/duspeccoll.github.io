---
layout: default
category: ArchivesSpace
title: Digital Objects
---

{% assign content = site.data.digital_objects %}

In ArchivesSpace, the Digital Object data model is used to record information about digitized or born-digital archival resources. The University of Denver uses the Digital Object data model for two purposes:

* to provide a rough inventory of what has been digitized or acquired digitally by Special Collections and Archives
* to support the publication of MODS records for ingest into the Digital Collections @ DU digital repository

Digital Objects are linked to the record for the Archival Object for which they are surrogate. Digital Objects are a sub-class of the Instance class in the ArchivesSpace data model; the corresponding sub-class for physical materials is the [Top Container](top_containers).

When a Digital Object is linked to, and made representative of, an Archival Object in ArchivesSpace, it is possible for the MODS Export function for that Archival Object to access the Digital Object metadata and populate the `<digitalOrigin>` and `<part>` elements of the MODS record with it. More information on this may be found in the workflow instructions below.

The University of Denver maintains the [ao_mods](https://github.com/duspeccoll/ao_mods) plugin for exporting MODS records from an Archival Object record, and the [digitizer](https://github.com/duspeccoll/digitizer) plugin for facilitating the creation and linking of Digital Objects from an item record.

## Field Guidelines for Digital Objects

{% include fields.html %}
