# Automated Publishing

The [CKAN API](http://docs.ckan.org/en/latest/api/index.html) allows for the automatic uploading and management of data. If you are considering using the API please get in touch with the data.gov.au team before proceeding. There are [a number of examples available from the data.gov.au github](https://github.com/datagovau/ckan-api-examples) that may be a useful place to start. 

## Using FME
An FME workbench has been developed to update existing datasets which have been previously published to data.gov.au utilising the CKAN API.

Before you start you will need:

* A unique API key - This is assigned to you once you have set up an account with data.gov.au.
* Publish your dataset to your organisation.
* The dataset's URL. Example: https://data.gov.au/api/rest/dataset/ballarat-planning-applications-currently-on-advertising
* Create a private parameter in the workbench with your API key. This is easier to use instead of copying and pasting your API key multiple times.

You can find a sample [FME workbench on the data.gov.au github](https://github.com/datagovau/ckan-api-examples/tree/master/FME). The example was created by [Matthew Swards](http://www.twitter.com/mattswards) from [City of Ballarat](https://data.gov.au/organization/city-of-ballarat).
