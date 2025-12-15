Objectifs :

Ouvrir et fermer le livre au clic.
Changer le thème (bibliothèque → nuit étoilée) via un bouton.
Activer des particules magiques, de la lumière ou du feu depuis le livre via des boutons dédiés.
Entendre des sons de feuilletage des pages pour plus de réalisme.
Réinitialiser complètement le livre et les effets à tout moment.



Fonctionnalités principales :
Couverture avant, couverture arrière et plusieurs pages intérieures.
Une page “magique” avec texte et possibilité de générer des particules dynamiques.
Pages qui se tournent avec des délais différents pour simuler un feuilletage réaliste.
Particules dynamiques animées vers le haut, avec couleurs et tailles variées.
Changement de thème jour/nuit via le bouton "Changer d'ambiance".
Sons synchronisés à chaque page tournée.
Boutons pour déclencher des effets supplémentaires :
Particules magiques (rainbowParticles())
Lumière dynamique (toggleLumiere())
Feu avec flammes, fumée et étincelles (toggleFire())
Bouton de réinitialisation pour stopper tous les effets et remettre le livre à l’état initial (resetBook()).
Technologies utilisées :
HTML : structure du livre, pages, couvertures et boutons.
CSS : style visuel, perspective 3D, animations de particules, flammes, lumière et étoiles.
JavaScript : ouverture/fermeture du livre, création et gestion dynamique des particules, feu et lumière, changement de thème, sons synchronisés et réinitialisation.
Résultat attendu et limites :
Livre interactif avec effet de feuilletage et ambiance immersive.
Particules magiques, flammes, lumière dynamiques et colorées qui apparaissent au clic.
Possibilité de changer l’ambiance (jour/nuit) à tout moment.
Sons synchronisés aux pages pour un réalisme accru.
Réinitialisation complète du livre et des effets via bouton.
Les particules et effets sont tous créés dynamiquement, ce qui peut affecter les performances si l’utilisateur laisse les flux continuer longtemps.
Positionnement des particules et des faisceaux lumineux pourrait être amélioré pour garantir qu’ils sortent toujours exactement du centre des pages ou des zones dédiées.
