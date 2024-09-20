
# Tennis data integration gcp

Welcome to the project where we build an automated data pipeline for tennis data using Google Cloud Platform (GCP). This tutorial guides you through the setup of a robust data pipeline that retrieves, processes, and visualizes tennis data.

## Project Overview

This project demonstrates the integration of several GCP services to create an efficient and automated data pipeline for tennis data. We will cover the following key components:

- **Data Retrieval**: Fetch data from the Tennis API using Python.
- **Storing Data in GCS**: Store the fetched data in a CSV file within Google Cloud Storage (GCS).
- **Cloud Function Trigger**: Create a Cloud Function that triggers upon file upload to the GCS bucket, executing a Dataflow job.
- **Cloud Function Execution**: Code within the Cloud Function that initiates the Dataflow job and passes required parameters.
- **Dataflow Job**: Load data from the CSV file in the GCS bucket into BigQuery.
- **Looker Dashboard**: Use BigQuery as the data source for your Looker Studio dashboard to visualize the data.

## Tech Stack

- **Google Cloud Platform (GCP)**
  - Google Cloud Storage (GCS)
  - Google Cloud Functions
  - Dataflow
  - BigQuery
  - Looker Studio
- **Backend**: Python

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AmmarNuh/tennis-data-integration-gcp.git
   cd tennis-data-pipeline

