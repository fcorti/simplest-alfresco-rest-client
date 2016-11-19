# The simplest Alfresco client using Google Material Design and Ajax

This Alfresco javascript client for REST APIs is a simple client enabling users to use the Alfresco REST API using a friendly interface. The client is developed to executed an [AJAX](https://en.wikipedia.org/wiki/AJAX) call in GET, POST, PUT or DELETE. The source code is written in [HTML](https://en.wikipedia.org/wiki/HTML) and uses the [Google Material Design](https://en.wikipedia.org/wiki/Material_Design) as stylesheet. All the source code is available into a single file called `index.html`.

Nothing is simpler than this...

## Prerequisites

Before installing the Alfresco javascript client for [REST API](http://docs.alfresco.com/5.1/pra/1/topics/pra-welcome-aara.html), you have to be sure to have an Alfresco instance installed into your environment. Suggested but not mandatory, is the installation of the [Alfresco API Explorer](http://docs.alfresco.com/5.1/pra/1/concepts/pra-rest-api-explorer.html).

Want to understand how to complete this task? 

Take a look at the Alfresco setup paragraph of the post [here](http://fcorti.com/2016/09/05/alfresco-development-framework-in-action/#alfresco_setup) (you can avoid to install the Enabling CORS module).

## How to install the client

To install the client, simply create the `simplest-alfresco-rest-client` into the `<alfresco>/tomcat/webapps` path and move the whole content of this project into the brand new folder.

Then you can restart your alfresco installation.

## How to use the client

To use the Alfresco javascript client for REST API, simply open a browser and access to the URL below.

`http://<alfresco_url>:<alfresco_port>/simplest-alfresco-rest-client/`

Then you can fill the requested fields and press 'Go' button.
If you have the API Explorer installed into your environment and want to access to them, you can simply press the 'API Explorer' button. Press "Reset" button to clean the result panel.
