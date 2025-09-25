FROM openjdk:8-jdk-slim
WORKDIR /app
ENV SA_LOGIC_API_URL=http://localhost:5000
COPY target/*.jar app.jar
EXPOSE 8080
CMD ["java","-jar","app.jar","--sa.logic.api.url=${SA_LOGIC_API_URL}"]