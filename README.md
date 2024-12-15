## Démarrer le projet

Pour démarrer le projet, vous avez deux options :

1. Avec Docker Compose :
    ```bash
    docker compose up -d
    ```

2. Avec le script `start.sh` :
    ```bash
    ./start.sh
    ```

2. Si rien ne bouge sur le terrain `restart.sh` :
    ```bash
    ./restart.sh
    ```

## Arrêter le projet

Pour arrêter le projet, vous avez deux options :

1. Avec Docker Compose :
    ```bash
    docker compose down
    ```

2. Avec le script `stop.sh` :
    ```bash
    ./stop.sh
    ```


## Prérequis

- Docker
- Docker Compose
- Permissions d'exécution pour les scripts `start.sh` et `stop.sh` :
  ```bash
  chmod +x *.sh stop.sh
