Voici le fichier CSV pour l'article du 1er décembre 2025. Cliquez sur ``world_cities_extended.csv`` puis sur l'icône de téléchargement en haut à droite.
![image](https://github.com/user-attachments/assets/cc58af19-5ee7-423a-8646-dc99f616e9fe)

Le fichier CSV contient 1024 lignes constituées de la façon suivante :
| Ville  | Code AITA de l'aéroport le plus proche | Distance (en km) depuis Paris | Continent | Pays | Booléen* |
| :---------------: |:---------------:| :-----:| :-----: | :-------: | :-------: |


*\*Le booléen indique s'il est nécessaire de prendre un autre moyen de transport pour rejoindre la ville depuis l'aéroport. Il vaut ``True`` si c'est le cas.* \
*Notez que nous avons considéré que l'aéroport est dans la ville s'il porte son nom, ce qui n'est pas forcément vrai.* \
*Par exemple, l'aéroport de Paris Vatry (XCR) porte le nom de Paris. Pourtant, pour se rendre à Paris, il faut prendre le car (voire même le TGV). À l'inverse, l'aéroport d'Helsinki Vantaa (HEL) est situé dans la ville de Vantaa, pourtant Vantaa possède le booléen ``True`` alors qu'Helsinki a le booléen ``False``.*\
*Repensez à deux fois en considérant la colonne du booléen !*
