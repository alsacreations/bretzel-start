# bretzel-start

Createur de nouveau projet HTML / CSS / JS en une ligne de commande.

Installez **Bretzel Start** via npm :

```
npm install -g bretzel-start
```

## votre première fois ?

Une fois installé globalement sur votre ordinateur (étape précédente), **Bretzel Start** permet de créer un nouveau projet basé sur [Bretzel](https://github.com/alsacreations/bretzel).

Il lui suffit de connaître : 
- le nom de votre projet (il va créer le dossier)
- le repo du projet à récupérer (ce sera "alsacreations/bretzel")

Voici la syntaxe :

```
bretzel-start nom-du-projet alsacreations/bretzel
```

Ou si vous êtes déjà dans le dossier de votre projet :

```
bretzel-start . alsacreations/bretzel
```


## pour aller plus vite encore

Si vous ne souhaitez pas préciser systématiquement le chemin vers le repo de bretzel, il est possible d'enregistrer votre configuration par défaut pour toutes les fois suivantes via `--configure`.

```
create-project --configure
Set repository: alsacreations/bretzel
Set key=value: (blank to skip) foo=bar
```

Puis il vous suffira de créer votre projet ainsi :

```
bretzel-start nom-du-projet
```

Ou encore mieux si vous êtes déjà dans le dossier de votre projet :

```
bretzel-start .
```

## License

MIT