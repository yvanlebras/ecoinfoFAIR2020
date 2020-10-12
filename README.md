# ecoinfoFAIR2020
Github Repo for ecoinfoFAIR2020 DevLog action

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
