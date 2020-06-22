# SNOMED CT FHIR Implementation Guide

This IG uses [FSH](https://build.fhir.org/ig/HL7/fhir-shorthand/).

To install (at least version 0.13.2):
```
npm install -g fsh-sushi
```

To build - part 1:
```
cd snomed-ig-fsh
sushi .
```

To build - part 2:
```
cd build
./_updatePublisher.sh 
./_genonce.sh -tx <URL for the terminology server instance>
```
URL for the terminology server will be provided.
