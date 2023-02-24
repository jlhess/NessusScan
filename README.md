<h1>Vulnerability Scan</h1>


<h2>Description</h2>
Project consists of noncredentialed and credentialed vulnerability scans using Nessus against a Windows 10 VM in different states. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>Nessus</b> 
- <b>VMware</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Proof of Concept:</h2>

<p align="center">
Noncredentialed scan: <br/>
<img src="https://i.imgur.com/YAccg4R.png" height="80%" width="80%" alt="NessusScan"/>
<br />
<br />
Credentialed scan:  <br/>
<img src="https://i.imgur.com/jPLY3gZ.png" height="80%" width="80%" alt="NessusScan"/>
<br />
<br />
Credentialed scan after installing a deprecated version of Firefox (3.6.12): <br/>
<img src="https://i.imgur.com/uegqEUD.png" height="80%" width="80%" alt="NessusScan"/>
<br />
<br />
Final credentialed scan after uninstalling deprecated software and installing Windows updates:  <br/>
<img src="https://i.imgur.com/9ABE06Q.png" height="80%" width="80%" alt="NessusScan"/>
<br />
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
