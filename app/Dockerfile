# Utilisation d'une image de base Python
FROM python:3.8-slim

# Définir le répertoire de travail
WORKDIR /app
# Installer les dépendances
RUN pip install --upgrade pip

# Copier les fichiers nécessaires
COPY . /app
ENV NAME World
# Exposer le port sur lequel l'application va tourner
EXPOSE 5000

# Commande pour démarrer l'application
CMD ["python", "app.py"]