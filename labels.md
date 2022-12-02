# Annotations

## Répertoire d’immeubles localisés (RIL)

Le RIL contient la liste des adresses d’habitation des communes de 10 000 habitants ou plus et **de la plupart des communes de moins de 10 000 habitants dans les DOM.** Seules les communes des Antilles-Guyane de Sainte-Julie, Saül, Camopi et Ouanary n’ont pas de RIL.

Informations utiles :

- Un élément du RIL correspond à la plus petite unité contenant des logements repérable sur le terrain à partir de son adresse. La plupart du temps, il s’agit d'un bâtiment associé à une adresse. Il peut également s’agir de deux bâtiments ou plus s’il n’est pas possible de les distinguer sur le terrain (par exemple, via un affichage "bâtiment A", "B" visible sur le terrain)
- Informations contenues dans le RIL pour chaque adresse :
    - un type (avenue, boulevard, rue, impasse, chemin, sente, etc.) et un nom de voie ;
    - un numéro dans la voie, éventuellement un suffixe (bis, ter, A, B, etc.) ;
    - un complément d’adresse (lieu-dit, numéro de bâtiment, etc.)
    - des coordonnées géographiques X et Y (cf. 2.3 pour la précision de ces coordonnées) ;
- Pour chaque ensemble immobilier :
    - la catégorie (habitation, communauté, établissement touristique) ;
    - le type (maison individuelle, ensemble de maisons individuelles, immeuble, etc.) ;
    - l’actualité (habitable, en construction, périmé) ;
    - le nombre de logements ;
    - la date de construction ;
    - la date d’entrée dans le répertoire ou la date de dernière modification ;
    - le numéro de permis de construire ;
    - le numéro de parcelle cadastrale.
- Référentiels géographiques des coordonnées :
    - UTM zone 20N en Guadeloupe et Martinique (code EPSG : 4559)
    - UTM zone 22N en Guyane (code EPSG : 2972)
    - UTM zone 38S à Mayotte (code EPSG : 4471)
    - UTM zone 40S à La Réunion (code EPSG : 2975)

### Processus de mise à jour en Antilles-Guyane :

Aux Antilles-Guyane, pour les habitations et les établissements touristiques, une campagne de mise à jour du RIL se déroule de novembre à octobre. Le RIL est mis à jour principalement par une enquête annuelle sur le terrain, appelée enquête cartographique, mais aussi à partir des permis de construire. Le RIL est également mis à jour avec les résultats du recensement, par les fiches navettes de novembre à mai et par les résultats de collecte à partir de mai. Le CorRIL doit ensuite expertiser le RIL avant le 30 septembre pour que les RIL soient livrés par les établissements régionaux de l’Insee dans leur version définitive avant le 31 octobre.

#### Enquête cartographique

L’enquête cartographique se déroule sur le terrain de fin avril à mi-août, avec un traitement par les gestionnaires jusqu’à fin août. Des enquêteurs de l’Insee mettent à jour les îlots concernés par la collecte de l’année suivante (en petite commune, tous les îlots appartiennent au même groupe de rotation). Par exemple, cette enquête a porté en 2021 sur les îlots du groupe de rotation n°4, dans lesquels ont été tirées les adresses collectées en 2022. Elle met également à jour les communautés. Elle est quasi-exhaustive, c’est donc la principale source de mise à jour du RIL en Antilles-Guyane. Seuls quelques îlots isolés sont enquêtés uniquement lors de la tournée de reconnaissance de la collecte (enquête dite « 2 en 1 »). De plus, certains îlots désignés par les communes comme n’ayant pas évolué depuis 5 ans ne sont pas enquêtés exhaustivement. Le RIL est donc mis à jour chaque année sur un cinquième du territoire de la commune, ce qui fait qu’il est plus ou moins à jour selon les îlots.

#### Permis de construire

Les permis sont fournis par le ministère chargé du logement et permettent aux équipes recensement de mettre à jour le RIL suite aux constructions de logements. Les permis sont livrés 4 fois par campagne (en novembre, février, avril et août). Les nouvelles constructions repérées lors du traitement des permis, ainsi que certaines habitations dont on veut vérifier l’état, sont envoyées aux mairies via dans des listes **d’entités adressées à confirmer** (EAAC). Les mairies peuvent alors répondre aux listes en signalant quelles constructions sont devenues habitables et peuvent être prises en compte pour le recensement. C’est la commune qui choisit le nombre d’envois qu’elle souhaite recevoir, de 1 à 4.

#### Intégration des résultats du recensement

#### Expertise des communes

#### Livraison du RIL

