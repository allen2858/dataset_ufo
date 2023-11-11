# dataset_ufo
Dataset about UFOs from recent years.


## Origin

- [Origin of Dataset](https://nuforc.org)
- [Version supplied for this project](https://iowa-my.sharepoint.com/personal/colbert_uiowa_edu/_layouts/15/onedrive.aspx?ga=1&id=%2Fpersonal%2Fcolbert%5Fuiowa%5Fedu%2FDocuments%2FUI%20Courses%2FDataWrangling%5Fdatasets%2Fufo)

## Current Status of Data

- Dataset includes UFO sightings from 09/2020 - 10/2023

## Data Dictionary

| Field         | Type          | Meaning                            |
| ------------- |:-------------:| ----------------------------------:|
| details       | text          | link to NUFORC website of sighting |
| date          | date/time     | date/time sighting occurred        |
| city          | text          | city sighting occurrred            |
| state         | factor        | state sighting occurred            |
| country       | factor        | country sighting occurred          |
| shape         | factor        | shape of sighted UFO               |
| summary       | text          | summary of sighting                |
| report date   | date          | date sighting was reported         |
| post date     | date          | date sighting was posted           |
| image         | image         | image of UFO                       |

## Change Log

- 11/11/2023: Updated all README files
- 11/11/2023: scraping completed and combined UFO dataset

## Notes
 
- Monthly datasets are in the archive file and all R files are in the code folder.
