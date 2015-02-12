---
layout: module
title: Module 2&#58; Setting Up Your Environment
---

We are going to install a basic package that contains the trip request object we are building a process for. 

## What you will learn
- Install an AppExchange package
- Review package commponents
- Define package access


## Step 1: Install the AppExchange Package

The AppExchange is the world's first on-demand application-sharing service. It provides a way to browse, test drive, share, and install applications developed on Salesforce's on-demand AppExchange platform.

Partners, developers, and anyone else who chooses to participate can offer their Apps on the AppExchange directory. This directory gives Salesforce users an easy way to find and install applications to expand their use of the AppExchange platform to new areas of customer relationship management (CRM) and beyond.
The app we are installing today is a private listing, private listings have not undergone the Salesforce security review process and should be installed only from trusted providers. 

Note: To install Apps from Appexchange you need to have the User Permission of “Download AppExchange Packages”.  System administrators have this permission enabled by default, but if other users would like to install packages they may need to contact the system administrator for their org. 

1. Login to your Salesforce Developer Edition

2. Copy and Paste this URL into the address bar of the browser http://bit.ly/TripApprovalPackage 

3. Select **Continue** 
![](images/package1.jpg)

1. Click **Edit** and **Continue**

1. Enter the namespace prefix you want to register, and click **Check Availability**. If the namespace you entered is not available, try again until you find a namespace that is available.

1. Click **Review My Selections**

1. Click **Save**


## Step 2: Enable Lightning Components

1. In Setup, click **Develop** > **Lightning Components**

1. Check the **Enable Lightning Components** checkbox

    ![](images/enable-lightning.jpg)

1. Click **Save**


## Step 3: Upload Bootstrap as a Static Resource

To help you make the application look good, you will use a version of Twitter Bootstrap customized to match the [Salesforce1 guideline](http://sfdc-styleguide.herokuapp.com/).

1. Download and unzip the Salesforce Foundation Bootstrap [here](http://developer.salesforcefoundation.org/bootstrap-sf1/)

1. In Salesforce, click **Setup** > **Build** > **Develop** > **Static Resources**

1. Click **New**
 
1. Specify **bootstrap** as the **Name**, then click the **Choose File** button, and select the **bootstrap.css** in the **dist/css** directory of the unzipped bootstrap folder

    ![](images/static-resource.jpg)


1. Click **Save**


<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-developer-edition.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="create-apex-controller.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
