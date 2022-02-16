# devops-with-docker
Introductory course to Docker and docker-compose. 


### Exercise 1.1

Started 3 containers from image that does not automatically exit (nginx) and stoped 2 of the containers leaving 1 up.

```
CONTAINER ID   IMAGE     COMMAND                  CREATED         STATUS                          PORTS     NAMES
a59b325ef51e   nginx     "/docker-entrypoint.…"   8 seconds ago   Up 7 seconds                    80/tcp    lucid_bhaskara
a57031dd955b   nginx     "/docker-entrypoint.…"   3 minutes ago   Exited (0) 2 minutes ago                  dreamy_chebyshev
ce6737b85637   nginx     "/docker-entrypoint.…"   3 minutes ago   Exited (0) 2 minutes ago                  cranky_brahmagupta
```

### Exercise 1.2

docker ps -a

```
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
```

$ docker images
```
REPOSITORY   TAG       IMAGE ID   CREATED   SIZE
```
