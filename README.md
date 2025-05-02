<h1>Splunk Log Analysis Lab</h1>


<h2>Description</h2>
In this lab, we set up a hands-on project using Splunk Enterprise to analyze web server logs. We ingest sample data into Splunk, perform search queries to explore the data, and build dashboards to visualize key metrics. This exercise demonstrates practical experience with Splunk’s core functions, providing a solid foundation in log analysis, visualization, and security monitoring.<br />


<h2>Languages and Utilities Used</h2>


- <b>Splunk Enterprise</b>
- <b>Search Processing Language (SPL)</b>

<h2>Environments Used </h2>

- <b>Splunk Enterprise (local install)</b> 

<h2>Takeaways</h2>

- <b>Splunk Configuration and Data Ingestion</b>: Successfully installed and configured Splunk Enterprise, ingested sample log data, and verified data indexing. Demonstrated familiarity with Splunk’s interface, data inputs, and indexing workflow.

- <b>Search Query Development and Analysis</b>: Gained hands-on experience writing SPL queries to explore, filter, and summarize log data. Developed proficiency in identifying top accessed pages, monitoring HTTP status codes, and analyzing traffic patterns over time.


- <b>Visualization and Alerting in SIEM</b>: Developed a custom dashboard in Elastic SIEM to visualize security events, demonstrating skills in data interpretation and pattern recognition. Successfully created and tested alert rules for detecting specific security events, showing competency in proactive incident response and alert management.


<h2>Program walk-through:</h2>

<p align="center">
Connecting to the Elastic Beats agent in order to receive data from Kali VM: <br/>
<img src="Agent Verifed Connection.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating security events using nmap for the SIEM to pick up on:  <br/>
<img src="Generating Security Events on Kali.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log analysis: <br/>
<img src="Log Analysis.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Custom query for nmap: <br/>
<img src="Custom Query.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<br />
<br />
Dashboard containing security events:  <br/>
<img src="Dashboard.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<br />
<br />
Alert to detect security events via email:  <br/>
<img src="Email Alert Setup.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
