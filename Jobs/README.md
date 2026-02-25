## projects/project/locations/location/instances/instance/integrations/GoogleChronicle/jobs/1/jobInstances/8
This job will synchronize information about Chronicle SOAR Cases and Chronicle SOAR Alerts with Chronicle SIEM.
 Note: This job is only supported from Chronicle SOAR version 6.1.44 and higher.


**Run Interval In Seconds:** None



Adding a readme on## projects/project/locations/location/instances/instance/integrations/GoogleChronicle/jobs/2/jobInstances/4
This job will sync new SOAR alerts with Chronicle SIEM.
Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.


**Run Interval In Seconds:** None


## projects/project/locations/location/instances/instance/integrations/MicrosoftAzureSentinel/jobs/26/jobInstances/7
This job synchronizes Google SecOps Alerts and Microsoft Sentinel Incidents. It ensures that comments, status, and tags are kept in sync between the two systems. For the job to identify the correct information, the Google SecOps case must have the “Microsoft Sentinel Incident” tag. If the alert didn’t originate from “Microsoft Azure Sentinel Incident Connector v2”,  you will need to add an “Incident_ID” context value to the case for the job to be able to find the correct information.


**Run Interval In Seconds:** None



Adding a readme on## projects/project/locations/location/instances/instance/integrations/SampleIntegration/jobs/25/jobInstances/3
This is an example of a simple job. It has 2 functions: if a case has a tag "Closed", it will close the case from the job, if a case has a tag "Currency", it will add a comment to the case.


**Run Interval In Seconds:** None


