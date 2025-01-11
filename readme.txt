I.	Description du projet :
Le projet a pour objectif de créer un modèle de classification multimodale capable de reconnaître et de classer des scènes à partir d'images et de fichiers audio. Il vise à extraire des caractéristiques pertinentes des données visuelles et auditives, en intégrant divers modèles d'apprentissage automatique et d'apprentissage profond, afin d'améliorer la précision de la classification. Ce projet s'inscrit dans le domaine de l'apprentissage automatique et de la vision par ordinateur, et utilise des techniques avancées de traitement d'images et de signaux audio.
II.	Objectifs du Projet :
L'objectif principal de ce projet de classification multimodale d'images et d'audio est de développer des modèles capables de reconnaître et de classer des scènes à partir de données visuelles et auditives. Plus précisément, les objectifs incluent :
1. Extraction de Caractéristiques : Utiliser un modèle VGG19 pré-entrainé sur la base de données ‘imagenet’ et d’explorer d’autres alternatives notamment RESNET et INCEPTION pour extraire les caractéristiques des images, et le LSTM pour extraire les caractéristiques pertinentes à partir des coefficients MFCC des enregistrements audio.
2. Classification Précise : Développer des modèles de machine learning et de réseaux de neurones denses pour les images et des LSTM pour l'audio afin d'atteindre une classification précise des différentes scènes.
3. Analyse des Performances : Évaluer les modèles via des matrices de confusion et des métriques comme la précision, le rappel et rapport de classification pour identifier les forces et les faiblesses.
4. Intégration Multimodale : Explorer l'impact de l'utilisation de différentes architectures et méthodes de fusion des données, notamment la méthode tardive ( late fusion), précoce ( early fusion) et hybride sur la performance de notre système final.




La base de données :
https://www.kaggle.com/code/kerneler/starter-scene-classification-images-40e223fe-3/


Instructions pour exécuter le projet

1. Accédez au lien du Google Drive :
https://drive.google.com/drive/folders/1JZPzpVJICCF7FTmF5-qVjP9Ywwpe-ifU?usp=sharing

2. Ajoutez un raccourci au dossier "Multimodale" dans votre Drive :

	- Faites un clic droit sur le dossier "Multimodale".
	- Sélectionnez "Organiser" → "Ajouter un raccourci".
	- Choisissez "Mon Drive" (ou My Drive) comme emplacement.

3. Ouvrez un fichier spécifique pour exécution :

	- Consultez le fichier Classification_Multimodale.txt dans le dossier.
	- Identifiez le fichier à ouvrir (lien fourni dans le texte).
	- Copiez le lien dans votre navigateur pour l'ouvrir directement dans Google Colab.