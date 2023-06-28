# DisableWinDefender
DisableWinDefender est un outil qui permet de désactiver temporairement/Définitif Windows Defender sur un système Windows.

# Fonctionnalités
- Désactivation temporaire de Windows Defender pour une utilisation spécifique.
- Réactivation automatique de Windows Defender après une durée prédéfinie.
- Interface en ligne de commande simple et conviviale.
- Configuration requise
- Système d'exploitation : Windows (versions prises en charge : Windows 10, Windows 8, Windows 7)
- Les droits d'administrateur sont nécessaires pour exécuter l'outil.
- Utilisation
**Téléchargez le fichier exécutable "DisableWinDefender.exe" depuis la page de téléchargement du projet.**

Assurez-vous d'avoir les droits d'administrateur sur votre système.

Ouvrez une fenêtre d'invite de commandes en tant qu'administrateur.

Accédez à l'emplacement où vous avez enregistré le fichier "DisableWinDefender.exe".

# Exécutez la commande suivante :

```shell
DisableWinDefender.exe --disable --duration <durée_en_minutes>
```

**Remplacez <durée_en_minutes> par la durée pendant laquelle vous souhaitez désactiver Windows Defender. Par exemple, si vous voulez le désactiver pendant 30 minutes, vous pouvez utiliser :**

```
DisableWinDefender.exe --disable --duration 30
```
**__Windows Defender sera désactivé pendant la durée spécifiée__.**


Après la fin de la durée spécifiée, Windows Defender sera réactivé automatiquement.

# Avertissement
La désactivation de Windows Defender peut laisser votre système vulnérable aux logiciels malveillants. Assurez-vous de réactiver Windows Defender après avoir terminé vos tâches nécessitant sa désactivation.
Utilisez cet outil à vos propres risques. L'auteur n'assume aucune responsabilité pour les dommages causés par une mauvaise utilisation de l'outil.
Contributions
Les contributions au projet sont les bienvenues. Si vous souhaitez apporter des améliorations ou signaler des problèmes, veuillez ouvrir une demande de pull ou une nouvelle question.

# Licence
Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus d'informations.

