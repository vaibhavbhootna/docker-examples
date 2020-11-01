FROM openjdk:oraclelinux8
WORKDIR /app
COPY soap-service-using-spring-0.0.1-SNAPSHOT.jar ./
COPY start.sh ./
RUN chmod +x /app/start.sh
EXPOSE 8080
CMD ["./start.sh"]