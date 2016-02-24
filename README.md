# docker
Docker respositories and  their Docker files
Versions

Apache Tomcat - 8.0.3 JDK - Oracle 1.8 CentOS - 6.7

Build docker build centos-tomcat path-to-dockerfile

OR

docker pull harsv/centos-tomcat

Run

docker run -d -p 8080:8080 harsv/centos-tomcat

Deploy Applications

curl --upload-file path-to-war "http://admin:password@_hostname_:8080/manager/text/deploy?path=/&update=true"
