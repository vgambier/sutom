# SUTOM

Jeu de lettres en ligne (et en français) basé sur Wordle. Le jeu se trouve à l'adresse https://sutom.margoulin.ml/ (originellement https://sutom.nocle.fr)

## Contributions

Tout d'abord, merci si vous contribuez :) Pour l'instant, le mieux, c'est de créer un ticket quand vous voyez un bug, ça me permettra de trier et de prioriser tout ce que je dois faire. Comme la base de code n'est pas aussi propre que je voudrais, merci de créer un ticket et d'attendre un retour de ma part ( @JonathanMM ) avant de vous lancer à corps perdu dans le code.

## Développement

### Avec npm

Pour pouvoir travailler en local, il faut commencer par installer ce qu'il faut à node :

```sh
npm i
```

Puis, on lance le serveur :

```sh
npm start
```

### Avec Docker

Un Dockerfile est disponible pour pouvoir démarrer le site en local sans `npm`.

```sh
docker build -t sutom .

docker run -it --rm -p 4000:4000 sutom
```

### Avec Docker Compose

Un fichier docker-compose.yml est également disponible:

```
docker-compose up
```

### Accès au site

Une fois démarré, le site sera dispo sur http://localhost:4000 et le typescript va se recompiler tout seul à chaque modification de fichier.

## Autres infos et remerciements

- Le dictionnaire utilisé est celui de [Grammalecte](https://grammalecte.net/dictionary.php?prj=fr). Merci à GaranceAmarante pour le script.
- Merci à Emmanuel pour m'avoir fourni des mots à trouver.
- Merci à tous les gens qui me remontent des bugs et qui me donnent des idées, ça m'aide beaucoup :)
- Merci à toutes les personnes qui jouent, c'est une belle récompense que vous me donnez.
