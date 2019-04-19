# tomcat-web
tomcat 9.0.16 deploy by docker-compose
1.0.1 tomcat 9.0.16 >> tomcat 8.5.28

Upload the Root.war in the webapps to run inhttp://{IP}:{port} directly.

# Docker Volume
volumes: - /home/USER/web/ROOT.war:/usr/local/tomcat/webapps/ROOT.war
