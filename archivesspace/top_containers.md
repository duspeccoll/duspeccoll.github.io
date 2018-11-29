---
layout: default
category: ArchivesSpace
title: Top Containers in ArchivesSpace
---

{% assign content=site.data.top_containers %}

Top Containers are used in ArchivesSpace to describe physical, circulating items. They are the same as item records in the library management system. ArchivesSpace draws a distinction between the physical aspects of containers (e.g. their profile, barcode, and location) and their archival aggregate aspects (e.g. the archival resources they contain). The former are recorded on the Top Container record; the latter are recorded on one or more Archival Object records describing the container's constituent archival resources.

Top Containers are a sub-class of the Instance class in the ArchivesSpace data model; the corresponding sub-class for digital materials is the [Digital Object](digital_objects).

Below is an example of a Top Container editing form in ArchivesSpace, including all fields for the data type:

<img alt="top container editing form" class="manual-img" src="{{site.baseurl}}/images/archivesspace/top_container.png"/>

Enter metadata for the Top Container according to the field guidelines below. When you are finished, click the "Create and Link to Top Container" button to save the record and link it to your Archival Object.

## Field guidelines for Top Containers

{% include fields.html %}
