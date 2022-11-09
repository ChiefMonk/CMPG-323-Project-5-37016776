
# CMPG 323 Project 5 : Testing and Robotic Process Automation (RPA) with UiPath
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
Using Power BI Desktop, a report named 'Connected Office – Device Monitoring' was created and the following visual reports, grouped by page, were developed and deployed at the Power BI service portal:

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
### Software Testing
* [Testing in .NET](https://learn.microsoft.com/en-us/dotnet/core/testing/)
* [Test Driven Development](https://deviq.com/practices/test-driven-development)
* [Unit testing best practices with .NET Core and .NET Standard](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-best-practices)
* [Unit testing C# in .NET Core using dotnet test and xUnit](https://learn.microsoft.com/en-us/dotnet/core/testing/unit-testing-with-dotnet-test)
* [What is User Acceptance Testing (UAT)? Examples](https://www.guru99.com/user-acceptance-testing.html)
* [What Is User Acceptance Testing (UAT): A Complete Guide](https://www.softwaretestinghelp.com/what-is-user-acceptance-testing-uat/)
* [User Acceptance Testing and the Application Lifecycle](https://www.red-gate.com/simple-talk/development/dotnet-development/user-acceptance-testing-application-lifecycle/)
* [What is Automation Testing? Test Tutorial](https://www.guru99.com/automation-testing.html)
* [Automated software testing](https://www.atlassian.com/continuous-delivery/software-testing/automated-testing)
* [Connected Office: Device Management](https://connectedoffice-devicemanagement.azurewebsites.net/)
* [CMPG-323-IOT-Device-Management](https://github.com/JacquiM/CMPG-323-IOT-Device-Management)


### Robotic Process Automation (RPA) with UiPath
* [UiPath Website](https://www.uipath.com)
* [Robotic Process Automation (RPA)](https://www.uipath.com/rpa/robotic-process-automation)
* [Introduction to RPA and Automation (Course)](https://academy.uipath.com/courses/introduction-to-rpa-and-automation)
* [UI Automation with UiPath](https://docs.uipath.com/studio/docs/ui-automation)
* [Excel Automation with UiPath Studio](https://www.uipath.com/learning/video-tutorials/excel-datatables-automation)
* [UiPath Automation Cloud Account](https://platform.uipath.com)
* [Introduction to UiPath Portal, Orchestrator & Studio](https://www.youtube.com/watch?v=BAYmmUuB2Zo)
* [How to Calculate and Update Data within an Excel Workbook in UiPath](https://www.youtube.com/watch?v=-w8rorapLS8)
* [UIPath read excel and enter the data into web forms](https://www.youtube.com/watch?v=lw6bxrMNzfM)
* [How to Automate a Website Login with UiPath Studio](https://www.youtube.com/watch?v=030dEAB8oyg)
* [UiPath - Use Application/Browser Activity| Modern Activity in UiPath | Open Browser & Application](https://www.youtube.com/watch?v=s1InnQCymPA)
* [UiPath Community Forums: Find A Chapter](https://community.uipath.com/chapters/)
* [How to Open Browser and Login with UiPath - Full Tutorial](https://www.youtube.com/watch?v=wk2PBLU3mg0)
* [UiPath RPA Beginners Tutorial - 2020](https://www.youtube.com/watch?v=3ZKzTHdpsTs)
* [How to get the entire row based on the cell value in UiPath](https://forum.uipath.com/t/how-to-get-the-entire-row-based-on-the-cell-value-in-uipath/193445/3)
* [UiPath Studio: Your First Process Automation](https://www.youtube.com/watch?app=desktop&v=OyQAhrcBr9U)



