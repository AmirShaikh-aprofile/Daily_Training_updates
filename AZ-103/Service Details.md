



Boot Diagnostic - We can check why VM is not starting up with SS and logs
Run Commands - We can run commands on VM withut login into it
Redeploying - redeploy the VM on another physical host (Helpfull while physical server maintainance)
Availability Set: An unplanned event wherein the underlying infrastructure fails unexpectedly. The failures could be attributed to network failures , local disk failures or even rack failures.
   Fault domains - are used to define the group of virtual machines that share a common source and network switch. You can have up to 3 fault domains.
   Update domains - are used to group virtual machines and physical hardware that can be rebooted at the same time. You can have up to 20 update domains.
Availability Zones - This features help provides better availability for your application by protecting them from datacenter failures. Each Availability zone is a unique physical location in an Azure region.
Scale set - Used for manul and auto scling of virtual machine,
Flexible Orchestration - 
Scale set with custom script - can insall the applications on via cutom script in scale set instance because the new machine should have same application running on new launched servers.
VM Images :- Can create a new image with underlying virtual machine with apps and tolls installed on it for new creatng new VM with same services
   Specialized VM images - Keeps users and machine information as it is
   Generic VM Images - Rremoved the used and machine information and original VM in unusable
Proximitry placement groups - The VM are created in nerby hardware for bettter networ performance
Azure Web App Service - the entire physhical and virtual infra takes care by the MS Azure
Web app slots - It will create same app staing slot and for newer version of application then we can swap the to production and stgin as per need
App service autoscaling - we can scale manually(Standard) and automatically(premium pan) as per need


