---
layout: default
category: ArchivesSpace
title: Accessions in ArchivesSpace
---

{% assign content = site.data.accessions %}

## Using Next Accession to create brief records

The University of Denver Libraries uses the [Next Accession](https://github.com/duspeccoll/next_accession) ArchivesSpace plugin to create brief accession records. The plugin works by taking as input the year in which the accession was processed. It then searches the database to determine the next accession number in sequence for that year, then presents the user with a form where they may enter the title of the accession record. Upon submission of the form, the user is redirected to a newly-created ArchivesSpace accession record with the automatically-generated accession identifier and user-generated title already populated. From here they may enter whatever additional metadata is necessary to fully describe the accession.

To use the plugin, follow these instructions:

1. Select the "Next Accession" plugin from the repository plugins menu:
<img class="manual-img" src="{{site.baseurl}}/images/next_accession/01.png"/>

2. Enter the year the materials were accessioned in Special Collections and Archives, then click "Submit."
<img class="manual-img" src="{{site.baseurl}}/images/next_accession/02.png"/>

3. The plugin will generate a form with the next accession number in the sequence pre-populated. You may then enter the title you wish to provide for the accession, then click "Submit" again.
<img class="manual-img" src="{{site.baseurl}}/images/next_accession/03.png"/>

4. When you are finished, ArchivesSpace will generate a brief Accession record for you with the system-generated ID and the title you provided. From here you may edit the record to provide additional information about the accession.
<img class="manual-img" src="{{site.baseurl}}/images/next_accession/04.png"/>

## Fields for Accession Records

The table below represents all information that is currently entered in an Accession record, with the field into which it is entered. If an ArchivesSpace form field is not in the table below, it is not currently in use.

{% include fields.html %}
