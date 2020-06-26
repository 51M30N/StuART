# StuART
Suite d'objets pure data pour un usage de régie

La Régie StuArt, actuellement développée par 
51m50n / La Caisse à Outils Numériques / Cie ONAVIO, est une suite logicielle / matérielle “open-source” de contrôle des outils techniques d’usage dans le spectacle vivant et l’art contemporain (lumière, son, vidéo, moteurs…) qui sera :
-une solution co-construite avec ses utilisateurs,
-modulaire et adaptable aux besoins de chacun,
-évolutive
-disponible librement pour tous (publications et téléchargements libres des codes informatiques, plans électroniques, fichiers 3D…)

La Régie StuArt est actuellement en phase de test  sur les créations de la Compagnie ONAVIO. 
Il s’agit aujourd’hui de développer l’outil pour le rendre disponible à d’autres acteurs culturels et utilisable  par tous sans connaissances informatiques avancées.

StuArt est destiné aux théâtres, festivals, musées, établissements artistiques et culturels, compagnies, ensembles musicaux et collectivités et, à tous les porteurs de projets artistiques et culturels utilisant dans leurs pratiques des effets techniques. Les  professionnels concernés seraient : régisseurs, créateurs lumière, metteurs en scène, chorégraphes, musiciens,  plasticiens… Le modèle économique de StuArt lui permettra également d’être utilisé dans le cadre de pratiques amateurs.


#Installation de StuART

StuART est écrit et optimisé pour fonctionner sous Raspbian Buster sur un raspberry pi 4 avec Pd 0.49.0

StuART n'est pas un logiciel, c'est une suite d'objets écrits avec PureData-Vanilla https://puredata.info/downloads/pure-data (Pd 0.49.0 sous Raspian)
sudo apt-get install puredata

La librairie cyclone est requise
sudo apt-get install pd-cyclone

penser a ajouter le repertoire ~/StuART dans pd[Fichiers>preferences>Chemins] ainsi que chacun des sous repertoires utilisés (cf StuART.pdsettings)

