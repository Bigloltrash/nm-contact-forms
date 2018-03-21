# nm-contact-forms
Documentation for [NM Contact Forms Wordpress plugin](https://wordpress.org/plugins/nm-contact-forms/)

Detailed WIKI [here](https://github.com/Bigloltrash/nm-contact-forms/wiki) !

## Introduction
First off all this contact form plugin is completely free and has no premium plugin bullshit.

NM Contact Forms is a plugin that allows you to build and manage dynamic forms for your website. With this plugin, you will be abble to add simple and efficient forms to be sent by mail. The plugin has an administration panel with a drag and drop feature to configure fields. A built-in anti-spam feature is present too.

Following field types available:

    TEXT
    TEXTAREA
    FREE TEXT WITH LABEL
    EMAIL
    SELECT
    CHECKBOXES
    RADIO BUTTONS
    SINGLE FILE UPLOAD
    GET VARIABLE
    SUBMIT
    HONEY POT
    HORIZONTAL RULES
    RECAPTCHA

Other functionnalities :

    Define zones in the form
    Choose placeholders
    Choose if field is required
    Make field read-only and pre-populate it with GET variable
    Use your own responsive stylesheet
    etc.
    
If you find any bugs, please report on [NM Contact Forms Support page](https://wordpress.org/support/plugin/nm-contact-forms) !

## Installation instructions
1. Upload /nm-contact-forms/ to the /wp-content/plugins/ directory
2. Activate the plugin through the ‘Plugins’ menu in WordPress
3. Create your contact form
4. Find generated shorcode and paste it where you want your form to show up.

## How to create a contact form
Install the plugin. After successful install Contact forms button will appear in the sidebar – click on it. This gonna take you to contact forms page. Click on ‘Add new’ button, enter form name and click ‘Add new form’. It will create a contact form below.

Once you have your form created you can start adding wanted fields by clicking ‘Add field button’.
Some fields such HoneyPot, reCaptcha, submit are allowed only once, so don’t panic if they grey out and become inactive later on.

Don’t forget to include Submit field as it’s compulsory field, otherwise users won’t be able to submit the form.

## How to use GET variable ?
GET variable allows to pass information from URL or from a posted form to the Contact Form. For example you create a link/button to contact us page that contains GET variable (http:/example.com/?product=Shampoo), in this case your GET variable name is ‘product’, so in NM contact form field settings you need to define same GET variable. When user visits Contact Us page, the field will be pre-filled with GET variable value. You can save some time for the users, so they doesn’t have to fill information that is already known, and just needs to be sent with form all together.

## What is Honey POT and how to enable it
HoneyPot is one of anti-spam methods. It creates a hidden field within contact form, that meant to be leaved blank. Bots aren’t always so smart, and they fill all fields regardless. That allows code to know, that contact form was filled by bot, and prevent from sending actual message to the receiver.

Pros and Cons:

Doen’t impact looks of the contact form, it’s hidden, so does not bother users.
This method won’t work if spam attack is targeted or bot is super advanced as it’s possible to teach bot to leave that field clear.

Works well for low traffic sites, that gets less of spammers interest.

To enable it, just click ‘add field’ button on the selected contact form, and set field type to HoneyPot.

## What is reCaptcha and how to enable it
reCaptcha is advanced third party anti-spam solution. It’s reliable anti-spam solution provided by Google.

To set up Google reCaptcha on NM contact forms plugin you have to gain ‘site key’ and ‘secret’ which you can do by registering your site on https://www.google.com/recaptcha/ (It’s completely free). Once you do that go, to NM Contact forms plugin settings, and enter you ‘site-key’ and ‘secret’ into the fields and hit save.

After that go back to the forms page, choose to which form you want to add Google reCaptcha then simply click ‘add field’ and set field type to reCaptcha.

## TODO list

    Custom error messages
    Auto response
    Custom email templates
    List of forms
