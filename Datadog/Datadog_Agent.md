# Datadog Agent
## Datadog Installation
- Created Windows VM in Azure
<img width="1863" height="916" alt="image" src="https://github.com/user-attachments/assets/ddacb468-67f8-4a39-8a87-f3f431ac4122" />

___
- Installed Datadog Agent
<img width="1318" height="333" alt="image" src="https://github.com/user-attachments/assets/b82692fa-e1d4-46d8-a58c-fb22a9a86c20" />

___
- Config file
- Log Level: info
Config File: C:\ProgramData\Datadog\datadog.yaml - Keeps all configuraiont and prameters
Conf.d Path: C:\ProgramData\Datadog\conf.d - Integration configuration can be set
Checks.d Path: C:\ProgramData\Datadog\checks.d - Containes any checks build by us

___
- Status - General Info
<img width="1127" height="907" alt="image" src="https://github.com/user-attachments/assets/5a3c5966-d929-455f-b437-57f523fa82a2" />

- Status -Collector
<img width="1133" height="893" alt="image" src="https://github.com/user-attachments/assets/d215ed4c-cb4d-438b-9f77-7ae4eeaea437" />

- Logs
<img width="1123" height="940" alt="image" src="https://github.com/user-attachments/assets/bf6ad4bd-d131-4989-80c4-497fde437b7d" />

- Setting -contains main configuration (datdog.yaml file) - Make sure to restart aganet if any changes done in file
<img width="1127" height="946" alt="image" src="https://github.com/user-attachments/assets/3918c4d6-19aa-4696-91c9-e063240b6924" />

- Checkes - shows checks status (checks.d file)
<img width="1112" height="968" alt="image" src="https://github.com/user-attachments/assets/29a1fdb6-c823-41c3-8914-a2ca83c801a8" />

- Can raise ticket to datadog
<img width="1131" height="926" alt="image" src="https://github.com/user-attachments/assets/6b71593f-ba85-4966-845b-1893a4a91fb0" />

- Host Reporting in datadog app
<img width="1916" height="905" alt="image" src="https://github.com/user-attachments/assets/5e3c8523-06f1-4d42-8b6d-24f642d80b81" />

___
- Host Mapping, Agent, System, Ntp metrics in Host Map
<img width="1905" height="898" alt="image" src="https://github.com/user-attachments/assets/a663d3ca-1239-4783-ae5d-f9b13428f441" />

___
## Tags in Datadog
- Unified Service Tagging (Reserved Tags) in Datadog
<img width="1915" height="983" alt="image" src="https://github.com/user-attachments/assets/22cde954-c76a-4dcb-8305-f94f230d5d1a" />

___
- Assigning Tags from datadog.yaml file
<img width="1098" height="537" alt="image" src="https://github.com/user-attachments/assets/677beab9-cc33-4911-aa4f-06b080d4f085" />

___
- Filtering, Grouping on Tags
<img width="1912" height="630" alt="image" src="https://github.com/user-attachments/assets/0d31640c-8401-4c49-82fa-de350afdee09" />

___
## Infrastructure Monitoring Processes
- Process Explorer
- Enable process monitoring from config file
<img width="1121" height="513" alt="image" src="https://github.com/user-attachments/assets/185ebbd0-ff3d-4cb4-aa41-4b34b2400203" />
<img width="1904" height="916" alt="image" src="https://github.com/user-attachments/assets/8ff5267a-a3ca-4dce-b090-47fae477113b" />
<img width="1902" height="905" alt="image" src="https://github.com/user-attachments/assets/9bd242d9-0c4a-4347-9984-74e5d9c8e5ff" />

- Can search particular process
<img width="1907" height="927" alt="image" src="https://github.com/user-attachments/assets/0ab997bf-e975-4574-af18-cace3e73919e" />

- Scrubbing Sensitive data - In order to hide sensitive data on the Live Processes page, the Agent scrubs sensitive arguments from the process command line. This feature is enabled by default and any process argument that matches one of the following words has its value hidden.
<img width="1107" height="904" alt="image" src="https://github.com/user-attachments/assets/e2e69e4a-2adc-4c4a-9b7a-2c332d6d7ffa" />

- Create Custom Process metrics
<img width="1919" height="768" alt="image" src="https://github.com/user-attachments/assets/b844d683-744a-4b64-8cf3-e78cbd8378c9" />

___
## Infrastructure Monitoring Containers
- Docker Setup
- Installed docker on windows machine and run nginx container
<img width="1268" height="836" alt="image" src="https://github.com/user-attachments/assets/a95c8138-8201-4431-9778-5e284fce10e3" />

- Installed datadog agent on docker container
<img width="1097" height="884" alt="image" src="https://github.com/user-attachments/assets/033ab6b3-c7d6-487c-9bab-fa9738a7f1e3" />
<img width="1029" height="684" alt="image" src="https://github.com/user-attachments/assets/bff5a19f-0684-4a90-9c9a-3a5ddaf4ace5" />

- Docker container reporting in console
<img width="1911" height="465" alt="image" src="https://github.com/user-attachments/assets/da5d0233-fd51-40fd-8fb7-2c4fd403d574" />

___
- Environment Variables Translation rules
- https://docs.datadoghq.com/containers/docker/?tab=standard#environment-variables


___
## Metrics and Metric View in Datadog
- Metric Summary page
<img width="1897" height="911" alt="image" src="https://github.com/user-attachments/assets/adb88be3-b886-4b6d-9528-7d490be5bff2" />

___
- Metrics Explorer
<img width="1917" height="911" alt="image" src="https://github.com/user-attachments/assets/e869ff83-33a0-4324-aaac-3565fe2e0dd3" />

