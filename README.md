# LSDC The Low Saxon Dialect Classification dataset

This dataset contains train and test data in 16 dialects or subdialects of Low Saxon from both Germany and the Netherlands covering various genres and a period of around 200 years from the early 19th to the beginning of the 21st century. This dataset will continuously be updated e.g. by removing mistakes in the annotation or adding new data. 

## Description of the data 

Dialects from the following (modern or historical) regions are represented in the dataset: Achterhoek (ACH), Drenthe (DRE), Groningen (GRO), Hamburg (HAM), Holstein (HOL), Mark Brandenburg (MAR), Mecklenburg-Vorpommern (MKB), Münsterland (MON), Northern Lower Saxony (NNI), Lower Prussia (NPR), Eastphalia (OFL), East Frisia (OFR), Western Overijssel (OVY), Eastern Westphalia (OWL), Sauerland (SUD) and Twente (TWE).

The texts used for this dataset belong to the following genres: administration, announcements and politics, fairytales and legends, (short) stories and (short) novels, songs and poetry, theatre plays, religious texts, meta-discussions about language (usually about Low Saxon) and discussions of history among others.

In addition to the actual train and test data, the dataset also includes lists of Low Saxon placenames which originally were used to test the influence of placenames on dialect classification accuracy. 

The data were split into sentences using NLTK's tokenize package and annotated according to century (19th, 20th or 21st) as well as dialect. The dialect annotation generally follows the information available about the original text sources. In addition, the test set was manually cleaned to remove sentences shorter than 4 words or written fully or mostly in languages other than Low Saxon such as German or Dutch. 

When using these data for training practical applications, one needs to take into consideration the following possible limitations of this dataset:
- While dialects from some regions, such as the Sauerland or Holstein, are represented by a variety of writers, others like Drenthe or Eastphalia are represented mostly or fully by texts from one author. 
- With the exception of e.g. passages of direct speech from novels, the dataset predominantly consists of literary and/or formal language. 
- The dialects from Mecklenburg-Vorpommern and Mark Brandenburg are only represented by data from the 19th century and therefore might not generalise well to more modern data. 
- There is no common standard orthography for Low Saxon, and even though many regions have some form of writing traditions and various institutes have published spelling rules for the local dialect, average Low Saxon speakers might not adhere to these rules or traditions because they e.g. simply do not know them or they have other preferences. 

## License

These data are released under this licensing scheme:

[![License: CC BY-NC-SA 4.0](https://licensebuttons.net/l/by-nc-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- We do not own any of the text from which these data have been extracted.
- We license the actual packaging of these data under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License

### Notice and take down policy

**Notice:** Should you consider that our data contains material that is owned by you and should not be reproduced here, please:

- Clearly identify yourself, with detailed contact data such as an address, telephone number or email address at which you can be contacted.
- Clearly identify the copyrighted work claimed to be infringed.
- Clearly identify the material that is claimed to be infringing and information reasonably sufficient to allow us to locate the material.
- And contact Janine Siewert at the following email address: janine DOT siewert AT helsinki.fi.

**Take down:** We will comply to legitimate requests by removing the affected sources from the next release of the corpus.
