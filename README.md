# munch
munch - Mobile Application Project (iOS)

Requirements

Software Requirements Specification

project: munch - iOS Mobile Application
team: Aid Idrizović, Morgan Rose, Mohammad (‘Irf’) Khan
school: Loyola University Chicago
date: 02/29/2016
version: 0.0.3

Table of Contents

Introduction
purpose
platform
scope
Description
background
software & UI
dependencies
target audience
Usage
interaction
product market
user
geographic
benefits of use
Future
force touch implementation
WatchOS application
beacon expansion
server api
Appendix 












I. Introduction
I.A. Purpose
	The purpose of this mobile application is to provide a convenient, on-the-go medium for community engagement through anonymous geotagging. 

I.B. Platform
 	The platform served is the Apple iPhone market with devices on iOS 8.0 and above. 

I.C. Scope
	The scope will be limited to Apple iPhone users that are motivated to engage with their geographic, local community through this mobile application. 

II. Description
II.A. Background
	The initial idea for this project began in January 2015 but was disbanded due to insufficient resources. The project came back to fruition on February 29, 2016 in a software engineering course instructed by George K. Thiruvathukal at Loyola University. The name for the project, munch, was the original name when the project was food-based and has been preserved for historical significance. 

II.B. Software & UI
	The software for the mobile application will be built primarily on Apple’s Swift Language using Apple’s Xcode IDE. A [insert type] database will be created to manage geotag information and statistics, for current and future implementations. User inputs, which also can be referred to as beacons, will be stored under the latitude and longitude of the tagged location, rounding to 4 digits past the decimal point. This will allow us to maintain an accuracy of 11 meters and more importantly will allow us to manage our database in a more efficient and effective manner. The application will be map-based, requiring the user’s location. Notifications can be turned on or off, depending on the user’s preference. When notifications are on, the application will check randomly, once per day, to see if you are less than .5 mile away from an active beacon and alert you accordingly.

II.C. Dependencies
 	The dependencies for this project include software from Apple. [Insert database dependencies] 

II.D. Target Audience
	Our target audience is Apple iPhone users that value the importance of community.

III. Usage
III.A. Interaction
	Upon downloading the application, the user will be instructed to enter their email. The email will only be used for user identification. The same email can only be logged in on one device and there is no log out button. Deleting the application will allow the user to start using a new email or log into another device. After the login screen, the user will be presented slides of instructions on how to use the application and the slides must be swiped to the end in order to access the main screen. The main screen will debut an interactive map that shows all the active beacons and also allows the user to set new beacons. Users can set 10 unique beacons and/or replenish 10 existing beacons for every 24 hours. To set a beacon, the user must press and hold down on a location for 2 seconds. Beacons are set on a 12 hour timer that can be replenished. To replenish a specific beacon, another unique user must tap and hold the beacon for two seconds. The user can also simply tap the beacon to get more information on the beacon. To access the notifications screen, the user must tap on the ‘i’ icon in the top right corner of the main screen. There the user can turn their notifications on or off. When the user is done, they click on the ‘Done’ button on the top right corner and it will take them back to the main screen. 

III.B.1. Product Market - User
 	The user market is the Apple iPhone community.

III.B.2. Product Market - Geography
	The geographic focus is highly populated urban areas.

III.C. Benefits of Use
	The benefits of using this application, is that it will allow to build and foster stronger offline communities among particular geographic locations. 

IV. Future
IV.A. Force Touch Implementation 	
Force Touch is a feature developed by Apple that senses the level of force exerted on an iPhone and responds respectively. A feature that Force Touch enables iPhone users to have is the ability to interact with applications without opening the actual application. To create a greater ease of use, we can utilize that feature and allow users to submit and/or refresh beacons, which will automatically be determined through obtaining the user’s location.

IV.B. WatchOS Application
For additional ease of use, an Apple WatchOS application can be created to complement the iPhone application. 

IV.C. Beacon Expansion
	As it stands, there are only support beacons available to users. However with the broader definition of the project, beacons can also be expanded to promote other community engagements. 

IV.D. Server API
	Since we will be collecting a plethora of data on communities, it would only be fair to be able to give it back to the communities. To accomplish this, we would create application program interface (API) that will allow anyone to access our data. 

V. Appendix
V. 	Will add later.
