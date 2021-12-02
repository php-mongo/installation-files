# Installation Files and Documentation
These web server configurations are places here for ease of access and to offer guidance for persons that wish to tackle manual installations.  
They are used by out automated installation scripts for the default and custom installation of PhpMongoAdmin.  
See below for some quick-start guides...

They have been seperated into primary groupings for Apache and Nginx.
Each group contains two separate installation contexts and each context offers a private and public access option.

At this time of writing the Nginx files are still a 'body of work' and will have further updated very soon.

## Documentation:

Setup assistance: 
https://phpmongoadmin.com/support/documentation/setup

Due to the nature of this application, some use cases may occur where there will be a temptation to place this application within the public webspace of another web app.  
We have designed PhpMongoAdmin so that its default installation process shall make it globally accessible via an aliased directory name.  
This has been dome in such a way as to maximise accessibility along with security.  PhpMongoAdmin can also be setup as a VirtualHost application using our automated installers.  

If you choose to 'nest' PhpMongoAdmin within another application please read this documentation:  
https://phpmongoadmin.com/support/documentation/setup/aliases-nesting-security

## Master Branch Setup Files Description
The configuration and installation / setup scripts provide with the primary application are detailed here:  
https://github.com/php-mongo/admin/blob/master/setup/SETUP.md

### Docker Compose Full
This readme document details the current process for setting of our docker-compose-full instance:  
https://github.com/php-mongo/docker-compose-full/blob/master/README.md