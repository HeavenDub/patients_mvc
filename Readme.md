# Application Spring Boot de gestion de patients  

### Encadré par Mr Mohammed Youssfi

L'application est une MVC Spring boot utilisant des extensions tel que :
* [MySQL comme Database ]
* [ThymeLeaf comme moteur de template pour les pages html]
* [Lombok Pour generer les getters/setters et autres ...]
* [JPA Buddy pour gerer les modeles de DATA]
* [Spring Security pour hoster une page login/logout et permettre les fonctions Admin et autres..]
* [Hibernate solution open source de type ORM (Object Relational Mapping) qui permet de faciliter le développement de la couche persistance d'une application.]

Le but de l'application est de gerer les patients d'un soit disant hopital, tout en ayant la possibilité d'utiliser les methodes CRUD 
afin de recevoir ces données sous fourmes de tableaux bien organisé , facilitant aux utilisateurs la vue de données.

![image](https://user-images.githubusercontent.com/44275564/165290965-6c671c62-2f20-47b3-962e-1215b42bc6f0.png)

On commence par l'interface Spring Boot Security  qui permettra le login/logout
![image](https://user-images.githubusercontent.com/44275564/165291205-6d80e63e-ccb5-4a1f-9ef3-29b0c34bcf59.png)

NavBar D'un utilisateur normal
![image](https://user-images.githubusercontent.com/44275564/165291346-6e15f53c-6cb0-40d4-8042-7364c34057c0.png)

Et ceci est l'interface patient d'un utilisateur normal, pas d'ajout et pas de modification.Mais  , quand il s'agit de compte admin declaré auparavant,
l'interface changeras en fonction et affichera ceci
![image](https://user-images.githubusercontent.com/44275564/166076556-c6ac539d-3178-47b3-881a-f326d2381406.png)

 Et vous pouvez y voir les bouttons de supression --->
 
 ![image](https://user-images.githubusercontent.com/44275564/166076623-a8f2c5b4-aeee-4085-bf9c-0066707cca3c.png)

 Avec une demande de verification de la supression 
 
 ![image](https://user-images.githubusercontent.com/44275564/166076676-b906756b-d055-4307-917a-6686059ade1c.png)

Mais pour l'edit voila le bouton: ![image](https://user-images.githubusercontent.com/44275564/166076739-a5280e4c-9007-4174-a3ec-5cfe8b3c4ffc.png)

et apres le click :

![image](https://user-images.githubusercontent.com/44275564/166076774-47a4b5cb-d331-425f-800d-302b668c2332.png)



