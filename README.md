# Springboot-Maven-RestApi
L'objectif de  ce projet est de mettre en place une API REST permettant de gérer les employés via des opérations CRUD (Create,Read,Update,Delete).

Les données sont stockées en mémoire à des fins de test.

## Fonctionalités 
* Créer un employé
* Lire les informations des employés
* mettre à jour les données des employés
* Supprimer un employé


## Dépendances utilisées 
  * Spring Data JPA
  * Spring Web
  * Lombok
  * Rest Repositories
  * H2 Database
    
## Prérequis 
Assurer vous d'avoir ces élements installés sur votre machine :
  * JDK 21 : ce projet est compatible qu'avec Jdk 21 
  * TOMCAT pour lancer le projet
  * MAVEN

## Installation et Execution 
1. Cloner le dépôt
   ```bash
   git clone https://github.com/Cyrille-18/Springboot-Maven-RestApi.git
2. Accéder au repertoire
   ```bash
   cd Springboot-Maven-RestApi
3. Compiler le projet avec maven
   ```bash
   mvn clean install
4. Lancer le projet
   ```bash
   mvn spring-boot:run
## API Endpoints
voici les endpoints de l'Api :
* ``GET /employes`` : recupère la liste de tous les employés
* ``POST /employes`` : ajoute un nouvel employé
* ``PUT /employes/{id}`` : mettre à jour les informations d'un employé
* ``DELETE /employes/{id}`` : supprime un employé
   
   
   
