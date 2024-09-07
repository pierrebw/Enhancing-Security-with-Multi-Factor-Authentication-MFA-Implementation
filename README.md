<h1>Managing MFA in Okta</h1>


<h2>Description</h2>
Implementing MFA in a home lab using Okta, which was installed and configured to better protect user accounts.
<br />


<h2>Environments Used </h2>

- <b>Okta</b> 

<h2>Walk-through:</h2>

<p align="center">
Added few users in Okta<br/>
<img src="https://i.imgur.com/4xSBdOj.png" height="80%" width="80%"/>
<br />
<br />
Created an MFA policy for the 'All Employees' group, requiring the use of Google Authenticator.<br/>
<img src="https://i.imgur.com/3IMettb.png" height="80%" width="80%"/>
<br />
<br />
Added Daniela Lock to the 'All Employees' group, which enforces the MFA policy.<br/>
<img src="https://i.imgur.com/7hKIm8P.png" height="80%" width="80%"/>
<br />
<br />
Tested logging in with Daniela's account and confirmed she was prompted to set up Multi-Factor Authentication.<br/>
<img src="https://i.imgur.com/BiY6Lga.png" height="80%" width="80%"/>
<br />
<br />
Verified that MFA works.<br/>
<img src="https://i.imgur.com/oMoXT3B.png" height="80%" width="80%"/>
<br />
<br />
Verified that Daniela was able to login.<br/>
<img src="https://i.imgur.com/JPEc8Sy.png" height="80%" width="80%"/>
<br />
