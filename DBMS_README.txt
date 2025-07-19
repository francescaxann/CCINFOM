HOW TO RUN AND COMPILE DATABASE APPLICAITON INSTRUCTIONS IN INTELLIJ.


--------------------------------------------------------------------------------------------------------------------------------------


1. Install necessary software. Make sure you have IntellIJ, a JDK (Java Development Kit), MySQL workbench,
MySQL connector, and JavaFX SDK installed on your system. 

# You can check by running on the terminal: java --version to see if you have java installed
# If not installed, download it from the following links:
# IMPORTANT! Make sure that your JDK and SDK versions are EQUAL 
(ex. JDK 21 and SDK 21 will work, but if SDK is too new or vice versa, it will not work.)

- https://www.jetbrains.com/idea/download/?section=windows   		/* IntellIJ */
- https://learn.microsoft.com/en-us/java/openjdk/download#openjdk-21    /* JDK */
- https://dev.mysql.com/downloads/workbench/    			/* MySQL workbench */ 
- https://dev.mysql.com/downloads/connector/j/    			/* MySQL connector */
- https://gluonhq.com/products/javafx/					/* JavaFX SDK */


--------------------------------------------------------------------------------------------------------------------------------------


2. Configure the necessary environment and paths to make everything work.

~ Setup JavaFX SDK on IntellIJ

# At this time, open your work folder in IntellIJ and click on the main menu (three horizontal lines) on the upper left.
# You should see the different options like "File", "Edit", "View", etc. Hover or Click on "Run".
# In the Drop down options, click on "Edit Configuations".
# Next you should see a '+' plus symbol on the left side of the options, click on it and choose "Application".
# In the field asking for "Main class", supply your Main class or driver class.
# You should also see a "Modify Options" drop down in the upper right of the choices, click on it and choose "Add VM options".
# A field will appear for VM options then in the VM Options field, paste this: 

--module-path "C:YourPath\Java\javafx-sdk-21.0.3\lib" --add-modules javafx.controls,javafx.fxml

(Be sure the path points to the lib folder of your extracted JavaFX SDK.)


~ Setup MySQL connector on IntellIJ

# To do this, click on the main menu (three horizontal lines) on the upper left again and Hover or Click "File"".
# In the Drop down options, click on "Project Structure".
# You will see on the left side a list of "Project settings", choose "Modules".
# There will then be a line with an unticked box with the reference to the MySQL connector JAR file, tick this box.


--------------------------------------------------------------------------------------------------------------------------------------


3. Run the Main App.


--------------------------------------------------------------------------------------------------------------------------------------


4. Experience and interact with the GUI of the Database Application.

# Enjoy :D

--------------------------------------------------------------------------------------------------------------------------------------


GITHUB LINK: https://github.com/francescaxann/CCINFOM

References:

> https://youtu.be/cKmr-9Wc2u4?si=ifZs2PseCmsYb8pp
> https://youtu.be/6E2B9XaJGF4?si=mdtCDPg5W3U1x5yi
> https://youtu.be/zCkhAVhuILs?si=31DSFW6Zt13uwdsZ
> https://youtu.be/8aTpDfsYTNQ?si=95JbZAf29tGB9fBP
> https://youtu.be/duEkh8ZsFGs?si=v6iYFuHtKAl-hq42
> https://youtu.be/UNQiD_mq_7I?si=9lz_sNuAejg_iolg
> https://youtu.be/Ope4icw6bVk?si=_p9XfrqBoDYVw6Zf
> https://youtu.be/zk1r3rt6eI8?si=dBoDzaAmSvQN5fvO

