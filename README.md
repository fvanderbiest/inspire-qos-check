# INSPIRE Quality of Service check

This repository provides a rough estimate of an SDI ability to meet the INSPIRE requirements for Quality of Service, as defined in: 
 * [View Services Technical Guidance](http://inspire.ec.europa.eu/documents/Network_Services/TechnicalGuidance_ViewServices_v3.11.pdf) chapter 6
 * [Download Services Technical Guidance](http://inspire.ec.europa.eu/documents/Network_Services/Technical_Guidance_Download_Services_v3.1.pdf) chapter 8


Easiest way to run it is with docker.

Create a copy of the `geograndest.env` file and run your own tests with:
```
docker run --env-file yours.env --rm fvanderbiest/inspire-qos-check
```

It was mainly tested against GeoServer instances.  
Checking other servers will probably require improvements. Contributions welcomed !
