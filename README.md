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

- <b>Dashboard Creation and Visualization</b>: Built a custom Splunk dashboard showcasing key metrics using tables, charts, and graphs. Demonstrated ability to translate raw data into meaningful visual insights, strengthening reporting and monitoring skills.


<h2>Program walk-through:</h2>

<p align="center">
Uploaded sample data into Splunk and confirmed indexing: <br/>
<img src="Sample Data Upload .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Identified the most frequently accessed web pages using SPL query:  <br/>
<img src="Generating Security Events on Kali.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Displayed a breakdown of HTTP status codes to monitor server health: <br/>
<img src="Log Analysis.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Visualized web traffic trends and HTTP status codes over time: <br/>
<img src="Custom Query.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<br />
<br />
Listed the top five client IP addresses by request volume:  <br/>
<img src="Dashboard.PNG" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<br />
<br />
Created a dashboard combining all panels for centralized analysis:  <br/>
<img src="dashboard first half.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="dashboard second half.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
