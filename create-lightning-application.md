---
layout: module
title: Module 4&#58; Add Process Object and Criteria
---

The process exists, but there is not criteria detailing when and where this process should run. We will add a target object to this process. This object will be where the process criteria will be defined, so for this example we will want to evaluate the process for the custom object we just installed called **Trip Requests**. With the power of the new Lightning Process Builder you are able to execute actions on objects related or unrelated to this original object. 



## What you will learn
- Define Process target object
- Define when target object should be evaluated
- Define Process criteria 


## Steps

1. In the Developer Console, click **File** > **New** > **Lightning Application**. Specify **QuickContacts** as the bundle name and click **Submit**

2. Implement the application as follows:



    ### Code Highlights:
    - The **link** tag references the bootstrap style sheet uploaded as a static resource in [module 2](setup-environment.html)
    - The application uses Bootstrap to implement a basic layout for the application
    - Lightning applications can include Lightning components and regular HTML markup

1. Click **File** > **Save** to save the file

1. Click **Preview** (upper right corner)

    ![](images/app-preview.jpg)

1.  Preview the application in the browser

    ![](images/app-layout.png)


<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-apex-controller.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="create-contactlist-component.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
