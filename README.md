# windows-server Project Description <a href ="">Youtube demonstration </a>
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
  <li>Next we will set start our virtual machine (either by double clicking the machine or the power button next to it) and upon starting it, it will
    basically prompt us for an Operating System as our machine is on but we haven't given it an OS yet so what we will do is we will click on the 
    small icon denoting folders and navigate to where we stored our Server 19 ISO(that we downloaded earlier) and it will probably be saved under a different name
    and we will select it and have it as our disk image, and finallly we will press start.As shown in the series of images below.
   
   <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/fcdaf33d-0689-4484-a908-30cd42d1f510" height ="80%" width ="90%" alt ="Clicking on Icon folder">
   <br />
   <br />
   <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/05c4adc2-f5e1-436c-9bc8-80b4e32595a8" height ="80%" width ="90%" alt ="Clicking on the add button to navigate to the downloaded ISO">
   <br />
    <br />
    <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/05c4adc2-f5e1-436c-9bc8-80b4e32595a8" height ="80%" width ="90%" alt ="Clicking on the add button to navigate to the downloaded ISO">
   <br />
    <br />
    <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/718989d9-c010-46f3-aa9a-6fe9780f1646" height ="80%" width ="90%" alt ="Selecting your server 19 ISO">
   <br />
    <br />
    <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/9cc880a7-1b38-4c43-bcfb-4c3f963e9e91" height ="80%" width ="90%" alt ="Final stage in selecting ISO for your pc">
   <br />
    <br />
    <li>Next will be setting up the server and initial configurations, the first thing to note is the OS to pick should be Window's Server Standard Evolution 2019(Desktop Experience)
        <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/900f03a4-7411-40d6-8b76-7abc8ca3b64b" height ="80%" width ="90%" alt ="Clicking on Icon folder">
    </li>
  <br />
  <br />
   <li>Click on Next until you arrive at the window where you will be prompted for a pasword in the intial login and here place the password as  "Password1"(For ease.. but you should probably select a secure password)
        <img src="https://github.com/pauldoescyber/windows-server/assets/172483061/409a41fa-5e52-4567-8853-5046e2b5cd40" height ="80%" width ="90%" alt ="Initial login">
    </li>
  <br />
  <br />
     <li>Once you set the password to unlock your server you need to input control alt delete.However this won't be possible from your host machine, hence the way to do this is input>keyboard>insert control+alt+delete as shown below
        <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/a5c4e016-6a17-4dda-8b8c-5b2beba5204d" height ="80%" width ="90%" alt ="Entering your virual machine">
    </li>
  <br />
  <br />
  <li>The next step would be to install Virtual Box guest CD additions to make your user experience smooth,while you use the vm. To do this click on devices followed by insert Guest additions CD image.
        <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/924f759b-6a53-4e40-83b5-91435786b2bf" height ="80%" width ="90%" alt ="Installing Guest additions CD image">
    </li>
  <br />
  <br />
  <li>Double click and run Virtual box Guest additions.
        <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/07a2d90b-6f58-4b0d-9bb3-0d47ef31ca6d" height ="80%" width ="90%" alt ="Checking reboot manually option after CD image is installed">
    </li>
  <br />
  <br />
<li>Once the additonal cd image has finished runnig opt to manually reboot later. THis is because the restart now option did not effect the desired results.This is illustrated bellow.
        <img src="https://github.com/pauldoescyber/ActiveDirectoryLab/assets/172483061/1ecb376f-b98b-469e-9a4d-b4941f2b47d1" height ="80%" width ="90%" alt ="Checking reboot manually option after CD image is installed">
    </li>
  <br />
  <br />
  



