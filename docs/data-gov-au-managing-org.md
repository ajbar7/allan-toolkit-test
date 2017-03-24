When the data.gov.au team create a publishing space for your organisation they will only add the minimum required information. It is up to your administrator to complete the details and add a logo.

# Updating an organisation’s details

To update your organisation’s details:

1. Browse to your organisation.
2. Click the **Manage** button near the top right of the page.
3. Complete the form on the page (a list of an attributes and their descriptions is available below).
4. Once finished click the **Update Organisation** button.

# Adding users to an organisation

You may choose to grant additional publishing privileges to other users in your organisation. Users may be granted different roles based on their requirements. A list of roles and their definition is available below.

To add users to your organisation:
1. Ensure that the user has created their account  and has provided you their username. 
2. Browse to your organisation.
3. Click the Manage button near the top right of the page.
4. Click the Members tab near the top of the page.
5. Click the Add Member button.
6. Type the username into the field listed under the Existing User label – this field should auto-complete. 
7. Select a Role for the user. 

# Removing users from an organisation

If you’d like to update or remove a user from your organisation:
1. Browse to your organisation.
2. Click the Manage button near the top right of the page.
3. Click the Members tab near the top of the page.
4. To update a user’s role click on the spanner icon corresponding to their name.
5. To delete a user click the red x button corresponding to their name.


# Organisation attributes

| Attribute Name | Description | Required |
|:---------------|:------------|:---------|
|Name|Name of the organisation.|Yes|
|URL|Allows you to set a custom location for the organisation. This value is derived from the Name field but can be updated by clicking the Edit button.|Yes|
|Description|A brief description of the organisation that will be displayed on your organisation’s page.|No|
|Image URL|Allows you to upload or link to an image for your organisation. It is recommended that you use a square image no smaller than 300 x 300 pixels. We strongly recommend that you chose to upload a logo.|No|
|Jurisdiction|A drop down list of Australian jurisdictions.|Yes|
|Geospatial Coverage|Refers to the geographical coverage over which your organisation is responsible.  Users can either enter a plain text description (like, ‘Australia’) or use a GeoJSON string (like {"type": "Polygon", "coordinates": [[[112.0, -44.0], [154.0, -44.0], [154.0, -9.0], [112.0, -9.0], [112.0, -44.0]]]})|Yes|
|Website|The link to your organisation's website.|Yes|
|Email|A general point of contact email for your organisation.|Yes|
|Telephone|A general phone number for either your organisation’s switchboard or data team.|Yes|

# Organisation member roles

| Role | Description | Organisational Privileges|
|:-----|:------------|:-------------------------|
|Member|Any user added to a **specific organisation** as a Member, the additional privileges apply only to a specific organisation to which the user has been added. | Can view any private datasets uploaded to the organisation |
|Editor|Any user added to a **specific organisation** as an Editor, the additional privileges apply only to a specific organisation to which the user has been added.| All privileges of an *Member* and can additional create new, and edit existing, datasets listed belonging to the organisation to which the user has been added|
|Admin|Any user added to a **specific organisation as an Admin**, the additional privileges apply only to the specific organisation to which the user has been added.| All privileges of an **Editor** and can also add and remove users from an organisation.|
