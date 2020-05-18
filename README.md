# THP_Final_Project_Animal_Matching

>*Crossing, Blending, Mixing, Petting, Breeding*

## 1. Présentation
### LE site de rencontre pour animaux 

Les animaux de compagnie ont eux aussi besoin de compagnie.
Le but de cette application est de transposer le concept des sites de rencontres pour les êtres humains aux animaux domestiques. Cette application permettra aux maîtres des animaux d'aider leurs compagnons à quatres pattes à trouver l'âme soeur :heart_eyes:, et accueillir, si affinité, de nouveaux membres dans la famille :wink:.
Chiens & chats dans un premier temps - et si ça marche comme sur des roulettes on passe aux NAC et autres animaux exotiques : hamsters :hamster:, rats :rat:, crocodiles:crocodile:, koalas :koala:, tigres du bengal:tiger:, écrevisses :fried_shrimp:, etc.
L'idée est de proposer un site pour permettre aux animaux de compagnie de trouver leur **perfect match** selon des critères de sélection : 
* caractère
* pedigree
* race 
* couleur des poils 
* etc.


## 2. Parcours utilisateur

* **Step 1** : L'utilisateur (propriétaire) crée un profil.
* **Step 2** : L'utilisateur peut créer le profil (de son ou) de ses animaux de compagnie et faire des recherches selon des critères (tags associés à l'animal). 
* **Step 3** : Après avoir créé le profil de son :dog: :cat:, il pourra liker un autre profil, demander en ami et matcher si réciproque.
* **Step 4** : Si il y a **match**, il pourra accéder à l'autre profil et communiquer avec lui (:cat:?)
* **Step 5** : :smirk_cat: :smirk_cat: :smirk_cat: :scream_cat: *(disclaimer: pour cette étape on vous aidera pas)*


## 3. Concrètement et techniquement

### 3.1. Base de données
La base de données pourrait ressembler à :
- Une table User (pour le maître)
  - Nom (propriétaire)
  - Email
- Une table Pet
  - Nom
  - Espèce
  - Genre
  - Race
  - Photo
  - Description
- Une table Friendship/Like
- Une table Tag
- Une table City / Region *quand on aura du succès*

Un user peut avoir N pets et chaque pet 1 user. On se servira de Friendship pour les relations entre pets (N-N).
<div class="text-center">
    
![alt text](https://www.ohpacha.com/3627-large_default/manteau-pour-chien-flocon-rose.jpg)
    
</div>

### 3.2. Front

* Une page d'accueil
* Les views de Devise 
* Des cards pour les Pets (en index)
  ...possible rendu dynamique avec JS
* Le dashboard du User et les profils des Pets
* Une barre de recherche pour les Tags

Probable utilisation d'un thème Bootstrap et de Javascript. On pense que l'**UX** et l'**UI** sont <span style="color:red">particulièrement importantes</span> au vu du projet, surtout en comparant à la [concurrence qui existe déjà](http://www.rencontre-animaux.fr/). 

### 3.3. Backend

#### Backend
On risque d'avoir pas mal de travail côté back-end pour améliorer l'expérience utilisateur et ajouter des options (notamment via les API).
Envoie d'emails aux utilisateurs: :bell: notifications, :heart: matchs, :email: messages...

#### API envisagées : 
- [ ] Google Maps - Localisation des autres utilisateurs
- [ ] Instagram / Twitter - Associer des comptes déjà en lignes
- [ ] Stripes - Option de compte premium (*ex: nombre de likes illimités, ton animal en front page ou front list*)
- [x] Pexels - Choper des images libres de droits (#catfish)

### 3.4. La team crocket *plus rapide que la lumière*
Nous sommes déjà 5 prêts à faire de ce projet **la prochaine licorne :rainbow:**
* Raphaël Delannay *a tenu les 7 premières semaines de THP*
* Lucile Gentaz *quand tu commences elle a déjà fini :trollface: ...les chips* 
* Agnès Arthaud *fait des tisanes #Josiane*
* Milena Lazzaretti *fait de son mieux*
* Jhonnatan Rangel *qu'est-ce qui est jaune et qui attend ?*
## 4. La version minimaliste mais fonctionnelle qu'il faut avoir livré la première semaine

Le MVP se résume a créer les profils (User/ Pets), afficher l'ensemble des profils de Pets et pouvoir faire matcher 2 Pets entre eux.

Les utilisateurs ne pourront accéder au contact de l'autre qu'une fois que le match est fait et s'occuperont d'échanger entre eux (pas de :cat: [codé](https://www.youtube.com/watch?v=aeePeVUW6-k) pour le moment).

Pas de fonctionnalité de géographie, ou d'ajout du compte instagram/twitter ou encore de compte premium.


## 5. La version que l'on présentera aux jury

D'autres possibilités d'amélioration 
- [x] Rechercher par tags
- [x] Afficher des matchs de proximités (géolocalisation)
- [x] Carousel :circus_tent: (fake swipe ou *en vedette*)
- [x] Lier le compte instagram de l'animal
- [x] Gestion des mails avec Sendgrid
- [ ] Chat avec Twilio
- [ ] Compte Premium


## 6. Notre mentor
On le cherche toujours, alors si tu veux participer à ce projet n'hésite pas à nous contacter ! 

Nos contacts slack : 

Agnès : @Agnès Arthaud <br />
Jhonnatan: @Jo <br />
Lucile: @lucile gentaz <br />
Milena : @Milena Lazzaretti <br />
Raphaël: @Raphael <br />


<div class="text-center">
    
![alt text](https://www.ohpacha.com/4550-thickbox/robe-de-mariee-pour-chien-deguisement-chien.jpg)
    
</div>
