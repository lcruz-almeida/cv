Objectifs :
Cette version vise à rendre le livre plus visuel et magique, avec un design différent et de nouvelles particules animées. L’idée reste la même : créer un livre interactif où l’utilisateur peut ouvrir et fermer le livre en cliquant dessus, mais avec un rendu plus stylisé et immersif.

Fonctionnalités principales :
Le livre a maintenant une couverture avant, une couverture arrière et plusieurs pages, dont une page spéciale contenant les particules magiques.
Les couvertures et pages sont stylisées avec CSS pour donner un effet 3D et un look plus sombre et mystique.
Le livre s’ouvre et se ferme au clic, grâce à un simple script JavaScript (classList.toggle('open')).
Les particules magiques apparaissent uniquement lorsque le livre est ouvert, avec couleurs blanc/magenta, tailles et positions variées.
Chaque particule est animée individuellement grâce à des keyframes CSS (floatUp), créant un effet de particules qui montent depuis le livre.
Les animations sont répétées en boucle et apparaissent avec des délais différents pour donner plus de variété et de réalisme.

Technologies utilisées :
HTML : structure du livre, couvertures, pages et particules.
CSS : style visuel, couleurs, ombres, perspective 3D, transitions et animations des particules.
JavaScript : gestion simple de l’ouverture/fermeture du livre via clic.

Résultat attendu et limites :
Le livre a un nouveau look sombre et mystique.
Les particules apparaissent de manière fluide et variée, donnant un effet magique et immersif.
Pas encore de boutons supplémentaires pour d’autres effets magiques.
Les animations sont toutes contrôlées par CSS, donc aucune logique avancée ni interaction complexe.
Aucun son ni synchronisation avec les pages.
