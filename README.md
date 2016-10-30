# Docker Image for bartobri/no-more-secrets

The docker image to the repository [https://github.com/bartobri/no-more-secrets].

More details and instructions can be found there.

#### Build

Run 

```
docker build -t freiit/no-more-secrets .
```
to build the container.

#### Run Example

Run with
```
ls -l | docker run --rm -i -e COLUMNS=$COLUMNS -e LINES=$LINES -e TERM=$TERM freiit/no-more-secrets 
```
