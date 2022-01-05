# Bibliothèques requises
>* **os**
>> Permet d'effectuer des operations systemes indepedement de l'OS
>>
>> Lire un fichier, écrire dans un fichier, créer un fichier
>>
>> Dans notre projet : utilisé pour parcourir les fichiers des repertoires des datasets
>
> * **numpy**
>> Bibliotheque de calculs mathematique fournissant des structures de données telles que les matrices et les tableaux multidimensionnels ainsi que des fonctions permettant de manipuer ces structures
>>
>> Dans notre projet : utilisé pour stocker les images chargées en memoire et les jeux d'entrainement et de test du modele
>
> * **pandas**
>> Librairie de manipulation de données potentiellement stockées dans des fichiers structurées tels que des fichier xml ou csv.
>>
>> Offre des structures de stockage et manipulations de données : les dataframes, les series
>>
>> Dans notre projet : utilisé pour charger en memoire et traiter les fichiers xml de la base de données 'Face Mask Detection'
> 
> * **matplotlib**
>> Librairie de dessins et de traitement de graphes.
>>
>> Permet egalement des traitement graphiques basiques.
>>
>> Dans notre projet : utilisée pour afficher les images passées dans la partie test avec des images externes
>
> * **notebook**
>> Application web permettant d'editer des fiches contenant du code executable
>>
>> Dans notre projet : utilisée pour mettre en forme le code
> 
> * **scikit-learn**
>> Librairie d'apprentissage automatique.
>>
>> Offre des outils de prediction statistique
>>
>> Dans notre projet : utilisée pour
>>> * modélier un modele de classification par descente de gradient
>>> * réaliser des prediction sur un dataset d'image de visages
> 
> * **scikit-image**
>> Librairie permettant de realiser des traitement mathematiques sur les images (extraction de features)
>>
>> Charge des images sous format de tableau numpy
>>
>> Dans notre projet : utilisée pour
>>> * Calculer le HOG d'une image
>>> * Redimentionner l'image
>>> * Convertir l'image en niveaux de gris
