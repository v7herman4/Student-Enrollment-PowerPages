# Student-Enrollment-PowerPages
Student enrollment Power Pages
Power Pages

# Student Enrollment Install and Configuration Instructions

## Licenses

For installation activities only, the following licenses are required:

_Power Apps Premium_

## Security Roles

For installation activities only, the following Security Roles must be assigned to the user performing the installation steps:

_Power Platform Admin OR Global Admin_ (Office 365 security roles)

## Create a Dev Environment and the Starter Site

### Create the Environment

Follow the instructions here to create a new environment with a Dataverse instance for the Development instance:

[Create and manage environments in the Power Platform admin center - Power Platform | Microsoft Learn](https://learn.microsoft.com/en-us/power-platform/admin/create-environment#create-an-environment-with-a-database)

Note: Create the Environment as type _Sandbox._ Do NOT create the Environment as type _Developer_.

### Create the Starter Site

Create a new Site in this environment:

[Create a site with Power Pages | Microsoft Learn](https://learn.microsoft.com/en-us/power-pages/getting-started/create-manage)

Use the Program Registration template:

[Program registration template | Microsoft Learn](https://learn.microsoft.com/en-us/power-pages/templates/after-school)

Note: we will NOT be using this site created with the Program Registration template. It is simply a way to download the pre-built solutions for Registration logic. Leave the default name for the site as is.

Wait until the Starter Site has finished getting ready.

![image](https://github.com/v7herman4/Student-Enrollment-PowerPages/assets/89024016/1b3974e3-790c-4973-a821-388f1502c03e)

![image](https://github.com/v7herman4/Student-Enrollment-PowerPages/assets/89024016/b2ba8b6d-9423-4e07-8063-a557f3e0faa1)



## Install the Student Enrollment Site Solution from GitHub

### Install Base Dataverse Solution

From the following location:

[https://github.com/v7herman4/Student-Enrollment-PowerPages/tree/main/Student-Enrollment-PowerPages](https://github.com/v7herman4/Student-Enrollment-PowerPages/tree/main/Student-Enrollment-PowerPages)

Download and import the following solution: _StudentEnrollmentMSFTFederal\_managed.zip_

### Create Student Enrollment Site

Once the import of the solution is complete, find the _Student Enrollment_ site in the list of Inactive Sites.

![image](https://github.com/v7herman4/Student-Enrollment-PowerPages/assets/89024016/a945ac65-fad0-457d-9059-5ee196fede78)


**Reactivate the Site**

Find the site in _Inactive Sites_. Click _Activate._

### Update the Site with the latest changes

Update your Site as needed.

# Appendix

## Connect GitHub to your Power Platform Environment

Follow these steps here.

[https://learn.microsoft.com/en-us/power-platform/alm/tutorials/github-actions-start](https://learn.microsoft.com/en-us/power-platform/alm/tutorials/github-actions-start)
