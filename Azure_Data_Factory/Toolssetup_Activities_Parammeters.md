# Setting up Project

1. Created Azure devops account account
2. Cloned the repo in VS code
3. Created test file and commited on azure devops repo
4. Created storage account
5. Created azure data factory resource
6. Created SQL server and database




____
- Created Azure devops account account
<img width="1912" height="668" alt="image" src="https://github.com/user-attachments/assets/07a314ec-1e50-42ff-b8d4-a2be9df833c6" />

___
- Cloned the repo in VS code
<img width="1919" height="634" alt="image" src="https://github.com/user-attachments/assets/e561289b-c23d-4a5c-b676-7639043f117e" />

___SQL serve
- Created test file and commited on azure devops repo
<img width="1919" height="666" alt="image" src="https://github.com/user-attachments/assets/6f53fd51-9c5c-4505-9007-a434cbc276a3" />

___
- Created storage account
<img width="1913" height="862" alt="image" src="https://github.com/user-attachments/assets/653efe6e-917e-432a-a4f1-17c500d3366d" />

___

- Created azure data factory resource
<img width="1637" height="647" alt="image" src="https://github.com/user-attachments/assets/a021f336-6d00-4883-8af0-b47e03ec2156" />

___
- Created SQL server and database
<img width="1626" height="824" alt="image" src="https://github.com/user-attachments/assets/aa6fd456-8c1c-4cb5-9a52-de30600450ea" />

___
- Setup azure data studio on laptop
<img width="1919" height="762" alt="image" src="https://github.com/user-attachments/assets/ebde426d-337a-4171-bbd9-7aadfaea0022" />

___
- Connect to the sql server and created test table
<img width="1919" height="639" alt="image" src="https://github.com/user-attachments/assets/80f819b7-be53-444d-b31b-1041c228815f" />

___
- Created new test pipeline to setup variable
<img width="1862" height="852" alt="image" src="https://github.com/user-attachments/assets/ac8092d2-ce5c-4c59-b916-b1db8c80b6a1" />

___
### Building data pipeling

- Created 2 landing and raw container
<img width="1871" height="614" alt="image" src="https://github.com/user-attachments/assets/5dd21644-2f6d-4904-9a96-a405c6f0d295" />

___
- Uploaded sample.zip folder in landing container
<img width="1871" height="450" alt="image" src="https://github.com/user-attachments/assets/85f342a2-9e03-466d-9706-d3757f6b40b1" />

__
- Creating data pipeline to copy and unzip the file
<img width="1864" height="824" alt="image" src="https://github.com/user-attachments/assets/30ba62e2-ca16-4b61-9968-5bb6625f7d44" />

___
- Pipeline was succesfully run and files are unziped
<img width="1873" height="747" alt="image" src="https://github.com/user-attachments/assets/83724678-43ca-4215-b632-89cb7f3a412d" />

___
- Building the Data Pipeline - Review and Organize
<img width="1867" height="788" alt="image" src="https://github.com/user-attachments/assets/acbe057b-0715-44fc-b483-d33b3d5e191c" />

___
- Importing Semi-Structured Data - Building the Pipeline
<img width="1859" height="910" alt="image" src="https://github.com/user-attachments/assets/015af8aa-4329-46e9-8f97-40a06ff4d574" />
<img width="1866" height="713" alt="image" src="https://github.com/user-attachments/assets/e8a6edc7-5283-4a61-8e83-9f16da533257" />

___
- Organizing the Pipeline
<img width="1869" height="862" alt="image" src="https://github.com/user-attachments/assets/85cb7b60-36f9-48a8-9e50-b43e36aac897" />

___
- Activity Dependencies - Examples
- On success dependency
- Deleted the sales folder from cleansed container and started validation
- First Acitivty, validation activity failed as no data in the source
<img width="1866" height="867" alt="image" src="https://github.com/user-attachments/assets/c203d14f-6784-41f5-adcf-2ca012a29fee" />
___
- On fail dependency
- Now adding failure dependency, means the set variable activity will execute if the validation activity fails
<img width="1868" height="841" alt="image" src="https://github.com/user-attachments/assets/098e6e2b-4a1d-4936-80e6-ca181b2b78b6" />

___
- On Skip dependency
- It will skip the acivity which is getting failed
<img width="1868" height="891" alt="image" src="https://github.com/user-attachments/assets/5686d1f7-e17e-4657-8238-b62e979f1d73" />

___
- Copy Activity Concepts
- Mapping scemas from source file
<img width="1860" height="803" alt="image" src="https://github.com/user-attachments/assets/b1967cfa-9f04-4fe2-8ce5-f7dbac49c564" />

___
- Helpful in data conversion from diffrent data processing tool
  <img width="640" height="351" alt="image" src="https://github.com/user-attachments/assets/dea651f5-cc74-462c-8673-aa0658a44a57" />

___
- Can preview the data
<img width="1866" height="803" alt="image" src="https://github.com/user-attachments/assets/94cdd82c-53cb-448c-a98c-c3adeab450e0" />

