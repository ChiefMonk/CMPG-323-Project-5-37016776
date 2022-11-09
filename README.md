
# CMPG 323 Project 5 : Reporting and Monitoring
<img src="https://github.com/ChiefMonk/CMPG-323-Overview-37016776/blob/main/nwu_logo.jpg" width="200px" style="text-align:center;float:center;" />

### Table of Contents
1. [Introduction](#intro) 
2. [Report Data](#data) 
3. [Data Visualisation](#visual)
4. [Contributors](#cont)
5. [References](#refs)

<a name="intro"></a>
## 1. Introduction
This is the fifth and final project of the CMPG 323 module deliverables. The Connected Office Initiative (COI) encapsulates the use of IoT devices within the network, placed all over the office building, to collect and share the data that these devices gather. The data can be shared in different ways. One of which is through visualisations built into a report or dashboard. The reports will be built in Power BI, an interactive data visualization software product developed by Microsoft with a primary focus on business intelligence.

<a name="data"></a>
## 2. Report Data
All the data included in this report is stored on the University's sharepoint server hosted at https://nwucloud.sharepoint.com/sites/CMPG323. The data was imported into Power BI by creating a live and secure data source connection and was appropriately mapped as follows:  

* Zone
    * ID
    * Zone Name
    * Zone Description

* Category
    * ID
    * Category  Name
    * Category  Description

* Sub Category
    * ID
    * Category ID
    * Sub Category Name
    * Sub Category Description

* Device
    * ID   
    * Device Name
    * Category ID
    * Zone ID
    * Status
    * Is Active	
    * Date Installed

<a name="visual"></a>
## 3. Data Visualisation
Using Power BI Desktop, a report named 'Connected Office – Device Monitoring' was created and the following visual reports, grouped by page, were developed and deployed at the Power BI service portal at https://app.powerbi.com/groups/me/reports/89fdee73-0e98-4200-ba93-603ddf012f58/ReportSection:

* High-Level Metrics
    * A summary view that shows business stakeholders a high-level view of the 'important' data.
    
* Device Monitoring
    * A visual that allows the user to monitor devices per category   
    * A visual that allows the user to monitor devices per zone
    * A visual that allows the user to monitor online versus offline devices (status should depict whether a device is online or offline)

* Device Registration
    * A visual that allows the user to see how many devices have been registered over a timespan   
    * A visual that allows the user to see how many categories
    * A visual that allows the user to see how many zones contain registered devices on a timeline

 The following filters were then applied to each page: 
   * Filter for users to filter the report based on device category
   * Filter for users to filter the report based on device platform
   * Filter for users to filter the report based on device zone
   * Filter for users to filter the report based on device registration date

<a name="cont"></a>
## 4. Contributors
* [Chipo Hamayobe (37016776)](https://github.com/ChiefMonk) - Project Lead

<a name="refs"></a>
## 5. References
### Reporting and Monitoring
* [Monitor and detect .NET exceptions](https://www.bugsnag.com/platforms/dotnet)
* [.NET Reporting](https://www.devexpress.com/subscriptions/reporting/)
* [Customize Your Reports With ActiveReports.NET](https://www.grapecity.com/activereportsnet)
* [Top 10 Benefits of .NET Reporting Tools](https://www.codeproject.com/Articles/5326032/Top-10-Benefits-of-NET-Reporting-Tools)
* [.NET Reporting and Dashboards](https://www.inetsoft.com/company/.net_reporting_and_dashboards)
* [.NET application performance monitoring template](https://learn.microsoft.com/en-us/system-center/scom/net-application-performance-monitoring-template?view=sc-om-2022)
* [.NET Application Performance Monitoring](https://www.manageengine.com/products/applications_manager/dot-net-application-monitoring.html)
* [Best 5 Tools for .NET Monitoring](https://stackify.com/best-5-tools-for-net-monitoring/)
* [.NET Performance Monitoring & Tracing](https://www.datadoghq.com/net-performance-monitoring/)
* [Confidently scale with .NET performance monitoring](https://newrelic.com/platform/application-monitoring/net)
* [.NET Error and Performance Monitoring](https://sentry.io/for/dot-net/)


### Power BI
* [Turn your data into immediate impact](https://powerbi.microsoft.com/en-cy/)
* [Go from data to insight to action with Power BI Desktop](https://powerbi.microsoft.com/en-in/desktop/)
* [Getting started with Power BI](https://powerbi.microsoft.com/en-in/getting-started-with-power-bi/)
* [Power BI Personal Portal](https://app.powerbi.com/home?cmpid=pbi-home-body-sta-free&noSignUpCheck=1)
* [Tutorial: Get started creating in the Power BI service](https://learn.microsoft.com/en-us/power-bi/fundamentals/service-get-started)
* [7 reasons to use Microsoft Power BI](https://www.stitchdata.com/resources/7-reasons-power-bi/)
* [How to use Microsoft Power BI - Tutorial for Beginners](https://m.youtube.com/watch?v=TmhQCQr_DCA)
* [Connecting Power BI to an Excel File Stored on Microsoft Teams, SharePoint or OneDrive as a Data Source](https://thejpanda.com/2021/03/18/power-bi-connecting-power-bi-to-an-excel-file-stored-on-microsoft-teams-sharepoint-or-onedrive-as-a-data-source/)
* [Connected Office Dataset.xlsx](https://nwucloud.sharepoint.com/:x:/s/CMPG323/EY0IBJY_mDxIlRBRTj-fiJkBJT4Cgd2qOHHzzyYECfhEnA?e=0a5VY8)
* [Power BI Custom Visuals - Timeline Storyteller](https://www.youtube.com/watch?v=fyyO2JmuNsg)
* [Power BI Tutorial for Beginners - Basics and Beyond](https://www.youtube.com/watch?v=AuYzsfXKkbM)
* [Introduction to Power BI](https://learn.microsoft.com/en-us/training/modules/introduction-power-bi/)
* [Bring AI to business users in your organization](https://learn.microsoft.com/en-za/training/paths/bring-ai-to-business-users-your-organization/)
* [Introduction to AI for business users](https://learn.microsoft.com/en-za/training/paths/introduction-ai-for-business-users/)
* [Explore what Power BI can do for you](https://learn.microsoft.com/en-za/training/modules/explore-power-bi-service/)
* [Power BI Tutorial](https://www.tutorialspoint.com/power_bi/index.htm)