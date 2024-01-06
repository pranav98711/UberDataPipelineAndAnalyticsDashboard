# Uber ETL Data Pipeline and Analytics Dashboard | Python | Google Cloud Storage | Mage | ETL | Big Query | Looker


![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/1728f1fb-95e2-4079-a1fd-2cbab43d9ad2)



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

[TransformationCode.webm](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/baad9513-3fed-46e7-93d7-825e16135314)

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


![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/5ea7f3d5-9729-474a-bb98-e83d20625d67)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/0834581e-7fa7-4407-af10-60d93dcb0b10)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/9dbc6f04-e91b-43cf-abcc-66a31b4a69d6)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/07b4324b-9c47-48b7-bf98-ddfab86efc6d)


## Step 7: Once, the pipeline is ready, add GCP credentials credentials to the configuration 'io_config.yaml' file. You can easily get the credentials from the APIs and Services tab from Google Console.

## Step 8: Using BigQuery to query the data, perform ETL operations so that data can be used for Data Analysis like creating dashboards, reporting, etc.

[71d4003d-485d-44d2-bd85-2608831adc48.webm](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/5151570e-95ec-4111-84fd-40a1e6b2cb29)


## Step 9: Finally, create a dashboard using any dashboarding/reporting software, I used Looker Studio but we can also use other tools like Power BI, Tableau, Qlik, etc.

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/640d5159-6e93-4743-8ccb-6530b7199109)

![image](https://github.com/pranav98711/UberDataPipelineAndAnalyticsDashboard/assets/58882791/9dec9a73-0216-4d6f-a905-fa51343fd6ac)


## View Live Dashboard Here: 
[https://lookerstudio.google.com/s/nQI06ax2wMY](https://lookerstudio.google.com/s/pvJN8GhzsYQ)https://lookerstudio.google.com/s/pvJN8GhzsYQ







