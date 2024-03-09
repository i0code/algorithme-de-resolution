# algorithme-de-resolution
Ce référentiel contient un code Python implémentant l'algorithme de résolution pour la logique propositionnelle. L'algorithme vise à déterminer si une formule logique donnée est valide ou non en utilisant la méthode de résolution.
# Comment ça marche
L'algorithme de résolution suit les étapes suivantes :

#### 1-Négation de la formule : La formule logique fournie est négativée.
#### 2-Transformation en CNF : La négation de la formule est transformée en forme normale conjonctive (CNF).
#### 3-Application de l'algorithme de résolution : L'algorithme de résolution est appliqué sur les clauses de la CNF.
#### 4-Vérification du résultat : Si une clause vide est trouvée, la formule est invalide. Sinon, elle est valide.

# Comment Utiliser le Programme
### Cloner le Référentiel:
#### git clone https://github.com/i0code/algorithme-de-resolution.git
### Exécuter le Programme :
#### cd algorithme-de-resolution
#### python Resolution.py
# Exemples d'utilisation
#### A & B & ~C & C  - non valid.
#### ~((~P | ~Z | R) & (~R) & P & (~T | Z) & T) - valid.
