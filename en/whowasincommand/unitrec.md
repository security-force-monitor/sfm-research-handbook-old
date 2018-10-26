# Unit Records on WhoWasInCommand

This page gives an overview of the data that visitors to WhoWasInCommand will find in a unit record.

This includes descriptions of different sections of the unit page, the data fields that are used to create it and links to more information about each field.

## Title area {#anatomy_unit_record_title}

![Image showing the title area of an organization record on WhoWasInCommand](/assets/org_record_anatomy_titlearea.png)

This section contains key information about the identity of the unit. It also contains links to download and print actions for the displayed record. Hover over any value in the Title area to display a little coloured circle; clicking on this will display the sources and confidence rating for each value. 

### Fields used in the title area

The following fields are used in the title area:

* [Organization: Name](/datamodel/organizations#organization_name)
* [Organization: Aliases](/datamodel/organizations.md#organization_alias)
* [Organization: Classifcation](/datamodel/organizations.md#organization_classification)
* [Organization: Country](/datamodel/organizations.md#organization_country)

When a field is empty, it will not be displayed in the Title area. 

## Content sidebar {#anatomy_unit_record_sidebar}

![Image showing the content sidebar of an organization record on WhoWasInCommand](/assets/org_record_anatomy_content_sidebar.png)

The content sidebar is a navigation aid. It provides quick links to different parts of the page. The items inside the content sidebar indicate what sort of data is available about this unit. For example if "Incidents" is not listed in the content sidebar, then there is no data available about incidents involving this unit.

## Areas of Operation {#anatomy_unit_record_area_of_operation}

![Image showing the Area of Operation map and table of a organization record on WhoWasInCommand.com](/assets/org_record_anatomy_areas_of_operation.png)

The areas of operation section contains a map and table that describe where an organization has operated in some manner. Click on the highlighted areas of the map to display the name of an area of operation. Grab the map to drag/pan it around. Swipe or use the `+` and `-` controls on the map to zoom in or zoom out. Hover over any value in the table and a little coloured circle will appear. Click on this to view the sources and confidence rating we have assigned to that value. 

### Fields used in the areas of operations section

The following fields are used in the areas of operation section:

* [Area of Operations: OSM object name](/datamodel/organizations.md#organization_aoo_osm_name)
* [Area of Operations: OSM object ID number](/datamodel/organizations.md#organization_aoo_osm_id)
* [Area of Operations: Date first cited](/datamodel/organizations.md#organization_aoo_date_first_cited)
* [Area of Operations: Start date?](/datamodel/organizations.md#organization_aoo_date_last_cited_is_start)
* [Area of Operations: Date last cited](/datamodel/organizations.md#organization_aoo_date_last_cited)
* [Area of Operations: Open-ended?](/datamodel/organizations.md#organization_aoo_open_ended)

The Areas of Operation section will display where there is a valid Area of Operations record that contains values for `Area of Operations: OSM object name` and `Area of Operations: OSM object ID number`. Otherwise, the section will not display.

## Sites {#anatomy_unit_record_sites}

![Image showing a map and table of sites - or bases - as part of an organization record on WhoWasInCommand.com](/assets/org_record_anatomy_sites.png)

This section contains a map and a table that describe sites associated with the organization. Clicking on the pins plotted on the map will display the name of the site. Grab the map to drag/pan it around. Swipe or use the `+` and `-` controls on the map to zoom in or zoom out. Hover over any value in the table and a little coloured circle will appear. Click on this to view the sources and confidence rating for that value.

### Fields used in the Sites section

The following fields are used in the Site section:

* [Site: Exact Location (Latitude or OSM Node Name)](/datamodel/organizations.md#organization_site_ex_loc_name)
* [Site: Exact Location (Longitude or OSM Node ID)](/datamodel/organizations.md#organization_site_ex_loc_id)
* [Site: Settlement (OSM Node Name](/datamodel/organizations.md#organization_site_settlement_name)
* [Site: Settlement (OSM ID)](/datamodel/organizations.md#organization_site_settlement_id)
* [Site: Top Administrative Area (OSM Name)](/datamodel/organizations.md#organization_site_top_admin_name)
* [Site: Top Administrative Area (OSM ID number)](/datamodel/organizations.md#organization_site_top_admin_id)
* [Site: Date of first citation](/datamodel/organizations.md#organization_site_date_first_cited)
* [Site: Founding date?](/datamodel/organizations.md#organization_site_date_first_cited_founding)
* [Site: Date last cited](/datamodel/organizations.md#organization_site_date_last_cited)
* [Site: open-ended?](/datamodel/organizations.md#organization_site_date_last_cited_open_ended)

The Sites section will display where there is a valid Site record. Otherwise, the section will not display on the unit record.

## Memberships {#anatomy_unit_record_memberships}

![Image showing a membership table of a organization record on WhoWasInCommand.com](/assets/org_record_anatomy_memberships.png)

This section contains a table indicating whether the organization has been a member of internal/national joint operations, international peacekeeping missions, or other multi-unit deployments. Hover over any value in the table and a little coloured circle will appear. Click on this to view the sources and confidence rating for that value.

### Fields used in the Memberships section

The following fields are used in the memberships section:

 * [Organization Membership](/datamodel/organizations.md#organization_membership)
 * [Membership: Date first cited](/datamodel/organizations.md#organization_membership_date_first_cited)
 * [Membership: Start date?](/datamodel/organizations.md#organization_membership_is_start)
 * [Membership: Date of last citation](/datamodel/organizations.md#organization_membership_date_last_cited)
 * [Membership: Open-ended?](/datamodel/organizations.md#organization_membership_open_ended)

Where a unit has no memberships attached to it, the memberships section will not display on the unit record.

## Member units {#anatomy_unit_record_member_units}

![](/assets/org_record_anatomy_member_units.png)

This section contains a table listing the units that comprise the present unit. For example, it will list units that have taken part in a joint operation, international peacekeeping missing or other multi-unit organization. However over any value in the table, and a little coloured circle will appear. Click on this to view the sources and confidnce rating for that value.

### Fields used in the Member Units section

The following fields are used in the member units section:

 * [Organization: Name](/datamodel/organizations.md#organization_name)
 * [Organization: Aliases](/datamodel/organizations.md#organization_aliases)
 * [Organization: Classifcation](/datamodel/organizations.md#organization_classification)
 * [Organization Membership](/datamodel/organizations.md#organization_membership)
 * [Membership: Date first cited](/datamodel/organizations.md#organization_membership_date_first_cited)
 * [Membership: Start date?](/datamodel/organizations.md#organization_membership_is_start)
 * [Membership: Date of last citation](/datamodel/organizations.md#organization_membership_date_last_cited)
 * [Membership: Open-ended?](/datamodel/organizations.md#organization_membership_open_ended)

## Parent Units {#anatomy_unit_record_parents}

![Image showing a table of parent units for an organization on WhoWasInCommand.com](/assets/org_record_anatomy_parents.png)

The parent units section displays an interactive chart. This shows the links between all units known to be above the present one in the overall organizational hierarchy of that security force, right up to the Commander in Chief or equivalent. The chart is drawn using parent relationships that are classified as `command` (rather than `informal` or `administrative`). They are drawn at the last cited or end date of the parent relationship. This date is displayed at the bottom of the chart. Where a unit has different parents at different times, a chart is drawn for each relationship: swiping left or right, or using the arrows at each side, displays these.


### Fields used in the Parent Units section

The following fields are used in the parent units sections:

* [Organization: Name](/datamodel/organizations.md#organization_name)
* [Organization: Parent](/datamodel/organizations.md#organization_parent_name)
* [Parent relationship: Classification](/datamodel/organizations.md#organization_parent_classification)
* [Parent relationship: Date first cited](/datamodel/organizations.md#organization_parent_date_first_cited)
* [Parent relationship: start date?](/datamodel/organizations.md#organization_parent_date_first_cited_is_start)
* [Parent organization: date last cited](/datamodel/organizations.md#organization_parent_date_last_cited)
* [Parent relationship: Open-ended?](/datamodel/organizations.md#organization_parent_open_ended)

Where a unit does not have a parent relationship, this section will not be displayed in the unit record.

## Subsidiaries {#anatomy_unit_record_subsidiaries}

![Image showing a table of subsidiaries on an organization record on WhoWasInCommand.com](/assets/org_record_anatomy_subsidiaries.png)

The subsidiaries section contains a table describing all units known to have been immediately below the current unit in the overall organizational hierarchy of that security force. Hover over any value in tables to display a little coloured circle; clicking on this will display the sources and confidence rating for each value. 

### Fields used in the Subsidiaries section

The following fields are used in the subsidiaries section:

* [Organization: Name](/datamodel/organizations.md#organization_name)
* [Organization: Aliases](/datamodel/organizations.md#organization_aliases)
* [Organization: Classification](/datamodel/organizations.md#organization_classification)
* [Organization: Parent](/datamodel/organizations.md#organization_parent_name)
* [Parent relationship: Classification](/datamodel/organizations.md#organization_parent_classification)
* [Parent relationship: Date first cited](/datamodel/organizations.md#organization_parent_date_first_cited)
* [Parent relationship: start date?](/datamodel/organizations.md#organization_parent_date_first_cited_is_start)
* [Parent organization: date last cited](/datamodel/organizations.md#organization_parent_date_last_cited)
* [Parent relationship: Open-ended?](/datamodel/organizations.md#organization_parent_open_ended)

Where a unit has no subsidaires, this section will not be displayed in the unit record.

## Personnel {#anatomy_unit_record_personnel}

![Image of a table showing a list of personnel on an organzation record on WhoWasInCommand.com](/assets/org_record_anatomy_personnel.png)

The personnel section displays a table showing all persons affiliated to this unit at any time in command, administrative and other roles. Hover over any value in the table to display a little coloured circle; clicking on this will display the sources and confidence rating for each value. 


### Fields used in the personnel section

The following fields are used in the personnel section:

* [Person: Name](/datamodel/persons.md#person_name)
* [Person: Organization](/datamodel/persons.md#person_organization)
* [Person: Role](/datamodel/persons.md#person_role)
* [Person: Title](/datamodel/persons.md#person_title)
* [Person: Rank](/datamodel/persons.md#person_rank)
* [Person: First citation](/datamodel/persons.md#person_date_first_cited)
* [Person: Start date?](/datamodel/persons.md#person_date_first_cited_is_start)
* [Person: First citation context](/datamodel/persons.md#person_date_first_cited_context)
* [Person: Last citation](/datamodel/persons.md#person_date_last_cited)
* [Person: End date?](/datamodel/persons.md#person_date_last_cited_is_end)    

Where no persons in the dataset are members of a unit, this section will not be displayed in the unit record.

## Incidents {#anatomy_unit_record_incidents}

![Image showing a list of incidents on an organization record on WhoWasInCommand.com](/assets/org_record_anatomy_incidents.png)

The incidents section displays a list of incidents of alleged human rights violations that sources allege the unit has committed. Hover over either the date or the incident description to display a little coloured circle that when clicked will show the sources and confidence rating we have assigned to this data.

### Fields used in the incidents section

The following fields are used in the incidents section:

* [Event: Start date](/datamodel/events.md#event_start_date)
* [Event: End date](/datamodel/events.md#event_end_date)
* [Event: Description](/datamodel/events.md#event_description)
* [Event: Perpetrator organization](/datamodel/events.md#event_perpetrator_organization)

If a source has not made an allegation against a unit, this section will not be displayed in the unit record.

## Changelog {#anatomy_unit_record_changelog}

![Image showing the changelog section that appears on organization records on WhoWasInCommand.com](/assets/org_record_anatomy_changelog.png)

The data displayed in any record on WhoWasInCommand is always the most up to date version. The changelog section shows when the data included in this record were first added and subsequently updated. This data is generated by the software that powers WhoWasInCommand whenever a new data import is run. Clicking on the name of the field will open a box showing all the changes that were made to a datapoint, including the time the change was made and the source used to evidence the change.

