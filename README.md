# MyCalendar

#Deployment methods

# Method 1 - Run the application in IIS Express server bulit into visual studio

## Open the solution in Visual Studio(2017 or later)

## Right click on the Solution and clean the project

## Click on the GoogleCalenderOperations project and rebuild the project.

## Right click on the GoogleCalenderOperations project -> Properties -> Web and make sure the Project URL is set to http://localhost:60531/

## Run the project


# Method 2 - Run the application in IIS server

## Open the solution in Visual Studio(2017 or later)

## Right click on the Solution and clean the project

## Click on the GoogleCalenderOperations project and rebuild the project

## Create a local folder to publish the project on the computer

## Right click on the GoogleCalenderOperations project and publish the project to above created folder

## Open IIS manager

## Right click on 'Sites' node and click on 'Add website'

## Create the web site giving the Physical path to the above published location. Make sure that you enter 60531 as the port with http binding.

## Open the browser and enter http://localhost:60531/

