# What is Virtualization ?
- Let's Understand With the help of Example **Why We Need Virtualization ?**
> - A person name Guatum Adani has a very passion about online bussiness. 
> - So he built an On-premises Infrastruture for his online company like he took a 10 computers of 4GB RAM,2 Core, 500GB SSD each so Total Capex(Capital Expenditure) is 10 Lac.
> - Also For those computers he need Electricity, Cooling Room and Security that means Opex(Operational Expenditure) is 50K/Month.
> - He create DNS server, DHCP Server, AD Server, Billing Server ... etc etc on that 10 computers.But billing server is used at month end only so reamaining days billing sever is useless and also at the time of festival DNS server is unreachable so many problems he faced.
> - His bussiness become very successful in early time. But He don't know about **Early Success is Scam**.
> - The company called ***Hindenburg Research*** did some bussiness expose against adani and his bussiness falls down very quickly.
> - his cost of computers and maintainance remains same. He become helpless.
> - So He Called Engineer **Arjun Kadam** For Help
> - Arjun Sold all computers at price 6 Lac and bought only 1 PC of 32GB RAM, 24 core ,2TB SSD in the price of 5 lac.
> - He did Virtualization and make 10 virtual machines of as each server needed.
> - So he also saves Capex and Opex.
> - Now We need to understand how he did **Virtualization** ?

- Virtualization is technique of splitting or adding physical resources into as many logical recources.
- Virtualization is technology that transform Hardware into Software.
- That actually means If you have Hardware (Physical Recources) of 4GB RAM then with the help of Virtualization you can divide it into 2-2GB logically.
- Every Virtual Machine work as single entity.
- Every machine in virtualization feels that only that machine is using hardware resources but actully resources are splitted logically.
- They don't have direct access to another machine.
- Let's Understand with the help of Graphics.

<img src="Images/BV.png?raw=true" alt="Before  Virtualization">
<img src="Images/AV.png?raw=true" alt="After Virtualization">

<br>

- With the help of Hypervisor we can do Virtualization.
## Advantages Of Virtualization
- High Availability.
- Reduce Cost (Opex + Capex).


On [Day 2](day02.md) we are going to see about **Hypervisor.**

