# Senior Design CS5002 - User Documentation

UC Rainfall Analysis

How to Use Our Website

NOTE: we are currently working out issues with AWS Support regarding hosting our dynamic PHP website publicly. Our registered domain is ucrainfall.org. In the meantime, the information below explains everything needed to navigate and use our website. 

This document focuses **solely** on how to use the **user-interactive** features of our website.

Contents specific to each page and other page info can be found at: 
https://github.com/prat97/CS-Senior-Design/blob/master/USER%20DOCS/WebsiteContents/WebsiteContents.md

# Instructions

To navigate between each of the five pages in our website, click the "Rainfall", "Structures", "Tools", "About", and "Contact" buttons located in the header near the top of the screen (shown in the image below)

<h2>1. "Rainfall" Page</h2>

![RainfallPage](https://github.com/prat97/CS-Senior-Design/blob/master/USER%20DOCS/Pictures/RainfallPage.png)

 * Page numbers selector - By clicking either the numbered pages or the "Next" and "Previous" buttons, one can navigate between each page of data (20 rows per page)

<h2>2. "Structures" Page</h2>

![StructuresPage](https://github.com/prat97/CS-Senior-Design/blob/master/USER%20DOCS/Pictures/StructuresPage.png)

 * First, view the data in the table on the right, then choose the building you'd like to know the status and/or erosion levels of, then click "Calculate"
 * View the now displayed data, and interpret results based on printed values/explanations (see image above)

<h2>3. "Tools" Page</h2>

![ToolsPage](https://github.com/prat97/CS-Senior-Design/blob/master/USER%20DOCS/Pictures/ToolsPage.png)

 * First, view the data in the table on the right, then choose the material type you'd like to estimate the cost of, dimensions (length, width, with height being optional), the unit types of these dimensions, and the unit type from the table you'd like to use to estimate costs of (see image above.)
 * After setting desired values, click "Calculate"
 * View the now displayed data, and interpret results based on printed values seen above.

<h2>4. "About" Page</h2>

![AboutPage](https://github.com/prat97/CS-Senior-Design/blob/master/USER%20DOCS/Pictures/AboutPage.png)

The about page requires no user-interaction.


<h2>5. "Contact" Page</h2>

![ContactPage](https://github.com/prat97/CS-Senior-Design/blob/master/USER%20DOCS/Pictures/ContactPage.png)

Depending on which member of our group you'd like to contact, click the respective person's name. Your default email application will open and put the selected group member's email address in the "To" field of a new email.

If needed, documentation regarding enabling/disabling this feature can be found at:
https://support.tryshift.com/kb/article/59-mailto-links-fixed/


# FAQ

**Question:** How do I access this website?

**Answer:** Currently, this website is only available if hosted locally, due to unexpected difficulties hosting a dynamic website via AWS. If desired, the files in https://github.com/prat97/CS-Senior-Design/blob/master/CODE can be downloaded, in addition to downloading hosting software "XAMPP", then copy all files in the CODE folder to your xampp\htdocs folder (e.g. C:\Users\Collin\Documents\xampp\htdocs\FinalProject). You will need to create this new folder called "FinalProject" and copy all the files in CODE here, then create a mysql database called "raspberrypi_seniordesign" and run each of the scripts in the SQL SCRIPTS folder (available in CODE) to create the database tables. You should then be able to access the website by visiting the URL http://localhost/FinalProject/Rainfall.php , if all of this was done successfully. Further documentation on XAMPP can be found here: https://www.ionos.com/digitalguide/server/tools/xampp-tutorial-create-your-own-local-test-server/

Other questions you may have can be found in this document or in one of the links in this document. Should you have any additional questions, please email me at foxcj@mail.uc.edu and I will get back to you as soon as I can. 
