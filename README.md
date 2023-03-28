<p align="center">
<img src="https://cdn.pixabay.com/photo/2019/11/19/08/44/map-4636843_960_720.jpg" alt="Traffic Examination"/>
</p>

<h1>VPN Setup and Usage (ProtonVPN)</h1>
In this tutorial, we will create a virtual machine in azure and setup ProtonVPN to test connection and observe searching the web in a different counrty. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- ProtonVPN Setup


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)


<h2>High-Level Steps</h2>

- Step 1 - Sign into portal.azure.com
- Step 2 - Create a virtual machine. Then from your personal computer open up note pad then go to https://whatismyipaddress.com/ and take note of your IPv4 adress and location.
- Step 3 - With VM machine you just created start remote desktop to connect to virtual machine. In Azure go to virtual machines then get that virtual machines IP address and copy that IP address into the remote desktop control. To get to remote desktop connection, type remote in the search bar (if using pc) and click remote desktop connection.
- Step 4 - Connect to remote desktop. Once connected copy and paste the https://account.protonvpn.com/dashboard into the web browser. From there sign into proton vpn with your user name and password you created. Then go to downloads and download Proton VPN to the virtual machine you created and the Proton VPN app should be in the virtual machine desktop.  
- Step 5 - Go to Proton VPN app in your virtual machine. Sign in. Once signed in click Japan to connect. Refresh the https://whatismyipaddress.com/ tab and notice how the IP address changed and the region/city.
- Step 6 - Next go to nba.com and notice how the webpage now is in japenese. You dont have to pick Japan, you can pick anywhere you want. Pretty cool!
- Step 7 - make sure to delete your resourse group and virtual machine when done so you wont use all your free subscription.
<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/htTFmDA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Sign into portal.azure.com. After signing in look above to find Virtual Machines and click create Virtual Machines (VMs). 
</p>
<br />

<p>
<img src="https://i.imgur.com/WdiyvR1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create the Virtual Machine (VM) and make region something else other than your region/country. Keep tabs of the note pad that you wrote your original region/city and IPv4 address.
</p>
<br />

<p>
<img src="https://i.imgur.com/IbG0HwY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After creating virtual machine I made my region Norway east zone 1 with 4 vpu's with windows 10 pro.
</p>
<br />
<p>
<img src="https://i.imgur.com/ac1aPqe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Here is how it looks when you get to remote desktop connection. Paste the IP address from the virtual machine you just made. Connect to the virtual machine and from there type in https://whatismyipaddress.com/ and get the new IP address, region and city.
</p>
<br />
<p>
<img src="https://i.imgur.com/rXuMCr5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Once connected copy and paste the https://account.protonvpn.com/dashboard into the web browser. From there sign into proton vpn with your user name and password you created. Then go to downloads and download Proton VPN to the virtual machine you created and the Proton VPN app should be in the virtual machine desktop. 
</p>
<br />
<p>
<img src="https://i.imgur.com/MlsoL5K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Notice how before your IP address was different and it was from oslo Norway. Open the Proton VPN app and click connect to japan.
</p>
<br />
<img src="https://i.imgur.com/ijEPJmW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now go back to https://whatismyipaddress.com/ and refresh the page. Notice now the IP address is different now and now the region/city is Japan. 
</p>
<br /><img src="https://i.imgur.com/ufqxfo4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Open a new tab and go to nba.com to observe the website in japenese. Since your using a vpn from Japan, now when you surf the web everything will mainly be in japenese.
</p>
<br />
