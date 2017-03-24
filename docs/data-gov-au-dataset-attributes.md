The below is a tables lists the attributes you will need to know about your dataset before uploading it to data.gov.au.

# Dataset Attributes

| Attribute Name | Description | Required |
|:---------------|:------------|:---------|
|Title|Name of the dataset. Be descriptive so that users can easily identify your data. For instance if you’re uploading a tree map dataset for be sure to add the name of the area to the dataset (eg ‘*Ballarat Tree Map*’ rather than just ‘*Tree Map*’).|Yes|
|URL|Allows you to set a custom location for the dataset. This value is derived from the **Name** field but can be updated by clicking the **Edit** button.|Yes|
|Description|A brief (or lengthy) description of your dataset.  This is also the appropriate section for any additional information about your data such as a quality statement or additional license information. You can format the text in this section using [markdown syntax](http://daringfireball.net/projects/markdown/syntax).|No|
|Keywords|Simple words or phrases that users may use when searching for your data. We recommend keeping the phrases to 3 words or less.|No|
|License|The usage license that your data can be used under. There are several options and the data.gov.au team will consider adding more licenses on a case-by-case basis.|Yes|
|Unpublished|Marking this checkbox will set this dataset as being unpublished. **NB**: Unpublished datasets are visible to the public. The unpublished flag refers to the availability of resources.|No|
|Organisation|The organisation to which the dataset belongs. This field will be populated based on your publishing privileges.|Yes|
|Visibility|This field has two settings. **Private** – the dataset will only be visible to members belonging to your organisation. **Public** – the dataset will be visible to everyone.|Yes|
|Geospatial Coverage|The geographical coverage over which the dataset covers.  Users can either enter a plain text description (like, ‘Australia’) or use a GeoJSON string (like {"type": "Polygon", "coordinates": [[[112.0, -44.0], [154.0, -44.0], [154.0, -9.0], [112.0, -9.0], [112.0, -44.0]]]})|Yes|
|Temporal Coverage From|Where a dataset covers a defined period of time this field represents the start date. Otherwise, where a dataset is for a single point in time this field represents that date.|Yes|
|Temporal Coverage To|Where a dataset covers a defined period of time this field represents the end date.|No|
|Language|The language the dataset is published in. This field is automatically set to English.|Yes|
|Update Frequency|How often it is expect that the dataset will be updated on data.gov.au.|Yes|
|Expose User Contact Details|Checking this box will add the contact details of the uploader to the dataset.|No|
|Add AGIFT Function/Theme|The operational function the data describes as represented by the Australian Governments' Interactive Functions Thesaurus.|No|
|Publisher|The name of the publishing entity. This will automatically be set to the name of the organisation. However, can be changed.|Yes|
|Contact|The contact point for the dataset. This will automatically be set to the contact provided for the organisation.|Yes|
|Jurisdiction|The Australian government jurisdiction to which the data relates to, this will be inherited from your organisation.|Yes|
|Geospatial Topic|High level Geographic Information (ISO19115) topic. This field will auto complete on input.|No|
|Data Models|Free text field for describing the data models, ontologies, or taxonomies related to the dataset.|No|
|Field of Research|Australian and New Zealand Standard Research Classification (ANZSRC) defined  field or fields of research relevant to the dataset.|No|

# Resource Attributes

| Attribute Name | Description | Required |
|:---------------|:------------|:---------|
|Last updated|The date when the resource was last changed. This can be changed manually when updating individual resources.|Yes|
|Created|The date when the dataset was created on data.gov.au. This value is automatically generated.|Yes|
|Format|The file type of the file. Can be automatically approximated from the uploaded file or manually set on upload.|Yes|
|Size|The file size of the uploaded resource. This value is automatically generated.|No|
|License|Inherited from dataset.|Yes|

# Data.gov.au Metadata Schema 
Data.gov.au uses components of the AGLS, Dublin Core and Data Catalog Vocabulary metadata standards as per below. We have adopted the approach based on analysis and expect to improve upon the metadata approach to get consistency of discovery data across all data types.

A mapping of data.gov.au's metadata schema and associated [can be downloaded from data.gov.au](http://data.gov.au/dataset/data-gov-au-metadata-and-other-schemas).
