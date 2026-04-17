# Sales-Performance-Dashboard---Looker-Studio
🎯 Objectif du Projet
Ce projet consiste en la création d'un tableau de bord décisionnel conçu pour les équipes Marketing et Commerciales. L'enjeu est de transformer des données brutes de transactions en insights actionnables pour piloter la croissance et la fidélisation client.

👤 Audience : 
Direction Commerciale : Vision macro et suivi des objectifs.

Équipes Marketing : Analyse du comportement client et segmentation.

Responsables Régionaux : Pilotage de la performance des points de vente.


🏗️ Architecture & Stack Technique
Entrepôt de données : Google BigQuery.
<img width="1882" height="837" alt="image" src="https://github.com/user-attachments/assets/0dd96586-2fef-4375-bfba-7184ab16f551" />
Source : Table prod_sales_kpi (données transactionnelles, CRM et produits).

Fréquence : Pipeline ETL avec rafraîchissement quotidien.

Modélisation : SQL pour le nettoyage et l'agrégation des KPIs.

📈 Indicateurs Clés (KPIs)

Le dashboard suit les métriques critiques suivantes :

Transactions : Volume total de ventes.

Revenue (Ordered vs Billed) : Suivi du chiffre d'affaires brut et net.

Client Value : Revenu moyen par client (LTV initiale).

Refund Rate : Suivi de la satisfaction produit et des retours.

Loyalty Share : Part du CA générée par les clients membres du programme de fidélité.

<img width="1125" height="573" alt="image" src="https://github.com/user-attachments/assets/9697440b-ef92-4411-b6a7-cf3d7a871d09" />
<img width="1142" height="456" alt="image" src="https://github.com/user-attachments/assets/694c31f4-add9-463c-abe3-686c93b515de" />

🛠️ Fonctionnalités d'Analyse:

Le rapport permet d'explorer les données selon plusieurs axes (drill-down) :

Temporalité : Comparaison Year-over-Year (YoY) et tendances journalières.

Produit : Performance par catégories et sous-catégories.

Client : Segmentation par genre et par niveau de fidélité (Bronze, Silver, Gold).

Géographie : Performance par région et par ville.

Dashbord qui nous montre les clients ayant effectuer leur achat dans la boutique (Store):

<img width="1157" height="525" alt="image" src="https://github.com/user-attachments/assets/a07f69e8-076e-4dd6-931f-87502be17312" />


❓ Questions Métiers Résolues
Croissance : Quelle est l'évolution du CA sur les 3 derniers mois comparée à l'année N-1 ?

Fidélisation : Quelle est la part de revenus générée par les clients récurrents vs les nouveaux ?

Profilage : Quel est le panier moyen d'une femme cliente "Gold" par rapport à un client "Silver" ?

Localisation : Quelles régions affichent le taux de remboursement le plus élevé ?
