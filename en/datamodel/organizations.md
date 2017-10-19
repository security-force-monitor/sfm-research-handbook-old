# Organizations

Organizations are official state or state-sanctioned organizations responsible for the internal or external security for a country, including police, army, navy, air force and other national security bodies. Organizations refer to any part of the hierarchy of a security force, ranging from a national defence ministry to a police post in a small town. We use the term "Unit" interchangably with "Organization". Organizations can also be groupings of organizations, including joint operations, task forces or peacekeeping missions.

Documented in this chapter are a range of different pieces of data about organizations, including:

* their existence and identity;
* their place in the structure of a security force;
* locations of physical infrastructure like post, bases and camps;
* their areas of operations; and,
* joint operations or missions they have been a member of.

## Summary of organization fields

|Name of field|Description|Examples of use |
| :--- | :--- | :--- |
|[Organization: ID](#organization_id)|A unique code assigned to each organization in the dataset|`a407be6a-28e6-4237-b4e9-307f27b1202e` |
|[Organization: Name](#organization_name)|Name of the organization|`3 Compañía de Infantería No Encuadrada`|
|[Organization: Aliases](#organization_aliases)|Other names for an organization, including aliaes, alternative spellings and abbreviations|`Tercera Compañía de Infantería No Encuadrada`, `3/a. Compañía de Infantería No Encuadrad`|
|[Organization: Country](#organization_country)|The country in which an organziation originates|`mx`|
|[Organization: Classification](#organization_classification)|General branch or tier of security force that an organization a part of|`Army`,`Ejército`|
|[Organization: Date first cited](#organization_date_first_cited)|The earliest date that a source shows an organization exists, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Organization: Start date?](#organization_date_first_cited_is_start)| Is the value in `Organization: Date first cited` the actual date on which an organization was founded, or the earliest date a source has referred to an organization?|`Y`,`N`|
|[Organization: Date last cited](#organization_date_last_cited)|The latest date that a source shows an organization exists, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Organization: Open-ended?](#organization_date_last_cited_open_ended)|Is the value in `Organization: Date last cited` the actual date on which an organization was disbanded, the latest date a source has referred to an organization, and can we assume this organization will continue to exist?|`Y`, `N`, `E`|
|[Organization: Parent](#organization_parent_name)|The immediate superior organization in the overall hierarchy|`1 Región Naval`|
|[Parent relationship: Classification](#organization_parent_classification)|Type of relationships that exists between two organizations| `Command`|
|[Parent relationship: Date first cited](#organization_parent_date_first_cited)|The earliest date that a source shows a parent organization relationship exists, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Parent relationship: start date?](#organization_parent_date_first_cited_is_start)|Is the value in `Parent relationship: Date first cited` the actual date on which an organization became the parent of another, or the earliest date a source has referred to the relatioship?|`Y`, `N`|
|[Parent organization: date last cited](#organization_parent_date_last_cited)|The latest date that a source shows a parent organization relationship exists, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Parent relationship: Open-ended?](#organization_parent_open_ended)|Is the value in `Parent relationship: Date last cited` the actual date on which an organization stopped being the parent of another, or latest date a source has referred to this relationship, and can we assume this relationship will continue to exist?|`Y`, `N`, `E`|
|[Headquarters](#organization_headquarters)|A headquarters is a uniquely named building or complex - like a barracks or camp - where the organization is located|`Campo Militar Número 5-C`|
|[Site: Exact Location (Longitude or OSM Node Name)](#organization_site_ex_loc_name)|The longitude or OSM Node name of the most precise location of a site associated with this organization| `30.09716`, `Masr Al-Gedida`|
|[Site: Exact Location (Latitude or OSM Node ID)](#organization_site_ex_loc_id)|The latitude or OSM node ID number of the most precise location of a site associated with this organization|`31.3280332`, `Masr Al-Gedida`|
|[Site: Settlement (OSM Node Name)](#organization_site_settlement_name)|The OSM node name of the city, town or village in which an organization site is based|`Tampico`, `Francisco Escarcega`, `Abu al Matamir`|
|[Site: Settlement (OSM ID)](#organization_site_settlement_id)|The OSM node ID number of the city, town or village in which an organization site is based|`273584290`,`286989920`,`769127625`|
|[Site: Top Administrative Area (OSM Name)](#organization_site_top_admin_name)| description | example |
|[Site: Top Administrative Area (OSM ID number)](#organization_site_top_admin_id)| description | example |
|[Site: Country](#organization_site_country)|The country in which and organization site is location|`mx`, `ug`, `ng`|
|[Site: Date of first citation](#organization_site_date_first_cited)| This field is for the earliest citation for the location of a site, either through direct reference in the source or by the date of its publication |`2012-11-23`, `2012-11`, `2012`|
|[Site: Founding date?](#organization_site_date_first_cited_founding)|Is the value in Site: Date first cited the actual date on which an organization site was founded, or the earliest date a source has referred to an organization site?|`Y`, `N`|
|[Site: Date last cited](#organization_site_date_last_cited)|This field is for the latest citation for the location of a site, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Site: open-ended?](#organization_site_date_last_cited_open_ended)|Indicates whether the value in Site: Date last cited is the actual date on which an organization site was disbanded, the latest date a source has referred to an organization site, and whether can we assume this organization site continues to exist|`Y`, `N`, `E`|
|[Area of Operations: OSM object name](#organization_aoo_osm_name)|A geographical area in which an organization exercises jurisdiction or has operated in any manner|`Baja California Sur`, `Kafr el-Sheikh Governorate`|
|[Area of Operations: OSM object ID number](#organization_aoo_osm_id)|A geographical area in which an organization exercises jurisdiction or has operated in any manner|`2589611`, `4103405`|
|[Area of Operations: Country](#organization_aoo_country)|The country in which an Area of Operation is located|`mx`, `ug`, `ng`|
|[Area of Operations: Date first cited](#organization_aoo_date_first_cited)|This field is for the earliest citation for an organization's Area of Operations, either through direct reference in the source or by the date of its publication| example |
|[Area of Operations: Start date?](#organization_aoo_date_last_cited_is_start)|Is the value in Area of Operations: Date first cited the actual date on which an organization's Area of Operations started, or the earliest date a source has referred to an organization's Area of Operations?|`Y`, `N`|
|[Area of Operations: Date last cited](#organization_aoo_date_last_cited)|This field is for the latest citation for an Area of Operations, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Area of Operations: Open-ended?](#organization_aoo_open_ended)|Indicates whether the value in Area of Operations: Date last cited is the actual date on which an organization ended operatiosn in the specified area, the latest date a source has referred to this Area of Operations, and whether can we assume an organization will continue to operate in an area beyond the date of last citation|`Y`, `N`, `E`|
|[Organization Membership](#organization_membership)|Internal/national joint operations, international peacekeeping operations, or other multi-unit efforts that this organization is a part of|Operación `Conjunta Chihuahua`, `Operation BOYONA`|
|[Membership: Date first cited](#organization_membership_date_first_cited)|This field is for the earliest citation for the location of a membership, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Membership: Start date?](#organization_membership_is_start)|Is the value in Membership: Date first cited the actual date on which a membership was started, or the earliest date a source has referred to an organization Membership?|`Y`, `N`|
|[Membership: Date of last citation](#organization_membership_date_last_cited)|This field is for the latest citation of a membership, either through direct reference in the source or by the date of its publication|`2012-11-23`, `2012-11`, `2012`|
|[Membership: Open-ended?](#organization_membership_open_ended)|Indicates whether we assume the relationship between organizations continues after the date in `Membership: Date last cited`|`Y`, `N`, `E`|
|[Notes](#organization_notes)|Analysis, commentary and notes about the organization that do not fit into the data structure|`Supported the the Michoacan Attorney General's Office in a raid performed on 13 January 2008` |

## Organization: ID {#organization_id}

### Description

A unique code assigned to each organization in the dataset.

### Type of field

Text and numbers

### Example of use

`a407be6a-28e6-4237-b4e9-307f27b1202e`

### Guidance on use

This field is created automatically when data is uploaded into the Monitor's online platform.

## Organization: Name {#organization_name}

### Description

Name of the organization.

### Type of field

Text and numbers

### Example of use

`3 Armoured Division of the Nigerian Army`, `3 Compañía de Infantería No Encuadrada`, `4 Batallón de Infantería`

### Guidance on use

Different sources will spell an organization's name in different ways, so we choose one of those names to be a canonical version. Wherever possible, we will choose the most complete and complex version of an organization’s name that can be evidenced by a source:

> Example: `3 Armoured Division` would be the entry, rather than the more informal `3 Division` \(which may have more citations\).

In addition to choosing the most complete and complex version of a organization's name, we also attempt to standardize names based on the overall structure of and reporting about the security forces:

> Example:`Police Divisions` are a class of police units in Nigeria. There are over 1000 units of this type nationwide. However, each individual `Police Division` may not have a citation for their formal name such as Lagos Police Division, but only have a citation \(or numerous citations\) for the less formal `Lagos Division`. The Monitor would list the name of the unit as `Lagos Police Division` with a note about the methodology behind that choice. The less formal `Lagos Division` name would be entered in the `Aliases or alternative spellings` field.
>
> Example: Army units of a country may follow a naming convention of a number and then name of unit: e.g. `3 Battalion` or `25 Brigade`. There may be a unit of which we only have citations for a variation on that: e.g. `Fourth Battalion`. In this case, the Monitor would list the name of the unit as `4 Battalion` with a note about the methodology behind that choice. The `Fourth Battalion` name variant would be entered in the `Aliases or alternative spellings` field

The Monitor does not use ordinal indicators like `1st` or `3rd` in the name of an Organization. Enter the name with the ordinal indicator in the `Organization: Aliases` field \(see below\).

Use the name in the local language \(official\) of the country where appropriate.

> Example: A unit in the Mexican Army would be called by its name in Spanish \(`10 Regimiento de Caballería Motorizado`\), rather than the English translation \( `10 Motorized Cavalry Regiment`\). See the section on Aliases of alternative spellings for more information on what to do with English language translations of names.

Where the name of an organization contains Roman numerals like `V` or `XI` these should not be turned into commonly used numbers like `5` or `11` respectively.

## Organization: Aliases {#organization_aliases}

### Description

Other names for an organization, including aliaes, alternative spellings and abbreviations.

### Type of field

Text and numbers

### Example of use

If `3 Compañía de Infantería No Encuadrada` is used as the canonical `Organization: Name` of an organization, entries in the `Organization: Aliases` field may include `Tercera Compañía de Infantería No Encuadrada` and `3/a. Compañía de Infantería No Encuadrad`.

### Guidance on use

Different sources will spell an organization's name in different ways. We choose and record a canonical version of a organization's name in the `Organization: Name` field. All other spellings that we have found are treated as aliases and stored in this field.

Although we do not use ordinal indicators like `2nd` or `10/o` in the canonical name we choose for an organization, where a source uses an Ordinal we record it as an alias.

> Example: We find a version of the organization name `10 Regimiento de Caballería Motorizado` that has an Ordinal indicator: `10/o. Regimiento de Caballería Motorizado.` We would record this in the `Aliases` field.

## Organization: Country {#organization_country}

### Description

The country in which an organziation originates.

### Type of field

Two letter country code

### Example of use

`mx`, `ug`, `ng`

### Guidance on use

The `Organization: Country` field identifies the country this organization comes from. All entries in this field are two letter country codes taken from [ISO 3166 which can be searched here](https://www.iso.org/obp/ui/#search).

> For example, an organization based in Nigeria would have the code `ng` and an organization based in Brazil would have the code `br`

## Organization: Classification {#organization_classification}

### Description

General branch or tier of security force that an organization is a part of.

### Type of field

Text and numbers

### Example of use

`Army`, `Ejército`,`Police`, `Military`,`Military Police`,`Joint Operation`

### Guidance on use

We use classifications to describe the basic nature of a specific organization: is it a police unit? Is it a military unit? Is it part of a joint operation? `Organization: Classification` values are useful supplements to `Organization: Parent` and `Organization: Membership` data we use to connect different units together.

The `Organization: Classification` field will contain a mix of standard terms and country-specific terms used to describe security force branches.

> For example: a standard term we would apply to army units is `Army`. The equivalent in Mexico would be `Ejécito`. We would capture both terms in the `Organization: Classification` field.

When applying a classification to an organization, we try to be as specific as the source allows.

> For example: In Mexico \(which has federal level, state level and municipal level police forces, all independent of one another\) a municipal police force in Mexico is given two classifications: `Municipal Police ; Police`. A state police unit is given two classifications: `State Police ; Police`. So when human rights reporting is specific in saying municipal police officers committed an abuse nearby where this unit is located, we tag it. When there is more vague reporting of just “police” committing abuses both units that have a Police classification and are located near where the abuse occurred are tagged.

In choosing terms to include in the `Organization: Classification` field we try to include terms that are used by country experts as well as those that are commons terms. We also try to be economical and create as few, distinct terms as possible.

## Organization: Date first cited {#organization_date_first_cited}

### Description

The earliest date that a source shows an organization exists, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields`Organization: Start date?`, `Organization: Date last cited` and `Organization: Open-ended?` the field `Organization: Date first cited` provides data about the time period we can evidence an organization has existed.

The `Organization: Date first cited` field contains a date that is either:

* The earliest date found in a source that specifically references an organization; or,
* The earliest date of publication of sources that make reference to an organization.

> For example, if three sources published on 1 January 2012, 1 February 2012 and 1 March 2012 all refer to 1 Motorized Brigade, we will use 1 January 2012 as the `Organization: Date first cited`. If the source published on 1 March 2012 refers to activity of 1 Motorized Brigade that occurred on 30 June 2011, we will use 30 June 2011 as the `Organization: Date first cited`.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Organization: Date first cited` .

This field is clarified by the field `Organization: Start date?` which indicates whether the date included here is the actual date on which an organization was founded.

## Organization: Start date? {#organization_date_first_cited_is_start}

### Description

Is the value in `Organization: Date first cited` the actual date on which an organization was founded, or the earliest date a source has referred to an organization?

### Type of field

Boolean

### Example of use

`Y`,`N`

### Guidance on use

This is a clarifying field for `Organization: Date first cited`. Where a source references an organization and specifies the date that organization was created we will enter `Y` . In all other cases we will enter a value of `N` to indicate that the date is not a start date, but the date of first citation.

## Organization: Date last cited {#organization_date_last_cited}

### Description

The latest date that a source shows an organization exists, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzy

### Example of use

`2013`,`2013-12`, `2013-12-28`

### Guidance on use

Along with the fields `Organization: Date first cited`, `Organization: Start date?`and `Organization: Open-ended?` the field `Date last cited` provides data on the time period we can say an organization has existed.

The `Organization: Date last cited` field contains a date that is either:

* The latest date found in a source that specifically references an organization; or,
* The latest date of publication of sources that make reference to an organization.

> For example, if three sources published on 1 January 2012, 1 February 2012 and 1 March 2012 all refer to 1 Motorized Brigade, we will use 1 March 2012 as the `Organization: Date last cited`. If the source published on 1 March 2012 refers to activity of 1 Motorized Brigade that occurred on 15 February 2012, we will use 15 February 2012 as the value in `Organization: Date last cited`.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Organization: Date last cited` .

This field is clarified by `Organization: Open-ended?`, which indicates whether the date in `Organization: Date last cited` is the date an organization was disbanded.

## Organization: Open-ended? {#organization_date_last_cited_open_ended}

### Description

Is the value in `Organization: Date last cited` the actual date on which an organization was disbanded, the latest date a source has referred to an organization, and can we assume this organization will continue to exist?

### Type of field

Single choice

### Example of use

`Y`,`N`,`E`

### Guidance on use

We use this field to clarify the meaning of the date entered in `Organization: Date last cited`. One of the below values should be chosen:

* `E` indicates the exact date this organization was disbanded, or ceases to exist.
* `Y` indicates that we assume this organization continues to exist.
* `N` indicates we do not assume that this organization continues to exist, but we do not have an exact end date.

## Organization: Parent {#organization_parent_name}

### Description

The immediate superior organization in the overall hierarchy. 

### Type of field

Text and numbers

### Example of use

`1 Región Naval`

### Guidance on use

`Organization: Parent` describes a hierarchical, time-bound relationship between two organizations that are part of the same branch of a security force. The parent is “above” or distinct and separate from the organization in some way. As a rule of thumb, generally parent organizations control the units that operate in the parent’s Area of Operations \(but not always\).

> For example, in Mexico `8 Zona Militar` is a parent of `19 Regimiento de Caballería Motorizada` between 15 May 1999 and 20 November 2006.

Over time, an organization may have different parents. Organizations can have multiple parent relationships at the same time. For example, sources could indicate an organization has a formal legal parent unit while at the same time a new security body established by decree can also directly order the organization to carry out operations, establishing a second parent relationship.

In our data model `Organization: Parent` relationships are different from `Organization: Membership`. Often when there is an "operation" or "joint task force", it may not have have personnel of its own. Rather, personnel from a range of different organizations are assigned to it. Generally, these types of arrangements don’t put the operation “above” the unit in the organizational chart. Rather, they are “on the same level” as it. We outline these types of relationships using the field `Organization: Membership`, which is documented below.

## Parent relationship: Classification {#organization_parent_classification}

### Description

Type of relationships that exists between two organizations.

### Type of field

Controlled vocabulary, single choice

### Example of use

`Command`

### Guidance on use

Organizations have a `Command` relationship when the parent organization can order the organization to perform some operational activity.

`Informal` relationships occur where no legal or formal relationship exists, but there is a relationship where parent organization could exert some form of influence on the organization.

> Example: Lagos state in Nigeria has a security council. This is a meeting of the governor, and the top commanders of police and military units in the state. The security council should be considered its own organization. By law a governor of a state is not in the chain of command for the military or police forces, but the security council membership establishes a relationship between the organizations and meetings often result in new approaches to security being taken, such as different deployments of police. In this case, we could make the determination that an informal relationship exists between the security council and the police and military organizations.

`Administrative` relationships exist where a formal, non-command relationship exists between organizations, or where an administrative description is more accurate of the relationship between two organizations.

> For example: the Minister of Defence in Nigeria is by law in charge providing administrative support to the Nigerian Army, establishing a relationship we could classify as `administrative`. The Standards Department of an Army Headquarters might be under the control of the Army Headquarters, meaning the Army Headquarters could appoint or fire the head of the Department. So technically the Department is under the “command” of the Headquarters, but describing this relationship as `administrative` is more helpful because the Department is not in the field conducting operations, it's an administrative organ of the Army Headquarters.





## Parent relationship: Date first cited {#organization_parent_date_first_cited}

### Description

The earliest date that a source shows a parent organization relationship exists, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields the fields `Parent relationship: Start date?`, `Parent relationship: Sate last cited` and `Parent relationship: Open-ended?` the field `Parent organization: Date first cited` provides data on the time period we can say one organization is the parent of another .

The `Parent organization: Date first cited` field contains a date that is either:

* The earliest date found in a source that specifically references a parent relationship; or,
* The earliest date of publication of sources that make reference to a parent relationship.

> For example, if three sources published on 1 January 2012, 1 February 2012 and 1 March 2012 all say that 3 Armoured Division became the parent of 1 Motorized Brigade, we will enter 1 January 2012 in`Parent relationship: date first cited`. If the source published on 1 March 2012 says that 3 Armoured Division became the parent of 1 Motorized Brigade on 30 June 2011, we will use 30 June 2011 as the `Parent relationship: date first cited`.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included `Parent relationship: Date first cited` .

This field is clarified by the field `Parent relationship: Start date?` which indicates whether the date included here is the actual date on which an organization became the parent of another.

## Parent relationship: start date? {#organization_parent_date_first_cited_is_start}

### Description

Is the value in `Parent relationship: Date first cited` the actual date on which an organization became the parent of another, or the earliest date a source has referred to the relatioship?

### Type of field

Boolean \(Yes, No\)

### Example of use

`Y`,`N`

### Guidance on use

This is a clarifying field for `Parent relationship: Date first cited`. Where a source references the parent relationship and specifies the date that the relationship was created we will enter `Y` . In all other cases we will enter a value of `N` to indicate that the date is not a start date, but the date of first citation.

## Parent organization: date last cited {#organization_parent_date_last_cited}

### Description

The latest date that a source shows a parent organization relationship exists, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields the fields `Parent relationship: Date first cited`, `Parent relationship: Start date?` and `Parent relationship: Open-ended?` the field `Parent organization: Date last cited` provides data on the time period we can evidence that one organization is the parent of another.

The `Parent organization: Date last cited` field contains a date that is either:

* The latest date found in a source that specifically references a parent relationship; or,
* The latest date of publication of sources that make reference to a parent relationship.

> For example, if three sources published on 1 January 2012, 1 February 2012 and 1 March 2012 all say that 3 Armoured Division became the parent of 1 Motorized Brigade, we will enter 1 March 2012 in `Parent relationship: Date last cited`. If the source published on 1 March 2012 says that 3 Armoured Division became the parent of 1 Motorized Brigade on 15 February 2012, we will use 15 February 2012 as the `Parent relationship: Date last cited`.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included `Parent relationship: Date last cited` .

This field is clarified by the field `Parent relationship: Open-ended?` which indicates whether the date included here is the actual date on which an organization stopped being the parent of another.


## Parent relationship: Open-ended? {#organization_parent_open_ended}

### Description

Is the value in `Parent relationship: Date last cited` the actual date on which an organization stopped being the parent of another, or latest date a source has referred to this relationship, and can we assume this relationship will continue to exist?

### Type of field

Single choice \(Y, N, E\)

### Example of use

`Y`,`N`,`E`

### Guidance on use

We use this field to clarify the meaning of the date entered in `Parent relationship: Date last cited`. One of the below values should be chosen:

* `E` indicates the exact date one organization stopped being the parent of another.
* `Y` indicates that we assume this parent relationship continues to exist.
* `N` indicates we do not assume that this parent relationship continues to exist, but we do not have an exact end date.

## Headquarters {#organization_headquarters}

### Description

A headquarters is a uniquely named building or complex - like a barracks or camp - where the organization is located. 

### Type of field

Text and numbers

### Example of use
`Campo Militar Número 5-C`

### Guidance on use

This field is used to record data about units that have a uniquely named building or complex for their headquarters.

> For example, `3 Battalion` in Nigeria is cited as being based in the `Lubanga Barracks` in `Enugu, Enugu State, Nigeria`.

This field should not be used for anything that matches the name or alias of a organization. For example, `North Sector Police Station` should not be put in this field if the name of the organization is `North Sector Police Station`.

## Site: Exact Location (Longitude or OSM Node Name) {#organization_site_ex_loc_name}

### Description

The longitude or OSM Node name of the most precise location of a site associated with this organization.

### Type of field

First value of a latitude/longitude pair (using [EPSG:3857](http://spatialreference.org/ref/epsg/wgs-84/)), or an OSM Node Name.

### Example of use

If used to record an OSM Node Name: `Masr Al-Gedida`
If used to record a latitude: `31.3280332`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision.

`Site: Exact Location (Longitude or OSM Node Name)` is the first of a pair of values with `Site: Exact Location (Latitude or OSM Node ID)`. It is used to record the most precise location of a site associated with an organization, whether this is a node on Open Street Map or a pair of geographical coordinates.

* Where an node for the exact site is present on Open Street Map we will enter its name in this field.
* Where no OSM node exists for the exact site a pair of coordinates will be used, the latitude value recorded in this field.

## Site: Exact Location \(Latitude or OSM Node ID\) {#organization_site_ex_loc_id}

### Description

The latitude or OSM node ID number of the most precise location of a site associated with this organization.

### Type of field

Second value of a longitude/latitude pair (using [EPSG:3857](http://spatialreference.org/ref/epsg/wgs-84/)), or an OSM Node ID number.

### Example of use

If used to record an OSM Node ID number: `452377264 `
If used to record a Longitude: `30.09716`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision.

`Site: Exact Location (Latitude or OSM Node ID)` is the second of a pair of values with `Site: Exact Location (Longitude or OSM Node Name)`. It is used to record the most precise location of a site associated with an organization, whether this is a node on Open Street Map or a pair of geographical coordinates.

* Where an node for the exact site is present on Open Street Map we will enter its ID number in this field.
* Where no OSM node exists for the exact site a pair of coordinates will be used, the latitude value recorded in this field.

## Site: Settlement (OSM Node Name){#organization_site_settlement_name}

### Description

The city, town or village in which an organization site is based.

### Type of field

Text, OSM node name, first in a pair of values

### Example of use

`Tampico`, `Francisco Escarcega`, `Abu al Matamir`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision. In `Site: Settlement (OSM Node Name)` we record the name of the OSM node that identifies a settlement in which there is an organization site. It could be a city, town or village or other OSM node that denotes a settlement.

## Site: Settlement (OSM ID) {#organization_site_settlement_id}

### Description

The city, town or village in which an organization site is based.

### Type of field

Number, OSM node ID number, second in a pair of values

### Example of use

`273584290`,`286989920`,`769127625`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision. In `Site: Settlement (OSM ID)` field we record the name of the OSM ID number that identifies a settlement in which there is an organization site. It could be a city, town or village or other OSM node that denotes a settlement.

## Site: Top Administrative Area (OSM Name) {#organization_site_top_admin_name}

### Description

The OSM relation name of the highest sub-national administrative area in which an organization site is based.

### Type of field

Text, OSM relation name, first in a pair of values

### Example of use

`Michoacán`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision. In `Site: Top Administrative Area (OSM Name)` we record the text name of highest level subnational boundary for the country in which the site is located, [as found in in OpenStreetMap](http://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative#Super-national_administrations).

> For example Mexico has both *municipios* \(administrative level 6 in OSM\) and states \(administrative level 4\). For a `site` based in Mexico, we would record in `Site: Top Administrative Area (OSM Name)` the name the "state" \(admin level 4\).

## Site: Top Administrative Area \(OSM ID number\) {#organization_site_top_admin_id}

### Description
The OSM relation ID number of the highest sub-national administrative area in which an organization site is based.

### Type of field

Number, OSM relation ID number, second in a pair of values

### Example of use
`2340636`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision. In `Site: Top Administrative Area (OSM ID number)` we record OSM relation ID number of the highest level subnational boundary for the country in which the site is located, [as found in in OpenStreetMap](http://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative#Super-national_administrations).

> For example Mexico has both *municipios* \(administrative level 6 in OSM\) and states \(administrative level 4\). For a `site` based in Mexico, we would record in `Site: Top Administrative Area (OSM Name)` the name the "state" \(admin level 4\).

## Site: Country {#organization_site_country}

### Description

The country in which an organziation site is located.

### Type of field

Two letter country code

### Example of use

`mx`, `ug`, `ng`

### Guidance on use

We identify `sites` with a number of different levels of geographical precision.The `Site: Country` field identifies the country in which an organization site is located. All entries in this field are two letter country codes taken from [ISO 3166 which can be searched here](https://www.iso.org/obp/ui/#search).

> For example, an organization site located in Nigeria would have the code `ng` and an organization site located in Brazil would have the code `br`.

## Site: Date of first citation {#organization_site_date_first_cited}

### Description

This field is for the earliest citation for the location of a site, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Site: Founding date?`, `Site: Date last cited` and `Site: Open-ended?` the field `Site: Date first cited` provides data on the time period for which can specify a site's location.

The `Site: Date first cited` field contains a date that is either:

* The earliest date found in any source that references the values contained in the pairs of fields that record `Site: Settlement`, or failing that, `Site: Top Administrative area`.
* The earliest date of publication of any source that references the values contained in the pairs of fields that record `Site: Settlement`, or failing that, `Site: Top Administrative area`.
.
In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Site: Date first cited`.

This field is clarified by the field `Site: Founding date?` which indicates whether the date included here is the actual date on which an organization site was founded.


## Site: Founding date? {#organization_site_date_first_cited_founding}

### Description

Is the value in `Site: Date first cited` the actual date on which an organization site was founded, or the earliest date a source has referred to an organization site?

### Type of field

Boolean \(Yes, No\)

### Example of use

`Y`,`N`

### Guidance on use

This is a clarifying field for `Site: Date first cited`. Where a source references an organization site and specifies the date that organization site was founded we will enter `Y` . In all other cases we will enter a value of `N` to indicate that the date is not a start date, but the date of first citation.

## Site: Date last cited {#organization_site_date_last_cited}

### Description

This field is for the latest citation for the location of a site, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Site: Date first cited`, `Site: Founding date?` and `Site is Open-ended?` the field `Site: Date last cited` provides data on the time period for which can specify a site's location.

The `Site: Date last cited` field contains a date that is either:

* The latest date found in any source that references the values contained in the pairs of fields that record `Site: Settlement`, or failing that, `Site: Top Administrative area`.
* The latest date of publication of any source that references the values contained in the pairs of fields that record `Site: Settlement`, or failing that, `Site: Top Administrative area`.
.
In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Site: Date last cited`.

This field is clarified by the field `Site: Open-ended?` which indicates whether the date included here is the actual date on which an organization site was terminated.

## Site: open-ended? {#organization_site_date_last_cited_open_ended}

### Description

Indicates whether the value in `Site: Date last cited` is the actual date on which an organization site was disbanded, the latest date a source has referred to an organization site, and whether can we assume this organization site continues to exist.

### Type of field

Single choice \(Y, N, E\)

### Example of use

`Y`,`N`,`E`

### Guidance on use

We use this field to clarify the meaning of the date entered in `Date last cited`. In entering a value for this field we use a variety of factors including: the history of basing for the unit, the overall structure and nature of the security forces, and the frequency of movement of similar units.

The values that can be entered in this field are restricted to the below:

* `E` indicates the exact date this organization site was disbanded, or ceases to exist.
* `Y` indicates that we assume this organization site continues to exist.
* `N` indicates we do not assume that this organization site continues to exist, but we do not have an exact end date.

## Area of Operations: OSM object name {#organization_aoo_osm_name}

### Description
A geographical area in which an organization exercises jurisdiction or has operated in any manner

### Type of field
Text and numbers, OSM object name, first in a pair of fields

### Example of use
`Baja California Sur`, `Kafr el-Sheikh Governorate`

### Guidance on use

The `Area of Operations` fields document multiple and concurrent areas of operation of an organization. The value entered in this field is the Open Street Map name for the lowest-level formal geographical area that best describes where an organization has operated in some manner.

## Area of Operations: OSM object ID number {#organization_aoo_osm_id}

### Description
A geographical area in which an organization exercises jurisdiction or has operated in any manner

### Type of field
Numbers, OSM object ID number, second in a pair of fields

### Example of use
`2589611`, `4103405`

### Guidance on use

The `Area of Operations` fields document multiple and concurrent areas of operation of an organization. The value entered in this field is the OpenStreetMap object ID number for the lowest-level formal geographical area that best describes where an organization has operated in some manner.

## Area of Operations: Country {#organization_aoo_country}
### Description

The country in which an Area of Operation is located.

### Type of field

Two letter country code

### Example of use

`mx`, `ug`, `ng`

### Guidance on use

We identify `Area of Operations` with two different levels of geographical precision.The `Area of Operations: Country` field identifies the country in which an organization has operated in some manner. All entries in this field are two letter country codes taken from [ISO 3166, which can be searched here](https://www.iso.org/obp/ui/#search).

## Area of Operations: Date first cited {#organization_aoo_date_first_cited}

### Description

This field is for the earliest citation for an organization's `Area of Operations`, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Area of Operations: Founding date?`, `Area of Operations: Date last cited` and `Area of Operations: Open-ended?` the field `Area of Operations: Date first cited` provides data on the time period for which can specify an organization's Area of operations.

The `Area of Operations: Date first cited` field contains a date that is either:

* The earliest date found in any source that references the values contained in the pairs of fields that record `Area of Operations`.
* The earliest date of publication for any source that references the values contained in the pairs of fields that record `Area of Operations`.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Area of Operations: Date first cited`.

This field is clarified by the field `Area of Operations: start date?` which indicates whether the date included here is the actual date on which an Area of Operations started.

## Area of Operations: Start date? {#organization_aoo_date_last_cited_is_start}

### Description

Is the value in `Area of Operations: Date first cited` the actual date on which an organization's Area of Operations started, or the earliest date a source has referred to an organization's Area of Operations?

### Type of field

Boolean \(Yes, No\)

### Example of use

`Y`,`N`

### Guidance on use

This is a clarifying field for `Area of Operations: Date first cited`. Where a source references an organization site and specifies the date that organization Area of Operations was started we will enter `Y` . In all other cases we will enter a value of `N` to indicate that the date is not a start date, but the date of first citation.

## Area of Operations: Date last cited {#organization_aoo_date_last_cited}

### Description

This field is for the latest citation for an Area of Operations, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Area of Operations: Date first cited`, `Area of Operations: start date?` and `Area of Operations: Open-ended?` the field `Site: Date last cited` provides data on the time period for which can specify an Area of Operations location.

The `Area of Operations: Date last cited` field contains a date that is either:

* The latest date found in any source that references the values contained in the pairs of fields that record `Area of Operations`.
* The latest date of publication for any source that references the values contained in the pairs of fields that record `Area of Operations`.
.
In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Site: Date last cited`.

This field is clarified by the field `Site: Open-ended?` which indicates whether the date included here is the actual date on which an organization site was ended, or whether we have reason to assume its continued existence beyond that date.

## Area of Operations: Open-ended? {#organization_aoo_open_ended}

### Description

Indicates whether the value in `Area of Operations: Date last cited` is the actual date on which an organization ended operatiosn in the specified area, the latest date a source has referred to this Area of Operations, and whether can we assume an organization will continue to operate in an area beyond the date of last citation.

### Type of field

Single choice from selection

### Example of use

`Y`,`N`,`E`

### Guidance on use

We use this field to clarify the meaning of the date entered in `Area of Operations: Date last cited`. In entering a value for this field we use a variety of factors to assess whether an organization continues to operation in any manner in this area beyond the date of the last citation. These include: the history of operations of the organization, the overall structure and nature of the security forces, and the frequency of movement of similar units.

> For Example, the `New York State police` would likely maintain an AOO over all of `New York State` even if the last citation available to us was from 2015.

The values that can be entered in this field are restricted to the below:

* `E` indicates the exact date an organization stops operating in the specified area.
* `Y` indicates that we assume this organization continues to operation in the specified area.
* `N` indicates we do not assume that this organization will continue to operate in the specified area, but we do not have an exact end date for this.


## Organization Membership {#organization_membership}

### Description
Internal/national joint operations, international peacekeeping operations, or other multi-unit efforts that this organization is a part of

### Type of field
Text and numbers,.

### Example of use
`Operación Conjunta Chihuahua`, `Operation BOYONA`

### Guidance on use

This field indicates whether an organization has had any memberships or attachments to internal/national joint operations, international peacekeeping operations, or other multi-unit efforts. Generally this means one of two things:

1\) Multiple units operate as part of an “operation” focused on a specific mission.
2\) Multiple units “lend” or otherwise deploy personnel who operate under the command of a force composition like a "Joint Task Force" or "Operation", which usually has a commander of its own.

> Example: soldiers from `1 Division` are deployed to the northeast of Nigeria to operate under `Operation BOYANA`. `1 Division` has a commander, but the soldiers as part of `Operation BOYANA` likely report to and take orders from the commander of `Operation BOYANA`. When the soldiers are done with their rotation, after several months, they return to their “home unit” `1 Division`. So while `Operation BOYANA` commands some soldiers who are part of `1 Division` it doesn’t technically command all of the soldiers of `1 Division` \(otherwise it would be the parent unit\) These operations - joint task forces, and so on - should have their own distinct `Organization` entries.

We treat task forces, operations, peace keeping missions that are constitued via a membership of other organizations as distinct organizations.


## Membership: Date first cited {#organization_membership_date_first_cited}

### Description

This field is for the earliest citation for the location of a membership, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Membership: Start date?`, `Membership: Date last cited` and `Membership: Open-ended?` the field `Membership: Date first cited` provides data on the duration of one organization's membership in another.

The `Membership: Date first cited` field contains a date that is either:

* The earliest date found in any source that references the values contained in the pairs of fields that record `Membership`
* The earliest date of publication of any source that references the values contained in the pairs of fields that record `Membership`.
.
In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Membership: Date first cited`.

This field is clarified by the field `Membership: Founding date?` which indicates whether the date included here is the actual date on which an organization membership was founded.


## Membership: Start date? {#organization_membership_is_start}

### Description

Is the value in `Membership: Date first cited` the actual date on which a membership was started, or the earliest date a source has referred to an organization Membership?

### Type of field

Boolean \(Yes, No\)

### Example of use

`Y`,`N`

### Guidance on use

This is a clarifying field for `Membership: Date first cited`. Where a source references a membership and specifies the exact date the relationship was established we will enter `Y` . In all other cases we will enter a value of `N` to indicate that the date is not a start date, but the date of first citation.

## Membership: Date of last citation {#organization_membership_date_last_cited}

### Description

This field is for the latest citation of a membership, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Membership: Date first cited`, `Membership: Start date?` and `Membership: Open-ended?` the field `Membership: Date last cited` provides data on duration of a membership.

The `Membership: Date last cited` field contains a date that is either:

* The latest date found in any source that references the values contained in the pairs of fields that record `Membership`; or,
* The latest date of publication of any source that references the values contained in the pairs of fields that record `Membership`.
.
In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Membership: Date last cited`.

This field is clarified by the field `Membership: Open-ended?` which indicates whether the date included here is the actual date on which an organization Membership was terminated.

## Membership: Open-ended? {#organization_membership_open_ended}

### Description

Indicates whether we assume the relationship between organizations continues after the date in `Membership: Date last cited`

### Type of field

Single choice \(Y, N, E\)

### Example of use

`Y`,`N`

### Guidance on use

We use this field to clarify the meaning of the date entered in `Date last cited`. In entering a value for this field we use a variety of factors including: the history of basing for the unit, the overall structure and nature of the security forces, and the frequency of movement of similar units.

The values that can be entered in this field are restricted to the below:

* `Y` indicates that we assume this membership continues to exist.
* `N` indicates we do not assume that this membership continues to exist.

## Notes {#organization_notes}

### Description

Analysis, commentary and notes about the organization that do not fit into the data structure.

### Type of field

Text and numbers

### Example of use

`Supported the the Michoacan Attorney General's Office in a raid performed on 13 January 2008`

### Guidance on use

We use this field to record information about the organization that is likely to provide useful context, additional information that does not fit into the data structure, and notes about how decisions were made about which data to include. Any sources used should be included inside the field.
