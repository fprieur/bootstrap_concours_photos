Pour installer le sous-thème, il est important que bootstrap soit déjà installé dans le site drupal: https://www.drupal.org/project/bootstrap

par la suite éxécuter les commandes suivantes dans sites/all/themes/

<pre>git clone https://github.com/fprieur/bootstrap_concours_photos</pre>
<br>
Pour activer le thème:
<pre>drush @alias-devotresite en bootstrap_concours_photos</pre>
<br>
Pour activer le thème par défaut:
<pre>drush @photos-deea vset theme_default bootstrap_concours_photos</pre>