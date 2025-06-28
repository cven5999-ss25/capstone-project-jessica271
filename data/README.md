# README
Dataset maintainer: Jessica Maina                                                                      ORCID iD: https://orcid.org/0009-0007-5229-3182                                                                    
## General information

1.  Title of Dataset: African Development Corridor Database 2022 by Thorn, Jessica P.R.; Mwangi, Ben; Juffe Bignoli; Diego
Published Sep 09, 2022; Updated Oct 04, 2022 on Dryad. [ https://doi.org/10.5061/dryad.9kd51c5hw]

2.  Author Information

**Author A**

- First name: Jessica
- Surname: Thorn
- ORCID iD
- Email:jessica.thorn@york.ac.uk

**Author B**

- First name: Diego
- Surname: Juffe Bignoli
- ORCID iD: https://orcid.org/0000-0002-1498-4317
- Email:diegojuffe@biodecisions.org

etc.

3.  Date of data collection (single date, range, approximate date):                             Published Sep 09, 2022; Updated Oct 04, 2022

4.  Geographic location of data collection:                                                       Africa

5.  Information about funding sources that supported the collection of
    the data:                                                                                         UK Research and Innovation : Project No. ES/P011500/1

## Sharing / access information

1.  Licenses/restrictions placed on the data:          https://creativecommons.org/publicdomain/zero/1.0/

Recommended: This work is licensed under the Creative Commons Attribution 4.0 International license (CC-BY-4.0).

2.  Links to publications that cite or use the data: https://datadryad.org/dataset/doi:10.5061/dryad.9kd51c5hw

3.  Links to other publicly accessible locations of the data:                                           https://doi.org/10.1038/s41597-022-01771-y

4.  Links/relationships to ancillary data sets:                                                         https://download.geofabrik.de                                                                       https://geonode.wfp.org/layers/geonode%3Awld_trs_airports_wf

5.  Was data derived from another source?                                                           Yes, some of the data was derived from other sources. For example, they ran searches on regional bodies website to get information, such as the national government websites.
## Methodological information

1.  Description of methods used for collection/generation of data:                                    Data collection was done in three stages:                                                              First, review of secondary sources' websites such as the national governments.                         Manual digitization of spatial features and temporal distribution. This included features like major roads.                                                                                           Lastly, technical validation  

2.  Methods for processing the data:                                                                       Data collection - interpolating - summarizing - integrating data

3.  Instrument- or software-specific information needed to interpret the
    data:                                                                                               Spatial software (GIS)                                                                                 https://unep-wcmc.maps.arcgis.com/home/webmap/viewer.html?webmap=aa6dcedfbede4b2188f90cda23ae03d0&extent=-110.8169,-57.1842,148.812,59.0403

4.  Standards and calibration information, if appropriate: -

5.  Environmental/experimental conditions:                                                              The study collected weather and temporal data from the region. It expresses a concern for development corridors causing environmental pollution and sustainability issues in Africa.

6.  Describe any quality-assurance procedures performed on the data:                           
Cross-referencing sources for roost data - Compared multiple reports for example, government reports on infrastructure.                                                                                         Georeferencing accuracy - The digitize map helped in eliminating spatial errors.                       Data consistency checks before using any secondary data                                                Standardized data sources - For example, government reports and NASA Power weather data.                    
7.  People involved with sample collection, processing, analysis and/or
    submission:
The dataset was processed and analyzed by the study’s authors.

Laura D. K. Fardell, Emma Hudson, Alice C. Hughes, Matthew J. Struebig, Alison J. Peel, were credited in the paper and dataset listing.

library(usethis)
use_git_config(user.name = "jessica271", user.email = "Jessica.Maina@colorado.edu")


