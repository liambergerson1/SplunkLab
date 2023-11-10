<h1>SIEM: Querying Logs with Splunk</h1>

<h2>Description</h2>
Splunk is a popular Security Information and Event Management (SIEM) tool that can query log files in order to discover potential data breaches. In this lab, I will import a log data file and query the logs within Splunk to determine if there are any potential data breach attempts. We are more notably searching for failed account access attempts to root.
<br />

<h2>Environments Used</h2>

- <b>Splunk Cloud</b>


<h2>Lab Walkthrough</h2>

<p align="center">
Splunk home page: <br/>
<img src="https://i.imgur.com/yFWIkx4.png" height="80%" width="80%" alt="Splunk Lab"/>
<br />
<br />
Add log data File:  <br/>
<img src="https://i.imgur.com/FrLPx9R.png" height="80%" width="80%" alt="Splunk Lab"/>
<br />
<br />
Log data index:  <br/>
<img src="https://i.imgur.com/zpKOJai.png" height="80%" width="80%" alt="Splunk Lab"/>
<br />
<br />
Setting the host as "mailsv" for the mail server:  <br/>
<img src="https://i.imgur.com/niKisfo.png" height="80%" width="80%" alt="Splunk Lab"/>
<br />
<br />
Narrowing search to failed access attempts for root:  <br/>
<img src="https://i.imgur.com/uLUgTNE.png" height="80%" width="80%" alt="Splunk Lab"/>
<br />



