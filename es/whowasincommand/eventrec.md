# Incident Records on WhoWasInCommand

*Nos encontramos actualmente en vías de traducir el texto completo.*


This page contains an overview of the data that visitors to WhoWasInCommand will find in an incident record. 

This includes the different sections of the incident record, the data fields that are used to create it and links to more information about each field. 

## Title area {#incident_record_anatomy_title_area}

![](/assets/incident_record_anatomy_title_area.png)

This section contains key information about the incident. It also contains links to download and print actions for the displayed record. Hover over any value in the title area to display a little coloured circle; clicking on this will display the sources and confidence rating for we have assigned to each value.

### Fields used in incident title area

The following fields are used in the incident title area section:

 * [Event: Start date](/datamodel/events.md#event_start_date)
 * [Event: End date](/datamodel/events.md#event_end_date)
 * [Event: Country](/datamodel/events.md#event_country)
 * [Event: Violation type](/datamodel/events.md#event_violation_type)

## Content sidebar {#incident_record_anatomy_content_sidebar}

![](/assets/incident_record_anatomy_content_sidebar.png)

The content sidebar is a navigation aid. It provides quick links to different sections of the record. The items inside the content sidebar indicate what sort of data is available about this incident. For example if "Perpetrator organizations" is not listed in the content sidebar, then there is no data available about alleged perpetrators of the incident.

## Location {#incident_record_anatomy_location}

![](/assets/incident_record_anatomy_location.png)

This section contains an interactive map and some text that describe the location where sources indicate that an incident occured.  Click on the pins placed in the map to display the name of a location. Grab the map to drag/pan it around. Swipe or use the `+` and `-` controls on the map to zoom in or zoom out. Hover over the text description of the location and a little coloured circle will appear. Click on this to view the sources and confidence rating we have assigned to that value.

### Fields used in incident location section 

 * [Event: Location](/datamodel/events.md#event_location)
 * [Event: Exact location (Longitude or OSM Node Name)](/datamodel/events.md#event_exact_location_longitude_name)
 * [Event: Exact location (Latitude or OSM Node ID number)](/datamodel/events.md#event_exact_location_latitude_id)
 * [Event: Settlement (OSM object Name)](/datamodel/events.md#event_settlement_name)
 * [Event: Settlement (OSM object ID Number)](/datamodel/events.md#event_settlement_id)
 * [Event: Top Adminstrative Area (OSM relation name)](/datamodel/events.md#event_top_admin_name)
 * [Event: Top Administrative Area (OSM object ID number)](/datamodel/events.md#event_top_admin_id)
 * [Event: Country](/datamodel/events.md#event_country)

## Description {#incident_record_anatomy_description}

![](/assets/incident_record_anatomy_description.png)

This section contains a direct quotation from the civil society, governmental or other source that describes the incident. As with all tables in person, unit and incident records on WhoWasInCommand, hovering over or tapping any value in the table will cause a little coloured circle to appear. Clicking or tapping again on this will show the sources and confidence ratings we have assigned to that value.

### Fields used in description section

The following field is used in the incident description section:

 * [Event: Description](/datamodel/events.md#event_description)

## Perpetrator organizations {#incident_record_anatomy_perpetrator_organizations}

![](/assets/incident_record_anatomy_perpetrator_organizations.png)

This section contains a table listing the organization(s) that sources allege committed the human rights violation(s) described in the incident. As with all tables in person, unit and incident records on WhoWasInCommand, hovering over or tapping any value in the table will cause a little coloured circle to appear. Clicking or tapping again on this will show the sources and confidence ratings we have assigned to that value.

### Fields used in perpetrator organizations section

The following fields are used in the perpetrator organizations section:

 * [Event: Perpetrator organization](/datamodel/events.md#event_perpetrator_organization)
 * [Organization: Name](/datamodel/organizations.md#organization_name)
 * [Organization: Aliases](/datamodel/organizations.md#organization_aliases)
 * [Organization: Classification](/datamodel/organizations.md#organization_classification)

## Changelog {#incident_record_anatomy_changelog}

![](/assets/incident_record_anatomy_changelog.png)

The data displayed in any record on WhoWasInCommand is always the most up to date version. The changelog section shows when the data included in this record were first added and subsequently updated. This data is generated by the software that powers WhoWasInCommand whenever a new data import is run. Clicking on the name of the field will open a box showing all the changes that were made to a datapoint, including the time the change was made and the source used to evidence the change.
