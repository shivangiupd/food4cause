# Food4Cause

## Contents

1. [Short description](#short-description)
1. [Demo video](#demo-video)
1. [The architecture](#the-architecture)
1. [Project roadmap](#project-roadmap)
1. [Authors](#authors)

## Short description

### What's the problem?
Millions of workers have fled from large towns and cities after they lost their jobs during the lockdown. The local governments may be rolling out broad programs. Despite the claims of the administration, 
ration and community kitchen meals are still not reaching those that need them the most. 

The cooperation at the local level is usually the most effective way of getting help. In the current crisis, we have  seen shortages of  food, medicines, cloths and other supplies.

### How can technology help?

As a solution we thought of a mobile application to coordinate residential association and voluntary organization .If they can provide food, supplies, medicines, or other essentials, they can use the mobile application and fill out a brief form that indicates what they are willing to donate and available quantities along with the location. This information is then stored  in the IBM Cloud database.

A Recipient or Volunteer, who is in need of food, supplies or other essentials, can enter the details of the items in the mobile app. The mobile application will do an internal search and match the  items already available in the donors list based on the location and send the notification to the donors. 

If the donor or association accepts the request they can collect the items and deliver it to a common point(If its an apartment near the security gate) and update details in mobile app. The app then notify this details to the recipient /volunteer and they can collect the items from the updated location.

### The idea
 - A Supplier opens the mobile application and fills out a brief form on what they can donate and there location.
 - This information is then stored in IBM Cloudant database.
 -  The Recipient/Volunteer launches the mobile app and fill the form on the requirement and the location.
 - The app tries to match the requirement against the stock based on location.
- If  the requirement matches with stock a notification will go to the supplier with the requirement.
- If the supplier accepts the request, he can fill the details(how much he can supply,    the date , location and time)
- This information will go to the recipient as a notification.
- The recipient can collect the items from the location on that particular time

## Demo video

![Watch the video](https://youtu.be/DdcYOnDTofM)

## The architecture

![Architecture](https://github.com/shivangi2416/food4cause/blob/master/SolutionArchitecture_Food4Cause.png)

- The Recipient user launches the mobile app and can access information across multiple services.
- The Recipient user can ask questions to Watson Assistant and get answers on food/service availability questions.
- The Supplier user can post the availability of resources they can provide, as well as locate the items they need.
- The Recipient user can obtain geolocation data to plot routes to collect (or drop off) supplies using HERE Location Services.


## Project roadmap

![Roadmap](https://github.com/shivangi2416/food4cause/blob/master/SolutionRoadMap_Food4Cause.png)

## Built with

* [IBM Cloudant](https://cloud.ibm.com/catalog?search=cloudant#search_results) - The NoSQL database used
* [IBM Cloud Functions](https://cloud.ibm.com/catalog?search=cloud%20functions#search_results) - The compute platform for handing logic
* Register for an IBM Cloud account.
* Install and configure IBM Cloud CLI.
* Register for a HERE account.
* Install React Native CLI dependencies (for iOS).
* Node.js
* Watchman
* Xcode
* CocoaPods

## Authors

List of contributors
 ##### Karthika M Nair
 ##### Shivangi Upadhyay
 ##### Paridhi Agarwal
 
