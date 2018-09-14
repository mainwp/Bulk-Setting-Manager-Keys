# Bulk Setting Manager Keys

This repository contains "Keys" for use with the [MainWP Bulk Settings Extension](https://mainwp.com/extension/bulk-settings-manager/).

The Bulk Settings Extension is a custom plugin built to allow the [MainWP Dashboard](https://wordpress.org/support/plugin/mainwp/) to control almost any WordPress plugin installed on a [MainWP Child site](https://wordpress.org/plugins/mainwp-child/).  

## How it Works

MainWP Bulk Settings Manager Extension works together with the [MainWP Key Maker plugin](https://wordpress.org/plugins/mainwp-key-maker/). The Key Maker plugin grabs necessary data from your WordPress site (where you have set you preferences), next, the Extension converts the data to a key that you can submit to the rest of your child sites and apply your preferences.

## Does Bulk Settings Manager work with XYZ plugin or theme?
While we have not tested every plugin or theme Bulk Settings Manager should technically work with any plugin or theme that uses standard forms.

**If you want to check if the information you want to work with will be recorded:**

1. Install the free [MainWP Key Maker plugin](https://wordpress.org/plugins/mainwp-key-maker/)
2. Submit the form you want to be able to use in Bulk Settings Manager.
3. Once you have submitted the form press the MainWP Key Maker button that will be in your WP Admin Top Menu.
4. You will now see at least 2 “Keys” that will pop up for you “Post-submission Request” and “Pre-submission Request” (you almost always want to use Post-submission since that is the information gathered after you submitted the form).
5. Now click on “Verify Form Fields and Values” this will show you in a human readable way what information was gathered.

If everything looks right and all your information was gathered correctly then you can be 99% sure that it will work with Bulk Settings Manager to change all your Child sites.

An example of where Bulk Settings Manager would not work is during the initial setup of JetPack where you are required to leave your Child site to verify login credentials.  However, you would be able to set up keys for JetPack after the verify credential step.

## Important Notes: ##
Pre-submission requests often don’t have all fields and values detected. Using the Pre-submission requests may lead to incomplete Keys. We strongly recommend using Post-submission requests!

In order to see the Post-submission request, you need to submit the form that you are trying to grab and make the Key. Once you get to the page where the form is located, make sure that the wanted values are correctly set, submit the form and after that, you will be able to see the Post-submission request.

Some forms are divided in multiple mini-forms. MainWP Key Maker plugin detects all mini-forms and displays Post-submission requests for all of them.

If you get multiple Post-Submission requests, be sure to use the Verify Form Fields and Values button and find the “biggest” one. The request that is showing all form fields will probably be the one.

## Related documents ##
[Bulk Settings Manager Workflow](https://mainwp.com/help/docs/bulk-settings-manager-extension/bulk-settings-manager-workflow/) 

[Create a Single Key](https://mainwp.com/help/docs/bulk-settings-manager-extension/create-a-single-key/)

[Add a Key to a Key Ring](https://mainwp.com/help/docs/bulk-settings-manager-extension/add-a-key-to-a-key-ring/)

[Save Keys to Child Sites](https://mainwp.com/help/docs/bulk-settings-manager-extension/save-keys-to-child-sites/)

[Bulk Settings Manager Settings](https://mainwp.com/help/docs/bulk-settings-manager-extension/bulk-settings-manager-settings/)
