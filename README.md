# Simple implementation of worker in PHP

## How to start worker

To start worker, just execute command:

```
$ docker-compose run --rm php php worker.php
```

You can run more than one worker ;)

## How to send message to queue

```
$ docker-compose run --rm php php new_tesk.php YOUR MESSAGE HERE 
```
