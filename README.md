# How to include version informations into a war

## Build

Build the war by running at command line:

    mvn clean install

from the directory in which there is the `pom.xml` file.

In the `target` directory you will find the war which contains
the `version.properties` which stores informations about the build.

## Deploy

Deploy the war into an application server then click the `version.properties`
link, which will appear on the welcome page, in order to see the build
informations stored in the `version.properties` static file.
