Cake manager project developed by Waracle developer has below technical issues that is why the service end point for cakes throwing 404 error
1) xml namespace referred on web.xml is pointed to wrong version that is corrected
2) Jetty plugin version is not defined under pom.xml

Original Project Info
=====================

git clone https://github.com/kshivarla/cake-manager.git

To run a server locally execute the following command:

`mvn jetty:run`

and access the following URL:

`http://localhost:8282/cakes` to view the cakes data in JSON format