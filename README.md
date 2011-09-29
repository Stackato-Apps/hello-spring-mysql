Spring Sample
=============

This is a Java sample using the Spring framework and a MySQL service.

Building the Application
------------------------

To build the application, make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *hello-java-1.0.war* file in the 'target' directory.

Running the Application
-----------------------

To run the application, make sure you have the Stackato client installed and that you are logged in to your target (e.g. http://api.stackato.local).

Then run:

	stackato push hello-spring-mysql --path target

When prompted to add a service, select "y" and add a MySQL service.

You can view the application at the 'Application Deployed URL'.
