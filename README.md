# **<p align="center">Analyse de données des meurtres d'Harold Shipman</p>**

<p align="center">
  <img src="Pictures\news-paper.jpg"/>
</p>

## **Sommaire**
---
### **1. Veille sur Microsoft Power BI**

#### **1.A - Qu'est ce que Power BI ?**

#### **1.B - Composants**

#### **1.C - Avantages**

#### **1.D - Inconvénients**

#### **1.E - Principales fonctionnalités**

#### **1.F - Les différentes sources de données utilisables**

#### **1.G - Les différents types de visualisations**

###  **2. Contexte du projet**

#### **2.A - Données utilisées**

#### **2.B - Problématique étudiée** 

### **3. Analyse des données** 

### **4.  Conclusion** 

---
---
![Power-BI-Cover](Pictures/power-bi-cover.jpg)
![Power-BI-Cover](Pictures/power-bi-cover.jpg)


## **<p align="center">1. Veille sur Microsoft Power BI</p>**
---
### **<p align="center">1.A - Qu'est ce que Power BI ?</p>**
---


**Power BI est le logiciel de [Business Intelligence](https://fr.wikipedia.org/wiki/Informatique_d%C3%A9cisionnelle) de Microsoft**. C'est l'outil d'[informatique décisionnelle](https://fr.wikipedia.org/wiki/Informatique_d%C3%A9cisionnelle) leader sur son marché (source : [powerbi.microsoft.com](https://powerbi.microsoft.com/en-gb/blog/microsoft-named-a-leader-in-the-2023-gartner-magic-quadrant-for-analytics-and-bi-platforms/)).
Il permet de créer des visuels (tableaux de bords, graphiques, cartes) qui s'alimentent à partir de plusieurs sources de données. Ces visuels sont intégrés dans des rapports dynamiques, qui peuvent être hébergés dans le cloud et rendu accessibles à de nombreux utilisateurs. 

Il s'agit d'un **ensemble de services logiciels, d'applications et de connecteurs** qui œuvrent ensemble pour **transformer des sources de données disparates en insights cohérents, visuellement immersifs et interactifs**. 

(source : [learn.microsoft.com](https://learn.microsoft.com/fr-fr/power-bi/fundamentals/power-bi-overview)).

### **<p align="center">1.B - Composants</p>**
---
**Power BI** est constitué de plusieurs éléments qui fonctionnent ensemble, dont ces **trois éléments de base** :
* Une application de bureau Windows appelée ***Power BI Desktop***.
* Un service SaaS (Software as a Service) en ligne appelé ***service Power BI***.
* Des applications ***Power BI Mobile*** pour des appareils Windows, IOS et Android.

Ces trois éléments (Power BI Desktop, le service et les applications mobiles) sont conçus pour permettre de **créer, partager et consommer de façon optimale des insights métier**, en fonction des besoins et des rôles des utilisateurs.

Power BI comprend également **deux autres éléments** : 
* ***Power BI Report Builder***, pour la création de [rapports paginés](https://learn.microsoft.com/fr-fr/power-bi/fundamentals/power-bi-overview#paginated-reports-in-the-power-bi-service) à partager dans le service Power BI.
* ***Power BI Report Server***, qui est un serveur de [rapports local](https://learn.microsoft.com/fr-fr/power-bi/fundamentals/power-bi-overview#on-premises-reporting-with-power-bi-report-server) dans lequel il est possible de publier les rapports Power BI après les avoir créés dans Power BI Desktop. 

(source : [learn.microsoft.com](https://learn.microsoft.com/fr-fr/power-bi/fundamentals/power-bi-overview)).

### **<p align="center">1.C - Avantages</p>**
---
* Peut être utilisé aussi bien par des utilisateurs débutants qu'expérimentés. 
* Tableaux de bord et rapports pré-conçus pour les solutions Saas.
* Tableaux de bord mis à jour en temps réel.
* Connexion aux sources de données fiable et sécurisée, aussi bien sur site que sur le Cloud.
* Déploiement rapide, configuration hybride et environnement sécurisé.
* Exploration de données en utilisant des requêtes en langage naturel.
* Nombreuses fonctionnalités de visualisation de tableau de bord.
* Intégration avec le coding en Python et R permettant de manipuler les visualisations.
* Nombreuses options disponibles pour préparer et nettoyer les données avec Power Query qui est par ailleurs propulsé par l'IA et le Machine Learning.
* Nombreuses mises à jour apportant de nouvelles fonctionnalités.
### **<p align="center">1.D - Inconvénients</p>**
---
* Les tableaux de bord et les rapports ne peuvent être partagés qu'avec des personnes ayant des emails sur le même domaine.
* Impossibilité de mélanger les données importées, les fichiers dépassant 1Go sont refusés. 

### **<p align="center">1.E - Principales fonctionnalités</p>**
---
* **Analyse de flux :** Power BI effectue des analuses des flux de données allant des capteurs d'usine aux médias sociaux permettant ainsi de faire une analyse en temps réel des données, facilitant ainsi la prise de décision. 

* **Techniques modernes de visualisation des données :** Power BI offre des outils de visualisation des données qui permettent de créer des rapports et des tableaux de bord interactifs.

* **Multiplicité des sources de données :** Les données peuvent être sous forme de feuille de calcul Excel ou de collection d'entrepôts de données hybrides locaux ou sur le Cloud.

* **Personalisation :** Power BI permet de personnaliser les rapports et les tableaux de bord selon les besoins spécifiques de l'utilisateur.

* **Q&A :** Power BI dispose d'une zone de questions-réponses qui permet aux utilisateurs de poser des questions en langage naturel et d'obtenir des réponses sous forme de visualisations.

* **Nettoyage et transformation des données :** Power BI offre des outils pour nettoyer et transformer les données avant de les utiliser dans les rapports.

* **Détection des anomalies et repérage des tendances :** Grâce à l'IA, Power BI peut détecter les anomalies et repérer les tendances dans les données. 

* **Création de tableaux de bord de base :** Power BI permet de créer des tableaux de bord de base pour visualiser les données.

* **Consommation de rapports et de tableaux de bord :** Les utilisateurs peuvent consommer des rapports et tableaux de bord créés par d'autres utilisateurs ou par eux-mêmes.

* **Partage et collaboration :** Power BI offre plusieurs façons de partager et de collaborer sur des rapports et des tableaux de bord. 

### **<p align="center">1.F - Les différentes sources de données utilisables</p>**
---
### **1.F - Les différents types de visualisations**
---


Power Bi permet de se connecter à une multitude de sources de données, en voici quelques exemples : 

* **Fichiers plats :** Ce sont des fichiers de données structurées comme les fichiers Excel, CSV, XML, JSON, etc.

* **Base de données SQL :** SQL Server, Access, Oracle, IBM DB2, MySQL, PostgreSQL, Sybase, Teradata, SAP HANA, Amazon Redshift, Google BigQuery, etc.

* **Flux OData :** OData(Open Data Protocol) est un protocole ouvert permettant de consommer des données sur le web. Power BI peut se connecter à des services web utilisant ce protocole.

* **Plateforme Azure Cloud :** Power BI peut se connecter à divers services Azure tels que Azure SQL Databse, Azure Synapse Analytics, Azure Data Lake Storage, etc.

* **Services en ligne :** Power Bi peut se connecter à divers services en ligne tels que SharePoint Online, Dynalics 365, Saleforce, Google Analytics, etc.

* **Autres sources de données :** Power BI peut également se connecter à d'autres sources de données telles que Hadoop, Exchange, Active Directory, etc.

Il est important de noter que **les données doivent être dans un format consommable** par le service Power BI. De plus, certaines sources de données peuvent nécessiter l'utilisation de Power BI Desktop ou des fonctionnalités avancées de requête de données et de modélisation dans Excel avant de pouvoir être utilisées dans le service Power BI. 

### **<p align="center">1.G - Les différents types de visualisations</p>**
---

Power BI offre une variété de visualisations pour aider à représenter les données de manière significative. En voici quelques types : 

* **Graphiques en aires :** Ce sont des graphiques en courbes dont la zone comprise entre l'axe et la ligne est remplie. Ils mettent en évidence l'ampleur du changement dans le temps et peuvent être utilisés pour attirer l'attention sur la tendance évolutive d'une valeur totale. 

* **Graphiques à barres et histogrammes :** Ils sont idéaux pour comparer des valeurs spécifiques dans différentes catégories.

* **Cartes :** Elles montrent un ou plusieurs points de données, un par ligne. 

* **Graphiques combinés :** Il associe un histogramme et un grapique en courbes. Cette combinaison permet de comparer plus rapidement les données. 

* **Arborescence hiérarchique :** Ce visuel permet de visualiser les données sur plusieurs dimensions. Il agrège automatiquement les données et permet d'explorer les dimensions dans n'importe quel ordre.

* **Graphiques en anneau :** Ils affichent la relation de parties par rapport à un tout.

* **Graphiques en entonnoir ** Ils permettent de visualiser un processus comprenant des étapes et des éléments qui passent de manière séquentielle d'une étape à la suivante.

* **Graphiques en jauge :** Ils sont utilisés pour afficher des proportions ou des parts de marché. 

Ces visualisations peuvent être ajoutées à des rapports Power BI, spécifiées dans Questions et réponses, et épinglées à des tablaux de bord. 