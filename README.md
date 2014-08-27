JTools-extras
=============

A collection of Java tools and utilities. These tools are either experimental or depend on third party libraries. The whole project depends on JTools and test code uses TestNG. Aside from that, each package documents its own dependencies.

Usage
-----

This project is intended to be a utility library. The Javadocs for the project are not complete yet, but the main classes are pretty well documented.

Dependencies
------------

This project currently requires the following to be on the classpath for the and build and test targets to run:

- madphysicist-JTools.jar, the current version of JTools.
- tools.jar that comes with the JDK.
- testng.jar and any dependencies that it may require to run the tests.

Update local paths to these files in config/local.properties in the section containing the test.*.jar properties

If testng requires additional dependencies (older versions require qdox.jar and bsh.jar, while some newer versions require jcommander.jar), edit the `testng-jars` path in the `compile-init` target in config/setup.xml

Versions of config/local.properties suitable for Ubuntu and Arch based systems are present in the repository. They should be renamed to config/local.properties before use.

