
# Mapping Documentation
   
**Version:**

**Authors**:

    
* Jhon Toledo Barreto
   
    
* Ana Iglesias-Molina
   

**Mapping file:**
author.ttl


**License**:

[![http://insertlicenseURIhere.org](https://img.shields.io/badge/License-Creative%20Commons%20Attribution%204.0%20International%20(CC%20BY%204.0)-blue.svg)](https://creativecommons.org/licenses/by/4.0/)



------


## **Namespaces used in the document**

| Prefix       |               IRI.                   |
| :----------- | :----------------------------------  |
| schema1     | http://schema.org/ |
| comp     | http://semweb.mmlab.be/ns/rml-compression# |
| map     | http://mapping.example.com/ |
| rr     | http://www.w3.org/ns/r2rml# |
| rev     | http://purl.org/stuff/rev# |
| gtfs     | http://vocab.gtfs.org/terms# |
| grel     | http://users.ugent.be/~bjdmeest/function/grel.ttl# |
| fnml     | http://semweb.mmlab.be/ns/fnml# |
| d2rq     | http://www.wiwiss.fu-berlin.de/suhl/bizer/D2RQ/0.1# |
| ql     | http://semweb.mmlab.be/ns/ql# |
| dct     | http://purl.org/dc/terms/ |
| formats     | http://www.w3.org/ns/formats/ |
| geo1     | http://www.w3.org/2003/01/geo/wgs84_pos# |
| rml     | http://semweb.mmlab.be/ns/rml# |



## Mappings
>[!NOTE]
>1. **Source**: This is where you define the source of your data, which can be a relational database, a CSV file, or any other structured data source. The logical source specifies the location and format of your source data.
>2. **Subject**: This part of the mapping defines how the data from the logical source will be used to create RDF subjects, typically using templates and column mappings.
>3. **Predicate Object**: These describe how the data from the logical source will be used to generate RDF triples, indicating relationships between subjects and objects.
>4. **JoinCondition**: is used to specify the conditions under which two data sources or tables should be joined when creating RDF triples through mappings.






----

**This documentation was generated using**  *[RMLdoc](https://oeg-upm.github.io/rmldoc/)*.