___
- Data integration unit (Default is 4)
<img width="1867" height="697" alt="image" src="https://github.com/user-attachments/assets/1250ccf4-2d43-4ef1-9292-ec2f8cca83df" />

___
- Expressions and Variables
- Setting up values for variables
<img width="1858" height="920" alt="image" src="https://github.com/user-attachments/assets/112db67a-3006-4c56-8e07-6d848cb2299a" />
- Enable breakpoit by red circle
<img width="956" height="347" alt="image" src="https://github.com/user-attachments/assets/1f297b94-47b4-4734-b65a-d26952e08b17" />

___
- Output
<img width="1867" height="818" alt="image" src="https://github.com/user-attachments/assets/ca4733c4-010f-42f9-bec0-a5d18d928963" />

___
- We can define the variable as per our requirement
<img width="1862" height="878" alt="image" src="https://github.com/user-attachments/assets/5e9382ba-6aff-4ed0-b9e9-0ee12e4cdaa9" />

___
- Parameters - We can set value to our variable at the runtimr of pipeline
<img width="1125" height="679" alt="image" src="https://github.com/user-attachments/assets/444bd424-b46e-4c7e-bb59-8ac8585c26d0" />
<img width="1865" height="812" alt="image" src="https://github.com/user-attachments/assets/d14b7fec-f726-46d1-882d-3add82ab0732" />
- Output
<img width="1865" height="827" alt="image" src="https://github.com/user-attachments/assets/e4ffbd1a-f5c1-4789-834d-83b4b9f5d7e2" />

___
- Global parameter
<img width="1866" height="468" alt="image" src="https://github.com/user-attachments/assets/3290e77d-ec73-442e-a503-eec1850e9825" />

___
- Added in variable value
<img width="1869" height="761" alt="image" src="https://github.com/user-attachments/assets/06f032e7-3f94-431c-8495-51ca1630b47c" />

- Output
<img width="1866" height="734" alt="image" src="https://github.com/user-attachments/assets/92a45883-c862-4eb1-9623-a50ff037ed94" />

___
- Created key valt secrect and assigned access policy to our ADF
<img width="1867" height="546" alt="image" src="https://github.com/user-attachments/assets/84c3cfc7-1312-4d2e-9781-ba41bdc0d71e" />

___
- Linked Keyvalt service in ADF
<img width="1866" height="715" alt="image" src="https://github.com/user-attachments/assets/e570ddf8-31ad-4264-b59b-2eea770f4273" />

___
- Changed selected methoed to keyvailt
<img width="1852" height="841" alt="image" src="https://github.com/user-attachments/assets/19c74574-a8e4-40fb-bcc9-adcf513a5022" />

___
## Importing Semi-Structured Data
### This task is to converted the json file in csv

1. Created new piepiline and added 'Get Metadata' activity, and seletecd the raw data folder location  also confirmed the connection to key vault
2. Created ForEach activiy added spoty activity in it.




- Created new piepiline and added 'Get Metadata' activity, and seletecd the raw data folder location  also confirmed the connection to key vault
<img width="1865" height="775" alt="image" src="https://github.com/user-attachments/assets/d4982697-7c07-4352-bc89-4b1e81df1d62" />
<img width="1856" height="508" alt="image" src="https://github.com/user-attachments/assets/7a6a6635-afd6-44e6-a274-cf46514c7287" />
<img width="1857" height="915" alt="image" src="https://github.com/user-attachments/assets/3575fcd1-a641-4b2f-861c-da00eda14fca" />

___
- Created ForEach activiy added spoty activity in it.
- Set source and sink
<img width="1852" height="917" alt="image" src="https://github.com/user-attachments/assets/c58ff353-8df6-43cf-b088-f653a5ec6081" />

____
- Created parameter for source data, as the file path was not selected
<img width="1866" height="753" alt="image" src="https://github.com/user-attachments/assets/73aa7b33-8ca0-43f7-ad03-ad128b3025cb" />

___
- Added dataset properties in source tab
<img width="1867" height="913" alt="image" src="https://github.com/user-attachments/assets/87ff1ab2-42b4-4d36-9b56-16c6a9593ab8" />

___
- Created parametes in sink destination
<img width="1852" height="907" alt="image" src="https://github.com/user-attachments/assets/c37f9397-b77b-41dc-ab9d-ec127104b952" />

___
- Added dataset properties in sink tab also changed the expression because the filesname should be changed from json to csv
<img width="1860" height="902" alt="image" src="https://github.com/user-attachments/assets/82a0cf84-0e89-4c2d-8666-6dde0099c9ed" />

___
- Changed copy behavior 
<img width="1863" height="912" alt="image" src="https://github.com/user-attachments/assets/f98eacb9-b89d-4378-9bbf-5c70cf748abd" />

__
- Added schema with json file name  
<img width="1866" height="927" alt="image" src="https://github.com/user-attachments/assets/f26f1957-4b82-48db-9269-039d8d8388e7" />

__
- After adding schemas, maaped the data same like csv file colums, it should i same structure as previos files
<img width="1852" height="908" alt="image" src="https://github.com/user-attachments/assets/95a9a5c8-1c26-4de3-950a-1ce5d2bee396" />

