# Reseaux-Generatifs-Depot-1
Le présent dépôt constitue la première partie d'un projet long et vaste. L'objectif final de ce projet n'est pas encore défini ; toutefois, certaines étapes à atteindre sont déjà clairement identifiées. L'avancement des travaux sera ajouté au fur et à mesure dans d'autres dépôts et en parallèle avec des publications sur LinkedIn.

Dans le présent dépôt, il s'agit de construire un GAN puis de l'entraîner sur plusieurs époques avec des ensembles de données variés et de vérifier la qualité des images générées au fil des époques. Les quatre jeux de données considérés ici sont : Flowers Recognition, LFW (Labeled Faces in the Wild), CIFAR-10 et CelebA.

Les contraintes liées aux GPU ont fortement restreint le nombre d'époques sur lesquelles je pouvais entraîner et générer des images, en particulier sur le jeu de données CelebA, où il ne m'était pas possible de dépasser 30 époques avant d'être à court de GPU. Toutefois, une astuce est en train d'être mise en place pour pallier ce genre de problèmes.

L'environnement de travail utilisé est Google Colab.
