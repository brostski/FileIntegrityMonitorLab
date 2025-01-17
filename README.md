<h1>File Integrity Monitor Home Lab</h1>

<h2>Description</h2>
This script creates a File Integrity Monitoring (FIM) solution that establishes a baseline for monitored files and continuously tracks their integrity. It calculates hash values for target files and compares them to the baseline, notifying users of any changes, deletions, or potential integrity compromises.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows PowerShell ISE</b>
- <b>SHA-512 (via the hashlib library)</b>
- <b>File I/O (os module for file handling)</b>
- <b>Terminal color output (colorama library for notifications)</b> 


<h2>Environments Used </h2>


- <b>Windows 11</b>
- <b>Windows Powershell ISE</b>



<h2>Program walk-through:</h2>

<p align="center">
Baseline Collection: <br/>
<img src="https://i.imgur.com/SOPi6cu.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Baseline Monitoring:  <br/>
<img src="https://i.imgur.com/kg1YRQV.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
Hash Comparison Loop: <br/>
<img src="https://i.imgur.com/UFJoHjV.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
<br />
<br />
User Notifications:  <br/>
<img src="https://i.imgur.com/Rc8Lzmr.png" height="80%" width="80%" alt="Active Directory Lab Steps"/>
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
