---
layout: module
title: Module 4&#58; Add Process Object and Criteria
---

The process exists, but there is not criteria detailing when and where this process should run. We will add a target object to this process. This object will be where the process criteria will be defined, so for this example we will want to evaluate the process for the custom object we just installed called **Trip Requests**. With the power of the new Lightning Process Builder you are able to execute actions on objects related or unrelated to this original object.  We will be able to add actions later on to create or update other types of objects, but this step determines which specific object the process criteria(s) will be on. 




## What you will learn
- Define Process target object
- Define when target object should be evaluated
- Define Process criteria 


## Step 1: Define the Object

1. In your new process screen, select the **Add Object** element. 
![](images/object1.jpg)

2. All of our standard and custom objects are available to select, including the object just installed with the AppExchange package. We want to Select the **Trip Request** object. 
3. Because we want to evaluate all elligible trip requests, even ones that were edited after creation, we select the option: 
    - Start the process: **When a record is created or edited** 
4. Leave the **Allow process to evaluate a record multiple times in a single transaction?** checkbox **Unchecked** 
*Note: If you select yes, the process can evaluate the same record up to five additional times in a single transaction. It might reevaluate the record because a process, workflow rule, or flow updated the record in the same transaction.
For example, your sales review process includes multiple steps, approvals, notifications, and fields that need to be updated. Some of these changes may be part of your process, or they may be managed by other workflow rules or flows in your organization. If you allow the Process Builder to reevaluate a record multiple times in a single transaction, you can manage and evaluate all of these changes—even changes from other processes—in a single transaction in your process.* 
5. Select **Save**
![](images/object2.jpg)



## Step 2: Define the Criteria




<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-apex-controller.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="create-contactlist-component.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
