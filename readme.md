  
<span style="font-family:Arial sans-serif;font-size:16px;">WD Synchronisation de fichiers</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">Cet exemple montre comment synchroniser deux répertoires de fichiers en WLangage. Après synchronisation le répertoire de destination est identique au répertoire source. La comparaison se base sur la présence et la date des fichiers. Ceci peut être très utile pour la gestion des sauvegardes.</span>

<span style="font-family:Arial sans-serif;font-size:14px;">Dans cet exemple, nous abordons surtout les fonctions de manipulation de fichiers sur le disque.</span>

  
<span style="font-family:Arial sans-serif;font-size:14px;">Résumé de l'exemple livré avec WINDEV : </span>

<span style="font-family:Arial sans-serif;font-size:14px;">Vous sélectionnez un répertoire source contenant les fichiers à sauvegarder, un répertoire de destination où sauvegarder ces fichiers. Vous lancez la synchronisation. L'application va comparer le contenu des deux répertoires. Si le fichier est absent, si le fichier source est plus récent… alors le fichier sera mis à jour dans le répertoire de sauvegarde. </span>

  
  
<span style="font-family:Arial sans-serif;font-size:14px;">( \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ ° \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_ )</span>

  
<span style="font-family:Arial sans-serif;font-size:10px;">Conditions d'utilisation :</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Le programme est fourni dans un but didactique.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">L'utilisation de ce programme s'effectue sous la responsabilité de son utilisateur. La responsabilité de PC SOFT ne pourra en aucun cas être mise en cause si le programme ne fonctionne pas tel que vous l'attendez, ou pour quelque raison que ce soit. </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Tout détenteur d'une licence WINDEV 28 enregistrée est autorisé à modifier ce programme, et est autorisé à l'inclure dans une ou plusieurs de ses applications. Dans ces cas, toute mention se rapportant à PC SOFT, à WinDev ou à WebDev devra être supprimée, afin qu'aucun doute ne puisse subsister dans l'esprit d'un utilisateur final.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Il est interdit de diffuser ou vendre ce programme exemple sans modification substantielle, ou sans l'inclure dans une application de taille substantielle.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Le support technique pour ce programme exemple est accessible à travers le service "Assistance Directe" uniquement.</span>

<span style="font-family:Arial sans-serif;font-size:10px;">Attention: si plusieurs personnes sont susceptibles d'avoir consulté ce programme, il se peut que le programme ait été modifié! </span>

<span style="font-family:Arial sans-serif;font-size:10px;">Assurez-vous d'étudier une version originale de ce programme.</span>

  
  