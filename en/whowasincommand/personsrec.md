# Person records in WhoWasInCommand

This page contains an overview of the data that visitors to WhoWasInCommand will find in a person record. 

This includes the different sections of the person record, the data fields that are used to create it and links to more information about each field.

## Title area {#person_record_anatomy_titlearea}

![Image showing the title area of a person record on WhoWasInCommand.com](/en/assets/person_record_anatomy_title_area.png)

This section contains key information about the identity of the person. It also contains links to download and print actions for the displayed record. Hover your mouse or tap any value in the title area and a little coloured circle will appear: click this to display the sources and confidence rating that we have assigned to that datapoint.

### Fields used in the title area

 * [Person: Name](/en/datamodel/persons.md#person_name)
 * [Person: Aliases](/en/datamodel/persons.md#person_other_names)
 * [Person: Country](/en/datamodel/persons.md#person_country) 

## Content sidebar {#person_record_anatomy_contentsidebar}

![Image showing the content sidebar of a person record on WhoWasInCommand.com](/en/assets/person_record_anatomy_content_sidebar.png)

The content sidebar is a navigation aid. It provides quick links to different sections of the person record. The items inside the content sidebar indicate what sort of data is available about this person.  If a particular section is not listed in the content sidebar - for example, "Subordinates" -  then there is no data available about the subordinates of this person.

## Last Seen As {#person_record_anatomy_last_seen_as}

![Image showing the Last Seen As section of a person record on WhoWasInCommand.com](/en/assets/person_record_anatomy_last_seen_as.png)

This section summarises the most recently-available data about a person's rank, role and membership of a unit. Hover over any value in this section and a little coloured circle will appear. Click on this to view the sources and confidence rating for that value.

### Fields used in the Last Seen As section

The following fields are used in the Last Seen As section:

 * [Person: Rank](/en/datamodel/persons.md#person_organization_rank)
 * [Person: Organization Name](/en/datamodel/persons.md#person_organization_name)
 * [Person: Role](/en/datamodel/persons.md#person_role) 
 * [Organization: Classifcation](/en/datamodel/organizations.md#organization_classification)
 * [Person Membership: Date last cited](/en/datamodel/persons.md#person_date_last_cited)
 * [Person Membership: End date?](/en/datamodel/persons.md#person_date_last_cited_is_end)

## Memberships {#person_record_anatomy_memberships}

![Image showing the memberships table on a person record on WhoWasInCommand.com](/en/assets/person_record_anatomy_memberships.png)

This section contains a table that describes the positions a person has held in different units. In this table, WhoWasInCommand will display a new membership row is displayed for each time a person changes organization, rank, role or title. This means that in some records a person may have multiple memberships in the same organization, but in different roles or at a different rank. 

As with all tables in person, unit and incident records on WhoWasInCommand, hovering over or tapping any value in the table will cause a little coloured circle to appear. Clicking or tapping again on this will show the sources and confidence ratings we have assigned to that value.


### Fields used in the Memberships section

The following fields are used in the memberships section:

 * [Person: Organization Name](/en/datamodel/persons.md#person_organization_name)
 * [Person: Role](/en/datamodel/persons.md#person_organization_role)
 * [Person: Rank](/en/datamodel/persons.md#person_organization_rank)
 * [Person: Title](/en/datamodel/persons.md#person_organization_title)
 * [Person Membership: Date first cited](/en/datamodel/persons.md#person_organization_date_first_cited)
 * [Person Membership: Start date](/en/datamodel/persons.md#person_date_first_cited_is_start)
 * [Person Membership: Date last cited](/en/datamodel/persons.md#person_date_last_cited)
 * [Person Membership: End date?](/en/datamodel/persons.md#person_date_last_cited_is_end)

## Chain of Command {#person_record_anatomy_chain_of_command}

![Image showing the Chain of Command interactive chart that appear on person records on WhoWasInCommand.com](/en/assets/person_record_anatomy_chain_of_command.png)

The chain of command section displays interactive charts. These show the links between all the units commanded by a person and all those superior to them, along with their commanders. The chart will display up to the highest-level unit in the organizational structure, creating a "line of sight" from the current unit to the top. 

The charts are drawn using parent relationships between organizations that are classified as `command` (rather than `informal` or `administrative`). You can learn more about this in the documentation for [Parent relationship: Classification](datamodel/organizations.md#organization_parent_classification) 

The charts are drawn at the last cited or end date of the parent relationship. This date is displayed at the bottom of the chart. Where a unit has different parents at different times, a chart is drawn for each relationship: swiping left or right, or using the arrows at each side, displays these.


### Fields used in the Chain of Command section

The following fields are used in the Chain of Command section:

 * [Organization: Name](/en/datamodel/organizations.md#organization_name)
 * [Organization: Parent](/en/datamodel/organizations.md#organization_parent_name)
 * [Parent relationship: Classification](/en/datamodel/organizations.md#organization_parent_classification)
 * [Parent relationship: Date first cited](/en/datamodel/organizations.md#organization_parent_date_first_cited)
 * [Parent relationship: start date?](/en/datamodel/organizations.md#organization_parent_date_first_cited_is_start)
 * [Parent organization: date last cited](/en/datamodel/organizations.md#organization_parent_date_last_cited)
 * [Parent relationship: Open-ended?](/en/datamodel/organizations.md#organization_parent_open_ended)
 * [Person: Name](/en/datamodel/persons.md#person_name)

## Superiors {#person_record_anatomy_superiors}

![Image showing the table of commanders of superior units that appears on a person record on WhoWasInCommand.com](/en/assets/person_record_anatomy_superiors.png)

This section displays a table of commanders of units that were superior to any units commanded by this person, along with the duration of overlap in service that sources are able to evidence. As with all tables in person, unit and incident records, hovering over or tapping any value in the table will cause a little coloured circle to appear. Click or tap again on this to view the sources and confidence ratings we have assigned to that value.

### Fields used in the superiors section

The following fields are used in the superiors section:

 * [Organization: Name](/en/datamodel/organizations.md#organization_name)
 * [Organization: Parent](/en/datamodel/organizations.md#organization_parent_name)
 * [Parent relationship: Classification](/en/datamodel/organizations.md#organization_parent_classification)
 * [Parent relationship: Date first cited](/en/datamodel/organizations.md#organization_parent_date_first_cited)
 * [Parent relationship: start date?](/en/datamodel/organizations.md#organization_parent_date_first_cited_is_start)
 * [Parent organization: date last cited](/en/datamodel/organizations.md#organization_parent_date_last_cited)
 * [Parent relationship: Open-ended?](/en/datamodel/organizations.md#organization_parent_open_ended)
 * [Person: Name](/en/datamodel/persons.md#person_name)

The below fields are calculated from the date values in the above fields:

 * Start of overlap: the earliest date that the present person and a commander of an immediately superior unit served at the same time.
 * End of overlap: the last date that the present person and a command of an immediately superior unit served at the same time.
 * Duration of overlap: the number of days the present person and an immediate superior served at the same time.

## Subordinates {#person_record_anatomy_subordinates}

![Image showing the table of subordinate personnel that appears on person records on WhoWasInCommand.com](/en/assets/person_record_anatomy_subordinates.png)

This section displays a table of commanders of units that were subordinate to any units commanded by this person. As with all tables in person, unit and incident records on WhoWasInCommand, hovering over or tapping any value in the table will cause a little coloured circle to appear. Click or tap again on this to view the sources and confidence ratings we have assigned to that value.


### Fields used in the subordinates section

The following fields are used in the superiors section:

 * [Organization: Name](/en/datamodel/organizations.md#organization_name)
 * [Organization: Parent](/en/datamodel/organizations.md#organization_parent_name)
 * [Parent relationship: Classification](/en/datamodel/organizations.md#organization_parent_classification)
 * [Parent relationship: Date first cited](/en/datamodel/organizations.md#organization_parent_date_first_cited)
 * [Parent relationship: start date?](/en/datamodel/organizations.md#organization_parent_date_first_cited_is_start)
 * [Parent organization: date last cited](/en/datamodel/organizations.md#organization_parent_date_last_cited)
 * [Parent relationship: Open-ended?](/en/datamodel/organizations.md#organization_parent_open_ended)
 * [Person: Name](/en/datamodel/persons.md#person_name)

The following fields are calculated from date values in the above fields:

 * Start of overlap: the earliest date that the present person and a commander of an immediately subordinate unit served at the same time.
 * End of overlap: the last date that the present person and a command of an immediately subordinate unit served at the same time.
 * Duration of overlap: the number of days the present person and an immediate superior served at the same time.

## Changelog {#person_record_anotomy_changelog}

![Image showing the changelog that appears at the bottom of organization records on WhoWasInCommand.com](/en/assets/person_record_anatomy_changelog.png)

The data displayed in any record on WhoWasInCommand is always the most recent version. The changelog section shows when the data included in this record were first added and subsequently updated. This data is generated by the software that powers WhoWasInCommand whenever a new data import is run. Clicking on the name of the field will open a box showing all the changes that were made to a datapoint, including the time the change was made and the source used to evidence the change.

