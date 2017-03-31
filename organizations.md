# Organizations

## ID {#organization_id}

The CMS will automatically create a unique ID for every Person, Organization and Event.

## Name {#organization_name}

Whenever possible the Monitor uses the most complex version of the organization’s name that also matches the general structure of the security forces of a country.

> Example: `3 Armoured Division of the Nigerian Army` would be the entry, rather than the more informal `3 Division` \(which may have more citations\).

The Monitor attempts to standardize names based on the overall structure of and reporting about the security forces:

> Example:`Police Divisions` are a class of police units in Nigeria of which there are over 1000 units nationwide.

However, each individual `Police Division` may not have a citation for their formal name such as Lagos Police Division, but only have a citation \(or numerous citations\) for the less formal `Lagos Division`.

The Monitor would list the name of the unit as `Lagos Police Division` with a note about the methodology behind that choice.

The less formal `Lagos Division` name would be entered in the Alias field \(more on that below\):

> Example: Army units of a country may follow a naming convention of a number and then name of unit: e.g. `3 Battalion` or `25 Brigade`. There may be a unit of which we only have citations for a variation on that: e.g. `Fourth Battalion`.

The Monitor would list the name of the unit as `4 Battalion` with a note about the methodology behind that choice.  
The Fourth Battalion name variant would be entered in the Alias field \(more on that below\)

The Monitor does not use ordinal indicators like `1st` or `3rd` in the name of an Organization.

Enter the name with the ordinal indicator in the Aliases of alternative spellings field \(more on that below\)  
Use the name in the local language \(official\) of the country where appropriate.

> Example: A unit in the Mexican Army would be called by its name in Spanish \(`10 Regimiento de Caballería Motorizado`\), rather than the English translation \( `10 Motorized Cavalry Regiment`\). See the section on Aliases of alternative spellings for more information on what to do with English language translations of names.

## Aliases or alternative spellings \(semicolon separated\) {#organization_other_names}

Use this field for all other names for the organization  
If the country being researched is non-English speaking, use this field for English language translations as well.

> Example: We’d put the English translation of `10 Regimiento de Caballería Motorizado`, `10 Motorized Cavalry Regiment`, here. In addition we’d put the Spanish name of the unit with an Ordinal indicator \(`10/o. Regimiento de Caballería Motorizado`\) in this field as well.

## Organization division\_id {#organization_division_id}

The `division_id` enables the system to identify which country this organization belongs to. All entries in this field are two letter country codes.

> For example, organizations based in Nigeria would have the code `ng` and an organization based in Brazil would the code `br`.

You can search for country codes here: [https://www.iso.org/obp/ui/\#search](https://www.iso.org/obp/ui/#search)

## Classification {#organization_classification}

We will build the classification list for each country covered by the Monitor cover. We will have in-person discussions to decide on a schema but here are some general guidelines and explanation for this field.

Classifications give context to Organizations and will be the filters for Maps and Charts on the Security Force Monitor web products.

Classification are created with several criteria in mind:

1\) Classifications would allow analysts to create meaningful links between human rights reporting and the Monitor’s data on security forces:

> Example - The Monitor classifies Army units as `Army` and police units as `Police`. This allows a user to click on a police unit and see all of the nearby human rights reporting on abuses committed by police, but does not connect any abuses committed by soldiers from the army to the police unit \(because the police unit is only tagged as Police\).  
> Example - In Mexico \(which has federal level, state level and municipal level police forces, all independent of one another\) a municipal police force in Mexico is given two classifications: `Municipal Police ; Police`. A state police unit is given two classifications: `State Police ; Police`. So when human rights reporting is specific in saying municipal police officers committed an abuse nearby where this unit is located, it is tagged. When there is more vague reporting of just “police” committing abuses both units that have a Police classification and are located near where the abuse occurred are tagged.

2\) They would be meaningful to experts on a country’s security forces

3\) They would be meaningful to non-experts

