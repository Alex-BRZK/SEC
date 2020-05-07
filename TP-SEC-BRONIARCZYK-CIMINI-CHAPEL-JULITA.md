
# Sécurité des systèmes d’informations : Gestion des risques

### BRONIARCZYK - CHAPEL - CIMINI - JULITA 
### 2020 - Licence Pro MRIT - parcours ASUR

## 1 - Environnement du TP et notation.

### 1.1 - Objectifs du TP :

> En Sécurité des Systèmes d’Informations les techniciens pensent en général Firewall, IPS/IDS, antivirus ... C’est une activité importante mais sans savoir ce qu’il faut protéger ces mesures techniques n’ont pas de sens.
> 
> L’objectif de ce TD/TP est de vous montrer comment définir ce qui est important à protéger : les biens ou actifs du système d’information. Il va s’agir pour vous d’acquérir un mode de raisonnement sur l’analyse de risques.
> 
> L’analyse de risque permet de faire le lien entre le terrain et les "généraux" de l’entreprise. Il fera avancer la sécurité dans votre entreprise. Ce n’est pas à l’informaticien mais au décideur de haut niveau de trancher entre l’acceptation , la réduction, la délégation et la supression des risques que vous aurez mis en évidence.
> 
> EBIOS 2010 est la méthode d’analyse de risques recommandée par l’A.N.S.S.I. C’est celle que vous utiliserez durant ces TD/TP mais il en existe beaucoup d’autres.

### 1.2 - Organisation, recommandations et notation du TP.
> 
> Il peut vous être explicitement demandé de faire valider votre travail au cours du TP par l’enseignant au fur et à mesure de votre avancement. 
> Tous les travaux sont à déposer sur l’ENT de l’IUT. 
> 
> Un travail doit être enregistrer avec les noms des personnes dans le nom du fichier, et l’intitulé du fichier doitêtre clair ( par ex : TP_GNS3_Etudiant1_Etudiantn). 
> Les délais sont parfois et exceptionnellement négociables mais une fois fixés doivent être respectés sous peine d’une note nulle.
> 
> L’objectif de cette séance est de vous former à "penser risques". Vous allez travailler par groupe de deux et en parallèle pour l’étude de cas (un étudiant analysera les événements redoutés et l’autre les scenarii de menaces). 
> 
> Vous ferez la synthèse sur le volet risque (Un risque c’est l’exploitation d’une vulnérabilité par une menace entraînant un impact). 

## 2 - Exercices sur la gestion des risques

### 2.1 - Analyse d’un risque autour d’un cycliste ?

On se propose d’analyser simplement les risques auxquels s’exposent un cycliste sans protection surla route.

1. Quel est le bien essentiel à protéger ?
> Le bien essentiel à protéger est le cycliste.

2. Quel est la vulnérabilité principale affectant le bien essentiel à protéger ?
> La vulnérabilité principale affectant le bien essentiel à protéger est sa tête.
 
3. Quel est la menace ?
> La menace est la chute par le biais d’un véhicule ou d’un obstacle.

4. Quels sont les impacts de cette menace sur le bien essentiel ?
> Les impacts sont les dommages physiques et matériels.

5. Quel est la vraisemblance de ce scénario de risques ?
> Taux de probabilité élevé

6. Quel peut être le scénario d’exploitation de la vulnérabilité par le risque ?
> Le scénario d’exploitation de la vulnérabilité par le risque est l’exploitation d’une vulnérabilité par une menace donnant lieu à un impact.

7. Quelle est la mesure de réduction du risque qui peut être adoptée ?
>  Le port d'un casque ou alors de ne pas faire de vélo afin de supprimer totalement le risque

