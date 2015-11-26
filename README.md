# userguide-fr
Guide de l'utilisateur

Pour compiler le guide utilisateur de MapMint au format HTML, il est nécessaire d'installer Sphinx (et Latex pour ceux qui voudrait produire un document au format PDF). Pour ce faire, utilisez les commandes suivantes :
commandes suivantes :

```
apt-get python-sphinx install -y texlive-latex-recommended \
  texlive-latex-extra texlive-fonts-recommended texlive-fonts-extra
```

Une fois ces éléments installé, vous n'avez plus qu'à tappper les commandes suivantes pour générer, respectivement, une documentation au format HTML ou PDF.

```
make html
make latexpdf
```


