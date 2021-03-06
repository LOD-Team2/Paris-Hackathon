# LOS Paris Hackathon: “Produce” track

The “Produce” track is about creating statistical linked data (or metadata). It will start Monday at 2PM and end on Wedenesday evening.

## Activities

Here is a non-limitative list of possible activities during the hackathon:
  * Create RDF data sets;
  * Create metadata for a data set (for example: description, provenance, etc.) and attach the metadata to the data;
  * Evaluate or test software packages or high-level tools.

In order to prepare for this track, it is recommended that the participants get familiar with the [Data Cube](https://www.w3.org/TR/vocab-data-cube/) W3C Recommendation.

## Agenda

The detailed agenda is indicated below. Please note that coffee will be provided at the start of each morning and afternoon session.

| Day       | Time    | Session |
|-----------|---------|---------|
| Monday    | 2:00 AM - 2:30 PM | Introduction(s) |
| Monday    | 2:30 AM - 3:15 PM | Presentation of the data sets |
| Monday    | 3:15 AM - 4:00 PM | Presentation of the standards and tools |
| Monday    | 4:00 AM - 6:00 PM | Hackathon activities |
| Tuesday   | 9:00 AM - 12:00 PM | Hackathon activities |
| Tuesday   | 12:00 PM - 1:30 PM | Lunch break |
| Tuesday   | 1:30 AM - 6:00 PM | Hackathon activities |
| Wednesday | 9:00 AM - 9:30 AM | Preparation of presentations |
| Wednesday | 9:30 AM - 10:00 AM | First presentation of results |
| Wednesday | 10:00 AM - 12:00 PM | Hackathon activities |
| Wednesday | 12:00 PM - 1:30 PM | Lunch break |
| Wednesday | 1:30 PM - 4:30 PM | Hackathon activities |
| Wednesday | 4:30 PM - 6:00 PM | Presentation of results |

## Suggestions

Here are some detailed suggestions in case you need inspiration.

### French Census data

An [example program](https://github.com/LOS-ESSnet/POP5) is provided that converts results from the French Census (the ‘POP5’ spreadsheet) into a Data Cube DSD and DataSet. You can try to adapt the program to [other Census data sets](https://www.insee.fr/fr/statistiques/3561090?sommaire=3561107), or to [previous years](https://www.insee.fr/fr/statistiques/2053581?sommaire=2118618) (for methodological reasons, you can only compare results that are separated by five years).


### Data Cube DSDs

You can create Data Structure Definitions for new multi-dimensional data sets using the DSD Editor or DSD Loader (see the [Tools page](../tools/tools.md)).

### Sirene enterprise registry

Insee publishes the French enterprise registry (Sirene) on the data.gouv platform (see [here](https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)). You can convert Sirene to RDF, using for example the ORG ontology.