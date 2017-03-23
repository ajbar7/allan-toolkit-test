A fundamental aspect of open data is that it’s available for re-use with formats and licencing that allow others to re-use and remix the data. This section will guide you through topics like:

* How to create datasets from new or existing data
* What metadata is and how you should add it
* What licences can be used for open data
* Tools for finding published data

# Process to opening a dataset

While each organisation’s approach to open data will vary, the first step is to determine the classification of the data. If it is unclassified then it is appropriate for public access. If it is classified, then you need to consider secure and non-open approaches to sharing the data.

## Steps

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

| Filetype | Openness | Notes |
|:---------|:---------|:------|
|CSV|High|The best format for opening structured data.|
|XLS/XLSX|Low|Limits machine reading and use on non-Microsoft systems.|

##### Spatial

| Filetype | Openness | Notes |
|:---------|:---------|:------|
|KML|High|An open standard developed for Google Earth. May not translate to other systems. KMZ is also available as a packaged set of KML files.|
|WMS|High|Standardised format for georeferenced map images.|
|WFS|High|Standardised format for geographical features.|
|GeoJSON|High|An open standard format designed for representing simple geographical features.|

#### Formatted properly for tabular data

Any tabular data should be published in a CSV file as well as being included as a report. This allows users to analyse the data without having to convert it to an appropriate format. This is especially important for reports in formats such as PDF which restrict access to data and limit the ability for people to share and remix. PDFs should be made accessible or converted to an alternative format whenever possible. Tabular data for publishing should be both:

* **raw** – presented in the simplest possible format with a single header row – and
* **clean** – using uniform data formatting (eg. Numerical dates, postcodes in every field) with no missing entries, no embedded non-text information, data in every field and as few mistakes as possible.

Obtaining raw, clean data can be a challenge if you’re converting an existing file into a file for uploading as part of a data set. It’s particularly important to look out for elements like merged cells and formulas which can prevent the data from being read.

