# Orchestre de lumière

Implémentation d'un système inspiré de l'installation [City Lights Orchestra](https://www.youtube.com/watch?v=Sun0TFQgPXk) d'Antoine Schmitt, pour contrôller à distance l'affichage d'un ensemble de terminaux. Voir également le [City Lights Orchestra Device (CLOD)](https://reso-nance.org/wiki/projets/clod/accueil).

![Illustration de la vidéo YouTube « City Lights Orchestra » par Antoine Schmitt](https://img.youtube.com/vi/Sun0TFQgPXk/maxresdefault.jpg)

## Guide de démarrage

1. Démarrer le serveur websocket sur la machine distante
    ```console
    service websocket start
    ```

2. Connecter les ordinateurs *musiciens* sur [cette page](https://ychalier-rlv.github.io/orchestre-de-lumiere/musicien.html)

3. Connecter l'ordinateur *chef* sur [cette page](https://ychalier-rlv.github.io/orchestre-de-lumiere/chef.html)


Il est possible d'ajouter et de supprimer dynamiquement les terminaux esclaves.

### Dépendances serveur

```
asyncio
websockets
```
