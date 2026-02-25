TP - Système de Réservation de Salles avec JPA/Hibernate

 Description
Ce TP a pour objectif de créer un système de réservation de salles en utilisant JPA/Hibernate afin d assurer la moddelisation des données et la gestion des relations entre les entités.

 Objectifs Pédagogiques
- Créer un système de réservation de salles avec des relations entre entités
- Implémenter une relation ManyToMany entre Salle et Équipement
- Configurer et tester différentes stratégies de cascade
- Expérimenter la suppression orpheline (orphanRemoval)

 Prérequis
- Connaissances de base en Java
- Compréhension des concepts de la POO
- Notions de base sur les bases de données relationnelles
- Maven installé
- JDK 8 ou supérieur

Technologies Utilisées
- **Java** - Langage de programmation
- **Maven** - Gestion de dépendances
- **Hibernate/JPA** - ORM pour la persistance des données
- **H2 Database** - Base de données en mémoire pour le développement

 Structure du Projet



 Concepts Clés
Relations JPA
@OneToMany : Relation un-à-plusieurs
@ManyToOne : Relation plusieurs-à-un
@ManyToMany : Relation plusieurs-à-plusieurs
@JoinTable : Table de jointure pour les relations ManyToMany

Cascade Types
PERSIST : Propage l'opération persist
MERGE : Propage l'opération merge
REMOVE : Propage l'opération remove
ALL : Propage toutes les opérations
orphanRemoval
Supprime automatiquement les entités enfants lorsqu'elles sont dissociées de leur parents

Requêtes SQL Générées
Le TP permet d'observer les requêtes SQL générées par Hibernate pour :
La création des tables
L'insertion des données
La gestion des relations
Les opérations de cascade
<img width="1600" height="863" alt="Capture d’écran 2026-02-23 202857" src="https://github.com/user-attachments/assets/580e9dff-fa2a-49c7-b4e0-7420544f000b" />

<img width="1595" height="862" alt="Capture d’écran 2026-02-23 203255" src="https://github.com/user-attachments/assets/f4db7c0c-9a92-455b-b8cd-c6e584b5365e" />

<img width="1598" height="865" alt="Capture d’écran 2026-02-23 203757" src="https://github.com/user-attachments/assets/8d77aa52-6b73-4bd3-a913-b489c6dec4e9" />


<img width="1600" height="860" alt="Capture d’écran 2026-02-23 205420" src="https://github.com/user-attachments/assets/1f62c089-015b-4152-8e94-dba9e4c6b9a7" />



<img width="1600" height="862" alt="Capture d’écran 2026-02-23 205510" src="https://github.com/user-attachments/assets/ca43add6-4fbc-40a9-97a2-e5d089b3374b" />


<img width="1600" height="860" alt="Capture d’écran 2026-02-23 205628" src="https://github.com/user-attachments/assets/13c6eb3d-8b57-42b8-948e-a76e482b59a4" />


<img width="1600" height="860" alt="Capture d’écran 2026-02-23 205813" src="https://github.com/user-attachments/assets/4deb3591-863b-42fe-a80f-7a2b7b5bc46b" />

<img width="1600" height="863" alt="Capture d’écran 2026-02-23 205932" src="https://github.com/user-attachments/assets/01267dc1-61b2-4e40-b53e-229edd88aaf3" />



<img width="1600" height="863" alt="Capture d’écran 2026-02-23 210014" src="https://github.com/user-attachments/assets/c3a64ee5-248b-447d-afc6-734e5b01b60c" />


<img width="1593" height="863" alt="Capture d’écran 2026-02-23 210055" src="https://github.com/user-attachments/assets/ac93488d-e7cd-4aeb-83d7-8fad9e858f31" />


<img width="1600" height="862" alt="Capture d’écran 2026-02-23 210131" src="https://github.com/user-attachments/assets/4861cbf9-e3fd-4bb0-b684-536def805d8b" />

<img width="682" height="677" alt="Capture d’écran 2026-02-25 145702" src="https://github.com/user-attachments/assets/5ae03afc-c82a-4827-b7ee-69315bec0804" />


