# High Availability (HA)
- In High Availability when the hist crashes or fails the VM gets restarted on another host.
- So there is very samll down time for restsrting VM.
- It provide automatic sever failure detection.
- HA is complete automated process.
- No passive standby ESXi host is require neither any extra VM (No Need Backup)
- HA does not use Vmotion
- Enable HA on the cluster setting in order to use HA.
<img src="Images/HA.png?raw=true" alt="High Availability ">


- For HA, We need following:
  - Cluster - Group of ESXi Host
  - Shared Storage
  - Vcenter server configured for the environment
  - Resource check - capacity check (It keep reserve space for HA)

  <hr>
  
  Thisis basic guide about HA.There is many more available on Internet so keep exploring. Here I am finishing Virtualization If you want to learn more then you can learn from YouTube and other resources for FREE. <br>
  Happy Learning !!!!!