4\) They are as comprehensive as possible, while being as few in number as possible

By necessity classifications vary slightly country to country - again the Monitor always tries to create as few classifications as possible.

> Example - Human rights reporting regularly refers to units and members of the `Nigeria Police Force` as “police”. Even though there are over a thousand different units in the police force, and at different levels of command authority, classifying all of them as `Police` would make sense in order to tag reports of abuses and the units themselves.
>
> Example - The `Central Security Forces \(CSF\)` in Egypt are generally deployed during riots and other civil disturbances. They are commonly referred to as the "riot police". However, “regular” police are also deployed when riots occur. Using a generic classification of `riot police` for `CSF` units could be confusing to experts, but creating a specific classification for `CSF` units could be confusing for non-experts. The Monitor splits the difference by classifying `CSF` units as `Central Security Forces \(riot police\)`.

## Parent Organization: The superior affiliated organization {#organization_organization_name}

The parent must be also entered into the sheet as its own organization.

Think of an organizational chart - the parent is “above” or distinct and separate from the organization in some way. As a rule of thumb, generally parent organizations control the units that operate in the parent’s Area of Operations \(but not always\).

Often when there is an operation or joint task force, it may not have have personnel of its own. Rather, it gets personnel assigned to it. Generally, these types of arrangements don’t put the operation “above” the unit in the organizational chart, but “on the same level” as it. These types of relationships are handled in another field Other Affiliation \(like joint task force\).

## Administrative, Command, or Informal parent relationship {#organization_organization_classification}

Organizations have a Command relationship when the parent organization can order the organization to perform some action, and/or remove or appoint the commander of the organization.

Informal relationships occur where no legal or formal relationship exists, but there is a relationship where parent organization could exert some form of influence on the organization.

> Example: Lagos state in Nigeria has a security council which is a meeting of the governor, and the top commanders of police and military units in the state. The security council should be considered its own organization. The governor has no legal authority to command the military or police forces, but the security council membership establishes a relationship between the organizations and meetings often result in new approaches to security being taken, such as different deployments of police. An analyst could make the determination that an informal relationship exists between the security council and the police and military organizations.

Administrative relationships exist where a formal, non-command relationship exists between organizations, or where an administrative description is more accurate of the relationship between two organizations.

> Example - the `Minister of Defence` in Nigeria is by law in charge providing administrative support to the `Nigerian Army`, establishing an administrative relationship.  
> Example - the `Standards Department` of an Army Headquarters might be under the control of the Army Headquarters, meaning the Army Headquarters could appoint or fire the head of the Department. So technically the Department is under the “command” of the Ministry, but describing this as Administrative is more helpful, the Department is not in the field conducting operations, it's an administrative organ of the Army Headquarters.

Organizations can have multiple parent relationships at the same time.

## Date of first citation for parent organization {#organization_organization_date_first_cited}

Note that in `Source: Date of first citation for parent organization \(MM/DD/YYYY\)` only put the citation for the earliest date. If there is only one citation, and it establishes the end date for a relationship, leave this field blank and enter that date and citation in the Date of last citation for parent organization and Source: Date of last citation for parent organization fields.

## Date of last citation for parent organization \(MM/DD/YYYY\) {#organization_organization_date_last_cited}

If there is only one citation for a relationship, and the citation is not for the end of that relationship, leave this field blank and only put the date in the Date of first citation for parent organization.

Note that for `Source: Date of last citation for parent organization` only put the citation for the latest date. If there is only one citation put it in the Source: Date of first citation for parent organization field, if appropriate, and leave this field blank.

## Assume Parent Organization and Relationship to Current Date? \(Y/N\) {#organization_organization_assume_to_current_date}

In many cases a relationship could be assumed past the last citation date. For example, where a battalion has been reporting to a brigade for years, one could safely assume that this relationship will continue.

