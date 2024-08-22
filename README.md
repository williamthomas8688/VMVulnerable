# Vulnerability Management W/ Nessus

This tutorial outlines the setting up vulnerability scanning and vulnerability remediation.<br />

<h2>Environments and Technologies Used</h2>
- Microsoft Azure Virtual Machines
- Nessus 
- Windows 11 
- Azure Resource Group


Create a resource group for the virtual machines

Create a the first VM (This VM will have nessus ans be device doing the scanning)

Login into the VM

Go to ("https://www.tenable.com/products/nessus/nessus-essentials") and install nessus

Create the second VM and allow all inbound port traffic

Remote into the second VM, search for "wf.msc"

Go back to the first VM and open nesssus > Then add the IP address of the second VM and run a basic network scan

# ------------------

Then check for vulnerabilities and remediate 

Then run a second scan after remedation and nessus should have no activites or vulnerabilities 


<h2>Deployment</h2>

<p align="center">
<img src="https://i.imgur.com/tsDbFGE.png" alt="Creation Of Resource Group"/>

</p>
<br />


<p align="center">
<img src="https://i.imgur.com/EEvXek2.png" alt="Creation Of VM"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/rWKr5ef.png" alt="Login into VM and go to the nessus lank and sign up"/>

</p>
<br />


<p align="center">
<img src="https://i.imgur.com/YDn0qcl.png" alt="Create the second VM and make it vulnerable > Go to wf.msc and turn off all firewalls in the VM > Then download a old version of firefox"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/yX4h2ln.png" alt="Then add the IP address into Nessus, and run a basic network scan"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/O5xHP6G.png" alt="Then View the Vulnerablities"/>
</p>
<br />

<p align="center">
<img src="https://i.imgur.com/st10WMN.png" alt="Turn on firewalls, delete old version of firefox, then run windows update"/>

</p>
<br />

<p align="center">
<img src="https://i.imgur.com/879XzT8.png" alt="Then run another network scan, scan should comeback empty due to it being no vulnerabilities"/>

</p>
<br />
