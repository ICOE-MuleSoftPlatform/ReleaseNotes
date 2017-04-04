• Logging is now more configurable via a logging class.
	• Set logging level using the log4j class com.icoe.healthcheckframework
• Added ability to do a traceroute.
	• Invoke with IP in the body and additional header in the request name: traceroute value: true
• Added ability to query a class path resource
	• http://sap-project-starter-template-sap-snc.cloudhub.io/healthcheck/LCM?resource=deployment_readme.txt
	• Some fixes around calling some funtions. 

• To apply changes
	• Obtain updated jar from nexus. Version remains unchanged for now. Goving forward will upgrade the version.
	• Add properties 
		• healthcheckservicedomain=tcccplatformframework-dev.cloudhub.io
		• healthcheckserviceport=443
		• integrationNameValue=<your app name that you use for logging>
