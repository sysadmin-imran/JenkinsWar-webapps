# JenkinsWar-webapps
JenkinsWar-webapps

docker-tomcat-war

A basic tutorial on running a web app and deploying a java war file on Tomcat  using Docker

Steps
Install Docker.

Clone this repository - $git clone https://github.com/sysadmin-imran/JenkinsWar-webapps.git

cd JenkinsWar-webapps # from your root directory

docker build -t tomcatwebapp:latest .

docker run -d --name tomcatwebapp -p 8082:8080 tomcatwebapp:latest

http://localhost:8082
