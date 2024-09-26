# DHIS2 Cancer Registry
# DHIS2 Metadata Configuration

This repository contains a JSON file with metadata configurations for various program stages, data elements, and option groups within a DHIS2 instance. The metadata focuses on oncology-related surgery, chemotherapy, and other medical programs. This configuration can be used to streamline data collection and reporting within health programs by configuring them in DHIS2.

## Contents

The JSON file includes:
- Program stages for various medical procedures
- Data elements related to oncology and other health programs
- Option sets for different health program choices
- Organization unit references

## How to Adapt to Your DHIS2 Instance

To use this metadata in your own DHIS2 instance, follow these steps:

1. **Update Organization Unit**
   - The current file uses the OrgUnit UID `JzMjFa3Cknd`.
   - Replace every occurrence of `JzMjFa3Cknd` with the UID of the OrgUnit in your DHIS2 instance.
   - Example: If your OrgUnit UID is `NEW_ORGUNIT_UID`, replace `JzMjFa3Cknd` with `NEW_ORGUNIT_UID`.

2. **Customize Program Stages**
   - Review and modify the `programStageSections` and `programStages` to align with your specific health programs or workflows.

3. **Adjust Data Elements**
   - Ensure that the `dataElements` (IDs and names) match the elements in your instance.
   - Create new data elements in DHIS2 if needed.

4. **Update User References**
   - Replace the `createdBy` and `lastUpdatedBy` fields with usernames and user IDs from your instance.
   - The current file uses the default `admin` user, which should be replaced with users from your organization.

5. **Modify Option Sets**
   - Review the `optionSet` section and adjust the options to reflect the actual datasets and choices used in your DHIS2 instance.

6. **Generate New IDs**
   - All resource IDs (e.g., programStage IDs, dataElement IDs) in this file are unique to the original DHIS2 instance.
   - You may need to generate new IDs for these objects if you are creating new ones in your DHIS2 instance.

## Important Note

Always test the adapted configuration in a non-production environment before applying it to your live DHIS2 instance.

## Support

If you encounter any issues or have questions about adapting this metadata to your DHIS2 instance, please open an issue in this repository.



- [Metadata DHIS2 version 2.40](https://github.com/hisprwanda/dhis2canceregistry/blob/main/metadataDHIS23.36.v2json)

for older versions of DHIS2
- [Metadata DHIS2 version 2.33](https://github.com/hisprwanda/dhis2canceregistry/blob/main/metadata_program.json)

- [Metadata DHIS2 version 2.36](https://github.com/hisprwanda/dhis2canceregistry/blob/main/metadataDHIS23.36.v2json)

# CANREG Export
These metadata works with DHIS2 Canreg app to export to CANREG5 for further cancer analyis

## Programs Rules
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

## License

This work is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

## About HISP Rwanda
This metadata configuration is provided by HISP Rwanda. For more information about our work and other projects, please visit our website: [www.hisprwanda.org](http://www.hisprwanda.org)
