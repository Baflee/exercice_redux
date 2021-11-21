# exercice_redux


##Exercice


Vous êtes l’architecte du système informatique de SpaceX.

Votre mission, si vous l'acceptez, est de modéliser et permettre les changements d'état du programme d'atterrissage en garantissant aucun bug.

Pour cette mission, vous avez choisi d'utiliser Redux afin de contrôler chaque changement d'état dans des reducers testé sous tous les angles.

De cette manière, vous évitez que le programme atteigne un état inattendu : chaque changement d'état passe par les reducers que vous pensez !

 

Le programme d'atterrissage contrôle l'angle des ailerons ainsi que la poussée du réacteur principal ainsi d'assurer un atterrissage sans faute !

Pour y parvenir, il garde également le contrôle des mesures atmosphériques : la pression, la température, le taux d'humidité et la vitesse du vent.

Tous ces paramètres influent sur la poussée et les angles à ajuster lors de l’atterrissage.

 

Heureusement pour vous, l'équipe R&D a mis une fonction pour calculer les angles des ailerons et la poussée du réacteur nécessaire à un atterrissage en douceur en fonction des paramètres météo.

Il suffit d'appeler calculateNewParams(weatherConditions). Vous devez néanmoins indiquer à l'équipe R&D l'interface de weatherConditions et de l'objet retourné pour qu'ils terminent cette fonction.

 

Langage à utiliser : Typescript

 

A. (20pts) Proposez une modélisation de l'état du programme d'atterrissage

 

B. (5pts) Proposez les actions de changement d'état : mise à jour des conditions météo partielle ou totale, des angles des ailerons et de la poussée du réacteur

 

C. (10pts) Ecrivez les reducers (avec tests)

## Modélisation
