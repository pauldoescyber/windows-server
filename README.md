# windows-server Project Description
This projects involves setting up a windows server on your virtual machine using oracle virtual box. The windows server can then be configured for DNS services , DHCP, AD DS and many more things. In the project linked here we follow through similar steps  but we configure the server for many of these services and also create a domain of 
users that will use the server we have set up for DNS, DHCP amongst other services. For this project however we will review how to set up the windows server on oracle virtual box.
<br />
<br />
# Project overview and summary
<img src="https://github.com/pauldoescyber/windows-server/assets/172483061/77c1fab5-583d-4ce9-8255-36e5188bb287" height ="80%" width ="80%" alt="Overview of the project">
<br />
<br />
<li>
  The first thing to do is download <a href="https://www.virtualbox.org/wiki/Downloads">virtual box</a> depending on the version of
 your OS <br/>
<img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/ac28e79d-b991-48b2-a4f5-41fe060cc252" height="80%" width="80%" alt="Downloading virtual box"/>
</li>
<br />
<br />
<li>
  Next we will download <a href ="https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019">Windows server 2019 ISO. Basically downoading the server. </a>   <br/>
<img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/1e6a9319-74ac-4a84-8076-e31fdd23b719" height="80%" width="80%" alt="Downloading Windows server 2019"/>
</li>
<br />
<br />
<li>Open virtual box and name your Virtual Machine DC or anything you really want  it really doesn't matter.Also while in this window ensure the version section is selected as Other Windows
   <img src="https://github.com/pauldoescyber/windows-server/assets/172483061/8c22deea-c303-4bf8-8445-b64c6135240b" height ="80%" width ="90%" alt ="Naming your domain controller">
  </li>
  <br/>
  <br />
  <li>Next is RAM allocation here it depends on your device..  for me with 8GB of ram I decied to allocate 2GB of RAM to my Windows server.
   <img src="https://github.com/pauldoescyber/windows-server/assets/172483061/a3ea5ea0-ad19-4f55-be89-095739043bce" height ="80%" width ="90%" alt ="RAM ALLOCATION">
  </li>
  <br />
  <br />
  <li>
    Next we will carry out processor allocation,depending on your computer's capabilities you will assign a number of cores to your virtual machine
    for me I assigned 2 cores out of a  possible 8 which worked well for me.To do this go to Settings > System > Processor.
   <img src="https://github.com/pauldoescyber/windows-server/assets/172483061/d362bf04-0ea5-4423-8c98-08f491fd2bbb" height ="80%" width ="90%" alt="Allocating the number of processors">
  </li>
  <br />
  <br />
  <li>Next we will set start our Domain controller/DC (either by double clicking the machine or the power button next to it) and upon starting it, it will
    basically prompt us for an Operating System as our machine is on but we haven't given it an OS yet so what we will do is we will click on the 
    small icon denoting folders and navigate to where we stored our Server 19 ISO(that we downloaded earlier) and it will probably be saved under a different name
    and we will select it and have it as our disk image, and finallly we will press start.As shown in the series of images below.
   
   <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/fcdaf33d-0689-4484-a908-30cd42d1f510" height ="80%" width ="90%" alt ="Clicking on Icon folder">
   <br />
   <br />
  



