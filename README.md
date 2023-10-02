# File-Sharing-and-Access 🫱🏻‍🫲 <p align="center">
<img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/3f104de9-b975-425a-8031-0edc0e3a69e8">
>
</p>

<h1>On-premises File Sharing w/Permissions(Windows)</h1>
This tutorial outlines the implementation of on-premises File Sharing within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy Network File-Sharing in Windows 10/11](https://www.youtube.com/watch?v=D_OsSGe9tNI)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Windows 10/11

<h2>Operating Systems Used </h2>

- Windows 10/11 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Enabling Network Sharing
- Sharing Files
- Permissions and Searching for Computer in Network

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/1dfdca70-ff41-446c-a19d-33b46984ac3a">
</p>
<p>
  <br />
  <img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/ed4e23b1-031f-4f26-8beb-b3eb5ba5bdf1">

  Type in Control panel in Windows seach bar and go into Network and Internet. Inside of network and internet go to change advanced settings. From there you change Network discovery and File sharing to On.  In All Networks turn on "Turn on sharing so anyone with network access can read and write files in public folders". Save changes and restart computer.
</p>
<br />

<p>
<p>
<img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/ecd93f41-96e5-48c0-9c21-c72741954f88">

</p>
<p>
<br />
<br />
  
<img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/3919ad64-014b-4060-afac-9b42fb1de11c">
<br />

  Right click file or folder and go into properties. In properties go into the sharing tab and click on "share" to see who has access to the folder. Add new users or remove them typing in their name or right clicking and hitting remove. On the right you can change permissions like read/write, no access or full access. 
</p>
<br />

<img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/97bc7dae-d37e-41fd-a91e-f4c84fd162b1">
<p>
<br />  
</p>


<img src="https://github.com/Klinsmannn/File-Sharing-and-Access/assets/146140975/3987773e-ba5c-4996-af6b-2623d5d97413">
</p>
<p>
 Right click file and go to properties to change permissions. In Securities tab go to Advanced and pick the group whos permission you want to change. Go into the search bar of your file explorer and look for the computer of the files you need and type in backslash twice with the computer name.    \\Computer Name
  
</p>
<br />
