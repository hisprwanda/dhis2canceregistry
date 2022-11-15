# DHIS2 Cancer Registry
National Cancer Registry: Web-based module built under DHIS2 tracker software that is used to collect and store information on confirmed cancer cases. The system is primarily used by cancer registry focal persons at district, provincial and referral hospitals to register confirmed cancer cases.

- [Metadata DHIS2 version 2.33](https://github.com/hisprwanda/dhis2canceregistry/blob/main/metadata_program.json)

- [Metadata DHIS2 version 2.36](https://github.com/hisprwanda/dhis2canceregistry/blob/main/metadataDHIS23.36.v2json)

# CANREG Export
These metadata works with DHIS2 Canreg app to export to CANREG5 for further cancer analyis

## Updated Programs Rules
  During the implementation of the DHIS2 Cancer Registry most important program rules were created. 
  They were created following the guidelines of the [International Association of Cancer Registries](http://www.iacr.com.fr/) (IACR).
  
  These guidelines are categoried as following:
  - Age Morphology Rare
  - Age Topography Rare
  - Age Topography Morphology Rare
  - Basis Morphology Query
  - Basis Morphology Topography Query
  - Grade Invalid
  - Sex Morphology Rare
  - Sex Topography Invalid
  - Topography Invalid
  - Topography Behavior Rare
  - Topography Morphology Rare
  
These updated validation checks / prgram rules can be found in this [directory](https://github.com/hisprwanda/dhis2canceregistry/tree/main/Oncology%20Validation%20Checks) 