La livraison des RIL marque la fin de la campagne. La livraison des RIL fait suite à l’expertise légale réalisée par les communes avant le 30 septembre. Avant de procéder à la livraison des RIL, les équipes recensement doivent justifier les fortes évolutions du nombre de logements habitables des îlots comprenant plus de 100 logements et des communes.

Première livraison des RIL entre mi-septembre et mi-octobre. Les RIL livrés sont contrôlés par l’Insee. Ces contrôles peuvent conduire à des suspensions qui nécessiteront de nouvelles livraisons des RIL avec une échéance fixée au 31 octobre. Quand les RIL livrés sont validées, l’Insee constitue les bases de sondages d’adresses et procède au tirage de l’échantillon des adresses à recenser pour l’enquête annuelle de recensement à venir.

#### Mise à jour des communautés

Intégration des fichiers administratifs. Les équipes recensement reçoivent, d’avril à juin, des listes d’ouvertures et de fermetures potentielles de communautés après traitement par l’Insee de fichiers administratifs provenant par exemple du Ministère de l’Éducation pour les établissements scolaires ou du Ministère des Solidarités et de la Santé pour les établissements sanitaires et sociaux.

### Processus de mise à jour à la Réunion

Similaire au processus Antilles-Guyane, campagne de mise à jour du RIL de novembre à octobre. Le RIL est mis à jour principalement par les permis de construire, les données fiscales et une enquête annuelle sur le terrain pour vérifier l’état des habitations en construction et de certaines parcelles cadastrales, appelée enquête cartographique en différentiel.

De 2011 à 2016, la principale source de mise à jour était l’enquête cartographique en différentiel, qui portait uniquement sur un seul groupe de rotation. Depuis 2017, les données fiscales sont mobilisées en complément de l’enquête cartographique en différentiel. Un rattrapage est effectué pour pouvoir mettre à jour tous les groupes de rotation chaque année à partir de 2023.

#### Les enquêtes terrain

**L’enquête cartographique en différentiel** est préparée à partir de mars et se déroule sur le terrain de mai à décembre. Les enquêteurs examinent des habitations en construction et leurs alentours pour voir si elles sont devenues habitables. Ils examinent également les habitations repérées grâce aux données fiscales. Pour cela, des gestionnaires traitent également des EA ou des parcelles cadastrales sur lesquelles on soupçonne un déficit dans le RIL. Elles sont repérées à la suite d’un appariement entre le RIL et des données fiscales (Fichiers démographiques sur les logements et les individus, qui apparie notamment des sources fiscales), réalisé par l’Insee. Les données fiscales constituent donc une source complémentaire à celle des permis pour améliorer la qualité du RIL. 

**L’enquête de mesure de la qualité du RIL** (EMQR) à La Réunion se déroule sur le terrain d’octobre à décembre. Les enquêteurs effectuent un ratissage complet d’îlots du groupe de rotation. L’objectif est d’évaluer la qualité du RIL sur ce groupe de rotation et de voir des
adresses habitables qui n’ont pas été repérées lors de l’enquête cartographique en différentiel.

### Processus de mise à jour à Mayotte

Identique au processus pour Antilles-Guyane.

### Dictionnaire

| Variable  | Longueur          | Description |
| :-------- |:-----------------:| :---------- |
| NumVoie | 4          | Numéro dans la voie (0 pour les adresses non normalisées) |
| Suffixe | 4          | Indice de répétition ou suffixe : BIS, TER, QUA...ou encore A, B... |
| TypeVoie | 4          | Type de voie selon norme DGFiP |
| LibVoie | 32          | Libellé de la voie |
| Rivoli | 7          | Code Rivoli de la voie |
| Complément | 32          | Complément d’adresse |
| Statut | 3          | Catégorie et actualité : habitation habitable (HAB) ou en cours de construction (EC), communauté (CMT), établissement touristique (HOT) |
| ID_Externe | 17          | N° de Permis de construire ou identifiant de la communauté au répertoire des communautés ou identifiant du dernier recensement exhaustif (soit en général celui de 1999) ou à blanc |
| NbLogement | 4          | Nombre de logements habitables à cette adresse (pour les adresses d’habitation, et mis à zéro pour les accès secondaires) |
| MAD_REFCAD | 10          | Référence cadastrale |
| Principal | 1         | 'O' pour OUI s’il s’agit d’un accès principal 'N' pour NON s’il s’agit d’un accès secondaire |
| iris2008 | 4          | Code IRIS |
| Id_ea(*) | 15          | Identifiant Insee pour le RIL |
| X | 10          | Valeur de l’abscisse exprimée avec 2 décimales (dans la projection choisie) |
| Y | 10          | Valeur de l’ordonnée exprimée avec 2 décimales (dans la projection choisie) |
| depcom | 5          | Code commune |
