# What is Hypervisor
- Hypervisor is piece of software or firmware that creates and run virtual machines.
- It also called **Virtual Machine Manager (VMM)** 
- There are two types of Hypervisor:
1. Type-1 Hypervisor (Bare Metal)
2. Type -2 Hypervisor (Hosted)

## Hypervisor Type-1
-  Also Known as Bare Metal.
- It directly run on system Hardware.
- A guest OS run on another level above the hypervisor.
- Type -1 acts as thier own OS.
- It is More Secure.
- Vmware ESXi is Type-1 Hypervisor that run directly on Sever(Machine) Hardware without depend on OS.
- ESXi provide a virtualization layer that abstract the CPU, Storage, memory and networking resources of the physical host(Hardware/Sever) into multiple virtual machines.
<img src="Images/t1.png?raw=true" alt="Type-1">

## Hypervisor Type-2
- Hypervisor that run on OS as an Application.
- It does not have direct acces to host hardware and recources.
- It is used as Testing and Learning Purpose.
- It is less secure
- Example: Vmware Workstation, Oracle Vmware, Microsoft Virtual PC..
<img src="Images/v2.png?raw=true" alt="Type-2">


## Difference Between Type-1 and Type-2 Hypervisor
<table>
  <tr>
    <th>Criteria</th>
    <th>Type-1</th>
    <th>Type-2</th>
  </tr>
  <tr>
    <td>aka</td>
    <td>Bare Metal</td>
    <td>Hosted</td>
  </tr>
  <tr>
    <td>Virtualization</td>
    <td>Hardware Virtualization</td>
    <td>Software Virtualization</td>
  </tr>
  <tr>
    <td>Operation</td>
    <td>Guest OS & Apps run on hypervisor</td>
    <td>Run as an application on Host OS</td>
  </tr>
  <tr>
    <td>Scalability</td>
    <td>Better</td>
    <td>Not Better</td>
  </tr>
  <tr>
    <td>System Independant</td>
    <td>It has direct access to hardware </td>
    <td>It does not direct access to hardware and resources</td>
  </tr>
  <tr>
    <td>Performance</td>
    <td>High</td>
    <td>Low</td>
  </tr>
  <tr>
    <td>Security</td>
    <td>More Secure</td>
    <td>Less Secure</td>
  </tr>
  <tr>
    <td>Example</td>
    <td>Vmware ESXi, Microsoft Hyper-V</td>
    <td>Vmware workstation, Microsoft VirtualPC</td>
  </tr>
  </table>

<br><br>

  This is about Hypervisor. In next day we will see Vmware Vsphere in detail.  [HERE ](day03.md)