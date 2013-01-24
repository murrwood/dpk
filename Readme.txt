Notes for Drupallos Pizza Kitchen
Example for Drupal 7 Mobile Web Development Beginners Guide

This instance of the Drupallos Pizza Kitchen resolves most of the discrepancies between the book and the example.
There are still difference but the instance works.

Notes:
1. This update is based on Drupal 7 version .19.  You may need to update to most recent version.
To do so, change the "projects[drupal][download][tag] = "7.19"" in the Make file.

Chapter 2 - Creating a database section
1. After copying the settings files review the database name,user name and password to make sure they match your environment.
   The book makes some assumptions that may or may not be correct.   Look for the $databases = array ( statement.
2. After changing the password for the admin account enter the url dpk.local/user to see the logon screen.
3. The "Locations" and "Your Order" are missing.  They will be added later.

Chapter 3 - Once Upon a Website...
1. Some of the problems mentioned in this section are not in the instance.  Not to worry.  They are not needed. 

Chapter 5
1. The .pdf file that contains the original menu is not present. 