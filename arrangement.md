---
layout: default
title: Arrangement and Physical Processing Guidelines
---

Archival collections may be processed to provide one or more levels of physical and intellectual control. These levels include the series, the file, and the item. Not all collections need every level of control. Most archival arrangement work involves progressively grouping and describing records along a continuum, from the largest and most general (i.e. the collection) to the smallest and most specific. When developing a processing plan for a collection, consider the level that makes most sense for the materials being arranged and described, taking into account the scale of the collection, the amount of time required for different levels of arrangement and description, and the relative value of those levels of arrangement and description for researchers.

## Collection

The collection is the highest level of arrangement and description for archival resources. It represents a record group transferred in whole or part to Special Collections and Archives, or an artificial construction of related archival resources arranged together by theme or common collector. Each collection receiving a Special Collections and Archives classification number is managed in the archives management system and represented at the collection level by a MARC record in the library management system.

At minimum, a collection should receive enough description that it is accessible in both library and archives management systems, with holdings (location) and item (circulating container) information in both places, enabling the collection materials to circulate. This is reflected in our Level 1 guidelines for description of archival collections. Processing beyond this level is a curatorial decision.

## Series and Sub-Series

Series and sub-series are aggregations of archival resources around a particular theme of arrangement, as determined by a curator and/or processing archivist. Not all collections merit series-level description; it is typically used in very large collections where order may be imposed on them by an archivist, or when series-level description reflects the original order of a record group transferred to the archives.

In Special Collections and Archives, series and sub-series are identified at the component level using a zero-padded two-digit numbers, ordered sequentially according to their arrangement in the collection. For example, the first series (Patient Records) of [B002 Jewish Consumptives' Relief Society Records](https://duarchives.coalliance.org/repositories/2/resources/496) would receive the SCA-provided identifier of **B002.01**.

## Container

Containers are the box, crate, wrapping, or other enclosure in which archival materials are stored and by which they are circulated in the library management system. Often they are also the lowest level of arrangement and description assigned to an archival collection, and as such may be considered an intellectual resource as well as a physical item.

ArchivesSpace separates these two functions of the container in its data model; circulating items are described as [Top Containers](archivesspace/top_container), and intellectual groupings of materials that are coincident with the container are described as archival objects within a collection. A Top Container record may be linked to one or more Archival Objects in ArchivesSpace, depending on the needs of the collection being arranged and described.

In Special Collections and Archives, containers are identified at the component level using zero-padded, four-digit numbers, ordered sequentially according to their arrangement in the collection. For example, in B002 Jewish Consumptives' Relief Society Records, Box 97 may be found in Series 1 (Patient Records); its unique SCA-provided identifier is **B002.01.0097**.

## Folder

When arranging manuscript or photographic material into folders, they may be assigned identifiers according to their order within their host container. These are assigned zero-padded four-digit numbers in sequence; for example, the first folder in B002 Box 97 (described above) would be assigned the identifier **B002.01.0097.0001**.

If describing a collection to the folder-level in the archival collection management system, records for each folder may be created as children of their host container, using the same identifiers that are indicated on the folders in hand. The folder should receive a descriptive title, creation dates (if known), subject and name authority headings to indicate the materials' form, subject(s), and attribution, and a brief description of their contents using the Abstract note. Materials in a folder are not typically sorted or arranged in any particular order, though if an order is apparent when the materials are processed, note of that order may be taken in an Arrangement note.

## Item and Sub-Item

The lowest level of arrangement and description applies to individual archival materials, such as a single photograph, scrapbook, or unit of correspondence. Sub-items may additionally be used if an "item" is an aggregate of other archival resources -- for example, an item that is a scrapbook may contain "sub-items" that are its individual photographs, clippings, or other ephemera.

In Special Collections and Archives, items and sub-items are identified at the component level using zero-padded, five-digit numbers, ordered sequentially according to their arrangement in the collection or container. For example, in Box 97, Folder 1 of B002 Jewish Consumptives' Relief Society Records, the first cataloged item in sequence would be assigned the unique SCA identifier of **B002.01.0097.0001.0001.00001**.

Item-level cataloging is the most intensive and time-consuming level of description we can provide. Because items are typically cataloged as a pre-requisite for digitization, we provide many subject and name authority headings and notes for these items in order to provide as many access points as possible in the digital repository and the ArchivesSpace public user interface. Because of this, item-level cataloging is reserved only for those collections slated for digitization, or identified as high-impact collections by curators or library administrators.
