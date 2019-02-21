# TSSB
Toolbar Safe Save Button (TSSB) est un plugin de sauvegarde automatique pour Unity 3D.

# DESCRIPTION
Une fois TSSB importé dans votre projet, redémarrez Unity et c'est prêt !
Cet outil tentera de sauvegarder vos changements toutes les 5 minutes, si vous souhaitez sauvegarder les changements, confirmez la sauvegarde dans la boite de dialogue de sauvegarde.

Dans l'éventualité où vous ne souhaitez pas sauvegarder les changements en attente, fermer simplement la boite de dialogue ou cliquer sur "ne pas sauvegarder".

Si aucune modification n'a été effectuée les 5 dernières minutes, la tentative de sauvegarde est ignorée. L'utilisateur aura un message d'information dans la console.

**AMÉLIORATIONS**

- Il est possible de changer le délai de sauvegarde (5 minutes / 300 secondes par défaut). Pour cela, rendez-vous dans le script *SafeSaveUpdate.cs* et modifiez la valeur **delta**. Cette variable représente le délai entre chaque tentative de sauvegarde, elle se calcule en secondes.

**BUG CONNUS**

- Lors de l'importation du UnityPackage, une erreur apparait dans la console et force l'utilisateur à redémarrer Unity.
- Lorsque l'utilisateur refuse la sauvegarde via le bouton prévu à cet effet, la sauvegarde n'est pas effectuée mais un message de confirmation de sauvegarde apparait quand même dans la console.
