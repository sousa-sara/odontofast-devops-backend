# Use a imagem base leve
FROM openjdk:17-slim

# Defina o diretório de trabalho
WORKDIR /app

# Copie o arquivo .jar para o container
COPY target/backend.jar /app/backend.jar

# Execute o aplicativo
ENTRYPOINT ["java", "-jar", "backend.jar"]
