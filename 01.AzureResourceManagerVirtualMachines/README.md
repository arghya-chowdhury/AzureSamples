<h2> Azure Resource Manager Template for Azure Virtual Machines </h2>
The folder contains an azure arm template which can be used to provision two vms and a load balancer to divert traffic in round robin fashion.
Once provisioned you can go to the individual Windows Server VM and install IIS and change the default IIS home page located in inetpub/wwwroot.
Now if you hit the load balancer public ip, you will notice that load balancer manages the traffic.

<a href="https://azuredeploy.net/" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>
<a href="http://armviewer.azurewebsites.net/view?url=https%3A%2F%2Fraw.githubusercontent.com%2Farghya-chowdhury%2FAzureSamples%2Fmaster%2F01.%2520AzureResourceManagerVirtualMachines%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

![Network](https://github.com/arghya-chowdhury/AzureSamples/blob/master/01.AzureResourceManagerVirtualMachines/Network.png)


