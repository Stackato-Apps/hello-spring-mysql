Spring Sample
=============

This is a Java sample using the Spring framework and a MySQL service.

Building the Application
------------------------

To build the application, make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *hello-java-1.0.war* file in the 'target' directory.

Deploying the Application
-------------------------

To deploy to stackato:

    mvn clean package 
    stackato push -n

You can view the application at the 'Application Deployed URL'.