This field exists because if the Monitor only displays data up to the last citation any Map and Chart showing the data would quickly be blank. Not every unit is reported on every day so it's impossible to keep things truly “up-to-date”.

There are always assumptions made in the sort of analysis done by the Monitor. For example, a parent relationship established between two units in the military sourced from a press briefing released at 09:00 AM might be changed by a second press briefing at 09:01 AM the same day. Having this field forces us to be more thoughtful about what we assume and why.

There are cases where there appears to be a temporary relationship, a historical relationship simply not enough data to base an assumption on. In these cases, the analyst would record an `N` in this field in order to state that there is no assumption this relation continue following the date of last citation.

## Headquarters \(Barracks, Base, Physical Asset\) {#organization_headquarters}

This field is used to record data about units that have a uniquely named building or complex for their headquarters.

> Example: `3 Battalion` in Nigeria is cited as being based in the `Lubanga Barracks` in `Enugu, Enugu State, Nigeria`.

This field should not be used for anything that matches the name or alias of a organization. For example, `North Sector Police Station` should not be put in this field if the name of the organization is `North Sector Police Station`.

## City or smallest administrative unit GeoName {#organization_geonames_name}

The Geoname data standard is used for all geographic entries. This way we don’t end up calling the same geographic area different names.

This field is for the city or smallest administrative unit that a unit is based in. For example a unit could be based in the city of New York or the county of King’s County.

However this field should not be used if the only information about a unit’s base is the state of New York \(which the ADMIN1 \(state, province, governorate, or other largest administrative unit\) Geoname field should be used\).

> Tricky Example: "At the weekend when our reporter visited Ikot Akpan Udo, there was a heavy security presence at all the police divisions from Ikot-Abasi, Mkpat Enin, Eket, Esit Eket, Onna and Ibeno areas."

In this example - a report visits a specific place \(Ikot Akpan Udo\) and sees a “heavy security presence” which we can assume to mean a lot of police officers

The place \(Ikot Akpan Udo\) would be the Area of Operations \(see relevant section below\), however, the article also states that the “heavy security presence” was “at all the police divisions from Ikot-Abasi, Mkpat Enin, Eket, Esit Eket, Onna and Ibeno areas.” - This implies that there are multiple Organizations - in this case Police Divisions in the Nigeria Police Force - that are based in the cities or “areas” of “ Ikot-Abasi, Mkpat Enin, Eket, Esit Eket, Onna and Ibeno”.

Organizations can be based in multiple cities, in which case a new row should be created for every city the unit is based in.

