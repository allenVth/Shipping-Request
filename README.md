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
__Domain__
1. Inside Github folder *Domain*, download the xml file.
2. After logged into instance, type in application navigator *Domain*.
  1. Under application *Domain Admin*, click module *Domains*
  2. On the column with label *Name*, right-click, then click Import XML. 
  3. Select file downloaded from *Domain* folder from Github.
