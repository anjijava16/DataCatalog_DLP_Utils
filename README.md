# DataCatalog_DLP_Utils

# Data Catalog 
Data Catalog is a fully managed and scalable metadata management service that empowers organizations to quickly discover, understand, and manage all their data.
It offers a simple and easy-to-use search interface for data discovery, a flexible and powerful cataloging system for capturing both technical and business metadata, and a strong security and compliance foundation with Cloud Data Loss Prevention (DLP) and Cloud Identity and Access Management (IAM) integrations.


Using Data Catalog
There are two main ways you interact with Data Catalog:
- Searching for data assets that you have access to.
- Tagging assets with metadata.

GCP Having by default below service in the Datacatalog:

  i.    BigQuery

  ii.   GCS
  
  iii.  Pub/Sub


i.   A simple and easy to use search interface for data discovery, powered by the same Google search technology that supports Gmail and Drive.
ii.  A flexible and powerful cataloging system for capturing technical and business metadata.
iii. An auto-tagging mechanism for sensitive data with DLP API integration.

Flow: On-premise (SQLServer---> Scrape ---> Prepare ---> Ingest)

https://medium.com/google-cloud/google-cloud-data-catalog-integrate-your-on-prem-rdbms-metadata-468e0d8220fb

https://github.com/GoogleCloudPlatform/datacatalog-connectors

https://github.com/GoogleCloudPlatform/datacatalog-connectors-rdbms


# Data Loss Prevention(DLP)
Fully managed service designed to help you discover, classify, and protect your most sensitive data.

Cloud DLP includes:

i. Over 120 built-in information type (or "infoType") detectors.

ii. The ability to define custom infoType detectors using dictionaries, regular expressions, and contextual elements.
De-identification techniques including redaction, masking, format-preserving encryption, date-shifting, and more.

iii. The ability to detect sensitive data within streams of data, structured text, files in storage repositories such as Cloud Storage and BigQuery, and even within images.

iv. Analysis of structured data to help understand its risk of being re-identified, including computation of metrics like k-anonymity, l-diversity, and more.

Reference Link: https://cloud.google.com/dlp/docs

