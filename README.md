# Map-the-Gatekeepers
Map Big-Tech takeout data to a common model so a person can transform their personal instance data into a common format.   

Project steps:
1) Start with just one datum (i.e., 'email' for Google takeout data) See sample Google instance data at  https://github.com/standard-personal-data-model/Map-the-Gatekeepers/blob/main/Profile.json   
2) Manually map it to a common data model (creating a mapping file)
3) Draft a transformation script, which:
   a) Takes in the instance data [jdoe53403@gmail.com from step-1 above] and the mapping file, and
   b) Transforms it into RDF triples that conform to the common data model

Developers should see the related Repo at https://github.com/standard-personal-data-model/Mapping-and-Transformation for examples of mapping files, transformation scripts, etc, and other prior work, but be aware this was draft work and likely has errors and gaps. 

Developers may use any common model they choose or create a new one.  One candidate is https://github.com/standard-personal-data-model/PDM-Glossary, which already includes the term 'EmailAddress.'  See PDM-Glossary v0-3, tab 'From Person Ontology' cell A59.  

Please email me at james.schoening@ieee.org for help in working or understanding this effort.  Thanks much!
