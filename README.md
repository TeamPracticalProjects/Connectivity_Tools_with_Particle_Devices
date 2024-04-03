# Connectivity_Tools_with_Particle_Devices
Document describing the IoT connectivity tools and techniques that we use with Particle devices.

*NOTE:  As of April 2024, the Google Apps Script line "EmailApp.sendMail(...);" seems to be treated by
receiving services as spam.  Changing this line to "GmailApp.sendMail(...);" appears to work.  After
changing this line in an alarm or alert script, Google will ask you to approve the script using your
Gmail account.  You must approve it in order to deploy the altered script.*

We (Team Practical Projects) have developed a number of tools and techniques for integrating our
Internet of Things projects with external apps and services.  We use Particle devices (see particle.io)
and cloud-based services that Particle provides to implement various integration scenarios:
## Real-time communication with a mobile app.
We describe how we create mobile apps that communicate with our embedded systems using MIT App Inventor 2
and Particle's cloud API.
## Device logging to a cloud spreadsheet.
We describe how we use Particle webhooks and Google Apps Script to log sensor data from our embedded
devices to Google Sheets.
## Real-time alarm/alert notification.
We describe how we use Particle webhooks, Google Apps Script and mobile providers' SMS gateways to
send alarm and alert messages to mobile devices using SMS texting.
## Device-device secure wireless communication.
We describe how we use Particle's publish/subscribe mechanism to securely and wirelessly communicate between
embedded devices.
## Integrating to a cloud database.
We describe how we use Particle webhooks and PHP to provide embedded devices a means to communicate with
cloud-based services that use a REST API, including third party services and our own cloud database.
