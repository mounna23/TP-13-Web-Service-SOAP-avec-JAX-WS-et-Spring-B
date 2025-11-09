# TP 13 : Web Service SOAP avec JAX-WS et Spring Boot
## Objectif du TP

Ce TP a pour objectif de :
Mettre en place un service web SOAP avec Spring Boot et Apache CXF.
Configurer les dépendances nécessaires pour un projet Spring Boot avec support SOAP.
Gérer des entités JPA dans un contexte de service web.

## Prérequis
Préparer :

- Un environnement de développement Java (Java 20 recommandé).
- Maven pour la gestion des dépendances.
- Une connaissance de base en Spring Boot et en services SOAP.
  
##### La structure finale du projet est la suivante :

<img width="1062" height="1908" alt="image" src="https://github.com/user-attachments/assets/4348009c-a3e2-4c8c-a853-b22f8f176350" />

## Tester le Service SOAP avec SoapUI

#### le fichier WSDL :

<img width="2940" height="1908" alt="image" src="https://github.com/user-attachments/assets/d2c69fc6-a834-4680-bf77-39c747c72b70" />

#### Tester les Méthodes du Service SOAP : 

 1. Tester la Méthode getComptes :
<img width="2940" height="1708" alt="image" src="https://github.com/user-attachments/assets/96e08634-4011-4474-b2ab-ab0e9fd57517" />

 2. Tester la Méthode getCompteById :
<img width="2940" height="1708" alt="image" src="https://github.com/user-attachments/assets/aa3e9ec1-6254-4311-8b1e-14ec36707e94" />

 3. Tester la Méthode createCompte :
<img width="2940" height="1708" alt="image" src="https://github.com/user-attachments/assets/265df43a-b92d-4e08-92b0-acc5e5460587" />

 4. Tester la Méthode deleteCompte :
    <img width="2940" height="1708" alt="image" src="https://github.com/user-attachments/assets/96419c57-460a-4604-9af7-40a9cb2f7079" />
    
## Conclusion :

Ce TP m’a permis de comprendre la mise en place d’un service SOAP avec Apache CXF sous Spring Boot, depuis la configuration du service et de la base H2 jusqu’à la publication du WSDL.
J’ai également appris à manipuler les annotations JAX-WS et JPA pour exposer et gérer des données via un service web.
