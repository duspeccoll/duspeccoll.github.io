---
layout: default
title: ArchivesSpace Documentation
---

The University of Denver uses [ArchivesSpace](http://duarchives.coalliance.org) as its collection management system for archival and manuscript collections. Materials that arrive as collected papers and/or manuscripts from a single entity, or as university records transfers, and that are assigned local call numbers for one of our four collecting areas, are primarily managed in this system. Monographic and serials content such as artists' books, official University of Denver publications such as University Bulletins, newspapers, and yearbooks, are managed in the library management system.

In ArchivesSpace, the [Resource](archivesspace/resources) is the primary data model. Resources use the [Encoded Archival Description](https://www.loc.gov/ead/) metadata standard. A Resource contains one or more Archival Objects, arranged in a tree; different levels on the resource hierarchy represent different levels of arrangement and description. These levels are documented [here](arrangement). A Resource may contain, and an Archival Object may represent, one or more of the following levels of archival description:

* Series (including sub-series)
* Files (including boxes and folders)
* Items (including sub-items)

The Archival Object should only be used to record descriptive metadata about the archival materials it represents. ArchivesSpace uses a separate class of data, the _Instance_, to record information about carriers of archival materials. The Instance contains two sub-classes: the _Top Container_ (representing physical items that have a barcode and may circulate), and the _Digital Object_ (representing digital manifestations of materials accessible via the digital repository and/or digital preservation system). Top Containers are documented [here](archivesspace/top_containers); Digital Objects are documented [here](archivesspace/digital_objects).

Consult the Digital Collections Librarian about any questions regarding resource or archival object descriptions in ArchivesSpace.

## Guidelines for ArchivesSpace Data Models

* [Archival Objects](archivesspace/archival_objects) (archival collection records for all components of an archival collection/Resource)
* [Container Profiles](archivesspace/container_profiles)
* [Corporate Entities](archivesspace/corporate_entities) (name authorities for organizations)
* [Dates](archivesspace/dates)
* [Digital Objects](archivesspace/digital_objects)
* [Extents](archivesspace/extents)
* [Families](archivesspace/families) (name authorities)
* [Notes](archivesspace/notes)
* [People](archivesspace/people) (name authorities for individuals)
* [Resources](archivesspace/resources) (archival collection records at the highest level of hierarchy)
* [Subjects](archivesspace/subjects)
* [Top Containers](archivesspace/top_containers)
