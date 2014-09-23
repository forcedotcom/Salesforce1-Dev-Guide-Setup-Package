## About Install
Use the link below to install the unmanaged package for the Salesforce1 App Developer Guide schema and miscellaneous extra components like Visualforce Pages, Static Resources, etc. 

##Installation URL
https://login.salesforce.com/packaging/installPackage.apexp?p0=04tA0000000AJGl

##Installation Steps
1. Log into your Developer Edition org. 
2. Paste the bit.ly link above into your URL bar after logging in.
3. Click 'Continue' on the Package Installation Details page. Note: You cannot have any objects in your org containing the same API name as anything in this package, if you do you will see an error after clicking 'Continue.'
4. Click 'Next' on 'Step 1. Approve Package API Access' of the package installer
5. Click 'Select security settings' on 'Step 2. Choose security level' of the package installer. In the list of profiles, find the custom Mobile Technician profile you created and change the access level picklist next to that profile to 'Mobile Technician' so that the permissions are carried over into your custom profile. If you have not created a custom profile for this, clone the Standard User profile and start over at step 2.
6. Once you have set the custom profile access level to 'Mobile Technician,' click Next.
7. Click 'Install' on 'Step 3. Install Package' of the package installer.  

##What else is in this repo?
There is a zip file in this repo containing the FlexiPage data/metadata for the admin guide. Please refer to the admin guide for instructions on how to deploy this package to your org. 