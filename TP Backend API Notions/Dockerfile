# Utiliser une image de base avec JDK (Java Development Kit)
FROM openjdk:21

# Copier le fichier .class dans le conteneur
COPY Main.class /app/Main.class

# Définir le répertoire de travail
WORKDIR /app

# Exécuter la classe Java
CMD ["java", "Main"]