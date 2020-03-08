
# 
# <center> M2 Datascience </center> 
# <center> Reinforcement Learning
 </center> 

## <center> Adnan Asadullah - Imad Al moslli </center> 

## Objectif 
Ce projet est basé sur l'article "A general reinforcement learning algorithm that masterschess, shogi, and Go through self-play" publié par Google DeepMind en décembre 2018.
 L’article présente le tout nouvel algorithme développé pour les jeux d’échecs, Shogi et Go : AlphaZero.

Contrairement aux algorithmes classiques développés pour ce genre de jeux, AlphaZero apprend tout de lui-même, on lui donne seulement les règles du jeu. 
C’était également le cas de l’algorithme AlphaGo Zero mais ce dernier ne jouait qu’au jeu de Go. AlphaZero a cette particularité qu’il n’est pas conçu pour un jeu en particulier.
L’apprentissage est composé de deux élements principaux : un réseau de neurones convolué et un arbre de recherche de type Monte Carlo (MCTS).




## Implementation 
Pour implémenter un MCTS sur le jeu du morpion, nous nous sommes appuyé sur plusieurs librairies:
- Nous avons avons commencé par récupérer une implémentation basique du jeu du morpion en python que nous avons nettoyé, disponible à cette adresse: 
https://python.jpvweb.com/python/mesrecettespython/doku.php?id=morpion\_console.
- Ensuite, nous avons ajouté et adapté un algorithme MCTS à notre jeu, en utilisant la librairie mcts.py, que l'on peut retrouver ici :
https://github.com/int8/monte-carlo-tree-search/blob/master/mctspy/tree/nodes.py
- Enfin, nous avons ajouté un algorithme de type alpha beta et nous avons fait varier les paramètres pour comparer les performances. 
Nous nous sommes appuyés sur une implémentation en python, que nous avons adapté pour notre cas d'usage : 
https://stackabuse.com/minimax-and-alpha-beta-pruning-in-python/