Geoname data will be shared with you and we will do a separate training on it. You can find more information about Geonames here: [http://www.geonames.org/](http://www.geonames.org/)

## City or smallest administrative unit GeonameID {#organization_geonames_id}

This is tied to the matching Geoname.

## ADMIN1 \(state, province, governorate, or other largest administrative unit\) Geoname {#organization_admin_level_1_geonames_name}

As a unit can be based in multiple cities, that means it can be based in cities in different ADMIN1 as well. Make sure the ADMIN1 matches the city on the row it is on.

## ADMIN1 \(state, province, governorate, or other largest administrative unit\) GeonameID {#organization_admin_level_1_geonames_id}

## Site: division\_id {#organization_site_division_id}

The division\_id enables the system to identify which country this organization belongs to, thus all entries in this field would be ia two letter country code.

> For example organizations based in Nigeria would have the code `ng` and an organization based in Brazil would the code `br`.  
> You can search for country codes here: [https://www.iso.org/obp/ui/\#search](https://www.iso.org/obp/ui/#search)

## Site: Date of first citation \(MM/DD/YYYY\) {#organization_site_date_first_cited}

This field is for the earliest citation for the unit being located at City or smallest administrative unit GeoName if there is no City or smallest administrative unit then use the earliest citation for ADMIN1.  
Always default to City or smallest administrative unit when you have that information.

## Is this the founding date? \(Y/N\) {#organization_site_date_first_cited_founding}

This field is a simple Y \(for yes\) or N \(for no\) that is tied to the City or ADMIN1 of an organization.  
This field is for the earliest citation for the unit being located at City or smallest administrative unit GeoName if there is no City or smallest administrative unit then use the earliest citation for ADMIN1.  
Always default to City or smallest administrative unit when you have that information.  
The main question for this field is - is the date the first time the organization was based in the city \(i.e. was it founded in this city on this date\)? Put another way - did this organization exist in this city before this date?  
If we don't know we record `N` in this field.  
If we can answer "yes this organization began being based in this city or ADMIN1 as of this date" we record `Y`.

## Site: Date of last citation \(MM/DD/YYYY\) {#organization_site_date_last_cited}

Follow the same rules as Site: Date of first citation.

## Assume Site \(City or smallest administrative unit GeoName and/or AMIN1\) to Current Date? \(Y/N\) {#organization_site_date_last_cited_assume_to_current_date}

For marking `Y` \(Y=yes, assume site to current date, so the site will displayed on the map up to the current date\) an analyst would have to make a determination using a variety of factors including: the history of basing for the unit, the overall structure/nature of the security forces, the frequency of movement of similar units.

For historical basing or for instances where the longevity of a unit being based in a Site is unclear, use `N`.

## Area of Operations: Geoname Name {#organization_area_geonames_name}

Organizations can have multiple areas that they are responsible for, are conducting operations in, or have jurisdiction over. The terms “area of responsibility”, “jurisdiction” and other variations have different levels of meaning depending on national or international law, and may not be used correctly by sources themselves. The Monitor uses the lowest common denominator of Area of Operations \(AOO\) - meaning this is an area in which the organization has operated in some manner - for all organizations.

AOOs are tied to the smallest formal geographic area possible. The areas generally follow the geographic sub-divisions of a country. This often means that the AOO is somewhat generalized because countries often do not have that many sub-divisions.

Organizations can have multiple AOOs at the same time - create a separate row for each AOO.

If the boundaries of their AOO is unclear the researcher should choose the highest level geographic area as the AOO.

> Example: a unit is described as operating “throughout California”. Here, use the entire State of California as the AOO and rate the entry with Low confidence. Or a unit operates “along the border” of two provinces - choose both provinces \(creating two separate records\) for each province.

The should put a note in the Notes field indicating that AOO was only given as “throughout California” or “along the border” of two provinces.  
If a unit conducts an operation in a city - ie “police raided a home in Ciudad Juarez” - use the ADMIN2 \(county, municipio, local government area, etc\) that Ciudad Juarez is located in.

This will require some research - an analyst will need to familiarize themselves with the geographic divisions of the country they are researching as they will be returning to these again and again.

Often we can infer the AOO of police units based on a crime being reported to them - as we assume the crime would be reported to the unit that has jurisdiction over where the crime occurred.

> Example: It is stated in an article that “The Rivers State Police Command yesterday confirmed the death of a clergyman, Pastor Geoffrey Ogagaghene at Ohalia-Elu town in Ogba/Egbema/Ndoni local government area of the State. The clergyman was reportedly killed by suspected herdsmen who were on a reprisal attack over the alleged stealing of their cattle. Media reports had it that more than six persons were killed. The Rivers State Police Command Public Relations Officer, Ahmad Muhammad said in a press statement in Port Harcourt yesterday that only one person was killed. He said assailants suspected to be herdsmen struck in Ohali-Elu and killed one Pastor, that the crisis was heightened because unspecified number of cows were allegedly stolen. He said, "The Command found it instructive to state that on Thursday 30/03/2016 about 5:30 am the police in Egi Division received a report that on Wednesday 29/03/2016, about 10:00 pm unidentified assailants suspected to be herdsmen struck in Ohali-Elu town leaving one pastor, Geoffrey Ogagaghene with severe cutlass cuts that later led to his death.”  
> In this case  the organization would be `Egi Division`, and it would have an `AOO` of `Ogba/Egbema/Ndoni` local government area with a first citation date of `29 March 2016`.

Note that `Source: Area of Operations` covers all citations for `Area of Operations` fields.

## Area of Operations: GeonameID {#organization_area_geonames_id}

## Area of Operations: division\_id {#organization_area_division_id}

## Date of first citation for area of operations \(MM/DD/YYYY\) {#organization_area_date_first_cited}

For `Source: Date of first citation for area of operations` follow the rules for date of first citation of parent units and sites outlined above. Only put the earliest date here unless the only citation you have is for the end of an AOO in which case put it in the Date of last citation for area of operations.

## Date of last citation for area of operations \(MM/DD/YYYY\) {#organization_area_date_last_cited}

## Assume Area of Operations to Current Date? \(Y/N\) {#organization_area_date_late_cited_assume_to_current}

If it reasonable, given what is known about the organization, the overall structure/nature of the security forces - that the organization likely maintains responsibility over this area in some way after the date of the last citation the analyst should mark this `Y`.

> Example: the `New York State police` would likely maintain an AOO over all of `New York State` even if the last citation you could find is from 2015.

## Other affiliation \(like joint task force\) {#organization_affiliation}

This field is for any memberships or attachments to internal/national joint operations, operations, or other multi-unit efforts.

Generally this means one of two things:

1\) Multiple units operate as part of an “operation” focused on a specific mission - eg `Operation Chihuahua` focused on narcotics cartels operating in Chihuahua state. Staffing and personnel were not affected, the operation generally existed in name only as a signifier for intensified efforts of police and military units already stationed in Chihuahua State. It is useful to capture which police and military units were part of this operation - as any abuses tied to “soldiers” or “police” during raids as part of the operation could be narrowed down quickly to a handful of potential units as responsible.

2\) Multiple units “lend” or otherwise deploy personnel who operate under the command of a Joint Task Force or Operation, usually which has a commander of its own.

