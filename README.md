<p align="center">
<img src="https://i.imgur.com/nBkHqaM.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />

<h1>How to Setup and Use a VPN | ProtonVPN</h1>


<h2>Description</h2>
This guide will show you, through the use of an Azure VM, how to setup and use a VPN, otherwise known as a Virtual Private Network.
<br/>


<h2>Environments and Utilities Used</h2>

- <b>ProtonVPN</b>
- <b>Microsoft Azure</b>

<h2>Project Walk-through:</h2>

<p align="center">
First, make an Azure VM: <br/>
<img src="https://i.imgur.com/kfDvsww.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Then go to https://whatismyipaddress.com to get your IP address and location. Keep this in mind, because we'll be using these later: <br/>
<img src="https://i.imgur.com/HFC2Kq8.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next, connect using Remote Desktop Connection:  <br/>
<img src="https://i.imgur.com/MlciCUt.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Once connected, go to the same IP website. Notice that the IP and location are different; this is because of the VM's set location (US West):  <br/>
<img src="https://i.imgur.com/OUA0Qqn.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Now, I can head over to ProtonVPN and sign up for a free account:  <br/>
<img src="https://i.imgur.com/o4fuKsp.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
After your account is made, download the Windows app:  <br/>
<img src="https://i.imgur.com/Uixhmx1.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Once it's installed, a pop-up will appear asking you to sign in with your account. After you do that, the main page where you can begin a VPN connection will appear:  <br/>
<img src="https://i.imgur.com/oTRNUsh.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Click on Quick Connect. It will automatically choose a random connection for you:
<img src="https://i.imgur.com/z1Gwtc0.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Refreshing the IP address website while connected should give you a new IP address and location. Here, instead of California, I'm in Washington:  <br/>
<img src="https://i.imgur.com/yn9xDec.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Using a VPN you can also go to different sites to see any differences, such as in languages. For example, entering www.disney.com on a Japanese VPN:  <br/>
<img src="https://i.imgur.com/BHbeXK4.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />

<h2>And that is how to set up a VPN!</h2>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
