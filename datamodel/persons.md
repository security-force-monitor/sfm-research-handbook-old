# Persons

Persons are natural persons who are affiliated with, or hold positions of command over a specific organization at a particular point in time.

## Summary of person fields

| Name of Field | Description | Example of Use |
| :--- | :--- | :--- |
| [ID](#person_id) | Unique identifier for the person | _a848de4e-ebeb-49d6-9099-7e68ca3b57fc_ |
| [Name](#person_name) | Name of person | _Sunday Jimmi Ayorinde Ilori_ |
| [Aliases or alternative spellings](#person_other_names) | Other names for a person | _Sunday Ilori_ |
| [Division ID](#person_division_id) | Two letter country code denoting a person's place of origin | _mx_ |
| [Organization](#person_organization) | The organization that the individual is affiliated with | _1 Battalion_ |
| [Role](#person_role) | The role the person serves in the organization | _Commander_ |
| [Title \(official title\)](#person_title) | The title \(if any\) of the person | _General Officer Commanding_ |
| [Rank](#person_rank) | The rank \(if any\) of the person | _Lieutenant Colonel_ |
| [First citation](#person_date_first_cited) | First source, by date, evidencing a relationship | _2007-09-31_ |
| [Start date?](#person_date_first_cited_is_start) | Is the first citation the date this person begun their affiliation with the organization? | _Y_ |
| [Last citation](#person_date_last_cited) | Last source, by date, evidencing a relationship | _2009-02-20_ |
| [End date?](#person_date_last_cited_is_end) | Is the last citation the date this person ceased to have an affiliation with the organization? | _N_ |
| [Notes](#person_notes) | Anything else relevant about this person that is not covered above | _Referred to as "new" as of 1 July 2012_ |

## ID {#person_id}

### Description

A unique number for each person in the dataset.

### Type of field

VARCHAR

### Example of use

`a848de4e-ebeb-49d6-9099-7e68ca3b57fc`

### Guidance on use

Use this field to put your name/initials and date on rows you enter data on. In the future this field will be used to create an unique identifier for each person in the Monitor’s database.

## Name {#person_name}

### Description

Full name of the person, including given, patronym and surnames.

### Type of field

VARCHAR

### Example of use

`Magaji Musa Majia'a` 

### Guidance on use

Different sources will spell a person's name in different ways, so we choose a name to be a canonical entry for that person. Whenever possible, this field will contain the most complicated or complete version of a person's name, even if it has the smallest number of citations. For example `Magaji Musa Majia'a` will be used instead of `Magaji Musa Majiaa`. Other names will be placed in the `Aliases or alternative spellings` field.

## Aliases or alternative spellings {#person_other_names}

### Description

Other names used to identify a person. 

### Type of field

VARCHAR, free entry

### Example of use

`Virgilio Daniel Méndez Bazan ; Virgilio Daniel Mendez Bazán`

## Guidance on use

Different sources will spell a person's name in different ways. We choose and record a canonical version of a person's name in the `Name` field. All other spellings that we have found are treated as aliases and stored in this field. This field may contain multiple values, which will be separated by a semi-colon.

## Division ID

### Description

Country where a unit that a person is a member of is located.

### Type of field

CHAR(2), controlled vocabulary

### Example of use

`mx`

### Guidance on use

Values for this field are chosen from the list of ISO 3166-1 alpha-2 codes ([on ISO](https://www.iso.org/obp/ui/#search/code/), and on [Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements). This field doe not denote the citizenship or country of origin of a person. Rather, it denotes where a unit they are a member of is located. For example, if `1 Batallón de Infantería` is located in Juarez, Mexico, the *unit* will be assigned a `Division ID` of `mx`. Any person who is a member of that organization will be assigned a `Division ID` of `mx` as well.  A person may have multiple `Division ID` entries in the event that they or a unit they are a member of is deployed to another country.

## Organization {#person_organization}

### Description

The organization that the person is a member of.

### Type of field

VARCHAR, free entry

### Example of use

`35 Batallón de Infantería`

### Guidance on use

Values in this field correspond with names of organizations that already exist in the dataset. A person can have multiple memberships of the same organization if there is a change to their `rank`, `title` or `role` with respect to the organization. An example of this is where a person is promoted. Another case where a person can have multiple membership of the same organization is where research indicates there are clear start or end dates to a membership. An example of where this might occur is if a person does multiples "tours" in a particular organization.

## Role {#person_role}

### Description

The role a person plays in the organization that is usually not evident from their `title` or `rank`.

### Type of field

CHAR(), controlled vocabulary 

### Example of use

`Commander`

### Guidance on use

The main role we record is `Commander`.

There are a variety of other roles a person can have including `Second in Command`, `Chief of Staff` along with other less common entries. They will vary between countries.

As a special note, heads of academic or other security force institutions will sometimes be referred to as the `Commandant`. In these cases, `Commandant` should be recorded in the `Title` field, and their role should be recorded as `Commander`.

If someone is referred to as “the head”, “chief” or some other variation indicating that they are in charge of a unit, they should be regarded as the `Commander`.

## Title \(official title\) {#person_title}

### Description

Titles that persons have that are separate from their rank or role.

### Type of field

VARCHAR, free entry

### Example of use

`General Officer Commanding`, `Jefe Del Estado Mayor`

### Guidance on use

The range of titles will vary from country to country. For example, commanders of army divisions in Nigeria, who usually hold the `rank` of `Major General` also hold the `title` of `General Officer Commanding`.

## Rank {#person_rank}

### Description

The official position of a person in the hierarchy of a security force

### Type of field

VARCHAR, free entry

### Example of use

`General de División`, `Teniente Coronel`, `Air Vice Marshal`

### Guidance on use

We remove any dashes that are contained in `rank` values. For example, we would enter `Brigadier General` rather than `Brigadier-General`.

## First citation {#person_date_first_cited}

### Description

The date of publication of the earliest source known to the Monitor that evidences the membership of a person in an organization.

### Type of field

Date (YYYY-MM-DD)

### Example of use

`1999-01-01`

### Guidance on use

This field is for the earliest source the Monitor has showing an affiliation between this person and the organization. The `title`, `role` and `rank` held by a person are assumed to continue until a source indicates a change. If the person's role, title or rank changes a new entry will need to be created to document that change and a new `first citation` or `fast citation` created to mark the change.

> If a source indicates that Major General Jack Johnson is the commander of 1 Division as of 2007-08-20 all of the revelevant fields would be entered based on that source. If another source states that Jack Johnson retired from the 1 Division on 2008-01-10 the last citation for Jack Johnson's affiliation would be 2008-01-10. However, this would also assume that Jack Johnson continued to have the Role of Commander and the Rank of Major General from 2007-08-20 until 2008-01-10.

## Start date? \(Y/N\) {#person_date_first_cited_is_start}

### Description

Indicates that the date recorded in `first citation` is the actual start date of a person's membership in an organization.

### Type of field

Boolean, Y/N

### Example of use

`Y`, `N`

### Guidance on use

Some sources specify an exact start for a person's membership in an organization. This should be used instead of the publication date of the earlier source evidencing a person's membership in an organization. For example, a person's _curriculum vitae_ may contain the exact date that a person joined a security force, and specify the unit. A `Y` value in this field indicates a hard start for a person's `role`, `title` and `rank` as well. A value of `N` is applied in all other cases.

## Last citation {#person_date_last_cited}

### Description

The date of publication of the most recent source known to the Monitor that evidences the membership of a person in an organization.

### Type of field

Date (YYYY-MM-DD)

### Example of use

`2014-08-22`

### Guidance on use

This field is for the latest source the Monitor has showing a membership of a person and an organization. If the person's `role`, `title` or `rank` changes a new entry will need to created to document that change and a new `first citation` or `last citation` created to mark the change.

## End date? \(Y/N\) {#person_date_last_cited_is_end}

### Description

Indicates that the date recorded in `last citation` is the actual end date of a person's membership in an organization.

### Type of field

Boolean, Y/N

### Example of use

`N`

### Guidance on use

If the date of last citation is end of this person's affiliation with the organization or the end date of their Role, Title or Rank, a `Y` value will be present. In all other cases, this value will be `N`.

## Notes {#person_notes}

### Description

Further information about this person that is relevant and interesting to the Monitor, but is not appropriate for other fields.

### Type of field

VARCHAR

### Example of use

`Created by bulk processing of SEDENA website snapshots made by Internet Archive.`

### Guidance on use

This field may be used to record observations made by the Monitor Staff Analyst relating to the sources, content or context of the record.
