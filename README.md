# SEGMENTATION CLIENT PAR LE KMEANS CLUSTERING

![une_segmentation_des_clients_efficace](https://user-images.githubusercontent.com/101726242/164234415-e9ff0ac1-aff4-4c99-b88d-9a6b0f4c6b5f.jpg)

La segmentation client consiste à identifier des sous-ensembles homogènes selon différents critères (comportement d’achat, données sociodémographiques, besoins, etc.), pour rationaliser l’allocation des ressources, plus globalement, la stratégie marketing à adopter. 

vec l’avènement et l’évolution des NTIC, la segmentation client a connu un tournant. On ne jure désormais que par le « big data » qui permet d’accéder plus facilement aux informations sur les clients à partir de tendances dégagées d’une énorme masse de données. Le big data, concept en vogue du moment que ce soit dans les médias ou dans les grandes multinationales rationalise la segmentation client et facilite la prise de décision, écartant les dilemmes concernant la composition des sous-groupes. Le machine learning vient également épauler le responsable marketing dans sa tâche de segmentation client.

**Segmentation ?**

Avant tout, il existe différents types de segmentation : géographique, démographique, psychologique et comportementale. Dans notre cas, nous allons essayer de comprendre le comportement des clients grâce aux informations de leur carte bancaire (% des dépenses sur les revenus, solde de compte, avances de fond, plafond de paiement etc.).

Nous allons donc essayer de définir des typologies de client par rapport à leurs comportement.
Pour cela il existe différentes techniques pour faire de la segmentation.

**Technique de segmentation**

Le scoring RFM par exemple, utilisé en Marketing. On donne un score à chaque client par rapport à leur récence d’achat, leur fréquence d’achat et la valeur monétaire qu’il dépense sur un temps donné. Cette technique nous permet d’identifier 9 typologies de client. Malheureusement cette technique peut se révéler limité puisque vous n’utilisez que ces 3 variables. En fait, plus vous aurez de variables, plus votre analyse se rapprochera de la réalité.

Grâce à la data science il est possible de créer des clusters (regroupement) de clients avec des algorithmes simples comme le CAH, le TSNE, Les Kmeans etc. Dans mon étude j’ai décidé d’utiliser les Kmeans, pourquoi ? C’est un algo qui est souvent utilisé dans la segmentation client, moins précis que le CAH (Classification Ascendante Hiérarchique) mais plus rapide et simple.

“Kmeans” est un algorithme de clustering qui permet d’identifier les patterns d’individus que l’on va regrouper selon des similarités. (Parfait pour segmenter)
L'objectif de ce projet était de développer un modèle de clustering qui sera utilisé pour la segmentation des clients d'un Centre commercial, Mall, épicéries , etc...
Le jeu de données utilisé est public.
