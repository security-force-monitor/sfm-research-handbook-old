# Persons

Persons are natural persons who are affiliated with, or hold positions of command over a specific organization at a particular point in time.

## Summary of person fields

| Name of Field | Description | Example of Use |
| :--- | :--- | :--- |
| to do | to do | to do|

## Person: ID {#person_id}

### Description

A unique number for each person in the dataset.

### Type of field

Text and numbers 

### Example of use

`a848de4e-ebeb-49d6-9099-7e68ca3b57fc`

### Guidance on use

This field contains an automatically-generated unique identifier for each person in the Monitor’s database.

## Person: Name {#person_name}

### Description

Full name of the person, including given, patronym and surnames.

### Type of field

Text and numbers

### Example of use

`Magaji Musa Majia'a` 

### Guidance on use

Different sources will spell the name of a person in different ways, so we choose a name to be a canonical entry for that person. Whenever possible, the canonical entry will contain the most complicated or complete version of a person's name, even if it has the smallest number of citations. For example `Magaji Musa Majia'a` will be used instead of `Magaji Musa Majiaa`. Other names will be placed in the `Aliases or alternative spellings` field.

## Person: Aliases {#person_aliases}

### Description

Other names used to identify a person. 

### Type of field

Text and numbers, free entry

### Example of use

`Virgilio Daniel Méndez Bazan`, `Virgilio Daniel Mendez Bazán`

## Guidance on use

Different sources will spell a person's name in different ways. We choose and record a canonical version of a person's name in the `Person: Name` field. All other spellings that we have found are treated as aliases and stored in this field. This field may contain multiple values, which will be separated by a semi-colon.

## Person: Country {#person_country} 

### Description

Country where an organization that a person is a member of is located.

### Type of field

Text, controlled vocabulary

### Example of use

`mx`

### Guidance on use

Values for this field are chosen from the list of ISO 3166-1 alpha-2 codes, which can be found ([on the ISO website](https://www.iso.org/obp/ui/#search/code/) and on [Wikipedia](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements). This field doe not denote the citizenship or country of origin of a person. Rather, it denotes where a unit they are a member of is located. For example, if `1 Batallón de Infantería` is located in Juarez, Mexico, the organization will be assigned a value of `mx` in the field `Organization: Country`. Any person who is a member of that organization will be assigned a value of `mx` in the field `Person: Country` as well.  A person may have multiple  entries for `Person: Country` where our research shows they or an organization they are a member of is deployed to different countries.

## Person: Organization Name {#person_organization_name}

### Description

The organization that the person is a member of.

### Type of field

Text and numbers, free entry

### Example of use

`35 Batallón de Infantería`

### Guidance on use

Values in this field correspond with names of organizations that already exist in the dataset (recording in the field `Organization: Name`. A person can have multiple memberships of the same organization if there is a change to their entries for `Person: Rank`, `Person: Title` or `Person: Role` with respect to the organization. An example of this is where a person is promoted. Another case where a person can have multiple membership of the same organization is where research indicates there are clear start or end dates to a membership. An example of where this might occur is if a person does multiples "tours" in a particular organization.

## Person: Role {#person_organization_role}

### Description

The role a person plays in the organization that is usually not evident from their `Person: Title` or `Person: Rank`.

### Type of field

Text and numbers, controlled vocabulary 

### Example of use

`Commander`

### Guidance on use

The most common value we record in `Person: Role` is `Commander`.

There are a variety of other roles a person can have including `Second in Command`, `Chief of Staff` along with other less common entries. They will vary between countries.

As a special note, heads of academic or other security force institutions will sometimes be referred to as the `Commandant`. In these cases, `Commandant` should be recorded in the `Title` field, and their role should be recorded as `Commander`.

If a person is referred to as “the head”, “chief” or some other variation indicating that they are in charge of a unit, they should be regarded as the `Commander`.

## Person: Title {#person_organization_title}

### Description

Titles that persons have that are separate from their rank or role.

### Type of field

Text and numbers, free entry

### Example of use

`General Officer Commanding`, `Jefe Del Estado Mayor`

### Guidance on use

The range of titles will vary from country to country. For example, commanders of army divisions in Nigeria, who usually hold the rank of `Major General` also hold the title of `General Officer Commanding`.

## Person: Rank {#person_organization_rank}

### Description

The official position of a person in the hierarchy of a security force.

### Type of field

Text and numbers, free entry

### Example of use

`General de División`, `Teniente Coronel`, `Air Vice Marshal`

### Guidance on use

We remove any dashes that are contained in `Person: Rank` values. For example, we would enter `Brigadier General` rather than `Brigadier-General`.

## Person Membership: Date first cited {#person_organization_date_first_cited}

### Description

The earliest date that a source shows that a membership relationship between a person and an organization  exists, either through direct reference in the source or by the date of its publication.

### Type of field

Date (YYYY-MM-DD), fuzzy

### Example of use

`2012`,`2012-11`, `2012-11-23`

### Guidance on use

Along with the fields `Person membership: Start date?`, `Person Membership: Date last cited` and `Person Membership: Open-ended?` the field `Person Memberships: Date first cited` provides data about the time period over which we can evidence a person's relationships to an organization 

The `Person Membership: Date first cited` field contains a date that is either:

* The earliest date found in a source that specifically references the relationship between a person and an organization; or,
* The earliest date of publication of sources that makes reference to the relationship between a person and an organization.

> For example, if three sources published on 1 January 2012, 1 February 2012 and 1 March 2012 all refer to this person as a commander, we will use 1 January 2012 as the value in `Person Membership: Date first cited`. If the source published on 1 March 2012 refers to this person as a commander on the date of 30 June 2011, we will use 30 June 2011 as the value in `Person Membership: Date first cited`.

The values for `Person: Title`, `Person: Role` and `Person: Rank` held by a person are assumed to continue until a source indicates a change in any of those values. If the person's role, title or rank changes a new entry will need to be created to document that change. This new entry will have updated values for `Person Membership: Date first cited` and related date fields.

> For example, if a source indicates that Major General Jack Johnson is the commander of 1 Division as of 2007-08-20 all of the revelevant fields would be entered based on that source. If another source states that Jack Johnson retired from the 1 Division on 2008-01-10 the last citation for Jack Johnson's affiliation would be 2008-01-10. However, this would also assume that Jack Johnson continued to have the Role of Commander and the Rank of Major General from 2007-08-20 until 2008-01-10.

In keeping with all date fields we include in this dataset, where our research can only find a year or a year and a month, this can be included in `Person Membership: Date first cited`.

This field is clarified by the field `Person Membership: Start date?` which indicates whether the date included here is the actual date on which the relationship between a person and an organization started.


## Person Membership: Start date? \(Y/N\) {#person_date_first_cited_is_start}

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

Text and numbers

### Example of use

`Created by bulk processing of SEDENA website snapshots made by Internet Archive.`

### Guidance on use

This field may be used to record observations made by the Monitor Staff Analyst relating to the sources, content or context of the record.
