---
id: tutorial
title: Tutorial
sidebar_label: Basic email sending procedure.
---

After you get through the basic flow of **Deltamailer.** You will have some knowledge of how to send email. In this section we will elobrate each steps described in basic flow.

As described earlier after login your first step to send email is to creating list.

## Create list 

This is the first step. At this step you need to create list. Navigate to `Home/Lists` then click
`Create list` on right side.

![](http://res.cloudinary.com/dmoborihs/image/upload/v1528706528/DeltamailerDocs/List.png)


* Then give name to the list.

* Give description if needed.

* Select one of the appropriate options as your need in `Unsubscription` field.

* Then click the `Create list` on buttom.

![](http://res.cloudinary.com/dmoborihs/image/upload/v1528729022/DeltamailerDocs/CreateList.png)
> Before creating list

![](http://res.cloudinary.com/dmoborihs/image/upload/v1528729453/DeltamailerDocs/aftercreating_list.png)
> Here I have created the list with name Docs Test

## Add Subscriber

Subscribers are those emails to whom we are sending the emails. Subscribers can be added singaly or multiple at a time. 

* Navigate to `List Action` drop down button on right side.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528729888/DeltamailerDocs/adding_subscriber.png) 

* Click `Add Subscriber` for adding only single subscriber.
    * Fill the fileds and click subscribe button.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528730128/DeltamailerDocs/single_subscriber.png)

* Click `Import Subscribers` for adding multiple subscribers.
	* In `CSV File` field upload csv file containing email with other information
	![](http://res.cloudinary.com/dmoborihs/image/upload/v1528737122/DeltamailerDocs/ImportSubscriber.png)
	* After you click next you will get following sereen
	![](http://res.cloudinary.com/dmoborihs/image/upload/v1528739328/DeltamailerDocs/While_Importing.png)
	>In this case your csv file is like this
	> ![](http://res.cloudinary.com/dmoborihs/image/upload/v1528739513/DeltamailerDocs/csv.png)
	> if you add more column you will get more field in above step.

	* In `Email` filed select `Enail address` from dropdown and in `Name` select `First Name` and click `Start import`
	>For creating with costum field [click here]()

Now, Importing suscribers is completed.

>Note: While importing your file should be in .csv format. 

## Create Template

Template is the structure of the email which will be sent to the subscribers.

To create template Navigate to `Templates` in menu.

* Then click the `Create Template` button on right side.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528740776/DeltamailerDocs/CreateTemplate.png)

* Then give `Template name` Choose one of the editor and give description if required.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528740928/DeltamailerDocs/templatename.png)

* Then click `Create Template` button at bottom to create template. After that you will get following screen. 
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528741441/DeltamailerDocs/tem1.png)
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528741441/DeltamailerDocs/tem2.png)
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528741440/DeltamailerDocs/tem3.png)
	> Merge tags are tags that are replaced before sending out the message. The format of the merge tag is the following: `[TAG_NAME]` or `[TAG_NAME/fallback]` where fallback is an optional text value used when `TAG_NAME` is empty.
	>To know about `Merge tags` [Click here]()

* `Template content` is the field which contains the template of email here you can use `Merge Tags` and made custom email easily for subscriber.
	> In the above example we have used `[FIRST_NAME/Customer]` merge tag which will merge data i.e. First Name from csv file used while importing subscriber.

Now, Click `Update` button to save template.

> You can also delete and create duplicate of template by clicking `Duplicate` and `Delete Template` bnutton on buttom right side.

## Create Campaigns


Now this is the last step for sending email. 
You need to create the campaign if you want reporting and anylisis of sent emails.

The list and the templates must be created earlier to create the campaign.
>Note: You can also create new campaign for existing list and template if you need same list and template in future  

Campaign generates the reports of delivered emails, black listed emails, bounced email, opened email.

* To create campaign Navigate to `Campaigns` on main menu.
* Then click `Create Campaigns`  use `Regular Campaign` from dropdown.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528773324/DeltamailerDocs/campaigns.png)
* Then give name to campaign.
* In the `List`  field use the required list.
* Similarly, in the `Template` use the required.
* `Email "from name"` is the name from which you will send email.
* `Email "from" address` is the email from which you will be sending email.
* `Email "reply-to" address` is the email to which subscriber will replay.
* `Email "subject line"` is the subject of the email.
* Select the appropriate check box if required.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528774001/DeltamailerDocs/cam1.png)
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528774000/DeltamailerDocs/cam2.png) 

Please click the `Update` button after filling the above field.

Now you will be redirected to the new tab Template from where you can update template of email if required.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528774231/DeltamailerDocs/cam_tem.png)
> You can also switch to Attachment tab if some file is to be attached in the email.

Click `Update` button to save campaign.

Now you will be redirected to new page from where you can send email to subscriber.
![](http://res.cloudinary.com/dmoborihs/image/upload/v1528774625/DeltamailerDocs/sending_email.png)

To send email click `Send to Subscribers` button.