> Example: soldiers from `1 Division` are deployed to the northeast of Nigeria to operate under `Operation BOYANA`. `1 Division` has a commander, but the soldiers as part of `Operation BOYANA` likely report to and take orders from the commander of `Operation BOYANA`. When the soldiers are done with their rotation, after several months, they return to their “home unit” `1 Division`. So while `Operation BOYANA` commands some soldiers who are part of `1 Division` it doesn’t technically command all of the soldiers of `1 Division` \(otherwise it would be the parent unit\) These operations - joint task forces, and so on - should have their own distinct `Organization` entries.

## Date of first citation for affiliation \(MM/DD/YYYY\) {#organization_affiliation_date_first_cited}

Follow the rules for parent units, sites, AOOs for the dates/citations.

## Date of last citation for affiliation \(MM/DD/YYYY\) {#organization_affiliation_date_last_cited}

## International affiliation \(like UN peacekeeping\) {#organization_affiliation_international}

This field should only be used for international peacekeeping affiliations. In the future it could also be used to record participation in international military exercises.

Peacekeeping missions should be entered as their own organization. Enter their information as a separate `Organization` record.

Peacekeeping missions are often referred to informally. Find the formal name on the relevant UN peacekeeping website.

If there is a specific unit designation given to the peacekeeping force - for example `NIBATT 12` or `Nigerian Battalion 12` - we would use that as the International affiliation.  
We would enter `Nigerian Battalion 12` as its own organization and make its parent unit the peacekeeping mission \(which would also be entered as its own organization\).

## Date of first citation for international affiliation \(MM/DD/YYYY\) {#organization_affiliation_international_date_first_cited}

Follow the rules for parent units, Sites, AOOs and so on that have been laid out above.

## Date of last citation for international affiliation \(MM/DD/YYYY\) {#organization_affiliation_international_date_last_cited}

## Notes {#organization_notes}

Use this section for any interesting information about the organization that does not fit anywhere else - please always include the citation!

