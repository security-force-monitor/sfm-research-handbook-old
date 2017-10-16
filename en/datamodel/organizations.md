# Organizations

Organizations are official state or state-sanctioned organizations responsible for the internal or external security for a country, including police, army, navy, air force and other national security bodies. Organizations refer to any any part of the hierarchy of a security force, ranging from a national defence ministry, to a police unit based in a small town. Organizations can also be groupings of organizations that occur, such as operations or peacekeeping missions.

## Summary of organization fields

| Name of field | Description | Example of use |
| :--- | :--- | :--- |
| [ID](#organization_id) | Unique identifier for the organization | _a848de4e-ebeb-49d6-9099-7e68ca3b57fc_ |
| [Name](#organization_name) | Name of the organization | _VII Región Militar_ |
| [Aliases](#organization_other_names) | Other names for the organization | _Séptima Región Militar_ |
| [Division ID](#organization_division_id) | Country | _mx_ |
| [Classification](#organization_classification) | Type of organization | _Ejército ; Militar_ |
| [Parent organization](#organization_organization_name) | Superior affiliated organization | _Estado Mayor de la Defensa Nacional_ |
| [Parent relationship](#organization_organization_classification) | Type of relationship | _Command_ |
| [Date of first citation for parent relationship](#organization_organization_date_first_cited) | First source, by date, evidencing a relationship | _1999-02-01_ |
| [Date of last citation for parent relationship](#organization_organization_date_last_cited) | The last source, by date, evidencing a relationship | _2016-07-05_ |
| [Assume parent relationship to current date?](#organization_organization_assume_to_current_date) | Do we have evidence to think the relationship continues after the last source? | _Y_ |
| [Headquarters](#organization_headquarters) | Uniquely named barracks, base, physical asset for this organization | _Campo Militar 1A_ |
| [City or other Node OpenStreetMap Name](#organization_osm_name) | Name of the City or other Node in OpenStreetMap | _Tuxtla Gutiérrez_ |
| [City or other Node OpenStreetMap ID](#organization_osm_id) | ID number linked to above OpenStreetMap Node | _269911529_ |
| [Highest level subnational boundary OpenStreetMap](#organization_admin_level_1_osm_name) | Highest level [subnational boundary in OpenStreetMap](http://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative#Super-national_administrations) | _Chiapas_ |
| [Highest level subnational boundary OpenStreetMap ID](#organization_admin_level_1_osm_id) | OpenStreetMap ID number of highest level subnational boundary | _2556679_ |
| [Site: division\_id](#organization_site_division_id) | Country | _mx_ |
| [Site: Date of first citation](#organization_site_date_first_cited) | First source, by date, evidencing a site | _2004-02-08_ |
| [Is this the Founding Date?](#organization_site_date_first_cited_founding) | Was the site's date of first citation the date the organization was founded? | _N_ |
| [Site: Date of last citation](#organization_site_date_last_cited) | Last source, by date, evidencing a site | _2005-06-04_ |
| [Assume site to current date?](#organization_site_assume_to_current_date) | Do we have evidence to think the relationship continues after the last source? | _Y_ |
| [Area of Operations: OpenStreetMap Name](#organization_area_osm_name) | OpenStreetMap name of an area \(relation in OSM\) that this organisation is responsible for, conducted operations in, or has jurisdiction over | _Chiapas_ |
| [Area of Operations: OpenStreetMap ID](#organization_area_osm_id) | ID for OpenStreetMap entry from above | _2556679_ |
| [Area of Operations: Division ID](#organization_area_division_id) | Country of Area of Operations | _mx_ |
| [Area of Operations: Date of first citation](#organization_area_date_first_cited) | First source, by date, evidencing this Area of Operations | _1999-02-01_ |
| [Area of Operations: Date of last citation](#organization_area_date_last_cited) | Last source, by date, evidencing this Area of Operations | _2016-07-05_ |
| [Area of Operations: Assume to current date?](#organization_area_date_last_cited_assume_to_current) | Do we have evidence to say this Area of Responsibility continues after the last source date? | _Y_ |
| [Other affiliation](#organization_affiliation) | Memberships or attachments to internal/national joint operations, peacekeeping operations, or other multi-unit efforts. | _Operation Pulo Shield_ |
| [Other affiliation: Date of first citation](#organization_affiliation_date_first_cited) | First source, by date, evidencing this affiliation | _2003-02-02_ |
| [Other affiliation: Date of last citation](#organization_affiliation_date_last_cited) | Last source, by date, evidencing this affiliation | _2005-03-09_ |
| [Notes](#organization_notes) | Anything else relevant about this organization that is not covered above | _Organization was trained by US forces in 2010_ |

## ID {#organization_id}

### Description

A unique code assigned to each organization in the dataset.

### Type of field

Text and numbers

### Example of use

`a407be6a-28e6-4237-b4e9-307f27b1202e`

### Guidance on use

This field is created automatically when data is uploaded into the Monitor's online platform.

## Name {#organization_name}

### Description

Name of the organization

Type of field

Text and numbers

### Example of use

`3 Armoured Division of the Nigerian Army`, `V Zona Militar`, `4 Batallón de Infantería`

## Guidance on use

Different sources will spell an organization's name in different ways, so we choose one of those names to be a canonical version. Wherever possible, we will choose the most complete and complex version of an organization’s name that can be evidenced by a source:

> Example: `3 Armoured Division` would be the entry, rather than the more informal `3 Division` \(which may have more citations\).

In addition to choosing the most complete and complex version of a organization's name, we also attempt to standardize names based on the overall structure of and reporting about the security forces:

> Example:`Police Divisions` are a class of police units in Nigeria. There are over 1000 units of this type nationwide. However, each individual `Police Division` may not have a citation for their formal name such as Lagos Police Division, but only have a citation \(or numerous citations\) for the less formal `Lagos Division`. The Monitor would list the name of the unit as `Lagos Police Division` with a note about the methodology behind that choice. The less formal `Lagos Division` name would be entered in the `Aliases or alternative spellings` field.
>
> Example: Army units of a country may follow a naming convention of a number and then name of unit: e.g. `3 Battalion` or `25 Brigade`. There may be a unit of which we only have citations for a variation on that: e.g. `Fourth Battalion`. In this case, the Monitor would list the name of the unit as `4 Battalion` with a note about the methodology behind that choice.  The `Fourth Battalion`  name variant would be entered in the `Aliases or alternative spellings` field

The Monitor does not use ordinal indicators like `1st` or `3rd` in the name of an Organization. Enter the name with the ordinal indicator in the `Aliases` field \(see below\).

Use the name in the local language \(official\) of the country where appropriate.

> Example: A unit in the Mexican Army would be called by its name in Spanish \(`10 Regimiento de Caballería Motorizado`\), rather than the English translation \( `10 Motorized Cavalry Regiment`\). See the section on Aliases of alternative spellings for more information on what to do with English language translations of names.

Where the name of an organization contains Roman numerals like `V` or `XI` these should not be turned into commonly used numbers like `5` or `11` respectively.

## Aliases {#organization_other_names}

### Description

Other names for an organization, including alternative spellings and abbreviations.

### Type of field

Text and numbers

### Example of use

If 3 Compañía de Infantería No Encuadrada is used as the canonical `name` of an organization, entries in the `Aliases` field may include `Tercera Compañía de Infantería No Encuadrada`  and `3/a. Compañía de Infantería No Encuadrad`.

### Guidance on use

Different sources will spell an organization's name in different ways. We choose and record a canonical version of a organization's name in the `Name` field. All other spellings that we have found are treated as aliases and stored in this field. Where the country being researched is non-English speaking, use this field to record English language translations of an organization's name.

Although we do not use ordinal indicators like `2nd` or `10/o` in the canonical name we choose for an organization, where a source uses an Ordinal we record it as an alias.

> Example: We find a version of the organization name `10 Regimiento de Caballería Motorizado` that has an Ordinal indicator: `10/o. Regimiento de Caballería Motorizado.` We would record this in the `Aliases` field.

## Organization division\_id

### Description

The country in which an organziation originates.

### Type of field

Two letter country code

### Example of use

`mx`, `ug`, `ng`

### Guidance on use

The `division_id` field identifies the country this organization comes from. All entries in this field are two letter country codes taken from  [ISO 3166 which can be searched here](https://www.iso.org/obp/ui/#search).

> For example, an organization based in Nigeria would have the code `ng` and an organization based in Brazil would have the code `br`

## Classification {#organization_classification}

### Description

General branch or tier of security force that an organization a part of.

### Type of field

Text and numbers

### Example of use

`Army`, `Ejército`,`Police`, `Military`,`Military Police`,`Joint Operation`

### Guidance on use

We use classifications to describe the basic nature of a specific organization: is it a police unit? Is it a military unit? Is it part of a joint operation? `Classification` values are useful supplements to `parent` and `membership` data we use to connect different units together.

The `Classification` field will contain a mix of standard terms and country-specific terms used to describe security force branches.

> For example: a standard term we would apply to army units is `Army`. The equivalent in Mexico would be `Ejécito`. We would capture both terms in the `Classification` field.

When applying a classification to an organization, we try to be as specific as the source allows.

> For example: In Mexico \(which has federal level, state level and municipal level police forces, all independent of one another\) a municipal police force in Mexico is given two classifications: `Municipal Police ; Police`. A state police unit is given two classifications: `State Police ; Police`. So when human rights reporting is specific in saying municipal police officers committed an abuse nearby where this unit is located, we tag it. When there is more vague reporting of just “police” committing abuses both units that have a Police classification and are located near where the abuse occurred are tagged.

In choosing terms to include in the `Classification` field we try to include terms that are used by country experts as well as those that are commons terms. We also try to be economical and create as few, distinct terms as possible.

## Date first cited

### Description

The earliest date that a source shows an organization exists, either through direct reference in the source or by the date of its publication.

### Type of field

Date \(YYYY-MM-DD\), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields`Start date of organization?`, `Date last cited` and `Open ended?` the field `Date first cited` provides data on the time period we can say an organization has existed. 

The `Date first cited` field contains a date that is either:

* The earliest date found in a source that specifically references an organization; or,
* The earliest date of publication of sources that make reference to an organization.

> For example, if three sources published on 1 January 2012, 1 February 2012 and 1 March 2012 all refer to 1 Motorized Brigade, we will use 1 January 2012 as the `Date first cited`. If the source published on 1 March 2012 refers to activity of 1 Motorized Brigade that occurred on 30 June 2011, we will use 30 June 2011 as the `Date first cited`.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in  `Date first cited` .

## Start date of organization?

### Description

Is the value in  `Date first cited`  the actual date on which an organization was founded, or the earliest date a source has referred to an organization?

### Type of field

Boolean \(Yes, No\)

### Example of use

`Y`,`N`

### Guidance on use

This is a clarifying field for `Date first cited`. Where a source references an organization and specifies the date that organization was created we will enter `Y` . In all other cases we will enter a value of `N` to indicate that the date is not a start date, but the date of first citation.   

## Date last cited

### Description

### Type of field

### Example of use

### Guidance on use

## Open ended?

### Description

### Type of field

### Example of use

### Guidance on use

## Parent Organization: The superior affiliated organization {#organization_organization_name}

The parent must be also entered into the sheet as its own organization.

Think of an organizational chart - the parent is “above” or distinct and separate from the organization in some way. As a rule of thumb, generally parent organizations control the units that operate in the parent’s Area of Operations \(but not always\).

Often when there is an operation or joint task force, it may not have have personnel of its own. Rather, it gets personnel assigned to it. Generally, these types of arrangements don’t put the operation “above” the unit in the organizational chart, but “on the same level” as it. These types of relationships are handled in another field Other Affiliation \(like joint task force\).

### Description

### Type of field

### Example of use

### Guidance on use

## Parent relationship classification {#organization_organization_classification}

Organizations have a Command relationship when the parent organization can order the organization to perform some action.

Informal relationships occur where no legal or formal relationship exists, but there is a relationship where parent organization could exert some form of influence on the organization.

> Example: Lagos state in Nigeria has a security council which is a meeting of the governor, and the top commanders of police and military units in the state. The security council should be considered its own organization. The governor has no legal authority to command the military or police forces, but the security council membership establishes a relationship between the organizations and meetings often result in new approaches to security being taken, such as different deployments of police. An analyst could make the determination that an informal relationship exists between the security council and the police and military organizations.

Administrative relationships exist where a formal, non-command relationship exists between organizations, or where an administrative description is more accurate of the relationship between two organizations.

> Example - the `Minister of Defence` in Nigeria is by law in charge providing administrative support to the `Nigerian Army`, establishing an administrative relationship.  
> Example - the `Standards Department` of an Army Headquarters might be under the control of the Army Headquarters, meaning the Army Headquarters could appoint or fire the head of the Department. So technically the Department is under the “command” of the Ministry, but describing this as Administrative is more helpful, the Department is not in the field conducting operations, it's an administrative organ of the Army Headquarters.

Organizations can have multiple parent relationships at the same time.

### Description

### Type of field

### Example of use

### Guidance on use

## Date of first citation for parent organization {#organization_organization_date_first_cited}

Note that in `Source: Date of first citation for parent organization \(MM/DD/YYYY\)` only put the citation for the earliest date. If there is only one citation, and it establishes the end date for a relationship, leave this field blank and enter that date and citation in the Date of last citation for parent organization and Source: Date of last citation for parent organization fields.

### Description

### Type of field

### Example of use

### Guidance on use

## Start date of parent relationship?

### Description

### Type of field

### Example of use

### Guidance on use

## Date of last citation for parent organization {#organization_organization_date_last_cited}

If there is only one citation for a relationship, and the citation is not for the end of that relationship, leave this field blank and only put the date in the Date of first citation for parent organization.

Note that for `Source: Date of last citation for parent organization` only put the citation for the latest date. If there is only one citation put it in the Source: Date of first citation for parent organization field, if appropriate, and leave this field blank.

### Description

### Type of field

### Example of use

### Guidance on use

## Parent relationship is open ended? {#organization_organization_assume_to_current_date}

In many cases a relationship could be assumed past the last citation date. For example, where a battalion has been reporting to a brigade for years, one could safely assume that this relationship will continue.

This field exists because if the Monitor only displays data up to the last citation any Map and Chart showing the data would quickly be blank. Not every unit is reported on every day so it's impossible to keep things truly “up-to-date”.

There are always assumptions made in the sort of analysis done by the Monitor. For example, a parent relationship established between two units in the military sourced from a press briefing released at 09:00 AM might be changed by a second press briefing at 09:01 AM the same day. Having this field forces us to be more thoughtful about what we assume and why.

There are cases where there appears to be a temporary relationship, a historical relationship simply not enough data to base an assumption on. In these cases, the analyst would record an `N` in this field in order to state that there is no assumption this relation continue following the date of last citation.

### Description

### Type of field

### Example of use

### Guidance on use

## Headquarters \(Barracks, Base, Physical Asset\) {#organization_headquarters}

This field is used to record data about units that have a uniquely named building or complex for their headquarters.

> Example: `3 Battalion` in Nigeria is cited as being based in the `Lubanga Barracks` in `Enugu, Enugu State, Nigeria`.

This field should not be used for anything that matches the name or alias of a organization. For example, `North Sector Police Station` should not be put in this field if the name of the organization is `North Sector Police Station`.

### Description

### Type of field

### Example of use

### Guidance on use

## Site: Exact Location \(Latitude or OSM Node Name\)

### Description

### Type of field

### Example of use

### Guidance on use

## Site: Exact Location \(Longitude or OSM Node ID\)

### Description

### Type of field

### Example of use

### Guidance on use

## City or other Node Name in OpenStreetMap {#organization_osm_name}

The OpenStreetMap data standard is used for all geographic entries. This way we don’t end up calling the same geographic area different names.

This field is for the city, village or other Node that a unit is based in. However this field should not be used if the only information about a unit’s base is in an administrative area \(which Highest level subnational boundary OpenStreetMap field should be used instead\).

> Tricky Example: "At the weekend when our reporter visited Ikot Akpan Udo, there was a heavy security presence at all the police divisions from Ikot-Abasi, Mkpat Enin, Eket, Esit Eket, Onna and Ibeno areas."

In this example - a report visits a specific place \(Ikot Akpan Udo\) and sees a “heavy security presence” which we can assume to mean a lot of police officers

The place \(Ikot Akpan Udo\) would be the Area of Operations \(see relevant section below\), however, the article also states that the “heavy security presence” was “at all the police divisions from Ikot-Abasi, Mkpat Enin, Eket, Esit Eket, Onna and Ibeno areas.” - This implies that there are multiple Organizations - in this case Police Divisions in the Nigeria Police Force - that are based in the cities or “areas” of “ Ikot-Abasi, Mkpat Enin, Eket, Esit Eket, Onna and Ibeno”.

Organizations can be based in multiple cities, in which case a new entry should be created for every city the unit is based in.

### Description

### Type of field

### Example of use

### Guidance on use

## City or other Node OpenStreetMap ID {#organization_osm_id}

This is tied to the matching OpenStreetMap entry.

### Description

### Type of field

### Example of use

### Guidance on use

## Highest level subnational boundary in OpenStreetMap \(name\) {#organization_admin_level_1_osm_name}

The Monitor always selects the highest level subnational boundary in OpenStreetMap - you can find a list here: [http://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative\#Super-national\_administrations](http://wiki.openstreetmap.org/wiki/Tag:boundary%3Dadministrative#Super-national_administrations)

For example Mexico has both municipios \(admin level 6 in OSM\) and states \(admin level 4\). The state \(admin level 4\) would be the appriopriate entry for an organization based in Mexico.

### Description

### Type of field

### Example of use

### Guidance on use

## Highest level subnational boundary in OpenStreetMap \(ID\) {#organization_admin_level_1_osm_id}

This would be the ID attached to the OSM entry from above.

### Description

### Type of field

### Example of use

### Guidance on use

## Site: division\_id {#organization_site_division_id}

The division\_id enables the system to identify which country this organization belongs to, thus all entries in this field would be ia two letter country code.

> For example organizations based in Nigeria would have the code `ng` and an organization based in Brazil would the code `br`.  
> You can search for country codes here: [https://www.iso.org/obp/ui/\#search](https://www.iso.org/obp/ui/#search)

### Description

### Type of field

### Example of use

### Guidance on use

## Site: Date of first citation {#organization_site_date_first_cited}

This field is for the earliest citation for the unit being located at City or other Node Name in OpenStreetMap if there is no City or other Node Name in OpenStreetMap then use the earliest citation for Highest level subnational boundary OpenStreetMap.  
If during the course of research a source ties an Organization ot a City or other Node then the first and last dates of citation should all be modified to match the date range for the City or other Node \(assuming it is in the same Highest level subnational boundary\).

### Description

### Type of field

### Example of use

### Guidance on use

## Is this the founding date? \(Y/N\) {#organization_site_date_first_cited_founding}

This field is a simple Y \(for yes\) or N \(for no\) that is tied to the Site \(either the City or other Node Name in OpenStreetMap or the Highest level subnational boundary OpenStreetMap depending\). Always default to City or other Node when you have that information.  
The main question for this field is - is the date the first time the organization was based in the city \(i.e. was it founded in this city on this date\)? Put another way - did this organization exist in this city before this date?  
If we don't know we record `N` in this field.  
If we can answer "yes this organization began being based in this city or highest level subnational boundary as of this date" we record `Y`.

### Description

### Type of field

### Example of use

### Guidance on use

## Site: Date of last citation {#organization_site_date_last_cited}

Follow the same rules as Site: Date of first citation.

### Description

### Type of field

### Example of use

### Guidance on use

## Is site open-ended? {#organization_site_date_last_cited_assume_to_current_date}

For marking `Y` \(Y=yes, assume site to current date, so the site will displayed on the map up to the current date\) an analyst would have to make a determination using a variety of factors including: the history of basing for the unit, the overall structure/nature of the security forces, the frequency of movement of similar units.

For historical basing or for instances where the longevity of a unit being based in a Site is unclear, use `N`.

### Description

### Type of field

### Example of use

### Guidance on use

## Area of Operations: OpenStreetMap Name {#organization_area_osm_name}

Organizations can have multiple areas that they are responsible for, are conducting operations in, or have jurisdiction over. The terms “area of responsibility”, “jurisdiction” and other variations have different levels of meaning depending on national or international law, and may not be used correctly by sources themselves. The Monitor uses the lowest common denominator of Area of Operations \(AOO\) - meaning this is an area in which the organization has operated in some manner.

AOOs are tied to the smallest formal geographic area possible. The areas generally follow the geographic sub-divisions of a country. This often means that the AOO is somewhat generalized because countries often do not have that many sub-divisions.

Organizations can have multiple AOOs at the same time - create a separate row for each AOO.

If the boundaries of their AOO is unclear the researcher should choose the highest level geographic area as the AOO.

> Example: a unit is described as operating “throughout California”. Here, use the entire State of California as the AOO and rate the entry with Low confidence. Or a unit operates “along the border” of two provinces - choose both provinces \(creating two separate records\) for each province.
>
> The researcher should put a note in the Notes field indicating that AOO was only given as “throughout California” or “along the border” of two provinces.

If a unit conducts an operation in a city - ie “police raided a home in Ciudad Juarez” the researcher should use the smallest subnational bounary that contains Ciudad Juarez.

This will require some research - an analyst will need to familiarize themselves with the geographic divisions of the country they are researching as they will be returning to these again and again.

Often we can infer the AOO of police units based on a crime being reported to them - as we assume the crime would be reported to the unit that has jurisdiction over where the crime occurred.

> Example: It is stated in an article that “The Rivers State Police Command yesterday confirmed the death of a clergyman, Pastor Geoffrey Ogagaghene at Ohalia-Elu town in Ogba/Egbema/Ndoni local government area of the State. The clergyman was reportedly killed by suspected herdsmen who were on a reprisal attack over the alleged stealing of their cattle. Media reports had it that more than six persons were killed. The Rivers State Police Command Public Relations Officer, Ahmad Muhammad said in a press statement in Port Harcourt yesterday that only one person was killed. He said assailants suspected to be herdsmen struck in Ohali-Elu and killed one Pastor, that the crisis was heightened because unspecified number of cows were allegedly stolen. He said, "The Command found it instructive to state that on Thursday 30/03/2016 about 5:30 am the police in Egi Division received a report that on Wednesday 29/03/2016, about 10:00 pm unidentified assailants suspected to be herdsmen struck in Ohali-Elu town leaving one pastor, Geoffrey Ogagaghene with severe cutlass cuts that later led to his death.”  
> In this case  the organization would be `Egi Division`, and it would have an `AOO` of `Ogba/Egbema/Ndoni` local government area with a first citation date of `29 March 2016`.

Note that `Source: Area of Operations` covers all citations for `Area of Operations` fields.

### Description

### Type of field

### Example of use

### Guidance on use

## Area of Operations: OpenStreetMap ID {#organization_area_osm_id}

The OpenStreetMap ID tied to the entry above.

### Description

### Type of field

### Example of use

### Guidance on use

## Area of Operations: division\_id {#organization_area_division_id}

The division\_id enables the system to identify which country the area of operations is located, thus all entries in this field would be a two letter country code.

> For example organizations based in Nigeria would have the code `ng` and an organization based in Brazil would the code `br`.  
> You can search for country codes here: [https://www.iso.org/obp/ui/\#search](https://www.iso.org/obp/ui/#search)

### Description

### Type of field

### Example of use

### Guidance on use

## Date of first citation for area of operations {#organization_area_date_first_cited}

For `Source: Date of first citation for area of operations` follow the rules for date of first citation of parent units and sites outlined above. Only put the earliest date here unless the only citation you have is for the end of an AOO in which case put it in the Date of last citation for area of operations.

### Description

### Type of field

### Example of use

### Guidance on use

## Start date of area of operations?

### Description

### Type of field

### Example of use

### Guidance on use

## Date of last citation for area of operations {#organization_area_date_last_cited}

### Description

### Type of field

### Example of use

### Guidance on use

## Assume Area of Operations to Current Date? \(Y/N\) {#organization_area_date_late_cited_assume_to_current}

If it reasonable, given what is known about the organization, the overall structure/nature of the security forces - that the organization likely maintains responsibility over this area in some way after the date of the last citation the analyst should mark this `Y`.

> Example: the `New York State police` would likely maintain an AOO over all of `New York State` even if the last citation you could find is from 2015.

### Description

### Type of field

### Example of use

### Guidance on use

## Organization membership {#organization_affiliation}

This field is for any memberships or attachments to internal/national joint operations, peacekeeping operations, or other multi-unit efforts.

Generally this means one of two things:

1\) Multiple units operate as part of an “operation” focused on a specific mission - eg `Operation Chihuahua` focused on narcotics cartels operating in Chihuahua state. Staffing and personnel were not affected, the operation generally existed in name only as a signifier for intensified efforts of police and military units already stationed in Chihuahua State. It is useful to capture which police and military units were part of this operation - as any abuses tied to “soldiers” or “police” during raids as part of the operation could be narrowed down quickly to a handful of potential units as responsible.

2\) Multiple units “lend” or otherwise deploy personnel who operate under the command of a Joint Task Force or Operation, usually which has a commander of its own.

> Example: soldiers from `1 Division` are deployed to the northeast of Nigeria to operate under `Operation BOYANA`. `1 Division` has a commander, but the soldiers as part of `Operation BOYANA` likely report to and take orders from the commander of `Operation BOYANA`. When the soldiers are done with their rotation, after several months, they return to their “home unit” `1 Division`. So while `Operation BOYANA` commands some soldiers who are part of `1 Division` it doesn’t technically command all of the soldiers of `1 Division` \(otherwise it would be the parent unit\) These operations - joint task forces, and so on - should have their own distinct `Organization` entries.

Taskforces, Operations, Peacekeeping missions and other entries here should be entered as their own organization. Enter their information as a separate `Organization` record. Peacekeeping missions are often referred to informally. Find the formal name on the relevant UN peacekeeping website. If there is a specific unit designation given to the peacekeeping force - for example `NIBATT 12` or `Nigerian Battalion 12` - we would use that as the International affiliation. We would enter `Nigerian Battalion 12` as its own organization and make its parent unit the peacekeeping mission \(which would also be entered as its own organization\).

### Description

### Type of field

### Example of use

### Guidance on use

## Organization membership: Date of first citation {#organization_affiliation_date_first_cited}

Follow the rules for parent units, sites, AOOs for the dates/citations.

### Description

### Type of field

### Example of use

### Guidance on use

## Is start date?

### Description

### Type of field

### Example of use

### Guidance on use

## Organization membership: Date of last citation {#organization_affiliation_date_last_cited}

Follow the rules for parent units, sites, AOOs for the dates/citations.

### Description

### Type of field

### Example of use

### Guidance on use

## End date of organization membership?

### Description

### Type of field

### Example of use

### Guidance on use

## Notes {#organization_affiliation_international}

Use this section for any interesting information about the organization that does not fit anywhere else - please always include the citation!

