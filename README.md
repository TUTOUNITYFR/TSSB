# TSSB
Toolbar Safe Save Button (TSSB) est un plugin de sauvegarde automatique pour Unity 3D.

# DESCRIPTION
Une fois TSSB importé dans votre projet, redémarrez Unity et c'est prêt !
Cet outil tentera de sauvegarder vos changements toutes les 5 minutes, si vous souhaitez sauvegarder les changements, confirmez la sauvegarde dans la boite de dialogue de sauvegarde.

Dans l'éventualité où vous ne souhaitez pas sauvegarder les changements en attente, fermez simplement la boite de dialogue ou cliquez sur "Don't Save".

Si aucune modification n'a été effectuée les 5 dernières minutes, la tentative de sauvegarde est ignorée. L'utilisateur aura un message d'information dans la console.

**AMÉLIORATIONS**

- Il est possible de changer le délai de sauvegarde (5 minutes / 300 secondes par défaut). Pour cela, rendez-vous dans le script *SafeSaveUpdate.cs* et modifiez la valeur **delta**. Cette variable représente le délai entre chaque tentative de sauvegarde, elle se calcule en secondes.

Exemple : Pour une sauvegarde automatique toutes les 10 minutes, mettez 600. (600 / 60 = 10).

**BUG CONNUS**

- Lors de l'importation du UnityPackage, une erreur apparait dans la console et force l'utilisateur à redémarrer Unity.

# CRÉDITS

TSSB a initialement été développé par Sioum, merci à lui d'avoir partagé cet outil avec la communauté !
Me concernant, j'ai apporté quelques modifications et améliorations au plugin et j'ai mis en place de répo Github afin de faciliter le téléchargement et la contribution au projet.

Si vous utilisez ce repo GitHub pensez à nous créditer dans votre jeu. Ce n'est pas obligatoire mais c'est fortement apprécié !

Vous appréciez mon travail en tant que créateur et que vous souhaitez me supporter ? Vous pouvez le faire sur Tipeee ou uTip :

- Tipeee : https://fr.tipeee.com/tuto-unity-fr/
- uTip : https://utip.io/tutounityfr
