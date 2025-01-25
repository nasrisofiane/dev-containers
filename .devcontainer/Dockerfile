# Utilisez l'image Debian 12 comme base
FROM debian:12

# Mettre à jour les sources et installer les dépendances nécessaires
RUN apt-get update && \
    apt-get install -y \
    openjdk-21-jdk \
    maven \
    git

# Exposer le port 8080 (ajuster si nécessaire)
EXPOSE 8080