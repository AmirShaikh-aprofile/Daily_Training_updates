<img width="1909" height="648" alt="image" src="https://github.com/user-attachments/assets/0cff2895-1c60-427b-9e51-1d8750305cde" /># The Azure Load Balancer Service
## Basic Load Balancer
1. Setup 2 VM with nginx intsall on it and enable default.html page for better understanding. Als used same NSG for both VM and used availablity set
2. Deassocciate public IPs of VM But, the basic LB is not available in MS Azure we need to practice on Standard SKU




___
- Setup 2 VM with nginx intsall on it and enable default.html page for better understanding. Als used same NSG for both VM and used availablity set
<img width="1313" height="405" alt="image" src="https://github.com/user-attachments/assets/31c5f458-0dc2-416f-8cd0-57d05ccab2e5" />
<img width="1614" height="438" alt="image" src="https://github.com/user-attachments/assets/043cd11a-3c7a-4fd9-b512-932560d557dc" />
___

- Deassocciate public IPs of VM But, the basic LB is not available in MS Azure we need to practice on Standard SKU

  ## Standard Load Balancer - SKU
  1. Created Storage account for shell script of nginx installation
  2. Created standard LB with frontendIP and backend pool
 


- Created Storage account for shell script of nginx installation
<img width="1909" height="648" alt="image" src="https://github.com/user-attachments/assets/cc8a8135-bc57-4348-8a85-a0a6fc813c8e" />

____
- Created standard LB with frontendIP and backend pool
<img width="1918" height="557" alt="image" src="https://github.com/user-attachments/assets/7cb2c582-3329-44a2-98d3-e3dc966a43e8" />
<img width="1914" height="535" alt="image" src="https://github.com/user-attachments/assets/b10727aa-3705-401b-81ed-de4567bc11a2" />
____
- Added Prob Health
<img width="947" height="538" alt="image" src="https://github.com/user-attachments/assets/3c51c716-e043-4b64-9749-89a9d2b3c11f" />
____
- Added LB rule
<img width="1903" height="395" alt="image" src="https://github.com/user-attachments/assets/5e1a641b-cc0a-4d2d-b5c9-d0546c92d66a" />
_______
- Webapp was not working on Windows server so created new backendpoll with linux server and addded new LB rule
- The website is accessable vie frontend IP of LB
<img width="676" height="200" alt="image" src="https://github.com/user-attachments/assets/379ee0cc-f67a-4679-a083-432e79469806" />
<img width="1902" height="574" alt="image" src="https://github.com/user-attachments/assets/1a2b18d1-1fe4-4200-b16b-a52c32dc2bdb" />
___
- Unable to connect the VMs from NAT rules, troushooting done and added new LB rule
<img width="1919" height="501" alt="image" src="https://github.com/user-attachments/assets/a80d6b01-1bb0-4665-a55c-5db9475e5c17" />
<img width="524" height="54" alt="image" src="https://github.com/user-attachments/assets/3db23212-572a-499d-9f44-659edf8960b0" />
___
- Added outbond rule for internet connection on VMs
<img width="715" height="153" alt="image" src="https://github.com/user-attachments/assets/1e0b84e9-1a2e-4f3a-b630-4fd0e0f75232" />
______
- Also able to login to windows server after changeing the inbond rule in NSG
<img width="1043" height="601" alt="image" src="https://github.com/user-attachments/assets/465c6513-d721-47ca-9f52-aac2422bf0ef" />

## Multi FrontEnd IPaddress
- We can create multiple fronendip because we cannot use the same for diffrent backendpool, but it is not working as expected, checked the inbond ruls also
<img width="337" height="106" alt="image" src="https://github.com/user-attachments/assets/0be5e580-0b50-4dfe-bbef-94342f46def9" />

















