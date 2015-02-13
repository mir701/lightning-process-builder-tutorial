---
layout: module
title: Module 5&#58; Add Process Actions
---

In this module, we will add actions to our the process. Using the Lightning Process Builder we have the ability to add either immediate or scheduled actions which will execute when the criteria we defined in the previous module evaluates to true. For this tutorial we will create a series of immediate actions. We will be creating 3 actions. Post to Chatter, Create a Record, and Submit for Approval. Without the Lightning Process Builder it would require code to create new related or unrelated records 



## What you will learn
- How to add immediate actions to the process builder


## Step 1: Add a Chatter Post action 
One of our business requirements is to notify the other travelers in the company about a new trip. We are going to post a notification to the travelers Chatter timeline including details about their trip, as well as a topic hashtag. You can also use Chatter post actions to 

1. In the Immediate Actions element directly to the right of the criteria you just created, Select **Add Action**
2. For the Action Type we will select **Post to Chatter**. 
*Notice the variety of action types you can create here.*
3. 


## Step 2: Add an Record Creation Action 
Using the Lightning Process Builder we can create entirely new records, of custom or standard objects, related or unrelated to the primary process object. Related would mean that there were lookup fields or relationships connecting the objects, such as the Account field on the Contact object. This means those objects are related in salesforce. For this step we will be creating a new **Event** record, which is not related to the Trip Request custom object. We will create a new record as well as populate fields on that record based on information in the Trip Request record. 

1. 

## Step 3: Add an Approval Action  

1. I



<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="create-lightning-application.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="create-searchbar-component.html" class="btn btn-default pull-right">Next <i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>
