FROM  maven:3.9.9-eclipse-temurin-21
WORKDIR /src
COPY pom.xml .
RUN  mvn dependency:go-offline -B
COPY src/ .
COPY data/jugadores.json .
COPY data/grupos.json .    
ENV APP_DATA_PATH=C:\Users\Alumno\Downloads\mundial-main\mundial-main
EXPOSE 8080


