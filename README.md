# CMPG-323-Overview---30598303
Overview of the module CMPG 323 and all projects and how i plan on tackling these projects
Each of my projects will have its own repository, thus 5 repositories in total, and all repositories will be linked back to the overview repository created in Project 1
I plan on using the same branching strategy for all my projects, I will be working directly on the main branch.
I will make use of a gitignore file in each project. I will use it to ignore backup files.
I have created my a ceasar cipher that i use to encrypt a text file that contains all my credentials and sensitive information.
Additionally I have this information stored on a usb as well as a printed copy which I keep seperate and a secure locations.

I will now add information about each project and how each project should be used:

Project 2:
I created an API with the following url: https://30598303api.azurewebsites.net/swagger/index.html. Here is a list of all the endpoints implemented in my API:

/api/Categories - GET
/api/Categories - POST
/api/Categories/{id} - DELETE
/api/Categories/{id} - GET
/api/Categories/{id} - PUT
/api/Devices - GET
/api/Devices - POST
/api/Devices/{id} - DELETE
/api/Devices/{id} - GET
/api/Devices/{id} - PUT
/api/Zones - GET
/api/Zones - POST
/api/Zones/{id} - DELETE
/api/Zones/{id} - GET
/api/Zones/{id} - PUT 

![image](https://user-images.githubusercontent.com/110592885/202443671-53662eba-0f65-48dc-b9f4-3c69a23ae628.png)

![image](https://user-images.githubusercontent.com/110592885/202443709-caa3bf96-84c8-429f-970d-02e1aeb6a681.png)

![image](https://user-images.githubusercontent.com/110592885/202443734-9ec6dfdf-29ca-4e4d-b89b-262151d7da55.png)

Project 3:
I created a web app and how this app will be used: 
This web app will be used to view and maintain the ConnectedOffice Database (update, delete, add and edit data in the tables). In order to view and edit data you need to register an account and login. If you already have an ccount you can just sign in. Here is a screen recording of how this app works after it has been published and hosted on Azure:

(https://github.com/AnriqueCloete/CMPG-323-Overview---30598303/files/10031386/Home.Page.-.Connected.Office_.Device.Management.-.Google.Chrome.2022-09-29.09-02-56.zip)

Here is the link to the site as well: https://30598303devicemanagementwebapp20220928150954.azurewebsites.net

Project 4:
This project is a process automation which automates the process of logging in to a web app and automating the addition, reading, updating as well as deletion of data from tables on the web app. The data is read from an excel file and added to a data table in UiPath. After each automation (addition, reading, updating, deleing) a test is done to see if the automation has been successful. On the last sheet of the excel workbook a true or false indicates whether an automation has been successful or not.

Here are screenshots of my automation published on Orchestrator:

![image](https://user-images.githubusercontent.com/110592885/202445570-6d26bf72-3098-4471-9d93-a6f7bf211da7.png)

Here is a screenshot of my asset which contain my login credentials used to log into the web app:

![image](https://user-images.githubusercontent.com/110592885/202445660-200fd87d-e703-4b7f-b75a-37b553e833b8.png)


Project 4:
I created a report in Power Bi. This report gives the current standings of devices in the organization with their current statusses and the category and zone to which each device belongs. This report will be used to make important decisions about devices and wether to add new devices or not. This report contains 3 pages: The first page contains a high level summary view of the organization currently:

![image](https://user-images.githubusercontent.com/110592885/202446154-29a07952-1964-4d19-a5dd-769970843101.png)

The second page is used for monitoring the devices:

![image](https://user-images.githubusercontent.com/110592885/202446255-0771a67e-7cff-4ecb-835a-a42d19984456.png)
