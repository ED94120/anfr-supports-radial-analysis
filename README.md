# anfr-supports-radial-analysis
Eric Denelle - avril 2026

## Informations générales

URL : https://ed94120.github.io/anfr-supports-radial-analysis/

Cette application évalue le nombre de supports d'antennes situées à proximité d'un point localisé sur une carte IGN.

L'utilisateur clique un point sur la carte et renseigne un rayon maximal. L'applicaction calcule le nombre de supports situés dans des rondelles centrées sur le point et de rayons croissants.

Les informations suivantes sont fournies :  
&nbsp;&nbsp;&nbsp;&nbsp;le nombre de supports localisés dans le cercle de rayon maximal,  
&nbsp;&nbsp;&nbsp;&nbsp;le nombre de supports dans chaque rondelle,  
&nbsp;&nbsp;&nbsp;&nbsp;la position et la distance au point des trois supports les plus proches.

## Informations particulières

L'application utilise un fichier au format geoJSON contenant les positions des supports.

Le fichier est créé à partir des informations ANFR.
