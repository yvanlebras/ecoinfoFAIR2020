# ecoinfFAIR2020
## C'est qui ?
- Coline Royaux, IE CNRS, développement d'outils Galaxy au PNDB, UMS BBEES, station marine de Concarneau
    - Mon travail : 
    - Mon background : 
- Elie Arnaud, IE MNHN, développement R / R Shiny et gestion de données/métadonnées au PNDB, UMS PatriNat, station marine de Concarneau
    - Mon travail : 
    - Mon background : 
- Yvan Le Bras, IR MNHN, chef de projet "Pôle national de données de Biodiversité" (PNDB de son petit nom), UMS PatriNat, station marine de Concarneau
    - Mon travail : Me poser tout le temps des questions liées à la gestion et l'analyse de données de biodiversité ;)
    - Mon background : Ecologie marine, Analyse de données *omiques, Bioinformatique

## La logistique
- serveur BigBlueButton accessible à cet URL : https://webconf.math.cnrs.fr/b/yva-rtm-4mv. En solution de dépannage, notamment en cas de problèmes, je propose d'utiliser jitsi via cet URL : https://meet.jit.si/ecoinfoFAIR2020

## Programme prévisionnel :
L'idée est de faire une première ~demi journée de présentation/formation introductive puis un grand temps d'échange (~2 jours) de travail en petits groupes
### Matin 19 : Intro ( 11h- 12H)
- Introduction aux journées en présentant la vision FAIR du PNDB
Après-midi 19 : plusieurs intervenants (13h-18h) :
- Aspect outils "génériques" de développement en écologie, orienté R
   - Formation rapide introductive à GIT et github
   - Bonnes pratiques de travail avec R / science reproductible / workflow / package via R, RStudio
   - Formation rapide développement d'une application Shiny
   - Formation rapide introductive à Docker avec application en SIG
- Aspect Métadonnées
   - Formation rapide introductive à l'EML
- Aspect Analyse de données
   - Formation rapide introductive à dev Galaxy dont conda

### Matin 20 (9h) -> Après-midi 21 (16h) : Travail en petits groupes / Hackathon / Collaboration Fest
- Sujets potentiels
   - développements "métadonnées" liés aux standards utilisés en écologie (Darwin-core / EML / ISO19115 / ISO19110...) et/ou aux catalogues de données/métadonnées (GeoNetwork/Metacat/Dataverse/Zenodo...)
       - ***Workflow BDD postgis mammifères marins (modélisée avec standards DarwinCore et EML) -> liste requêtes d’intérêt -> publication dans Metacat + geonetwork + GBIF ? (Emilie)***
           - mettre au point un workflow de création / structuration de bdd et publication dans metacat voir GBIF
           - standardiser les descripteurs (attributs des données) + métadonnées (qui, quoi, ou et comment)
                - mapper les attributs avec DarwinCore 
        - ***Lien Metacat - geoserver en s’appuyant sur SOLR : publier des flux WMS/WFS des (méta)données mammifères marins issues de Metacat (Arnaud)***
   - développement de scripts R en mode function / package
   - développement d'applications R Shiny
       - ***Tableau de bord de la surveillance de la biodiversité terrestre (Guillaume, Morgae, Sarah) ***
   - containerisation d'applications R Shiny pour intégration dans Galaxy
   - développement d'outils Galaxy à partir de scripts R
   - développement de matériels de formation 'e-learning" via l'infrastructure du Galaxy Training Network

## Prise de Notes
### Aspect outils "génériques" de développement en écologie, orienté R
#### Introduction aux journées en présentant la vision FAIR du PNDB
Présentation : Yvan Le Bras, Pôle national de données de Biodiversité, MNHN



#### Formation rapide introductive à GIT et github
Présentation : Alain Danet, UMR CESCO, MNHN / Nicolas Casajus, CESAB, FRB



#### Bonnes pratiques de travail avec R / science reproductible / workflow / package via R, RStudio
Présentation : Sébastien Rochette, ThinkR



#### Formation rapide développement d'une application Shiny
Présentation : Elie Arnaud, Pôle national de données de Biodiversité, MNHN



#### Formation rapide introductive à Docker avec application en SIG
Présentation : Julien Ancelin, LIENSs - Unité Expérimentale St Laurent de la Pré, INRAE




### Aspect données et Métadonnées


#### Formation rapide introductive à l'EML
Présentation : Yvan Le Bras, Pôle national de données de Biodiversité, MNHN




### Aspect Analyse de données

#### Formation rapide introductive à dev Galaxy dont conda
Présentation : Anthony Bretaudeau, Plateforme GenOuest Rennes, BIPAA, INRAE





