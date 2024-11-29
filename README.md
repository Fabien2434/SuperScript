#!/bin/bash

# Vérification des arguments:
PROJECT_NAME="$1"

PROJECT_DIR="./$PROJECT_NAME"

# Création du dossier Projet:
mkdir -p "$PROJECT_DIR"

# Création du fichier README.md:
touch README.md /home/fabien/Projets/SuperScript/

# Création du fichier Script:
SCRIPT_FILE="$PROJECT_DIR/$PROJECT_NAME.SH"
