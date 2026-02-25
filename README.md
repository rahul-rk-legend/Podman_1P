# GitSync

## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|True|
|Microsoft Azure Sentinel Incident Connector v2|Connector works with Microsoft Azure Sentinel incidents. Connector's Dynamic List can be used to specify the incidents names that needs to be fetched. See connector documentation for more information.|True|
|Microsoft Graph Mail Connector|Connector can be used to fetch emails from the Microsoft Graph Mail service. Connector dynamic list can be used to filter specific values from the email body and subject parts using regexes. By default, regex is used to filter out the urls from the email.|True|
|Sample Integration - Simple Connector Example|This is an example of a simple connector. It's integrated with "api.vatcomply.com" service and provides all of the main design ideas necessary to build a stable connector. Dynamic List defines what rates should be returned for a given currency and expects input in the format "EUR" etc.|True|
|VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|True|


## Playbooks
|Name|Description|
|----|-----------|
|Podman_1P_Playbook_1||
|Podman_1P_Playbook_2||


## Visual Families
|Name|Description|
|----|-----------|
|Podman_1P_Visual_Families_1|Podman_1P_Visual_Families_1|
|Podman_1P_Visual_Families_2|Podman_1P_Visual_Families_2|
|Podman_1P_Visual_Families_4|Podman_1P_Visual_Families_4|
|Podman_1P_Visual_Families_5|Podman_1P_Visual_Families_5|


## Jobs
|Name|Description|
|----|-----------|
|Google Chronicle Sync Job|This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM. Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.|
|Sync Incidents|This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.|
|projects/project/locations/location/instances/instance/integrations/GoogleChronicle/jobs/1/jobInstances/8|This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM. Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.|
|projects/project/locations/location/instances/instance/integrations/GoogleChronicle/jobs/2/jobInstances/4|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|projects/project/locations/location/instances/instance/integrations/MicrosoftAzureSentinel/jobs/26/jobInstances/7|This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.|
|projects/project/locations/location/instances/instance/integrations/SampleIntegration/jobs/25/jobInstances/3|This is an example of a simple job. It has 2 functions: if a case has a tag "Closed", it will close the case from the job, if a case has a tag "Currency", it will add a comment to the case.|

