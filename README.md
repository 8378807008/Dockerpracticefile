 FROM ubuntu :20.04
RUN apt update
RUN apt install tomcat -y
 CMD ["catalina.sh", "run"]
EXPOSE 8080
