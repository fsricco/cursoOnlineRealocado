FROM openjdk:8-jre-slim
WORKDIR /plataformaDeCursosOnline
COPY target/*.war /plataformaDeCursosOnline/plataformaDeCursosOnline-0.0.1-SNAPSHOT.war
EXPOSE 9090
CMD java -XX:+UseContainerSupport -Xmx512m -Dserver.port=9090 -jar plataformaDeCursosOnline-0.0.1-SNAPSHOT.war
