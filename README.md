# Shipping Request

## Description
Project *Shipping Request* was created so end user can specify the methods their request will travel and type of mail delivery.

## Technologies Used
* ServiceNow
* Workflow Editor
* Service Portal

## Features
* Checks either individual or group tasks status to decide how to proceed to workflow.
* Loops eventqueue *trigger notification* from how much end user requested.
* Autopopulates fields, modify mandatory and visibility status of variables based on user input.

## Getting Started
* Create an account in [ServiceNow](https://developer.servicenow.com/dev.do)
* Order an instance. After obtaining the instance, copy the created password down so you can modify it later inside the instance.

___Domain___
1. Inside Github folder *Domain*, download the xml file.
2. After logged into instance, type in application navigator *Domain*.
    1. Under application *Domain Admin*, click module *Domains*
    2. On the column with label *Name*, right-click, then click Import XML. 
    3. Select file downloaded from *Domain* folder from Github.
    
___Update Set___
1. From the folder *Update Sets* download the xml file.
2. In the instance, type in the navigator *update sets*
    1. Click the module *Retrieved Update Sets*.
    2. Click the link *Import Update Sets from XML*.
    3. A new record will show up, open it.
    4. Click *Preview*.
    5. If no errors show up, click *commit update sets*.
3. To switch domain, click the gear symbol on the upper right of the screen.
4. On *General*, there's the domain scroll-bar, switch to *Cognizant*
    
___Service Portal___
1. Back in the instance, in the navigator type *Maintain Categories*.
2. Search for *facilities* categories. 
3. Open it and change active to on.
4. To enter SP, substitute the * with your instance's number: https://dev*****.service-now.com/sp.
5. Click on *Request Something*. 
6. Select *Facilities* category and search for *Project2*
