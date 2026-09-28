# GLPI + phpIPAM Docker

Déploiement de GLPI et phpIPAM avec Docker Compose.

## Architecture

- GLPI
- phpIPAM
- MariaDB 11
- Une base MariaDB dédiée à GLPI
- Une base MariaDB dédiée à phpIPAM

## Services

GLPI :
http://localhost:8080

phpIPAM :
http://localhost:8081

## Installation

1. Copier `.env.example` vers `.env`
2. Modifier les mots de passe
3. Démarrer les conteneurs avec Docker Compose

```bash
docker compose up -d
