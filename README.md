Informations sur les séances de démos (06/09/17)
Déroulement des démos
Les démonstrations ont pour but de vous faire pratiquer les notions vues en cours, et sont essentielles pour votre apprentissage. Elles pourront comporter des aspects TP (papier crayon) et Labo, où vous implémenterez et expérimenterez avec des algorithmes d'apprentissage. Le langage utilisé sera Python.

Contact des auxiliaires d'enseignements

Vous pouvez poser vos questions sur les démos à Tegan <tegan.jrm@gmail.com> ou Philippe <philippe.lacaille@umontreal.ca> par courriel.

Comptes
Vous devriez maintenant tous avoir accès aux machines des salles de labo. Si ce n'est pas le cas, contactez-nous tout de suite!

Pourquoi Python?
Python est un un choix fait avec un biais d'informaticien. C'est un cours IFT après tout! Cela dit Python possède de nombreux avantages.

On veut un langage de programmation de haut niveau supportant de manière directe, simple et intuitive la manipulation de vecteurs et matrices (donc ni Java ni C). Parmi les langages de ce genre on peut citer Matlab, R, et Python (avec le package numpy). Python est un langage généraliste plus propre que Matlab, et plus simple à apprendre et à maîtriser que R. On veut que vous puissiez rapidement implanter un modèle chez vous, pour vos propres problèmes. Python est open source et gratuit et de nombreuses librairies d'apprentissage machine existent. De plus, Python est très populaire et bien supporté.

Petite note sur SAGE. SAGE est essentiellement construit sur ipython, numpy et matplotlib (et beaucoup plus) mais apporte quelque changements incompatibles à la syntaxe python. Nous préférons utiliser directement python et ses modules (plus largement connus).

Comment débuter avec Python
Nous vous suggérons de procéder dans l'ordre suivant:

Pour travailler sur les ordinateurs du laboratoire, vous devez ajouter les lignes suivantes à votre fichier ~/.bashrc

export PATH=/u/dift3395/.local/bin:$PATH

export PYTHONPATH=/u/dift3395/.local/lib/python2.7/site-packages

Pour travailler de chez vous il vous faudra installer python, numpy, matplotlib et ipython.

Si vous êtes sous linux vous devriez pouvoir les installer facilement avec le gestionnaires de paquet de votre distribution.
Sur les autres systèmes, installer chaque composante individuellement est plus complexe, alors nous suggérons la distribution Python Anaconda ['https://store.continuum.io/cshop/anaconda/'] (pour Windows, Mac OS X,  ou Linux).
Une fois installé ces éléments, trouvez comment démarrer une console/terminal/command-prompt et y lancer ipython --pylab pour pouvoir expérimenter en mode interactif.
Quoi apprendre:

Commencez par passer à travers le tutoriel de Python (voir les liens ci-dessous).
Puis le tutoriel et la documentation de numpy.
Enfin regardez les possibilités d'affichage graphique avec matplotlib.
Pour écrire des programmes python il vous faudra un éditeur ou un IDE qui comprend la syntaxe python. Il y a l'embarras du choix. Voir ci-dessous:

Parmi les éditeurs simples voici quelques suggestions: (vous pouvez aussi examiner une liste plus complète)

Pour les vétérans unix/linux: emacs ou vim
Sur linux il y a aussi kwrite et gedit qui supportent bien le Python.
Sur Windows/Mac/Linux vous pouvez télécharger et installer Komodo Edit
Sur windows il y a aussi Notepad++ (surtout si vous le connaissez déjà).
Parmi les IDE plus complètes allez voici quelques suggestions:

Spyder (Spyder is the Scientific PYthon Development EnviRonment) pour Windows/Mac/Linux (installé automatiquement avec plusieurs des distributions mentionnées ci-haut)
Pour les habitués de l'IDE Eclipse (disponible sur toutes les plateformes) vous pouvez y installer le plugin PyDev
L'IDE NetBeans (plus simple à maîtriser qu'Eclipse) a également un plugin pour Python qu'il vous faudra installer.
PyCharm (pas gratuit, mais parait-il excellent)
Outils pour faire de la science avec Python
NumPy: librairie pour la manipulation facile et efficace des matrices.
Le livre sur NumPy: lecture recommandée. Tutoriel en anglais.
SciPy: collection des librairies (basée entre autres sur NumPy) qui contient beaucoup des trucs utiles:
Matplotlib: affichage des graphiques à la Matlab. Très simple a apprendre est très utile comme module.
iPython: le Python interactif++. Fortement conseillé a utiliser! A lancer avec ipython --pylab pour loader automatiquement numpy, matlplotlib etc.
Numpy et matplotlib sont des packages Python. Lorsque vous démarrez l'interprète, vous pouvez y avoir accès avec import. Renseignez-vous sur le mécanisme de import. Voici quelques exemples de façons d'importer numpy puis la façon correspondante d'appeler la fonction range().

import numpy ---> numpy.range()
import numpy as np ---> np.range()
from numpy import * ---> range()
Lorsque vous utilisez l'argument --pylab pour ipython, cela fait plus ou moins:

from pylab import * from numpy import * from scipy import * 
Que sont pylab et scipy? Où est matplotlib? À vous de lire sur le sujet. Sachez simplement que matplotlib sera importé.

La liste des liens:
Tutoriel NumPy en anglais.
Python Wiki: le wiki officiel.
Wikipedia: présentation du langage et beaucoup de liens vers d'autres ressources.
Open Directory FAQs, Help, and Tutorials: collection de page web sur le langage
Vous avez trouvé un lien d'intérêt? Partagez-le en postant un message sur le forum du cours.