8. Refaites un check du risque et des scénarios de menaces en affinant l’analyse (prenez le cas d’un cycliste roulant à plus de 30 Km /heure et sujet à des chocs plus importants ?
>Les biens supports et les biens essentiels.
    • Lister les menaces
    • Lister les vulnérabilités
    • Obtention des risques : exploitation d’une vulnérabilité par une menace suivant un scénario et donnant lieu à un impact
    • Lister et classifier les risques
Il y a trois choix : ignorer (mais le RSSI a fait son travail), atténuer ou supprimer.

9. Quelle mesure pouvez vous proposer pour réduire ce risque ?
> On pourrait interdire le vélo ou alors déjà le port d’un casque. Mais également utiliser des pistes cyclabes. 

### 2.2 - Biens essentiels et biens supports

##### 1. Classez les biens supports suivant selon les catégories issues de la méthode EBIOS 2010 : matériels(MAT), logiciels (LOG), canaux informatiques et de téléphonie (RSX), personnes (PER), supportspapier (PAP), canaux interpersonnels (CAN), locaux (LOC) :

* La fibre optique **-> MAT**
* Le document imprimé **-> PAP**
* Les bandes de sauvegarde **-> MAT**
* L’autocom **-> MAT**
* Un smartphone **-> MAT**
* Le SGBD Mysql **-> LOG**
* Les discussions de couloir **-> CAN**
* Le système d’exploitation Linux **-> LOG**
* client de courrier électronique **-> LOG**
* Le poste de travail **-> MAT**
* La salle de conférence **-> LOC**
* La ligne téléphonique **-> RSX**
* Un étudiant  **-> PER**



#### 2. Parmi les biens suivants quels sont les biens essentiels et les biens supports ?
* Le serveur supportant l’application SCODOC. **-> Support**
* Les notes des étudiants. **-> Essentiel**
* Le dossier d’entrée en licence. **-> Support**
* Le directeur de la licence MRIT si l’étude de risque porte sur l’ouverture de la licence **-> Support**
* Les salles de réunion visio de l’IUT **-> Support**
* L’enseignement des langues **-> Essentiel**
* Un téléphone professionnel **-> Support**
* Un carnet d’adresse électronique  **-> Support**

#### 3. Dans le cas d’un tunnel routier quels sont les biens essentiels et les biens supports ?
> **Dans ce cas, les biens essentiels sont :**
    • la gestion de l’éclairage ;
    • le recyclage de l’air ;
    • la route.

> **Les biens supports sont :**
    • les ampoules ;
    • les ventilateurs ;
    • les capteurs ;
    • les caméras.



### 2.3  Analyse de risque simplifiée sur une évaluation écrite

1. Quel est l’événement redouté pour un enseignant sur une évaluation écrite ?
> L’évènement redouté pour un enseignement sur une évaluation écrite est la tricherie. L’impact est la valeur du diplôme obtenu.

2. Quel est le bien essentiel ?
> Le bien essentiel est le processus d’évaluation que l’on veut protéger.

3. Quels sont les critères de sécurité concernés (DICT) ?
> DICT → Disponibilité Intégrité Confidentialité Traçabilité. 

>Les critères de sécurité concernés sont :
>    • Intégrité ;
>    • Confidentialité ;
>    • Traçabilité.

4. Quels sont les impacts de haut niveau ?
> Les impacts de haut niveau sont :
    • la perte de confiance et de motivation ;
    • la dévalorisation du diplôme.

5. Quel est le bien support ?
> Le bien support est la copie de l’étudiant.

6. Quelle est la menace ?
> La menace est la tricherie de l’étudiant mais également l’enseignant.

7. Quelles sont les vulnérabilités essentielles du bien support ?
> Les vulnérabilités essentielles du bien support sont :
    • la visibilité de la copie ;
    • la transmissibilité.

8. Quels sont les scenarii de menaces et leurs probabilités d’occurence ?
>Les scenarii des menaces et leurs probabilités d’occurrence sont :
    • un coup d’œil d’échange d’informations entre deux étudiants (forte probabilité) ;
    • un échange vocal entre deux étudiants (forte probabilité).

9. Quel est le risque ?
> Le risque est que l’étudiant va exploiter le fait de voir la copie du voisin qui permettra une triche et qui pourra engendrer à long terme la décrédibilisation du diplôme.

10. Quelles sont les mesures de sécurité à prendre pour limiter ce risque ?
> Les mesures de sécurité à prendre pour limiter ce risques sont :
    • s’assurer de l’espacement des élèves lors de l’évaluation ;
    • différencier les copies ;
    • pénaliser la triche.

## 3 - Etude de risques sur la vulnérabilité des données d’un chercheur en déplacement.

### 3.1 - Le contexte

Un chercheur est amené à se déplacer 60 jours par à l’étranger pour participer à des conférences . 
Il voyage avec son ordinateur portable ( un lenovo sous windows 10 sans chiffrement). L’ordinateur contient ses articles , des documents de travail et ses messages. 
Il peut communiquer avec sa base au travers d’une liaison VPN. Il ne se déplace que dans des pays ou le nombre d’enlèvement de personnes est nul, mais sous des latitudes tropicales (fèvre jaune mortelle, dengue, malaria.. ). 
Il continue à travailler pendant ses déplacements et communique avec son laboratoire et d’autres entités amies de part le monde. Un laboratoire dépend pour son financement des brevets issus de la recherche. 
Les chercheurs de ce laboratoire sont en lien avec l’industrie et des processus secrets de fabrication "hi-tech". La plupart encadrent des équipes et ont un besoin permanent de communications.

### 3.2  Mini étude de risques

1. Quel est le bien essentiel (c’est un processus) ?
> Le bien essentiel est la communication (liaison VPN, vocales).

2. Quelles sont les biens supports ?
> Les biens supports sont :
    • le chercheur ;
    • l’ordinateur ;
    • les pays où il se déplace ;
    • le laboratoire ;
    • les brevets issus de la recherche ;
    • les chercheurs de ce laboratoire.

3. A votre sens donnez les deux évènements les plus redoutés par les métiers. Quels en sont les impacts prévisibles ( échelle de 1 à 4 du plus faible au plus fort ) ?
> Les deux évènements les plus redoutés par les métiers sont :
    • une panne du VPN : impacts fortement prévisibles (4) ;
    • un problème physique pour le chercheur : impacts fortement prévisibles (4).


4. Pour deux des biens supports principaux donnez leurs vulnérabilités et les menaces possibles.
> Les biens supports principaux, ainsi que leurs vulnérabilités et les menaces possibles associés sont :

> • Le chercheur : il faut qu’il soit en bonne santé et qu’il ne soit pas face à des risques trop importants, il peut faire face à des menaces physiques mais également matérielles.
 
> • L’ordinateur : il faut que ce matériel fonctionne correctement et qu’il soit bien sécurisé ainsi que la liaison VPN, il est possible que l’ordinateur ou mêmes les données tombent entre de mauvaise main ou même que le matériel (ordianteur) tombe en panne, ce sont des menaces envisageables.

5. Donnez quelques scenarii de menaces. Quel est la probabilité de ces scenarii ?

> * 1. Le chercheur perd son ordinateur : faible probabilité (mais possible).
> * 2. Le chercheur a des problèmes physiques ou matériels : forte probabilité.
> * 3. L’ordinateur ne fonctionne plus : probabilité moyenne (non-prévisible).
> * 4. Le chercheur n’arrive plus à communiquer avec le laboratoire : probabilité moyenne.
> * 5. La communication n’est plus possible entre le laboratoire et les industries : faible probabilité.

6. Exprimez en Français les risques (exploitation d’une vulnérabilité d’un bien support par une menace et donnant lieu à un impact).
> Exemples de deux risques :

>    1. Le chercheur va perdre son ordinateur, la personne qui va le récupérer va essayer d’avoir accès aux données présentes sur ce dernier, ce qui pourra engendrer une grosse perte de données et surtout une grosse faille de sécurité suivant les informations qu’il contenait. Le laboratoire avec lequel il travail pourrait donc perdre en crédibilité si un tel problème arrive.
       
>   2. La communication entre le chercheur et le laboratoire n’est plus possible, le chercheur ne peut donc plus s’informer et faire transiter des données entre lui et le laboratoire ce qui engendre alors un manque à gagner et une perte de temps pour le laboratoire. Comme expliqué précédemment, le laboratoire avec lequel il travail pourrait donc perdre en crédibilité si un tel problème arrive.

7. Proposez des mesures pour réduire les risques.
> Si le chercheur perd son ordinateur il serait possible d’utiliser la géolocalisation pour trouver où est l’ordinateur ou encore bloqué l’accès à distance. Il serait également possible de mettre en place plusieurs systèmes de sécurité sur ce PC afin d’y avoir accès comme de long mot de passe et différents systèmes d’authentification pour s’y connecter.

> Si la communication n’est plus possible entre le chercheur et le laboratoire il faudrait penser à pouvoir utiliser un autre moyen de communication dans le cas où la liaison VPN n’est plus utilisable ou que le laboratoire n’est plus accessible.


## 4 - Etude détaillée de risques sur un examen national

### 4.1 - Présentation du cas
L’Examen classant National est un examen qui permet de classer les étudiants de médecine en vue de l’internat. 
C’est un examen national informatisé.
Votre travail est de réaliser une étude de risques sur ce projet par groupe de deux.
C’est un projet réel qui a fait l’objet d’une présentation aux journées systèmes et réseaux de 2015.

Vous aurez pour support la vidéo issue des JRES : https://registry.iutbeziers.fr:12443/risques/videojres-risques.mp4accessible aussi sur youtube https://www.youtube.com/watch?v=GQzhKvn9H58.

Les supports ( présentation et article ) sont sur Moodle.
Les pages suivantes aussi peuvent être utiles :
— http://pascal-aubry.fr/content/examens-numeriques-a-l-universite-securite-technique-et-organisation-jres-2015
— http://pascal-aubry.fr/sites/pascal-aubry.fr/files/sides-jres-2015-article.pdf

En vu de réduire les risques le guide d’hygiène informatique de l’ANSSI ou la norme ISO 27002 sont vos amis :
— http://www.entreprises.gouv.fr/files/files/directions_services/information-strategique-sisse/guide_hygiene_informatique_anssi.pdf

Vous pourrez trouvez par analogie des idées exploitables sur cette étude de risque en sécurité industrielle https://www.ssi.gouv.fr/uploads/2014/01/securite_industrielle_GT_details_principales_mesures.pdf 
Après avoir visionné la vidéo et lu l’article vous pouvez commencer l’étude de risques. 

Vous avez une feuille de calcul sur l’ENT pour vous aider à remplir les différentes rubriques. Vous la rendrez sur Moodle à la fin de l’étude.

### 4.2 - Etude du contexte

1. Qu’est-ce qui est à l’origine de l’étude (motif, événement...) ?

> L’origine de l’étude est de **mettre en place des examens numériques** dans les universités, mais également de **montrer la sécurisation de ce type d'examen**.

2. Quel est l’objectif de l’étude (son but et les livrables attendus) ?

> L’objectif de l’étude est de **mettre en place un examen classant national** nommé ECNi pour juin 2016 qui concerne les sixièmes années de médecine. 
> Cet examen est organisé par le CNG (Conseil National de Gestion) qui dépend du ministère de la santé. Mais également de montrer les avantages de l'utilisation d'un tel système d'examen.

> L’aspect numérique et la mise en place d’un tel examen permet de :
    • mieux discriminer les étudiants avec un classement beaucoup plus juste car il y aura plus de questions que sur papier ;
    • utiliser des médias plus riches (vidéos, images plus claire) ;
    • faire une meilleure progressivité des examens ;
    • réutilisation des sujets possibles ;
    • réduction des temps/coûts de correction ;
    
>Ce projet présente plusieurs étapes notoires comme des audits, des ECNi de tests nationales puis les vrais ECNi ont lieu. Il y a également pas mal d’examens facultaires pour les étudiants.

3. Comment organisez le travail (actions, rôles, charges...) ?
> Tous les métiers de la DSI sont impliqués dans ce projet :
    • les **architectes du SI** : afin de provisionner les plateformes SIDES pour les enseignants et les étudiants ;
    • les **ingénieurs systèmes et réseaux** : afin de gérer les infrastructures ;
    • les **informaticiens de proximité** : afin de gérer le parc informatique et d’en créer un nouveau avec les tablettes :
    • les **responsables sécurité (RSSI)** : afin de réaliser les analyses de risques (grosse implication dans ce projet).

4. Que sait-on du contexte (externe et interne) ?
> Contexte externe :
    • le **Campus Santé** où se trouve les tablettes connectées en wifi sur des bornes et qui vont être dans un bâtiment dans lequel vont composer les étudiants ;
    • le **Campus Beaulieu** où se trouve les serveurs (DNS, DHCP, CAS, …) ;
    • le **serveur SIDES** via une liaison renater.

> Contexte interne :
    • un **nouveau parc informatique de tablette** de la marque « Apple » pour une meilleure homogénéité et car elles étaient déjà achetées pour la plus part ;
    • des **chariots** pour stocker, transport, charger les tablettes.


5. Qui assure les rôles de MOA (Définition des besoins) et de MOE (hébergement, qualification et l’intégration) ?
> **MOA** : les services de scolarité et la DSI.

> **MOE** : les informaticiens de la DSI.

> Les **utilisateurs** sont les **enseignants** (fabrique et corrige les sujets) et les **étudiants** (réalise les examens sur ces sujets).

6. Comment les risques sont-ils gérés actuellement ?
>Les **risques** sont gérés par des procédure :
    • en cas d’incendies ou d’autres problèmes naturels ;
    • en cas de pertes de services essentiels ;
    • en cas d’erreurs et de négligences de comportements;
    • en cas de malveillances et de fraudes.

7. Quelles sont les limites du périmètre étudié ?
> Les **limites** du périmètre étudié sont :
    • le campus sur lequel on fait les tests (donc l’université) ;
    • ils ne prennent pas en compte la partie internet de renater ou des serveurs SIDES.

8. Qui doit participer à l’étude ?
> Les **enseignants** et les **étudiants** doivent participer à l’étude.

9. Quels sont les référentiels applicables (cherchez sur internet on le trouve ) ?
> Les référentiels applicables au vue des enjeux juridiques et financiers sont :
    • la **PSSI** (Politique de Sécurité des Systèmes d’Information) **propre au projet SIDES**, dont l’université à eut connaissance en cours de mise en œuvre ;
    • La **PSSI de l’établissement** ;
    • Le **RGS** (Référentiel Général de Sécurité) qui s’applique à tous les télé-service de l’administration ;
    • La **PSSIE** (Politique de Sécurité des Systèmes d’Information de l’État).

10. Quelles sont les contraintes qui pourraient impacter l’étude ?
> Les contraintes qui pourraient impacter l’étude sont la gestion d’un nouveau parc de tablettes (Apple) et l’utilisation des logiciels associés. Il y a également le changement d’architecture réseau (renforcée dans ce cas).

> Il faut également prendre en compte le contexte et répondre au DICT :

> **Disponibilité** :
    • les examens doivent se tenir, dans le temps et le lieu impartis; 
    • les menaces d’indisponibilité les plus probables ont été mises en évidence avec l’identification des SPOF (Single Point Of Failure) ;
    • points faibles du système.
      
>  **Intégrité** :
    • rien ne doit perturber les flux des données avant (procédures administratives d’enregistrement des acteurs, préparation des sujets, ...) et pendant les examens (composition des étudiants);
      
>   **Confidentialité** :
    • tous les échanges doivent être sécurisés car toute fuite d’information au-delà du « besoin d’en connaître » peut-être synonyme d’invalidation des examens, avec ses conséquences;
      
>   **Traçabilité** :
    • les actions des utilisateurs pendant les examens doivent être tracées. 

> Le principal risque concerne l’indisponibilité, c’est-à-dire qu’il faut que les examens se tiennent dans des conditions satisfaisant le CNG et dans des délais satisfaisant également, sachant que la tolérance maximum d’indisponibilité pendant cet examen est très faible (15 minutes maximum).

11. Contre quels types de menaces décide-t-on de se protéger ?
> Les menaces contre lesquelles on décide de se protéger sont les suivantes :
    • les connexions multiples ;
    • l’usurpation d’identité électronique ;
    • l’intrusion dans les salles d’examens ;
    • les pertes de connaissances au sein de l’équipe ;
    • les pertes de données ;
    • les sinistres (problèmes à sources non humaines) ;
    • les erreurs et négligences de comportement ;
    • les erreurs de conception, de configuration ou de manipulation ;
    • l’absence de documentation ;
    • le non respect des lois et réglementations ;
    • les pertes de traçabilité et d’imputabilité des actions ;
    • les vols et divulgations d’informations ;
    • les perturbations des activités ;
    • la propagation de virus et codes malveillants ;
    • l’altération ou destruction d’informations ;
    • les intrusions sur les SI ;

12. Quelles sont les mesures de sécurité existantes ?
> Les mesures de sécurité existantes sont :
> -  les menaces liées au projet :
        ◦ sinistres
        ◦ erreurs humaines et négligences de comportement
        ◦ malveillances et fraudes
> - exemples de traitement du risque :
        ◦ chiffrement de toutes les communications ;
        ◦ renforcement de l’architecture réseau existante ;
        ◦ séparation logique des réseaux ;
        ◦ contrôle physique des personnes ;
        ◦ contrôle des connexions ;
        ◦ mise au point de procédures d’alertes.

### 4.3 - Etude des biens essentiels et des biens supports

Lister les biens essentiels et les biens supports. 
Réalisez un tableau rattachant à chaque bien support les biens essentiels qui lui sont rattachés.


| Biens supports | Biens essentiels | 
| -------- | -------- | 
|Borne Wi-Fi|	Connexion Wi-Fi|
|Equipements informatique|	Infrastructure réseau|
|Réseau informatique	|Données de l'examen|
|Tablettes	|Examen|
|Humains, Matériels|	Examen|
|Sujets	|Examen|
|Réseau informatique|	Données du réseau|
|Equipements et réseau informatique|	Données du réseau|
|Réseau informatique	|Examen|
|Réseau électrique	|Bâtiment|
|Données du serveur	|Données de l'examen|
|Logiciel informatique	|Configuration du logiciel|




### 4.4 - Etudiez les évènements redoutés

Les événements redoutés sont obtenus par interview des "métiers". Extrayez-les de la vidéo ou de l’article et imaginez ce que vous pourriez redouter en tant que responsable du département de médecine.
Sur le classeur de calcul le premier onglet est dédié aux échelles (impact et vraisemblance). Dans le cas d’une étude réelle, l’établissement de ces échelles serait de votre responsabilité mais elles vous sont données ici.

>   • les connexions multiples ;
    • l’usurpation d’identité électronique ;
    • l’intrusion dans les salles d’examens ;
    • les pertes de connaissances au sein de l’équipe ;
    • les pertes de données ;
    • les sinistres (problèmes à sources non humaines) ;
    • les erreurs et négligences de comportement ;
    • les erreurs de conception, de configuration ou de manipulation ;
    • l’absence de documentation ;
    • le non respect des lois et réglementations ;
    • les pertes de traçabilité et d’imputabilité des actions ;
    • les vols et divulgations d’informations ;
    • les perturbations des activités ;
    • la propagation de virus et codes malveillants ;
    • l’altération ou destruction d’informations ;
    • les intrusions sur les SI ;


### 4.5 - Listez les menaces

Pour celà vous vous servirez du document "EBIOS-2-Bases-de-connaissances" et de l’annexe C de la norme iso 27005.


| Menaces | Exemples | 
| ---- | ---- | 
| **Physiques** | Incendie |
||Dégâts des eaux |
||Destruction de matériel|
|||
|**Evènements climatiques**| Séisme |
||Phénomène météorologique|
|||
|**Perte de services essentiels**| Panne de climatisation|
||Panne électrique|
|||
|**Problèmes techniques**|Dysfonctionnement du matériel|
||Panne du matériel|
||Problème logiciel|
|||
|**Erreur/négligence de comportement**|Erreur de conception|
||Erreur de configuration|
||Absence de documentation|
||Non respect des lois|
|||
|**Malveillance/fraude**|Vol d’informations|
||Divulgation d’informations|
||Perturbation des activités|
||Propagation de virus|
||Destruction d’informations|



### 4.6 - Listez les vulnérabilités

Vous pouvez vous inspirer du guide de sécurisation de l’informatique industrielle et de l’annexe D de la norme iso 27005.

|Vulnérabilitée|Exemples|
|----|----|
|||
Hardware	|Capacité du matériel
||Intégrité de l'équipement
||Pas assez de documentation
||Faille de sécurité du serveur
||Maintenance insuffisante
||
Software	|Pas assez de documentation
||Pas assez de tests
||Faille de sécurité du serveur
||Le sujet est disponible à tous
||Intégrité du logiciel
||
Network|	Réseau Wi-Fi
||Conformité de l'infrastructure réseau
||Failles de sécurité des équipements et du réseau
||Les données circulent en clair sur le réseau
||Sécurité du réseau
||
Personnel|	Manque de vérification d'identité des étudiants
||Manque de contrôle de sécurité
||Visibilité, transmissibilité ou infiltration de clean sheet (donc tricherie)
||
Site	|Conformité du bâtiment
||Conformité des équipements à l'intérieur de ce bâtiment
||Faille de sécurité
||
Organisation|	Suivre des procédures atteignant différents problèmes

### 4.7 - Réunissez les évènements redoutés et les scénarii de menaces pour analyser les risques


Pour cette question, nous avons répondu via un Tableur, comportant tout les données voulues.

Disponible à ce lien : https://github.com/Alex-BRZK/SEC/


### 4.8 - Prenez la place du décideur et traiter les risques 
Les risques  sont classés en fonction des critères donnés dans les échelles. 
Vous devez décider si vous acceptez le risque sans rien faire en tant que décideur, si vous demandez sa réduction vous devez lister les méthodes proposées et chiffrer ( achat d'un firewall , embauche ...), ou refuser le risque en décidant d'arrêter. 
Donc j'attends une décision et de la technique de votre part.


[![Button](https://i.imgur.com/bfX43uC.png)](https://github.com/Alex-BRZK/SEC/) 
