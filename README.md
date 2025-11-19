# CV


## 🚀 CV orienté  Infrastructure & Automatisation (IAC)
Ce projet héberge les sources d'un CV  conçu pour un profil technique SRE/DevOps/Automatisation. Son principal atout est la séparation du contenu et de la forme pour une maintenance simplifiée.

## ✨ Caractéristiques Techniques
Data-Driven (IAC appliqué au CV) : L'intégralité du contenu est gérée via un fichier de données JSON simple (cv-data.json).

* Technologies : HTML, CSS, JavaScript (Vanilla).
* Design Responsive & Print-Ready
* Impression PDF : Mise en page garantie au format A4 deux colonnes (grâce aux @media print).

## Affichage Web : Mise en page adaptée aux écrans de mobiles et tablettes (@media screen).

## 🔧 Maintenance et Personnalisation

La modification du CV est simple et centralisée.

### 1. Mise à jour du Contenu (Textes, Expériences, Compétences)
Vous ne devez éditer QUE le fichier cv-data.json.

Le code JavaScript se charge de lire ce fichier et de générer l'intégralité du HTML à chaque chargement de page.

⚠️ Attention : Le JSON est sensible à la syntaxe. 
Assurez-vous de bien respecter l'usage des guillemets doubles (") pour les clés et les valeurs, et des virgules (,) pour séparer les éléments.

###  2. Modification des Couleurs (Thème)
Toutes les couleurs principales sont gérées via les variables CSS au début du fichier de style (style.css).
ligne 5 :     --light-text-color: 
Vous pouvez changer le thème global du CV en modifiant les variables dans le bloc :root, généralement situées aux alentours de la ligne 50 du fichier CSS :

### Bonus
Générer le gradient de la page : 
https://cssgradient.io/

