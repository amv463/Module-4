# Choice of Configuration and operational data

#Status: accepted

#Context:

The establishment of specific configuration and operational data is required 
due to the application creating and storing information about users.

#Decision:

A base for working with the application was needed, along with files to configure
the application with sample data to provide proof of the concept. In addition, 
volumes were added to the 'docker-compose.yml' file in order to introduce data 
persistence. The files used for configuration are listed below: 

'createdata.sql'
'createuser.sql'

#Consequences:

While data persistence allows data to be saved locally and remain when the 
application is launched and brought down, the configuration data used, though 
simple, effectively demonstrates the application. 

