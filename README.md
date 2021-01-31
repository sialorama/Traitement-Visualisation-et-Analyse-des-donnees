# Traitement-Visualisation-et-Analyse-des-donnees

Contexte du projet
1.Déploiement de l’environnement

Assurez-vous que les bibliothèques ci-dessous sont présentes dans votre environnement : • Pandas • Numpy • SciPy • Matplotlib

2.Sources de données : Manipulation

• Vous avez à disposition un répertoire nommé Data. Il existe dans ce répertoire un ensemble de fichiers(credit_immo.*) qui représentent les mêmes données avec des extensions différentes (csv, json, xls). En utilisant la ou les bibliothèques adéquates, chargez et visualisez ces fichiers.

• En utilisant les bibliothèques adéquates, créer une base de données formée de 6 lignes et 4 colonnes. Les colonnes représentent respectivement les variables "taux_de_ventes, croissance_vente, ratio_benefice, ratio_perte".

• En utilisant la fonction dataset.reindex() et dataset.isnull(), introduire des données manquantes et récupérer les indices des valeurs manquantes. Puis remplacez les valeurs manquantes par 0 par exemple. Puis supprimez ces valeurs manquantes.

3.Traitement des données

Traitement des données renvoie à une série de processus qui permettent d’extraire de l’information ou de produire du savoir à partir de données brutes. Ces processus, une fois programmés, sont le plus souvent automatisés à l’aide d’ordinateurs. Les étapes pour le processus de traitement de données consiste à :

Importer les bibliothèques adéquates.
Importer le jeu de données (data-set).
Transformer les valeurs manquantes en moyenne (SimpleImputer).
Encoder les valeurs catégoriques (LabelEncoder).
Fractionner le jeu de données pour l’entrainement et le test (Training and Test set).
mise à l’échelle des features (StandardScaler).
Vous avez à votre disposition un fichier nommé credit_immo.csv. Appliquez les étapes de prétraitement sur cette base de données.

4.Visualisation de données

Chargez le fichier Montant_Temps.csv. Puis en utilisation la fonction iloc, découpez vos données en données d’abscisses et d’ordonnées qui représentent respectivement le temps et le montant du capital. Puis tracez le montant du capital en fonction du temps (avec la focntion plot()) . Puis sauvegardez vos graphiques.

4.1 Rajoutez du style à vos graphiques

Annotez vos courbes et amusez vous avec les paramètres d’affichages pour changer les aspects des graphiques que vous avez crées.

4.2 Visualisation de données sous forme de nuage de points

Illustration de vos données en nuage de points est utilisé pour déterminer la solidité d’une relation entre deux variables numériques. Avec les bibliothèques de python, visualisez vos données sous forme de nuage de point.


5.Analyse de données

5.1 Mesure de tendance centrale

Mesure de tendance centrale est le nombre qui caractérise le centre d’une distribution et la position des diverses valeurs de la distribution par rapport à ce centre. Il s’agit ici de calculer la moyenne, le médiane et le mode d’une distribution. Vous avez à disposition le fichier nommé tendance_centrale.csv. Chargez ces données puis en utilisant les outils nécessaires appliquez la mesure de tendance centrale sur ces données.

5.2 Analyse de la variance

En statistique, l’analyse de la variance est un modèle statistique utilisé pour comparer les moyennes d’échantillons. Ce test s’applique lorsque l’on mesure une ou plusieurs variables explicatives catégorielle (appelées alors facteurs de variabilité, leurs différentes modalités étant parfois appelées « niveaux ») qui ont de l’influence sur la loi d’une variable continue à expliquer. Faites une analyse de variance sur le jeu de données issu de tendance_centrale.csv.


5.3 Analyse de corrélations

L’objectif de l’analyse de corrélation est étudier la liaison entre deux variables quantitative. Soient X et Y deux grandeurs statistiques quantitatives observées. On souhaite :

• Déterminer s’il existe une relation entre X et Y . • Caractériser la forme de la liaison(la relation) entre X et Y (positive ou négative,linéaire ou non linéaire,monotone ou non monotone) • Tester si la liaison est statistiquement significative • Quantifier l’intensité de la liaison

Utlilisez le jeu de données (iris.csv)

5.3.1 Analyse graphique

• L’analyse graphique est une bonne manière de comprendre les différentes caractéristiques énumérées ci-dessus. Le graphique "nuage de points" est l’outil privilégié. Nous plaçons en abscisse la variable X, en ordonnée la variable Y, chaque observation est positionnée dans le repère ainsi constitué. L’intérêt est multiple : nous pouvons situer les proximités entre les individus; • Etudier la forme globale des points, voir notamment s’il existe une forme de liaison ou de régularité; • Détecter visuellement les points qui s’écartent des autres, les observations atypiques; • Vérifier s’il n’y a pas de regroupement suspects, laissant entendre qu’il y a en réalité une troisième variable qui influence le positionnement des individus. . . • A partir de la base de données qui vous est fournie, illustrez quelques types de liaisons qui peuvent exister entre 2 variables.

Utlilisez le jeu de données (iris.csv)

5.3.2 Analyse mathématique : coefficient de corrélation de Pearson Le coefficient de corrélation linéaire simple, dit de Bravais-Pearson(ou de Pearson), est une normalisation de la covariance par le produit des écarts-type des variables : rx,y = COV(X,Y) / (E(X) x E(Y)) Avec les outils et bibliothèques de Python, calculez le coefficient de corrélation de Pearson sur la base de données fournie et interprétez les résultats.

Utlilisez le jeu de données (iris.csv)

Pou aller loin:

Essayer d'integrer toutes ces fonctionnalités dans une interface graphique et qui permet de visualiser les différentes extensions des fichier pour ne plus à avoir passer par la console.
