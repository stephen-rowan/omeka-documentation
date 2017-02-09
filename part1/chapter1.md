# Setup Virtual Machine

In VirtualBox 5.1 :

File-&gt;New

| Name and Operating System |  |
| :--- | :--- |
| Name | YOUR-VM-NAME |
| Operating System | Linux |
| Version | Ubuntu \(64 bit\) |
|  |  |
| Memory Size | 1024 MB |
|  |  |
| Hard Disk | Create a virtual hard disk now. |

---

| Create virtual hard drive |  |
| :--- | :--- |
| File location : | YOUR-VM-NAME |
| File Size : | 8.00 GB |
| Hard Disk type : | VirtualBox Disk Image |
| Storage on Hard Disk : | Dynamically Allocated |


## Configure Virtual Machine

### Settings-&gt;System-Processor 

|  |  |
| :--- | :--- |
| Processor\(s\) | 2 |
| Extended Features  | Enable PAE/NX [^1] |

### Settings-&gt;Storage

In the Storage Settings go to Attributes->Optical Drive and load  an Ubuntu Server ISO image [^2].

### Network

Configure Port-forwarding

Network -> Adapter 1 -> Advanced -> Port Forwarding

| Name | Protocol | Host IP | Host Port | Guest IP | Guest Port |
|:--- |:--- |:--- |:--- |:--- |:--- |    
| HTTP | TCP      |         |      8080 |          |         80 |
| SSH  | TCP      |         |      2221 |          |         22 |

### Shared Folders

Create a shared folder on your desktop to transfer files to virtual machine ...

/home/[name]/Desktop/[VM Name]

* Uncheck Read-Only
* Select Auto-Mount

--

[^1]: Physical Address Extension (PAE) The processor must be running in Physical Address Extension (PAE) mode to use the NX processor feature. PAE is a processor feature that enables x86 processors to access more than 4 GB of physical memory on capable versions of Windows.

[^2]: ubuntu-16.04.1-server-amd64.iso used in this install



