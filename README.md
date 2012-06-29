Spring Sample
=============

This is a Java sample using the Spring framework and a MySQL service.

Building the Application
------------------------

It is possible to build the application either with Ant or Maven.

### Ant

Make sure your have [Ant](http://ant.apache.org/ "Ant") installed.
Then, *cd* into the root directory and execute:

	ant clean package
	
That will create the *hello-java-1.0.war* file within the 'target' directory.

### Maven

Make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *hello-java-1.0.war* file within the 'target' directory.

Deploying the Application
-------------------------

To run the application, make sure you have the Stackato client installed and that you are logged in successfully for your desired target environment (e.g. http://api.stackato.local).

Then execute:

	stackato push -n 
	
Notice that it detected the app type as "Java Web Application".

Then go on your application url.

That's all. Have fun!
