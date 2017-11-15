# mon docker file

# on récupère la dernière version de debian
FROM debian:latest

# on déclare un propriétaire du fichier
MAINTAINER nicolas.andrieux27@gmail.com

# mettre a jour les branches pour être sur d'avoir la dernière version
RUN apt-get update

# suppression des fichiers archive qui sont dans le temp
# RUN apt-get clean all

# on install git
# -y pour valider de base
RUN apt-get install -y git

# on install apache
# -y pour valider de base
RUN apt-get install -y apache2

#exposition du port 80
EXPOSE 80








# Pour lister les images:
# docker images

# Pour supprimer une image
# docker rmi IMAGE_ID

# Pour lister les instances d'image en cours d'éxécution
# docker ps

# Pour stopper une execution
# docker stop INSTANCE_ID

# Pour supprimer une execution
# docker rm INSTANCE_ID



# Déclaration des variable d'environnement dans le docker file
#
# Les commandes RUN sont éxécuter en sudo
#
#
#
#