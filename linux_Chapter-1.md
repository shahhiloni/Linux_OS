-------------------------  Chapter - 1 - Visualization with hypervisor -------------------

1. Visualization Technology with hypervsior 
- Hypervisor : A hypervisor in linux is a software layer (or sometimes hardware  + software) that allows you to run multiple operating systems (called virtual machine or VMs) on a single physical computer at the same time. 

- divided physical system resources (RAM, CPU, Storage)
- allocates them to multiple virtual machines (VMs)
- manage their execution independently 

2. why do we need a Hypervisor
- Because without a hypervisor, only one OS can run on a machine at a time
- For example only linux or only windows or only macOS

- with a Hypervisor, you can run: 
linux + windows + Mac(as virtual machine)

- multiple linuxx servers for testing 
- isolated environments for development

3. Types of Hypervisor 
    1. Bare metal (Hardware): Runs directly to an hardware without a Host OS 
    Ex: KVM (linux), Microsoft Hyper - V, VM ware ESX, etc..

    2. Hosted : Installed on top of a host operating system 
    Ex: VirtualBox, VM ware workstation, etc..




