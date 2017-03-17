# Publishing open data

A fundamental aspect of open data is that it’s available for re-use with formats and licencing that allow others to re-use and remix the data. This section will guide you through topics like:

* How to create datasets from new or existing data
* What metadata is and how you should add it
* What licences can be used for open data
* Tools for finding published data

## Process to opening a dataset

While each organisation’s approach to open data will vary, the first step is to determine the classification of the data. If it is unclassified then it is appropriate for public access. If it is classified, then you need to consider secure and non-open approaches to sharing the data.

### Steps

1. Choose data sets for release in line with your organisation’s approach and your users’ needs.
2. Clarify who will be responsible for preparing, releasing and updating the data.
3. Apply an open licence – the APS default is Creative Commons Attribution
4. Make the data available
5. Make the data discoverable on or through data.gov.au

# Sourcing data

These possible sources of data that your organisation could open should be considered as part of a larger process to develop and maintain an open data strategy.

## Data from new projects

When commissioning research, collecting data or establishing a new ICT system, adopt information management and procurement practices that ensure you have access to associated raw data in an open format and the right to publish that data online under an open licence. See Licensing your data for more information. This is important if a service provider is contracted to collect the data or to develop a website or mobile app built on an agency data source. Effective information governance ([PSI Principle 3](https://www.oaic.gov.au/information-policy/information-policy-resources/principles-on-open-public-sector-information)) will help you ensure that your agency has access to the raw data that was used to create existing publications or apps.

You should also ensure that other people in your organisation are aware that these governance processes and practices exist and are followed.

## Releasing unpublished data

Consider whether your agency has unpublished data that could be released as open data. This may come from public reports, studies and newsletters that have only included processed data with select results from internal analysis.

Internal data such as project locations, demographic research and administrative data should also be considered for release.

Agencies wishing to convert or release previously unpublished data should first consider legislative and policy requirements that may prevent publication or require modification of the data before release.

In particular, you should consider obligations under the Australian Privacy Principles (APPs) in the Privacy Act 1988. Guidance about the Privacy Act is available in the OAIC's [APP Guidelines](http://www.oaic.gov.au/privacy/applying-privacy-law/app-guidelines/). In addition, the OAIC's [Information Policy Agency Resource 1 — De-identification of data and information](http://www.oaic.gov.au/information-policy/information-policy-resources/information-policy-agency-resources/information-policy-agency-resource-1-de-identification-of-data-and-information) discusses de-identification as a technique that allows agencies to balance privacy and transparency objectives when publishing open data.

# Creating datasets

## Creating a basic open data set

Creating a dataset can be a quick and easy process. At its most basic, a data set is simply a structured presentation of data, such as a spreadsheet, with some special features. These features can be designed as part of the data set from the beginning, or changed before publishing.

An open data set must be:

### Saved in an open format

Any type of data can be shared in an open format but sometimes this means transforming the data from the original format to a different format. The benefit to agencies in publishing data in an open format is it makes it easier for someone else to reuse the data, such as another government agency or company. The benefits of open data come often from the ability to analyse and remix data alongside other data sets.

The table below rates common file types for their accessibility to users with a range of computing systems and access requirements.

For data.gov.au, it should be noted that users can publish any data file type, and that Finance encourages organisations to publish the most machine readable and open format. Data.gov.au automatically generates full API access to tabular and spatial datasets uploaded to data.gov.au (through CKAN and Geoserver) and is investigating similar support for other data types. Agencies should contact the data.gov.au team if they are considering publishing relational databases, realtime data or other data types.

If you are creating data for analysis or machine processing, it is important to note that spatial files, CSV and XLS are the only formats that automatically generate visualisations or API access for your data set on data.gov.au. CSV/XLS files will need to be structured according to the advice on the creating data sets page. Data.gov.au provides mapping services for some geospatial data types including KML, and will advise on additional formats as they are supported.

#### Data Formats

##### Tabular

##### Spatial

|Filetype  |Openness|Notes                                                                                                                                 |
|:----------|:-------|:-------------------------------------------------------------------------------------------------------------------------------------|
|KML        |High    |An open standard developed for Google Earth. May not translate to other systems. KMZ is also available as a packaged set of KML files.|
