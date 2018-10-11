# Research methodology

Security Force Monitor follows a four phase process when researching the security forces of a country.

## Phase 1: Scope out sources {#method-phase-1}

### General sources {#method-phase-1-general}

Security Force Monitor collects data about the persons and organizations that comprise security forces, along with allegations of human rights abuses made against security forces. This data is carefully collected from a variety of sources, generally online. These include:

* Laws of the country;
* Official government media;
* Press releases from the relevant ministries of the country \(Information, Defense, Interior, and others\);
* Security force newsletters;
* Social media pages for security services or government agencies;
* Statistics and data agencies;
* Local government websites;
* Human rights commissions;
* Third country government publications and other documents;
* United Nations publications and other documents;
* Local news reportage;
* Civil society and human rights reporting;
* Academic research; and,
* Other country specific sources.

The Monitor also identifies non-digital resources such as monographs, scholarly literature, biographies and other materials about security services. The existence and availability of these type of sources vary widely from country to country.

### State administrative structures and geography {#method-phase-2-admin}

Security Force Monitor researchers familiarize themselves with the country’s governance and administrative structures, gaining understanding about the levels of government \(for example: local, regional, state, national\) and their connection to different security forces. In examining this we also flag where there might be major changes in the structure of government, such as those that may accompany a constitutional referendum or a peace process. These affect how the Monitor will represent data on security forces over time.

