# Mini Projet Web : Phase 2
## Description design balsamiq 

### Les éléments communs :

comprenant :<br>
*   La barre de présentation generale pour l'administrateur contenant le logo et le nom de la division , des mots de bienvenue et un bouton d'ajout des candidats à la liste des membres disponibles (présent seulement dans la landing page) qui charge la page insert contenant un formulaire rempli par l'administrateur .
*  Une liste défilable présantant des photos miniaturisées et les noms complets des astronautes disponibles surmonté d'une barre de recherche pour ces derniers . <br>


### Landing page :

![156313098_278654926946513_5794737332705628251_n](https://user-images.githubusercontent.com/78099799/109582480-8bc29880-7afe-11eb-9e8b-66f1b6521e5f.png)


c'est la page d'accueil qui presente des informations sur l'équipe en cours à bord de la station spatiale y compris des graphiques représentant les scores et les états de santé (psychologie , generale , niveaux de radiations suite aux spacewalks ...) mis à jour des membres de l'équipe , la statut de la mission (niveau d'achèvement, niveau d'oxygène restant , niveau de synchronisation de groupe , temps écoulé ) et quelques informations sur l'équipe de surveillance et de controle de la mission actuelle .


### On hover :

![156395119_5098521593554410_5599512221318590344_n](https://user-images.githubusercontent.com/78099799/109582570-ab59c100-7afe-11eb-9a6b-b7c496291654.png)


En survolant un membre de la liste des astronautes disponibles (nom ou photo), un pop-up apparait , il contient une photo élargi , le nom et des informations générales sur cet astronaute .

### On click :

![155839658_434986834441579_4162038546355980622_n](https://user-images.githubusercontent.com/78099799/109582604-bca2cd80-7afe-11eb-9afe-e445f42b3b93.png)

Lorsqu'on clique sur un astronaute le bouton d'ajout des candidats présent dans la barre de présentation generale devient le bouton de suppression de l'astronaute selectionné de la liste des astronautes disponibles . Tous les informations de ce dernier apparaient au-dessous sous differentes formes (nom , alias , drapeau de son pays d'origine , à bord l'iss ? , infos generales , citation favorite , constellation favorite , traits de personalité , compétences techniques , tâches terminées avec succès , rapport complet , qui l'a recommandé (si c'est le cas) , coéquipiers recommandés , infos de contact) à l'addition d'une partie présentant les membres choisis pour la prochaine mission (appelé la barre d'équipage de l'expédition prochaine) avec la possiblité d'ajouter l'astronaute selectionné et/ou soustraire un ou plus des autres membres à travers un drag and drop (glisser et déposer) un bouton de retour vers la landing page et un bouton d'edition des informations sont aussi présents .

### On Delete :
![155829987_3050333505185567_5922024410456828164_n](https://user-images.githubusercontent.com/78099799/109582676-da703280-7afe-11eb-98e2-131a6d88c2da.png)

Un message temporaire de validation confirmant la suppression d'un astronaute de la liste d'équipage de l'expédition prochaine .

### On add :
![155456559_1106170239883495_6083071507788598023_n](https://user-images.githubusercontent.com/78099799/109582717-ecea6c00-7afe-11eb-8611-0f088bb7e627.png)

Un message temporaire de validation confirmant l'ajout de l'astronaute selectionné à la liste d'équipage de l'expédition prochaine .

### After add or delete :
![155808055_168436324943438_1850342074115892516_n](https://user-images.githubusercontent.com/78099799/109582741-fd024b80-7afe-11eb-9541-9b23c1c62e05.png)

après un drag and drop sur un astronaute nous restons dans la même page mais avec une petite différence, l'astronaute ajouté est en fait présent dans l'équipage de l'expédition suivante. et après suppression, l'astronaute supprimé n'est plus dans l'équipage.

### On modif :
![156598492_262408895448053_4966746815989906252_n](https://user-images.githubusercontent.com/78099799/109582774-0d1a2b00-7aff-11eb-967b-bf9ae3b0e84b.png)

lors d'un clique sur l'icône d'édition (présent dans la barre d'équipage de l'expédition prochaine) on sera redirigé vers la page des modifications des informations de l'astronaute déja affiché. Après les changements , si on veut les valider on clique simplement sur le bouton de confirmation , sinon on clique sur reset et tous les modifications seront annulées .

### On insert : 
![156375515_340736530615653_5268041357981832423_n](https://user-images.githubusercontent.com/78099799/109582824-21f6be80-7aff-11eb-95f7-4a9557f388a9.png)

la page insert qui contient un formulaire contenant plusieurs champs rempli par l'administrateur permettant l'ajout d'un candidat a la liste des astronautes disponibles qui devient ensuite prét a être ajouté aux membres choisis pour la prochaine expedition (via la barre d'équipage de l'expédition prochaine) . Ii on veut valider on clique simplement sur le bouton de confirmation , sinon on clique sur reset et tous les champs deviennent vide de nouveau . 2 boutons de navigation sont aussi présent en bas de page l'un pour retour a l'accueil et l'autre pour retour en haut de page .
