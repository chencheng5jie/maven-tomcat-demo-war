Tomcat - Webapplication with maven pluggin to create WAR file .

Build & Deploy : mvn tomcat7:deploy -Dtomcat.username=admin -Dtomcat.password=admin





#tomcat-users.xml - Add below in tomcat container

<role rolename="manager"/>
<role rolename="tomcat"/>
<role rolename="manager-script"/>
<role rolename="manager-gui"/>
<user username="admin" password="admin" roles="manager,manager-gui,manager-script,tomcat"/>