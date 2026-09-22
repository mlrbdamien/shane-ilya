# Shane & Ilya · chapitre deux

Page de fans non officielle : l'histoire de Shane et Ilya, de Regina 2008 au chalet 2017, et le décompte avant la saison 2 de Heated Rivalry.

Site statique, un seul `index.html`. Aucune image de la série : tout est dessiné en SVG, CSS et canvas.

## Fond sonore

Le fichier `assets/fond-sonore.mp3` est lu en boucle quand on touche « Écouter en lisant » (Safari sur iPhone interdit le son automatique). Tant que le fichier n'existe pas, les boutons de son restent masqués.

Pour changer de musique, remplacer ce fichier en gardant le même nom.

## Changer la date

En haut du script, dans `index.html` :

```js
var SORTIE = {
  iso: '2027-04-01T06:00:00+02:00',
  estimee: true
};
```

Mettre l'instant exact de la sortie dans `iso` (avec le décalage horaire), puis passer `estimee` à `false` quand la date officielle est connue.

## Aperçu local

```bash
python3 -m http.server 4174
```