___

## Custom Metrics Agent Check
- Create .py file and save in check.d folder
<img width="1048" height="793" alt="image" src="https://github.com/user-attachments/assets/e288e625-a0a9-4c02-8f6c-6b03725da5be" />

___
- Create yaml file and folder and save in conf.d folder
<img width="966" height="785" alt="image" src="https://github.com/user-attachments/assets/d7f11087-c526-4d52-b49d-c124f26fe24e" />

___
- Restart the agent and check the checkes summary
<img width="1128" height="851" alt="image" src="https://github.com/user-attachments/assets/975c344d-2b00-48fc-ade9-807c6f94d3a1" />

__
- Search for custom mettrics we have created
<img width="1357" height="744" alt="image" src="https://github.com/user-attachments/assets/41e9c42e-4d52-4981-8ff2-d1605425cae1" />

___
## Custom Metrics - DogStatsD & Python app
- Python application code to instrument
<img width="1351" height="743" alt="image" src="https://github.com/user-attachments/assets/a8e44e5f-8a5e-468c-b04d-8d9d17ae625d" />

___
- Instrument Python app for COUNT metric type
<img width="1906" height="911" alt="image" src="https://github.com/user-attachments/assets/10eb0bbe-ff2d-43f9-8e1f-1a8f283c81a7" />
<img width="1912" height="910" alt="image" src="https://github.com/user-attachments/assets/e9414070-e74d-4858-bd97-618114c1c925" />

___
-  Instrument Python app for GAUGE metric type
-  Instrument Python app for HISTOGRAM & DISTRIBUTION
<img width="1897" height="913" alt="image" src="https://github.com/user-attachments/assets/7ed89248-cd5f-4200-aafd-ec6301e3fa71" />

___
## Events
- Event Log Check to capture Windows Events
- We can find all list of events logs with below command:
  -  PS C:\Users\azureuser> Get-WinEvent -ListLog * | sort Record

___
- Updated the required configuration in conf.yaml file and agent manager.
<img width="1308" height="736" alt="image" src="https://github.com/user-attachments/assets/64aa0766-8b17-4996-af57-3b1ceea935a3" />
<img width="1139" height="256" alt="image" src="https://github.com/user-attachments/assets/0c94a7b6-da04-4372-b510-c3cb3b60dc1c" />
<img width="1032" height="721" alt="image" src="https://github.com/user-attachments/assets/63fc4d2d-a24e-433b-ae98-422ceccd160c" />
<img width="1901" height="983" alt="image" src="https://github.com/user-attachments/assets/d4e42d22-002c-4039-b530-cf3f7ba3f26c" />

___
- Creating Custom events for application
<img width="1900" height="897" alt="image" src="https://github.com/user-attachments/assets/72538456-8b6b-418a-9f4c-e36c368bc911" />

___
## Notebook
- Create notebook - Add Timeseries Cell
<img width="1898" height="899" alt="image" src="https://github.com/user-attachments/assets/3779799e-f8aa-4729-a044-05f6b83f44f3" />

___
-  Add Text, Table cells in notebook
-  Version History
<img width="1891" height="891" alt="image" src="https://github.com/user-attachments/assets/79568d33-aacd-40f6-8cd4-bc03881285f1" />

___
## Dahsboards
- Types of dashboards
<img width="1908" height="894" alt="image" src="https://github.com/user-attachments/assets/95fa1698-8e40-4122-ac64-100f479b3003" />

___
- Timeseries widget created
<img width="1901" height="901" alt="image" src="https://github.com/user-attachments/assets/a817a750-0ef3-4da6-92f6-eba9ff20a2ed" />

___
- Find Correlations in metrics - If we want to see the same pattern of diffrent meteric we can add in correlation
<img width="1905" height="987" alt="image" src="https://github.com/user-attachments/assets/3bf5ac19-b074-4eed-80b2-c2eadcc0c51b" />

___
- Practices Dashboard Widget
<img width="1891" height="916" alt="image" src="https://github.com/user-attachments/assets/e3a7d3b4-2adf-426f-92e1-a0e5756636db" />

___
- Template Variables - We can create it for sperate view as per the services or requirement
<img width="1900" height="904" alt="image" src="https://github.com/user-attachments/assets/d3a464a2-864b-4458-90da-cce096359714" />

___
- Dashboard Setting
<img width="1900" height="903" alt="image" src="https://github.com/user-attachments/assets/64892153-3c54-4254-9080-f861551ea7e3" />

___
## Monitors and Alerts
- Prepared the Alert the run the testing, received alert email
<img width="1911" height="917" alt="image" src="https://github.com/user-attachments/assets/30ed943b-2ff4-4261-91c7-493981884477" />
<img width="1244" height="808" alt="image" src="https://github.com/user-attachments/assets/5b70e686-53ab-4e7d-97d2-6e8064d2dd6c" />

___
- Created alert and stop the datadog agent, received alert on email.
<img width="1897" height="892" alt="image" src="https://github.com/user-attachments/assets/ca028c72-c722-41b9-94ec-54a4d366593b" />
<img width="1222" height="809" alt="image" src="https://github.com/user-attachments/assets/655ef31b-eacc-4dae-ac47-7abaf14417bd" />

___
-  Downtime - Created Downtime as maintainence window for host offilne
<img width="1908" height="903" alt="image" src="https://github.com/user-attachments/assets/6a191c75-2fb9-42ba-955e-6c0916c5cade" />

___
- Started Datadog Agent
<img width="1222" height="794" alt="image" src="https://github.com/user-attachments/assets/026368db-a5f3-48d0-856c-8794728b2e66" />

