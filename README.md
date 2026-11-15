# Food 11 challenge

## Comment se servir des réseaux

Cette archive zip contient un code de main.m par réseau entraîné.

Les codes qui existent dans ce zip sont :

- main_shufflenet
- main_mobilenetv2
- main_shufflenet_cutdown

Il existe un dossier src avec le code matlab. Pour que ce code fonctionne, il faut, au même niveau que src, un dossier avec data avec dedans deux sous dossier **test/** et **train/**.

Ce code va alors afficher à la fin de l'entraînement, la matrice de confusion et dans le terminal les différentes métriques sur la performance du réseau. De plus, il créera un json dans un dossier **out/** qui contient les prédictions sur le jeu de test.

Pour les codes utilisant des réseaux pré-entraînés, il faut les avoir préalablement téléchargés (par exemple vis Add-On Matlab), c'est valable pour shufflenet, shufflenet_cutdown et mobilenetv2

Sur le code shufflenet-cutdown ***spécifiquement*** il faut faire tourner le .mlx avant main pour créer le réseau shufflénet tronqué.
