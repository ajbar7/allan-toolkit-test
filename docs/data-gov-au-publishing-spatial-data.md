# Publishing spatal data

Before you can publish your first dataset you’ll need to:

1. create an account; and
2. request publishing privileges. 

We’ve created a publishing data worksheet which captures all the information that will be required to publish data. If you'd like a copy of the most current worksheet [send us an email](data@pmc.gov.au).

**Before you publish your dataset please ensure that it complies with our [terms of use](https://data.gov.au/about).** 

Once your publishing organisation has been created and you’ve been granted the appropriate publishing privileges follow the below steps to publish your first dataset.

1. Browse to your organisation’s page on data.gov.au.
2. Click the **Add Dataset** button near the top of the page.
3. The form on the subsequent page represents the required information about your dataset (a useful lookup table of dataset attributes is available in a subsequent section).
   * Fields marked with a red asterisk are mandatory
4. Once you’ve completed the form click the **Next** button at the bottom of the page.
5. On the page you will be asked to add files (or links to a web services) to the dataset you can follow the instructions for uploading a resource file / adding a resource link. 
6. Once done click the Finish button.

## Spatial data on data.gov.au

Any new spatial data uploaded will be picked up by an automated process which runs daily across data.gov.au. This automated process will add additional resources to your dataset automatically to make the spatial data more accessible. If your data has not been picked up by the automated process please send the team an email.

data.gov.au will only work with a single spatial file per dataset. Adding multiple spatial files to a single dataset will disable the data.gov.au's spatial ingestor for that dataset.

### Making tabular data spatial using csv-geo-au

The [csv-geo-au specification](https://github.com/TerriaJS/nationalmap/wiki/csv-geo-au) can be used to publish point or region-mapped Australian geospatial data in CSV format to data.gov.au and other open data portals. 

## Uploading a resource file

You can upload nearly any kind of spatial files but only KML, KMZ and SHP files are supported by data.gov.au's geospatial ingestor.

1. Click the **Upload** button and browse to the location of the file you are uploading on your computer.
2. You will need to give your file a **Name**. This will be displayed on the dataset landing page.
3. If appropriate give the resource a short **Description**.
4. If you do not select a **Format** for the resource the platform will attempt to automatically detect the file type.
5. If you are uploading a zip file you may choose to extract a subset of ‘interesting’ files from the compressed file by selecting the **Extract Resources from Zip Files** checkbox. You can read more about the zip extractor here.
6. The **Last Modified** field will be auto complete to the current date if left blank.

### Uploading a shape file

A shapefile package is made up of multiple required files. When uploading a shapefile create a zip file including the below files to ensure that ingestion is successful.

* .dbf
* .shp
* .prj
* .shx

Even though the file is a zip please set the **Format** of the resource to "SHP".

## Linking to an existing resource

*Please note that linking to a spatial file, regardless of format will not be picked up by data.gov.au's geospatial ingestor.*

1. Click the **Link** button and enter the url for the resource you’re linking to. 
2. You will need to give your file a **Name**. This will be displayed on the dataset landing page.
3. If appropriate give the resource a short **Description**.
4. If you do not select a **Format** for the resource the platform will attempt to automatically detect the file type.
5. The **Last Modified** field will be auto complete to the current date if left blank.

# Managing a spatial dataset

## Applying a style to a layer

When a spatial layer is added to data.gov.au it will have a default geoserver style applied. For polygons this is a grey fill with a black outline and for point data this will be a red square. At this time there is no automatic way to apply a custom style. However, you may choose to supply a styling layer as part of your zip package for users of GIS software. 

If you require that a custom style is applied to your layer you will need to create and submit an SLD file to the data.gov.au team via email. A good resource for creating SLD files is the [SLD Cookbook](http://docs.geoserver.org/stable/en/user/styling/sld/cookbook/) from the Geoserver website.

## Updating a dataset

If you’re only updating the information (or metadata) related to a dataset follow the instructions below. If you’re looking to update a data resource related to the dataset refer to the section below.

1. Browse to the relevant dataset.
2. Click the **Manage** button located near top right of the page.
3. On the subsequent page the metadata associated with a dataset can be updated.
   * Fields marked with a red asterisk are mandatory.
4. Once finished click the **Update Dataset** button at the bottom of the page.

## Updating a resource

When updating a spatial resource you will only need to replace the file that was originally uploaded to the site. The resources generated by data.gov.au (WMS, WFS and GeoJSON) will be automatically updated. If you are changing the structure of your file (*for example, changing a field name*) you may need to get in touch with the data.gov.au team to update schema in geoserver to reflect these changes.

Please note that it will take up 24 hours for any updated data to be picked up by data.gov.au's geospatial ingestor and that it may also take a further 24 hours for any cached tiles to be updated on the NationalMap preview.

To update a resource in your dataset follow the instructions below:

1. Browse to dataset you’d like to update.
2. Click on the resource you originally uploaded, this will take you to the landing page for the resource.
3. Click the **Manage** button located on the near top right of this landing page.
4. Click the **Red X** button to remove the current version of the resource.
5. From here follow the instructions to uploading a resource file, available above. 
6. Click the Update Resource button

## Deleting a resource

Unless it is absolutely required it is not recommended that resources are deleted. If you are simply looking to provide updated data it is possible to simply override a resource while preserving its unique identifier. It is not possible to reverse a deleted resource and applications which use the resource as listed on data.gov.au may break as a result.

If you intend to remove the dataset that has been ingested, the data.gov.au team will also need to manually remove the layer from geoserver, so please send us an email to let us know.

To delete a resource:

1. Browse to the dataset and select the resource that you’d like to delete.
2. Once you are on the resource page click the **Manage** button located on the top right of the page.
3. Near the bottom of the page there will be a **Delete** button.
4. You will be asked to confirm that you’d like to remove the resource. If you are sure you want to remove the resource click the **Confirm** button.

## Deleting a dataset

If you decide to delete a dataset from data.gov.au please note all resources associated with the database will become unavailable. This includes its unique name / URL which will not be usable again. The data.gov.au team will also need to manually remove the layer from geoserver, so please send us an email to let us know if you decide to delete a spatial dataset.

To delete a dataset from the site:

1. Browse to the dataset you’d like to delete.
2. Click the **Manage** button on the top right of the page.
3. Scroll to the bottom of the manage dataset page and click the **Delete** button.
4. You will be asked to confirm that you’d like to delete the dataset. If you are sure click the **Confirm** button.
