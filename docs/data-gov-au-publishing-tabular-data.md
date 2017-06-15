# Publishing tabular data

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

## Uploading a resource file

You can add most file types to a dataset as a resource. 

To make best use of data.gov.au it is recommended that you use a data format recognised by the platform. You may also link directly to data hosted elsewhere by your agency or your hosted web services (APIs). Where you link directly to a web service either link, or upload, documentation on how make use of it.

1. Click the **Upload** button and browse to the location of the file you are uploading on your computer.
2. You will need to give your file a **Name**. This will be displayed on the dataset landing page.
3. If appropriate give the resource a short **Description**.
4. If you do not select a **Format** for the resource the platform will attempt to automatically detect the file type.
5. If you are uploading a zip file you may choose to extract a subset of ‘interesting’ files from the compressed file by selecting the **Extract Resources from Zip Files** checkbox.
6. The **Last Modified** field will be auto complete to the current date if left blank.

## Linking to an existing resource

1. Click the **Link** button and enter the url for the resource you’re linking to. 
2. You will need to give your file a **Name**. This will be displayed on the dataset landing page.
3. If appropriate give the resource a short **Description**.
4. If you do not select a **Format** for the resource the platform will attempt to automatically detect the file type.
5. The **Last Modified** field will be auto complete to the current date if left blank.

## CSV and tabular data to API

When uploading a machine readable CSV file it may take some time for the full dataset to become available via API. A dataset with only a few thousand rows should only take a few minutes to become completely available, but datasets with millions of rows can take up to a few hours. 

If you have any concerns over the ingestion of your dataset please send the team an email.

# Managing a tabular dataset

## Updating a dataset

If you’re only updating the information (or metadata) related to a dataset follow the instructions below. If you’re looking to update a data resource related to the dataset refer to the section below.

1. Browse to the relevant dataset.
2. Click the **Manage** button located near top right of the page.
3. On the subsequent page the metadata associated with a dataset can be updated.
   * Fields marked with a red asterisk are mandatory.
4. Once finished click the **Update Dataset** button at the bottom of the page.

## Adding a new resource to an existing dataset

When adding resources to existing datasets you’ll need to follow these steps before you can upload your files:

1. Browse to dataset you’d like to update.
2. On the top right of the dataset page click the **Manage** button.
3. At the top of the manage dataset page click the **Resources** link.
4. Click the **+ Add new resource** button which will bring you to the new resource page.
5. From here follow these instructions to uploading a resource file, available above.

## Updating a resource

When making an updating a dataset, as for example adding new data to the end of an existing file, it is preferable to overwrite the existing resource. Overwriting a resource ensures that the unique identified and link (e.g. [ad5c6594-571e-4874-994c-a9f964d789df](http://data.gov.au/dataset/disaster-events-with-category-impact-and-location/resource/ad5c6594-571e-4874-994c-a9f964d789df)) for the resource remains the same. A single persistent identifier is very valuable to users accessing the data through mechanisms such as an API. 

When replacing an existing resource with a new version, where practical, the resource should continue to use the same format and structure. Overwriting a resource with different kind of file format (replacing CSV with an XLS) or changing the files structure may limit its usability for existing users.

If you plan to change the structure or format the data you should consider adding the new file as a different resource to the existing dataset. This will allow developers to continue to use the existing API while they make the necessary changes to their code.

To update a resource in your dataset follow the instructions below:

1. Browse to dataset you’d like to update.
2. Click on the resource that requires an update, this will take you to the landing page for the resource.
3. Click the **Manage** button located on the near top right of this landing page.
4. Click the **Red X** button to remove the current version of the resource.
5. From here follow the instructions to uploading a resource file, available above. 
6. Click the Update Resource button

## Deleting a resource

Unless it is absolutely required it is not recommended that resources are deleted. If you are simply looking to provide updated data it is possible to simply override a resource while preserving its unique identifier.

It is not possible to reverse a deleted resource and applications which use the resource as listed on data.gov.au may break as a result.

To delete a resource:

1. Browse to the dataset and select the resource that you’d like to delete.
2. Once you are on the resource page click the **Manage** button located on the top right of the page.
3. Near the bottom of the page there will be a **Delete** button.
4. You will be asked to confirm that you’d like to remove the resource. If you are sure you want to remove the resource click the **Confirm** button.

## Deleting a dataset

If you decide to delete a dataset from data.gov.au please note all resources associated with the database will become unavailable. This includes its unique name / URL which will not be usable again.

If you would like to have a dataset completely removed from the site please email: data@pmc.gov.au.

To delete a dataset from the site:

1. Browse to the dataset you’d like to delete.
2. Click the **Manage** button on the top right of the page.
3. Scroll to the bottom of the manage dataset page and click the **Delete** button.
4. You will be asked to confirm that you’d like to delete the dataset. If you are sure click the **Confirm** button.
