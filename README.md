# D-tection-Automatique-des-discours-haineux-pour-la-s-curit-des-enfants-en-ligne


Avec l’essor du numérique et l’accès généralisé aux plateformes en ligne, les
enfants sont de plus en plus exposés à des contenus textuels potentiellement nui-
sibles, tels que les discours haineux, les insultes ou les propos discriminatoires. Ce
mémoire s’attaque de front à cette problématique urgente de protection des enfants
sur Internet, en proposant une solution innovante, accessible et performante pour
la détection automatique de contenus textuels nuisibles via l’apprentissage auto-
matique. Pour répondre à cet enjeu, nous avons mis en place un modèle finement
optimisé, composé de plusieurs étapes clés. Tout d’abord, les textes extraits des
jeux de données ont été nettoyés, puis transformés en représentations numériques
à l’aide de la technique dite CountVectorizer, qui permet de convertir les mots en
vecteurs exploitables par un algorithme. Ensuite, un rééquilibrage des classes a été
réalisé grâce à la méthode d’oversampling, afin d’éviter que certaines catégories
soient sur-représentées. Le cœur du système repose sur un modèle statistique ap-
pelé régression logistique multinomiale, dont les paramètres ont été ajustés avec
soin pour améliorer la précision et maximiser les performances de classification.
Ce modèle a été entraîné sur une partie des données, puis testé sur un ensemble
séparé pour évaluer sa performance. Les résultats parlent d’eux-mêmes : notre sys-
tème, bien que simple, atteint et surpasse même les modèles plus complexes avec
un F1-score de 96% et une précision de 97% sur le jeu Davidson, et un F1-score
de 88% avec une précision de 89% sur le jeu MetaHate. Ces performances, ob-
tenues avec une architecture simple, montrent qu’un modèle transparent, facile à
comprendre et à déployer peut être aussi efficace, voire plus, que des approches
beaucoup plus complexes.
