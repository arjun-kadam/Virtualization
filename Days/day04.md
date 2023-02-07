# Migration In Virtual Machines
- It is technique of moving a virtual machine from one host to another host or from one datastore to another.

```
    Migration
        |
        |
        |----- Cold Migration
        |
        |
        |----- Suspended Migration
        |
        |
        |----- V-motion
        |
        |
        |----- Physical to Virtual (P2V)
        |
        |
        |----- Virtual To Virtual (V2V)
```
>Note: DataStore stores VM files, Logfiles, Virtual disk & ISO Images
<hr>

## Cold Migration
- Movement of virtual machine to another host in **Powered-OFF** state.
- VM must be powered-off during migration.
- Cold migration are flexible than Vmotion.
- Can be used to move a VM between data centers, as longer both data centers are on the same Vcenter Server instances.
- Chances of Failure is less.

## Suspended Migration
- Migrating a VM that is in **Suspended state.**
- Suspended state is like Paused state in which you resume from same point on later stage.
- Suspended & Vmotion migration are considered as HOT because in both case VM is in running state.
- Primary reason to suspend a VM on an ESXi host is troubleshooting.

## Vmotion
- Vmotion is part of Vmware Vsphere Suit.
- Migrating a VM that is in **Powered ON** state.
- This is very useful as it this does not cause any down time for the VM.
- Vmotion moves a running VM to a Different ESXi host the same cluster (Predifned Group Of ESXi Hosts)
- It is also Known as **Live VM Migration**
- In Vmotion machine is migrated from one ESXi host to another in Powered ON state, Whereas in Storage Vmotion machine is migrated from one datastore to another datastore in Powered ON state.

## Physical to Virtual (P2V)
- Convert physical computer to virtual one.
- eg. You have a webserver running in physical hardware then you can run Vmware Vcenter Converter, target the webserver and have a copy of the physical server created on an ESXi Host.

## Virtual to Virtual (V2V)
- Migration are exactly like P2V migration except that the source of machine is already virtual machine.
- eg. Migrating from Microsoft Hyper-V to Vmware ESXi would be considered a V2V migration.

<hr>

This is for today. Now on next & last day we will see about [High Availibility](day05.md)