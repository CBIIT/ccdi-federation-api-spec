# CCDI Federation Data V1.2.0 Resource User Guide
---
This User Guide provides information to understand the Data Federation Resource application programming interface (API) available to users.

## Subjects

### Retrieve All Subjects:
Easily access a comprehensive list of subjects within the CCDI federated ecosystem.
- **Filtering:** Refine search by sex, race, ethnicity, identifiers, vital status, age at vital status, depositions, and unharmonized metadata fields.

### Retrieve Specific Subject by ID:
Quickly fetch detailed information about a specific subject using its unique ID (organization, namespace, and name).

### Group Subjects and Get Counts:
Organize subjects by any metadata field and receive aggregated counts for better insights.
- **Filtering:** Refine search by sex, race, ethnicity, identifiers, vital status, age at vital status, depositions.

### Summary Information for Subjects:
Obtain summary statistics and high-level information for all subjects in the system.

### Retrieving Associated Participant IDs: 
Retrieve participant records cross-linked across different datasets, studies, and organizations within the CCDI federated ecosystem using the subject-mapping endpoint, which leverages the CCDI Participant index (CPI). Input one or more participant IDs to retrieve all associated identifiers and their respective domains. 

Refine search further by additional metadata fields such as sex, race, ethnicity, vital status, age at vital status, depositions, and both harmonized and unharmonized metadata fields.

## Samples

### Retrieve All Samples:
Access an extensive list of samples within the CCDI federated ecosystem.
- **Filtering:** Narrow down results by disease phase, library strategy, preservation method, tumor grade, specimen molecular analyte type, tissue type, tumor classification, age at diagnosis, age at collection, tumor tissue morphology, depositions, diagnosis, and unharmonized metadata fields.

### Retrieve Specific Sample by Name:
Fetch detailed information about a specific sample using its unique identifier (organization, namespace, and name).

### Group Samples and Get Counts:
Organize samples by any metadata field and receive aggregated counts for better insights.
- **Fields include:** Disease phase, anatomical sites, library strategy, preservation method, tissue type, tumor classification, age at diagnosis, age at collection, tumor tissue morphology, depositions.

### Summary Information for Samples:
Get summary statistics and high-level information for all samples in the system.


## Files

### Retrieve All Files:
Access a comprehensive list of files within the CCDI federated ecosystem.
- **Filtering:** Refine search by file type, size, checksums, description, depositions, and unharmonized metadata fields.

### Retrieve Specific File by Name:
Quickly fetch detailed information about a specific file using its unique name (organization, namespace, and name).

### Group Files and Get Counts:
Organize files by any metadata field below and receive aggregated counts for better insights.
- **Fields include:** type, size, checksums, description, depositions

### Summary Information for Files:
Obtain summary statistics and high-level information for all files findable through the CCDI Data Federation Resource.

## Metadata Fields

### Retrieve Metadata Fields for Subjects:
Access detailed metadata fields supported for subjects.
- **Fields Include:** name, race, sex, vital status, age at vital status, identifiers, ethnicity.

### Retrieve Metadata Fields for Samples:
Access detailed metadata fields supported for samples.
- **Fields Include:** disease phase, library strategy, tumor classification, tumor tissue morphology, preservation method, tissue type, age at collection, age at diagnosis, depositions.

### Retrieve Metadata Fields for Files:
Access detailed metadata fields supported for files.
- **Fields Include:** description, name, size, type, MD5 checksum, depositions.

## Namespaces

### Retrieve All Namespaces:
View all namespaces within the server for better data organization.

### Retrieve Specific Namespace by Name:
Fetch detailed information about a specific namespace using its unique name (organization and namespace).

## Organizations

### Retrieve All Organizations:
Access a complete list of organizations within the server.

### Retrieve Specific Organization by Name:
Quickly fetch detailed information about a specific organization using its unique name.

### API Implementation Information:
Get detailed information about the API implementation for better integration and usage.

## Experimental

### Retrieve Sample Diagnosis:
Quickly obtain a comprehensive list of samples, filtered by their diagnosis and other relevant metadata.
- **Fields include:** diagnosis, disease phase, anatomical sites, library selection method, library strategy, library source material, preservation method, specimen molecular analyte type, tissue type, tumor classification, age at diagnosis, age at collection, tumor tissue morphology, depositions.

### Retrieve Subject Diagnosis: 
Quickly obtain a comprehensive list of subjects, filtered by their diagnosis and other relevant metadata.
- **Fields include:** sex, race, ethnicity, identifiers, vital status, age at vital status, depositions.

---
The v1.2.0 release of the CCDI Data Federation API has been designed to be fully functional, providing useful and accessible information to users. For detailed information on the limitations of this version, please visit (link to limitations doc in this folder)

These features and query capabilities are designed to enhance your experience and efficiency with the CCDI Data federation API. 

For more details, please refer to our [API documentation](https://cbiit.github.io/ccdi-federation-api-aggregation/).
