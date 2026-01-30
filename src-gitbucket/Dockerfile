FROM eclipse-temurin:17.0.17_10-jre-noble

ADD https://github.com/gitbucket/gitbucket/releases/download/4.45.0/gitbucket.war /opt/gitbucket.war

RUN ln -s /gitbucket /root/.gitbucket

CMD ["sh", "-c", "java -jar /opt/gitbucket.war"]