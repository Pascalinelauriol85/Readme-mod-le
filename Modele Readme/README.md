# THP_ProjetFinal
Proposer un site fonctionnel de notre choix

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)

## 0. Titre
IZITEAM
## 1. Présentation
L'objectif est de créer une plate-forme de mise en relation de porteurs de projets et de développeurs informatiques. 
Le service est totalement gratuit parce que lorsqu'on a une bonne idée on n'a pas forcément le budget pour la développer 💪.
## 2. Parcours utilisateur
Une landing page avec la présentation du concept IziTeam (un bon gros <code>bootstrap</code> avec de jolis effets) 
La liste des derniers inscrits qui proposent leurs compétences. 
La liste des derniers projets proposés. 
Avant de consulter quoi que ce soit l'utilisateur du site devra se connecter. 
Ensuite il a la possibilité d'aller consulter les projets et de voir les personnes qui sont inscrites. 
Le porteur de projet définira son projet via un formulaire. 
Possibilité pour les utilisateurs de se contacter entre eux.
## 3. Concrètement et techniquement
Site écrit en <code>Rails</code>, hebérgé sur <code>Heroku</code>. 
Base de données <code>PostgreSQL</code>. 
Front-end en <code>HTML5</code> et <code>bootstrap</code>. 
Un minimum de Javascript pour commencer. 
Un minimum de <code>Javascript</code> pour commencer. 
Il faudra pouvoir envoyer des mails automatiquement.

### 3.1. Base de données
@@ -34,7 +34,7 @@ Il faudra pouvoir envoyer des mails automatiquement.
Le design de la base est effectué en premier lors de la conception de l'application.
On modélise sur dbdiagram.io/ puis on exporte le modèle en <code>PostgreSQL</code>.
Ça nous permettra de comparer si on genere à l'identique.  
Le modèle sera conçu en 3e forme normale .. Au minimum [3FN](https://fr.wikipedia.org/wiki/Forme_normale_(bases_de_donn%C3%A9es_relationnelles))]
Le modèle sera conçu en [3e forme normale](https://fr.wikipedia.org/wiki/Forme_normale_(bases_de_donn%C3%A9es_relationnelles)) .. au minimum !

### 3.2. Front

@@ -69,16 +69,16 @@ Des moussaillons motivés, compétents et sympas 😎.. Mais enfin si on est arr
- <code>Discord</code> : Vocal ouvert en continu.
- <code>Rspec</code> : Et oui on va faire des tests ... Même sur la partie objet.

Perso, ~~je peux boire trois pintes de bière sans trop de difficulté~~ j'ai pas eu de difficultés particulières avec <code>Heroku</code> et <code>GitHub</code>. Le code que j'écris en <code>ruby</code> me fait penser à du 💩 donc je ne ferai pas office de référent technique. Par contre je connais très bien les bases de données et le design de DB. <code>Bootstrap</code> me plaît bien. Et je peux m'occuper des tests sous <code>Rspec</code>. 
Perso, ~~je peux boire trois pintes de bière sans trop de difficulté~~ j'ai pas eu de difficultés particulières avec <code>Heroku</code> et <code>GitHub</code>. Le code que j'écris en <code>ruby</code> ça me fait penser à du 💩 donc je ne ferai pas office de référent technique. Par contre je connais très bien les bases de données et le design de DB. <code>Bootstrap</code> me plaît bien. Et je peux m'occuper des tests sous <code>Rspec</code>. 

- Un volontaire pour gerer le Trello.
- Un volontaire pour gérer le Trello.
- Un volontaire pour garantir la qualité du code de l'équipe.
- Un/deux volontaire(s) pour creuser <code>Bootstrap</code>.
- Un volontaire pour nous créer des données cohérente avec <code>Faker</code>.
- Il faudrait quelqu'un qui s'intéresse à <code>Bundler</code> mais là je crois que c'est difficile à trouver  
 **... Tout ça en mode détendu ... On ne va pas révolutionner internet.**

Celui qui arrive à faire fonctionner ce qui suit est recruté direct
Celui qui arrive à faire fonctionner ce qui suit est recruté direct  
`config/initializers/backtrace_silencers.rb  
Rails.backtrace_cleaner.add_silencer { |line| line =~ /lib/ }`

@@ -91,7 +91,7 @@ Rails.backtrace_cleaner.add_silencer { |line| line =~ /lib/ }`
- Liste des développeurs.
- Un formulaire qui permet de proposer un projet.
- Un formulaire qui permet de proposer ses compétences.
- CRUD et REST of course.
- CRUD et REST of course.  
 ... Le tout fonctionnel sur <code>Heroku</code>

## 5. La version que l'on présentera aux jury