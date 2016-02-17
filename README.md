# IBM-CaseManager-Maven-Install
This is a Maven POM project which takes a directory location and installs the IBM Case Manager 

# Usage
* Open the POM file and change the property value for "icm.install.path" to the install path of your Content Engine
* Run 'mvn install' (local Maven) or 'mvn deploy' (remote Maven)
* Now you can make use of the IBM Case Manager JARs available in your Maven repository

# Deployed JARs
In groupId 'com.ibm.icm.api'
* acmapi.jar
* eeapi.jar
* icm-external-api.jar
* JSON4J.jar
* JSON4J_Apache.jar
* secauditschema.jar
* casemgmtschema.jar
In groupId 'com.ibm.icm.plugins'
* ICMAPIPlugin.jar
* ICMAdminClientPlugin.jar
