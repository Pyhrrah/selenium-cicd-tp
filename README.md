Partie 2.3 : Analyser le rapport généré

On peut voir qu'il n'y a aucun test de présent, mais qu'il y a toute fois 4 erreurs de remontées (4 fois la même) qui sont :
    - OSError: [WinError 193] %1 n’est pas une application Win32 valide

Ces erreurs sont remontées comme elles le seraient dans une console avec tous les éléments liés à l'appel de ces erreurs

On voit également qu'il y a d'autres filtres (sans résultat pour l'instant) qui sont :
    - Failed
    - Passed
    - Skipped
    - Expected failures
    - Unexpected passes
    - Errors
    - Reruns
Avec seulement "Erreurs" qui comporte 4 éléments

Partie 5 :

Apres avoir corrigé le probleme lié à chrome, 6 tests sur 7 sont passé (l'opération sur les floats a échoué mais l'opération sur les nombres négatifs est passé)

On peut voir dans les filtres qu'il y a 6 tests passé et 1 échoué, avec les details qu'on peut afficher