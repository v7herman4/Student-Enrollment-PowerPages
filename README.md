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

![](RackMultipart20231122-1-6vu4f2_html_2daf5e9d89baefa9.png)

![](RackMultipart20231122-1-6vu4f2_html_846e32693c982740.png)

## Install the Student Enrollment Site Solution from GitHub

### Install Base Dataverse Solution

From the following location:

[https://github.com/v7herman4/Student-Enrollment-PowerPages/tree/main/Student-Enrollment-PowerPages](https://github.com/v7herman4/Student-Enrollment-PowerPages/tree/main/Student-Enrollment-PowerPages)

Download and import the following solution: _StudentEnrollmentMSFTFederal\_managed.zip_

### Create Student Enrollment Site

Once the import of the solution is complete, find the _Student Enrollment_ site in the list of Inactive Sites.

![](RackMultipart20231122-1-6vu4f2_html_ef9c6439102358fc.png)

**Reactivate the Site**

Find the site in _Inactive Sites_. Click _Activate._

### Update the Site with the latest changes

Update your Site as needed.

# Appendix

## Connect GitHub to your Power Platform Environment

Follow these steps here.

[https://learn.microsoft.com/en-us/power-platform/alm/tutorials/github-actions-start](https://learn.microsoft.com/en-us/power-platform/alm/tutorials/github-actions-start)
