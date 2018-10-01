# skunksworks-parrot
![Platform](https://img.shields.io/badge/platform-Desktop-blue.svg)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

This project is under development.

Skunkworks-parrot is a Desktop applications for supervisors to create and send notifications to their field workers for better coordination of their work. [skunkworks-bat](https://github.com/opendatakit/skunkworks-bat) is an Android app that receives these notifications. 
The client can send notifications to all or a group of workers. These groups can either be an ODK Groups or a custom groups created in this application. For the custom groups, users are required to scan the QR code using skunkworks-bat generated by the admin after creating the group to be part of the group. Whereas members of ODK Groups are added by default.
It is part of Open Data Kit (ODK), a free and open-source set of tools which help organizations author, field, and manage mobile data collection solutions. Learn more about the Open Data Kit project and its history [here](https://opendatakit.org/about/) and read about example ODK deployments [here](https://opendatakit.org/about/deployments/).


## Setting up your development environment

1. Download and install [Git](https://git-scm.com/downloads) and add it to your PATH

1. Download and install [IntelliJ IDEA](https://www.jetbrains.com/idea/) 

1. Fork the collect project ([why and how to fork](https://help.github.com/articles/fork-a-repo/))

1. Clone your fork of the project locally. At the command line:

        git clone https://github.com/YOUR-GITHUB-USERNAME/opendatakit/skunkworks-parrot

 If you prefer not to use the command line, you can use IntelliJ IDEA to create a new project from version control using `https://github.com/YOUR-GITHUB-USERNAME/opendatakit/skunkworks-parrot`. 

1. Open the project in the folder of your clone from IntelliJ IDEA ide.

2. To run the project, click on the green arrow at the top of the screen. 

3. Click on the configure option after you run the app for the first time.

4. Create a Firebase project and add necessary data to sync the app with firebase. Step by step instructions for creating a Firebase project can be found [here](https://drive.google.com/open?id=10_9oU_8zrek7lt7BRYmJJwo22rs51uAw). 


## Prerequisites

[ODK Sync Endpoint](https://docs.opendatakit.org/odk2/sync-endpoint/) server is needed for the application to run. Once the server is up, enter the url in configure section of the app. Users with 'SITE_ACCESS_ADMIN' role can only access the application.
