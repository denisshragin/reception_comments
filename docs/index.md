---
title: Écrire un commentaire  # This changes the browser tab title
---

:memo: Afin de rendre les commentaires ajoutés dans les CAO plus clairs, plus cohérents et exempts de fautes d'orthographe et de grammaire, plusieurs commentaires prédéfinis ont été modifiés et plusieurs nouveaux commentaires ont été ajoutés dans LIMS en décembre 2025.
 
**Quelques règles de base pour écrire de bons commentaires :**

- Ne pas laisser la première ligne vide ;
- Ne pas laisser de lignes vides entre les commentaires ;
- Mettre un point « . » à la fin d'une phrase ;
- Mettre une espace avant et après « : » ;
- Mettre chaque commentaire sur une nouvelle ligne ;
- Mettre la mention « Commentaires du client : » avant les commentaires du client ;
- Mettre une espace entre le nombre et l'unité de mesure, par exemple « 10.36 mg/L » ;
- Pour les échantillons de BNQ, utiliser le commentaire prédéfini en changeant seulement le numéro d'échantillonneur ;
- Utiliser le nom d'analyse complet dans les commentaires, sans abréviations, sauf pour les analyses qui comportent déjà des abréviations reconnues (COV, par exemple).


### Mieux comrendre le message du client sur le CP

Il n'est souvent pas facile de déchiffrer ce qui est écrit sur le CP ; cependant, en connaissant les paramètres et les unités associés, il est plus facile de bien comprendre le message du client. Dans le tableau ci-dessous, les paramètres et les unités de mesure les plus fréquents sur les CP des clients sont présentés.

| Paramètre      | Unité        | Unité                         |
|----------------|--------------|-------------------------------|
| Température    | °C           | degré Celsius                 |
| Conductivité   | µS/cm        | microsiemens par centimètre   |
| oPO₄           | mg/L         | milligramme par litre         |
| Alcalinité     | mg CaCO₃/L   | milligramme CaCO₃ par litre   |
| Débit          | m³/j         | mètre cube par jour           |


### Compléter le commentaire général prédéfini

Plusieurs commentaires prédéfinis sont conçus de façon générale et doivent être complétés en ajoutant l'information notée sur le CP, comme, par exemple, la température mesurée par le client (« Température mesurée par le client : * °C. ») ou la date et l'heure d'échantillonnage (« Échantillon composé 24 heures, soit du * au *. »). Il peut s'agir également de l'information obtenue au moment de la réception, par exemple un délai dépassé pour l'une des analyses à l'arrivée au laboratoire (« L'analyse de XXX a été effectuée dans un délai dépassé. »). Dans ces cas, les symboles « * » et les lettres « XXX » (« YYY », « ZZZ ») doivent être remplacés correctement.

S'il s'agit d'un commentaire contenant « * » (sauf le commentaire **« * La température a été omise lors de la réception de l'échantillon. »**), il faudrait remplacer « * » par la valeur appropriée (date, heure, température) ; cependant, il ne faudrait pas supprimer les espaces qui entourent « * », ni ajouter de nouvelles espaces avant ou après.
Par exemple : « Température à la réception : * °C. » doit être correctement modifié comme « Température à la réception : 15.2 °C. » et non comme « Température à la réception :    15.2°C. ».
S'il s'agit d'un commentaire contenant « XXX » (« YYY » ou « ZZZ »), il faudrait remplacer « XXX » par le nom d'analyse complet.
Par exemple : « L'échantillon pour l'analyse de XXX a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. » doit être modifié comme suit : « L'échantillon pour l'analyse du pH-15 °C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. » (**« XXX » a été remplacé par « le pH-15 °C »**).
 
 
Par exemple, au lieu d’utiliser le commentaire « pH reçu et analysé hors délai », il faudrait utiliser le commentaire prédéfini *« L’échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »*
ou *« L'échantillon pour l'analyse du pH EU a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »*
ou les deux commentaires ensemble si les deux analyses pH-15°C et pH EU sont demandées.

*« L'échantillon pour l'analyse du pH EU a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client*.  
*L'échantillon pour l'analyse du pH-15°C a été reçu après l'expiration du délai de conservation réglementaire. L'analyse a été effectuée à la demande du client. »*
 
 
### Commentaires pour les analyses de la DBO

L'analyse de la Demande biochimique en oxygène est une analyse avec un court délai analytique ; cependant, l'échantillon peut être congelé pour prolonger la durée de conservation. Présentement, dans LIMS, il existe 6 paramètres distincts pour l'analyse de la demande biochimique en oxygène :

| Paramètre | Nom complet                                                |
|---------- |------------------------------------------------------------|
| EDCDBOT01 | Demande biochimiqe en oxygène totale-5 jours               |
| EDCDBOT04 | Demande biochimiqe en oxygène totale-5 jours non-congelé   |
| EDCDBOC01 | Demande biochimiqe en oxygène carbonée-5 jours             |
| EDCDBOC02 | Demande biochimiqe en oxygène carbonée-5 jours non-congelé |
| EDCDBOS01 | Demande biochimiqe en oxygène dissous-5 jours              |
| EDCDBOSC1 | Demande biochimiqe en oxygène carbonée et dissous-5 jours  |

Étant donné que toutes les analyses de la Demande biochimique en oxygène sont effectuées en 5 jours, et que les analyses EDCDBOT01 et EDCDBOT04, ainsi que EDCDBOC01 et EDCDBOC02, sont identiques à l'exception du fait que T04 et C02 ne doivent pas être congelées, voici le tableau des paramètres de la DBO et les noms d'analyse correspondants à utiliser dans les commentaires.

| Paramètre | Nom à utiliser dans les commentaires                                             |
|---------- |------------------------------------------------------------|
| EDCDBOT01 | Demande biochimiqe en oxygène totale                       |
| EDCDBOT04 | Demande biochimiqe en oxygène totale                       |
| EDCDBOC01 | Demande biochimiqe en oxygène carbonée                     |
| EDCDBOC02 | Demande biochimiqe en oxygène carbonée                     |
| EDCDBOS01 | Demande biochimiqe en oxygène dissous                      |
| EDCDBOSC1 | Demande biochimiqe en oxygène carbonée et dissous          |

Si l'échantillon pour l'analyse de la Demande biochimique en oxygène (totale, carbonée, dissoute ou carbonée et dissoute) a été congelé par le client (ou à la réception), il faut utiliser le nom complet de l'analyse dans le commentaire ajouté, par exemple :

«*L'échantillon pour l'analyse de la demande biochimique en oxygène **totale** a été congelé par le client.*»

Si plusieurs paramètres de la DBO sont demandés par le client (DBOT01 et DBOC01, ou DBOT04 et DBOC02), il faudrait ajouter le commentaire avec le nom complet de l'analyse pour CHAQUE paramètre de la DBO concerné, par exemple :

«*L'échantillon pour l'analyse de la Demande biochimique en oxygène **totale** a été congelé par le client.*

*L'échantillon pour l'analyse de la Demande biochimique en oxygène **carbonée** a été congelé par le client.*»
