# nexus-settings

This repository contains two files.

settings.xml
============

For local or internal Jenkins.  Either use this file or some of its contents to setup access to our new Nexus server.

You will require a system account.  If you don't already have one contact Service Desk to create one.

**Important:** In the interest of security you should consider changing this password on a regular basis.

public-settings.xml
===================

Identical to settings.xml except that the username and password need to be set as environment variables in your build. 

Rename this file to settings.xml

For a typical usage in Circle CI see the following:

	https://github.com/Financial-Times/sample_java_nexus 
	https://circleci.com/gh/Financial-Times/sample_java_nexus 

