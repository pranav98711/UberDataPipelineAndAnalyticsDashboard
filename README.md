# Uber ETL Data Pipeline and Analytics Dashboard | Python | Google Cloud Storage | Mage | ETL | Big Query | Looker


![image](https://private-user-images.githubusercontent.com/81063457/257497004-2f929820-68b1-4b3c-9d66-87bdc3f757bf.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDQxNzQxNDcsIm5iZiI6MTcwNDE3Mzg0NywicGF0aCI6Ii84MTA2MzQ1Ny8yNTc0OTcwMDQtMmY5Mjk4MjAtNjhiMS00YjNjLTlkNjYtODdiZGMzZjc1N2JmLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMDIlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTAyVDA1MzcyN1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJhNjM0OTcxMWNiMTFkZDI1ODI5MmQ2Y2E0Y2FlYzlhOWVkMWNhY2FmZjEwZjE2YjY4ZTljOGIxOTQ1YTM3NTgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.tLdLvuHNN4BvGi3TTXU1KivX43luuQWlaMNYjqomL0Q
)



## Problem Statment
Perform data analtyics on Uber Cab data and create dashboard with insights from the given dataset.

## Technology Stack
Programming Language - Python
Google Cloud Platform
Google Storage
Compute Instance
BigQuery
Looker Studio
Mage ETL Data Pipeine Tool - https://www.mage.ai/


## Step 1 : Architecture Diagram



![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/b8a9c1f1-dd7d-46b9-917e-edf62e48b6e2)

## Step 2: Data Modeling and creating an ER Diagram to get a better understanding of the data


![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/blob/main/Images%26Vids/257492171-629e317a-7deb-48dc-9afa-f920f89ae636.png)

## Step 3: Writing the Transformation code in Python



## Step 4: Create a project and a bucket on the Google Cloud Platform, upload the data, select the server and set the appropriate permissions.

a. Create a Cloud Storage Bucket:
   - Navigate to Google Cloud Console.
   - Create a new bucket with a unique name.
   - Configure region, storage class, and access settings.
   - Upload data to the bucket and make it public.

b. Deploy Compute Engine Instance:
   - Launch a Compute Engine instance on GCP.
   - Configure instance details, such as name, region, and machine type.
   - Allow SSH access and create the instance.




## Step 5: Create a Virtual Machine Instance in GCP using GCP Compute Engine.

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/d74bf8d2-dca8-4fce-b6e3-778920f79a80)![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/5e2539f2-faaa-474a-b795-e2e3a1b336a3)
![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/d27e4acd-acec-41c0-a312-1a8859f06de7)



## Step 6: Connect the VM to Mage Project using SSH Linux Terminal and create a mage project (also download the necessary dependencies). Create a data pipeline using Mage Blocks like data loader, transformer, and exporters. Add your transformation code to the data transformer with the necessary changes.


![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/e0580009-3ab0-4963-bc45-e1a39c953889)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/f7e9d396-9944-4008-9346-96cd3a6a17c2)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/fdf78740-ebe8-4ef9-85d0-85ba1db9763e)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/58b32e05-538b-4a9d-b27d-7210a22b82c2)

## Step 7: Once, the pipeline is ready, add GCP credentials credentials to the configuration 'io_config.yaml' file. You can easily get the credentials from the APIs and Services tab from Google Console.

## Step 8: Using BigQuery to query the data, perform ETL operations so that data can be used for Data Analysis like creating dashboards, reporting, etc.


## Step 9: Finally, create a dashboard using any dashboarding/reporting software, I used Looker Studio but we can also use other tools like Power BI, Tableau, Qlik, etc.

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/9dec9a73-0216-4d6f-a905-fa51343fd6ac)


## View Live Dashboard Here: 
[https://lookerstudio.google.com/s/nQI06ax2wMY](https://lookerstudio.google.com/s/pvJN8GhzsYQ)https://lookerstudio.google.com/s/pvJN8GhzsYQ







