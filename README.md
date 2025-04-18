# E-Commerce_Web_Scraping--GeekBuying-

Ce projet consiste en une solution automatisée de web scraping pour extraire des données produits du site GeekBuying (plateforme e-commerce spécialisée dans l'électronique et les gadgets high-tech), en utilisant Selenium pour naviguer et interagir avec des pages web dynamiques. L'objectif est de collecter des informations structurées telles que les noms des produits, les prix, les promotions, les évaluations clients, les descriptions techniques et les liens d'achat. Ces données sont ensuite nettoyées, stockées dans un format exploitable (CSV, JSON ou base de données) et analysées pour permettre des comparaisons de prix, une veille concurrentielle ou la génération d’alertes sur les promotions.

La particularité de ce projet réside dans l’utilisation de Selenium pour contourner les défis posés par le chargement dynamique du contenu via JavaScript, contrairement à des outils comme BeautifulSoup qui ne gèrent que le HTML statique. Des techniques de waiting (attente explicite des éléments) et de rotation d’User-Agents sont implémentées pour éviter le blocage par le site. Le script peut être déployé avec des intervalles de requêtes respectueux (pour éviter le surchargement des serveurs) et intégré à un pipeline de données plus large (automatisation via Scrapy ou orchestration avec Apache Airflow).

Applications possibles :

Suivi des tendances produits (prix, disponibilité).

Algorithme de recommandation pour acheteurs.

Benchmark concurrentiel pour revendeurs.

Outils utilisés : Python, Selenium WebDriver, Pandas (nettoyage), éventuellement Docker pour le scaling.* 
