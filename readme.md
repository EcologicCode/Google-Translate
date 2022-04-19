1 Extrairez les fichiers;<br>
2 Configurez le fichier :<br>
  index.php, ligne 26, remplacez "url=docs/" par "url=[chemin de votre site, exemple : https://exemple.com]/docs/"<br>
3 Supprimer le fichier index.html dans le dossier docs<br>
4 Insérez votre site dans "docs/"<br>
5 Sur la page de votre site index.html, ajoutez : "<button onclick="location.href='/../index.php?lang=n&url=-'">Language</button>"<br>
6 Videz votre serveur<br>
7 Mettez tout cela sur votre serveur !<br>