The [clean-sheet.org](http://clean-sheet.org) website is a very useful resource for publishers of open data.

#### Accompanied by supportive/contextual documentation

Supportive documentation, caveats and contextual information should be included in descriptive information about the data set. If the information is extensive, it may also be possible to upload it as an additional resource to the dataset. Please do not put the data into the documentation itself, as it will restrict access to the data. This means the data will become less accessible to users, and will not be able to be picked up by APIs, data visualisation tools or other machine-to-machine processes.

#### Formatted to be useful

Data should be published with consideration for how it will be most useful. For example, column labels with internal codes like ‘DBQ-12-W’ will be a lot less useful than human-readable labels like ‘Drop Bear Queries 2012 Western Site’.
This is also a consideration when publishing data. For example, a data set on ‘procurement contract data’ with individual files for each year will make it easier for users to locate related data than individual data sets for each year. It will also be easier for data custodians to manage and maintain.

# Where to publish

There are a range of data publishing options available to government organisations based on the jurisdiction and type of data. See below for national data publishing options, or [view this dataset](http://data.gov.au/dataset/list-of-australian-government-data-portals), that containing a list of Australian government open data portals.

* [data.gov.au](http://data.gov.au), the single point of discovery for Federal open data.
* [NationalMap](http://nationalmap.gov.au), a spatial visualisation tool for government open data. Users can’t publish information directly to the site, but it draws data from data.gov.au and directly from agencies when relevant.

# Intro to metadata

Metadata is information about data. It describes the content, format, quality, currency and availability of data in a consistent and meaningful way.

Metadata is useful for cataloguing single documents, but is most important for managing a large body of data. This is particularly important for open government data, as people who work with the data may be combining data sets from a wide range sources, both inside and outside of government.

Establishing a common vocabulary for metadata – using standards – makes it possible for users to find and remix data in a clear and structured way. As open data infrastructure evolves, detailed metadata will not only allow more people to find your data, it will also allow them to re-use the data in more meaningful ways.

## How is it used?

There are a range of metadata standards that are used based on the data that is being described and where it is available. Each metadata standard contains elements, or fields, that describe the data. A common example of a metadata element is the ‘Title’, which contains the name of the dataset.

The data.gov.au metadata section has information on the simple form on data.gov.au that is used to make data discoverable through the sites. For people who need technical information, the metadata requirements for specific data types such as spatial data are also described there.

Spatial data could catalogues should use the [ANZLIC metadata schema](http://www.anzlic.gov.au/resources/anzlic-metadata-profile).

## Licensing your data

Licences provide a clear and standardised guide for other people about how they can use your data, including the option to reuse, remix and share the content.

The [Intellectual Property Principles for Commonwealth Entities](https://www.communications.gov.au/policy/policy-listing/australian-government-intellectual-property-rules) requires agencies to encourage public use and easy access to published material. This includes permission for public use and re-use of material without requiring royalties and on a non-exclusive basis.

The default licence for the Australian Government is the Creative Commons By Attribution license for publishing data and information, unless a clear case is made for another open licence. You can access the licence text on the Creative Commons website in either [plain English](https://creativecommons.org/licenses/by/3.0/au/deed.en) or [legal code](http://creativecommons.org/licenses/by/3.0/au/legalcode).

# Privacy and security

It is important to ensure you approach data publishing with privacy and security principles in mind. For more information about privacy and security considerations, please refer to the [Principles on Open Public Sector Information](https://www.oaic.gov.au/information-policy/information-policy-resources/principles-on-open-public-sector-information) from the Office of the Australian Information Commissioner.

# Standards

Standards are an important aspect of open data, as they ensure data is accessible and interoperable. There are a wide range of standards that may be relevant to data projects, relating to issues like spatial information, metadata and addressing.

## Standards management

System owners and data owners should, wherever possible, consider relevant international and Australian standards for their data.

Standards bodies dealing with data include:

* [International Organization for Standardization](http://www.iso.org/iso/catalogue_ics) (ISO)
* [Open Geospatial Consortium](http://www.opengeospatial.org/standards) (OGC)
* [Standards Australia](http://www.standards.org.au/)

Australian Government Standards that have been adopted for use include:

* [AGLS](http://www.agls.gov.au/) (National Archives standard for making online information and services visible, manageable and interoperable)
* [ANZLIC Spatial Metadata Profile](http://www.anzlic.gov.au/resources/anzlic-metadata-profile)
* [Statistical Data and Metadata Exchange (SDMX)](http://www.abs.gov.au/ausstats/abs@.nsf/Lookup/1407.0.55.002main+features22013) (Managed by the Australian Bureau of Statistics)

# Intro to spatial data

Spatial data is any data that refers to places in the physical world. This can include:

* Geographic features like mountains and lakes
* Man-made objects like houses and roads
* Non-physical objects or information about the location like electoral boundaries or internet quality

Spatial data sets are fundamentally the same as all other data sets; they simply contain fields for spatial information such as latitude and longitude as well as their other information. This means all the guides to making data open still apply.

## The Statistical Spatial Framework

The ABS's [Statistical Spatial Framework](http://www.nss.gov.au/nss/home.nsf/pages/Statistical%20Spatial%20Framework%20Homepage) provides a principals based framework for spatially enabling socio-economic datasets, including administrative datasets, to ensure consistency and comparability. Implementation of the framework is supported by guidance material and resources, and references existing standards and infrastructure. Key guidance materials include:

* [SSF-on-a-page](http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+on+a+page/$File/SSF%20on%20a%20page.pdf) (includes resource links)
* [Geocoding Using Address](http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+Guidance+Material/$File/Geocoding%20Unit%20Record%20Data.pdf)
* [Using Geography with Statistics](http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+Guidance+Material/$File/SSF%20Guidance_Geographic%20Boundaries%20and%20Classifications_1.pdf)
* [Protecting Privacy for Geospatially Enabled Statistics](http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+Guidance+Material/$File/SSF%20Guidance_Geographic%20Differencing_1.pdf)
