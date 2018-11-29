---
layout: default
category: ArchivesSpace
title: Resources in ArchivesSpace
---

{% assign content=site.data.resources %}

This guide covers the creation and management of descriptive metadata for Resources in ArchivesSpace. A Resource is a group of one or more items sharing a unifying characteristic, or a group of records collected by a person, family, or corporate body in the course of their personal or business affairs. The Resource is the basic building block of descriptive metadata in ArchivesSpace, containing one or more Archival Objects, individual components of the collection.

## Managing Resources and Archival Objects

You may enter new Archival Objects within a collection hierarchy as either Children (at the level below the current record) or Siblings (at the same level as the current record). Use the "Add Child" button to add a new Archival Object at a level below the current object. Use the "Add Sibling" button to add a new Archival Object at the same level as the current object. Siblings and children are automatically added as the last item in a sequence; you may need to re-position them in the tree to maintain proper order, if the box you are adding precedes the last box in the current series or collection.

{% include fields.html %}

<a name="extent-calculator"/>
## Calculating Extent for Resources

ArchivesSpace includes an Extent Calculator as part of the Top Container suite of tools. Provided a collection has all of its Top Containers linked to it, and all of these Top Containers are linked to Top Containers, ArchivesSpace is able to generate an extent automatically without any other human intervention.

To use it, open any Resource record. In the toolbar, click on the "More" dropdown menu, then click "Calculate Extent." You can calculate a collection's Extent at any time, but you must be in Edit mode to add the calculated extent to the Resource.

The report displays the calculations ArchivesSpace made to determine the extent. These are based on the number of container profiles linked to the Resource. The report also displays the Extent it will attach to the Resource, if you tell it to. If you are happy with the results of the Extent Calculator, click on the "Create Extent" button to attach the calculated Extent to the Resource. You can edit the calculated extent before you attach it. Note that the new Extent will be added in addition to any other Extents attached to the Resource; you will need to delete any and all existing Extents if you want to replace them.

Sample Extent Calculator output, including what displays if the calculator encounters Top Containers without a linked Container Profile, may be found below:

<img alt="sample extent calculator output" class="manual-img" src="{{site.baseurl}}/images/archivesspace/extent_calculator.png"/>
