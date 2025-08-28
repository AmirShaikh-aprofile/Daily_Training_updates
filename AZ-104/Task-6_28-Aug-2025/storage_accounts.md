## Storage account in azure

1. Create storage account with unique name
2. Create container for uploaded blob files
3. Given access to blob storage to access it from URL (But not safe)
4. Azure storage explorer (Can't install due to company policy)
5. Genrating SAS token to access the blob and container
6. Creating SAS for container and account level with access key
7. We can change access policy as per the need
8. can create time base access policy
9. Azure Storage Accounts - Data Redundancy - For critical data fr high availability in multiple Azone and Aregion. It will increase the cost.
10. Azure storage Access tier
11. Changing access tier
12. Lifecycle management rule for object of whole storage account
13. Enable access tracking
14. Replicate the blobs in another account
15. Creating snapshot before making change in blob and can keep its versioning
16. Created directory in file share but unable to connect due the port 445 is not open on laptop
17. Snaptop for azure file share
18. Encryption via keyvault (Pending practice)
19. Azure Storage Accounts - AzCopy Tool
20. We can enable the file to access the storage account and for only 1 IP



___
- Create storage account with unique name
<img width="1909" height="700" alt="image" src="https://github.com/user-attachments/assets/dee6268c-fe68-4d67-be7c-10918d2c1df0" />

____
- Create container for uploaded blob files
<img width="1908" height="860" alt="image" src="https://github.com/user-attachments/assets/d5924a2b-6b86-4a9e-8a75-3ff4513d445f" />

___
- Given access to blob storage to access it from URL (But not safe)
<img width="1919" height="394" alt="image" src="https://github.com/user-attachments/assets/818fea44-1121-47f4-aea9-e706ee698450" />
<img width="1274" height="241" alt="image" src="https://github.com/user-attachments/assets/526ca163-063f-4d84-ac84-8380cdc439da" />

____
- Genrating SAS token to access the blob and container
<img width="1902" height="904" alt="image" src="https://github.com/user-attachments/assets/2869d3bd-a3a6-4492-bfe7-68c208205fcc" />

___

- Crateing SAS for container and account level with access key
<img width="1903" height="900" alt="image" src="https://github.com/user-attachments/assets/02be1753-4d37-420a-86b9-601c07272af8" />
<img width="1887" height="900" alt="image" src="https://github.com/user-attachments/assets/9cdd2240-957e-4d81-8cf0-e5e90d9574a5" />

____
- We can change access policy as per the need
<img width="1919" height="576" alt="image" src="https://github.com/user-attachments/assets/e4bd3d5e-e404-4c8e-844b-0d8a836a9249" />

____
- We can create time base access policy 
<img width="1912" height="511" alt="image" src="https://github.com/user-attachments/assets/7ab1d39b-af39-4f05-bcc6-342dfb96898c" />

___
- Azure Storage Accounts - Data Redundancy - For critical data fr high availability
<img width="750" height="795" alt="image" src="https://github.com/user-attachments/assets/9187f083-4280-44a6-b152-5456dd38235f" />
<img width="1895" height="915" alt="image" src="https://github.com/user-attachments/assets/7b0754ae-755a-4391-b84c-127d01bf2a8f" />

____

- Azure storage Access tier
<img width="874" height="450" alt="image" src="https://github.com/user-attachments/assets/05f72f42-223e-4150-bcf9-7655644e8d9b" />

___
- Changing access tier
<img width="1418" height="884" alt="image" src="https://github.com/user-attachments/assets/c67a833c-715d-4f2b-8302-9952f603da13" />

___

- Lifecycle management rule for object of whole storage account
<img width="1917" height="766" alt="image" src="https://github.com/user-attachments/assets/11853413-28ff-437a-98d7-deb22eae7805" />

___
- Enable access tracking
<img width="586" height="368" alt="image" src="https://github.com/user-attachments/assets/00b7578f-0aac-433d-be65-230fcfb71a29" />

___
- Replicate the blobls in another account
<img width="1919" height="645" alt="image" src="https://github.com/user-attachments/assets/2dc3f4bd-7e17-4057-b8ad-ffd021c434f4" />

___
- Creating snapshot before making change in blob and can keep its versioning
<img width="1911" height="485" alt="image" src="https://github.com/user-attachments/assets/b5914b9f-c017-4745-9da3-c055824cc6c4" />
<img width="886" height="251" alt="image" src="https://github.com/user-attachments/assets/4edfe307-c9f8-4108-903d-ef74629caee3" />

___

## File share

- Created directory in file share but unable to connect due the port 445 is not open on laptop
<img width="1914" height="336" alt="image" src="https://github.com/user-attachments/assets/a7ec3c33-fe54-496b-a7ba-3639331c6a51" />
<img width="1110" height="629" alt="image" src="https://github.com/user-attachments/assets/20dc3973-e605-42f6-81d0-68b8697d525e" />

___
- Snaptop for azure file share
<img width="1919" height="402" alt="image" src="https://github.com/user-attachments/assets/0ec35674-350b-4f5a-8237-ff8ac27c6a89" />

___
- Soft delete for file share within 7 days
  <img width="1919" height="358" alt="image" src="https://github.com/user-attachments/assets/50dd4b30-f6a0-4c0c-938b-d92e378081c3" />

___

- Azure Storage Accounts - AzCopy Tool - Resources
The following can be used as a reference for the prior chapter

To download the AzCopy tool one can visit the following URL - https://learn.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-v10?tabs=dnf

First ensure to create the shared access signature and replace it in the commands accordingly

1.  To create a container

azcopy make "https://appstore35545.blob.core.windows.net/data?sv=2021-06-08&ss=b&srt=sco&sp=rwdlaciytfx&se=2023-01-27T21:10:21Z&st=2023-01-27T13:10:21Z&spr=https&sig=OCyNZlTtxO5aFpppfnk6WLEXW%2BqouaTFavnIFg67zXM%3D"



2. To upload a file

azcopy copy app.yml "https://appstore35545.blob.core.windows.net/data/app.yml?sv=2021-06-08&ss=b&srt=sco&sp=rwdlaciytfx&se=2023-01-27T21:10:21Z&st=2023-01-27T13:10:21Z&spr=https&sig=OCyNZlTtxO5aFpppfnk6WLEXW%2BqouaTFavnIFg67zXM%3D"



3. Download blob data

azcopy copy "https://appstore35545.blob.core.windows.net/data/app.yml?sv=2021-06-08&ss=b&srt=sco&sp=rwdlaciytfx&se=2023-01-27T21:10:21Z&st=2023-01-27T13:10:21Z&spr=https&sig=OCyNZlTtxO5aFpppfnk6WLEXW%2BqouaTFavnIFg67zXM%3D" "app.yml"

___
We can enable the file to access the storage account and for only 1 IP, we add the vnet usung service endpoint
<img width="1896" height="875" alt="image" src="https://github.com/user-attachments/assets/8ad18765-0f41-46c4-af71-1a733fbf79db" />
