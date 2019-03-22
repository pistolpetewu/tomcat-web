# tomcat-web
tomcat 9.0.16 deploy by docker-compose

Upload the Root.war in the webapps to run inhttp://{IP}:{port} directly.

# Docker Volume
volumes: - /home/USER/web/ROOT.war:/usr/local/tomcat/webapps/ROOT.war