Examining the administrative geography of a country provides important context for the structure and operations of the security forces. This part of the scoping process also gives us insight into how much of a country’s administrative geography is represented in online gazetteers \(like [OpenStreetMap](https://nominatim.openstreetmap.org/) or [GeoNames](https://www.geonames.org)\) that the Monitor uses in its analysis.

### Potential high value datasets {#method-phase-1-datasets}

During this first phase, researchers also identify sources that could be turned into large, high value datasets for the Monitor. These are sources that contain a sufficiently large amount or complex type of data that technical help is necessary to extract it in a timely way; doing the work “by hand” is possible, but would be slow and error prone. These high value data extraction tasks use techniques such as web-scraping, scripted parsing and geospatial analysis. An example of these types of sources are the [Internet Archive snapshots the official webpage of the Mexican Army and Air Force](https://web.archive.org/web/20050908175401/http://www.sedena.gob.mx/ejercito/comandancias/index.html) \(and child pages\) going back more than a decade which outline the top level structures of the Mexican army and its commanding officers.

## Phase 2: Write a Country Guide {#method-phase-2}

The sources gathered during our scoping phase are used to write a Country Guide to assist with further research.  
The Guide begins as a general overview of the structures of security services of a country. It gives researchers a general framework to help organize and prioritize research, by giving an estimate of the scale of the work: number of installations, organizations, persons that need to be researchers in detail.

> For example, the Monitor's scoping research on Nigeria revealed that by law every state and the federal territory has a Police Command. By extension this means since 1996 \(when the last states of Nigeria were created\) there have been 37 Police Commands. Statistics from the Nigeria Police Force show that between 2007 and 2012 most Police Commands were in charge of 2 to 3 Police Area Commands \(though some heavily populated states have more, with Lagos having the most at 8\). These statistics also show that on average each state and the federal capital territory had 30 Police Divisions, which by law are generally under the command of a Police Area Command. Thus, from a few initial sources a Monitor researcher can have a general sense of the structure of the police and a useful metric to compare the Monitor’s dataset against.

Further, a list of keywords and sources is created for researchers as well - these serve as leads for researchers to follow.

This Country Guide is updated as new details on the security forces are discovered through the course of the Monitor's work.

## Phase 3: Conduct detailed research {#method-phase-3}

Researchers use the initial keywords and sources to begin a “deep dive” into the security forces.

Anything relating to the types of information the Monitor collects is entered into the Monitor’s database. The [Data Model section](/en/datamodel/README.md) of this Research Handbook gives detailed guidance to Monitor researchers about the types of data to take from sources and how it should be entered.

Additionally, data from this research is used to update the Country Guide to provide greater granular detail on the security forces of a country or to update sections as needed. New sources and keywords discovered during research are added to the existing guide as well.

As the Monitor builds its database on the security forces of a country, new information is cross-referenced to further evidence data, discover gaps, or identify mistakes. There are three key questions Monitor researchers ask themselves whenever they review information in a source:

* "Does this make sense given what is detailed about the security forces from other sources?"
* "Is it possible this source is correct and our other sources are incorrect?"
* "Do I have enough information to accept or reject what this source says?"

The Country Guide acts as a framework for researchers to understand the security forces and to help a researcher answer these questions. Data entered into the Monitor’s databases are progressively updated as new information is found. Throughout, researchers take a number of quality assurance steps to validate the data against the standards set out in the [Data Model section](/en/datamodel/README.md).

## Phase 4: Publish data {#method-phase-4}

Researchers will publish data online when confident that the main branches and overall structure of a country’s security forces are adequately covered. Data is published online on the Monitor’s innovative platform: [WhoWasInCommand.com](https://whowasincommand.com/).

## Timebound Data

Answering the question “who was where when?” is central for investigations into allegations of human rights abuse\(s\). Because of this perhaps one of the most defining, and complicaticating, features of the Security Force Monitor’s data is that almost everything we research is connected to time including:

* Existence of units
* Parent relationships between units
* Location of units
* Areas of operation for units
* Membership/participation of units of in multi-unit operations
* Positions held by people

While attaching time to data points aids our mission to support human rights investigations and advocacy, it raises methodological challenges and questions such as:

* Why the Monitor would \(or would not\) connect two bits of data through time
* How the Monitor handles gaps in the public record
* Questions analysts run through while reviewing time based information

In an ideal world the Monitor would have a source from every day of the year stating where a unit was located or conducting operations. Barring that, having multiple sources regularly making statements like “since X date this unit has been based in this city” would be tremendously helpful. Unfortunately, neither scenario currently occurs, or is likely to occur in the near future, making it necessary to develop a robust way of thinking through time.

Broadly speaking the Security Force Monitor uses agreement among sources to build up details on security force units and individuals. Most of the Monitor’s sources, like government press releases and newspaper articles, can be used to link a value, such as the location of a unit, to a specific date \(usually the date of publication\). As we collect more sources we need to determine what agreement among sources means for time based values, like the location of a unit.

> Example: the Monitor comes across Source A published on 1 July 2012 stating that the 1 Battalion is based in Lagos. If Source B published on 3 August 2012 also states that the 1 Battalion is based in Lagos we have a decision point about what claim we should make.

Utilizing sources A and B we have two options which can be expressed in text:

1. Separate claims: “As of 1 July 2012 the 1 Battalion was based in Lagos and as of 3 August 2012 the 1 Battalion was based in Lagos, the Monitor does not know where the battalion was based between those two points in time.”
2. Contiguity claim: “From at least 1 July 2012 to at least 3 August 2012 the 1 Battalion was based in Lagos.”

Thus, whenever the Monitor gets a new source of information we have to decide whether to make a “separate” or “contiguity” claim. Based on the example of the 1 Battalion above the Monitor would run through a series of questions to determine which claim \(if any\) to make:

* In general, how do other battalions operate, are they sedentary, or highly mobile?
* How has the 1 Battalion acted in the past, has it been sedentary or highly mobile?
* Are there other sources disputing these claims \(i.e. 1 Battalion being based solely in another city\)?
* Are there any sources indicating the 1 Battalion was in Lagos in July and/or August as part of a “special”, “emergency” or otherwise temporary posting?
* Are there sources that indicate the 1 Battalion moved in between these two points of time and thus these should be treated as separate deployments to Lagos?
* Is there anything related to the 1 Battalion’s parent or child units that may impact where it was based?
* Are there any other mitigating sources \(i.e. major restructuring of the military, constitutional changes, etc.\) which may impact the basing of the unit?
* Is more research needed before the Monitor can make any claim?

An argument could be the Monitor should always make “separate claims” as that would be more faithful to the sources. However, the result likely mean an almost incomprehensible amount of detail in the records of people and units, which would obscure when changes really did occur, for instance when a person changed positions or a unit ends operations in an area.

Perhaps the most important point is that it even though data points, like where a unit is based, can be continuous through time, it should never be assumed that those types of features remain consistent between two or more sources. Time is a constant challenge, but given that is a key element in identifying perpetrators of human rights abuses it is necessary to get it right.

