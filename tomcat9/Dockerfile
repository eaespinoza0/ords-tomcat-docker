FROM tomcat:7.0.82-jre8

COPY ords.current.zip ords.current.zip

COPY entrypoint.sh entrypoint.sh

RUN chmod +x entrypoint.sh

RUN mkdir i

VOLUME ["/usr/local/tomcat/webapps/i"]

ENTRYPOINT ["./entrypoint.sh","run"]