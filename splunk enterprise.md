**Splunk enterprise tutorial**

Splunk Enterprise is a software product that enables you to search, analyze, and visualize the data gathered from the components of your IT infrastructure or business.
Splunk Enterprise takes in data from websites, applications, sensors, devices, and so on.
After you define the data source, Splunk Enterprise indexes the data stream and parses it into a series of individual events that you can view and search.
**Most users connect to Splunk Enterprise with a web browser and use Splunk Web to administer their deployment, manage and create knowledge objects, run searches, create pivots and reports, and so on**.
You can also use the command-line interface to administer your Splunk Enterprise deployment.

**#splunk has apps to integrate it with like virus total like kind of things but they are around 900 of them** 

An app is a collection of configurations, knowledge objects, views, and dashboards that runs on the Splunk platform. 
A single Splunk Enterprise installation can run multiple apps simultaneously. 
**Browse available apps on Splunkbase** or build your own on the Splunk developer site.
**Features of splunk** - **indexing, search, alert, dashboards, pivot , report, mdata model**
**Pivot**
Pivot refers to the table, chart, or data visualization you create using the Pivot Editor. The Pivot Editor lets users map attributes defined by data model objects to a table, chart, or data visualization without having to write the searches in the Search Processing Language (SPL) to generate them. Pivots can be saved as reports and added to dashboards.
SPLUNK ENTERPRISE USERS - 5  Admin, knowledge manager , user, pivot , developer
**Splunk Enterprise deployments**
As long as the machine that generates the data is a part of your network, Splunk Enterprise can collect the data from anywhere, whether the data is local, remote, or in the cloud.
**Splunk Enterprise performs three main functions as it processes data:**

It ingests data from files, the network, or other sources.
It parses and indexes the data.
It runs searches on the indexed data.
**Single-instance deployments**

**Distributed deployments**
To support larger environments where data originates on many machines, where you need to process large volumes of data, or where many users need to search the data,

In simple terms, a distributed Splunk setup divides the work into three main parts, and each part has a specific job to do:

1. **Data Input (Data Ingesting) Tier:**
   - **Job:** This part is responsible for getting the data into Splunk. Think of it as the "data collectors" that grab logs and information from different sources (like servers, apps, or devices) and send it to the next part for processing.
   - **Tool:** Splunk **Forwarders** are the data collectors.

2. **Indexer Tier:**
   - **Job:** Once the data arrives, this part organizes and stores it in a way that makes it easy to search later. It's like taking messy information and turning it into something searchable, like creating a database of logs.
   - **Tool:** The **Indexer** is where the data is processed and stored.

3. **Search Management Tier:**
   - **Job:** This is the part where you run searches and generate reports on the data. It allows you to ask questions like "What happened on my system last night?" and get answers based on the data collected and stored.
   - **Tool:** The **Search Head** handles search requests and shows the results.

### To summarize:
- The **Forwarders** collect data.
- The **Indexers** organize and store that data.
- The **Search Head** helps you find and analyze that data.

In a big setup, these parts are often separated onto different machines to handle lots of data more efficiently.
**Secure Splunk Enterprise**
**Authenticate users and edit roles	
Secure Splunk data with SSL	
Audit Splunk Enterprise	
Use Single Sign-on (SSO) with Splunk Enterprise	
Use Splunk Enterprise with LDAP	**




