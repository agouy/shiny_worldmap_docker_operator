# Worldmap

```
https://github.com/agouy/shiny_worldmap_docker_operator.git
```
## Build

```bash
VERSION=0.0.4
docker build -t agouy/worldmap:$VERSION .
docker push agouy/worldmap:$VERSION
git add -A && git commit -m "$VERSION" && git tag -a $VERSION -m "++" && git push && git push --tags
```

```bash
# renv cache ~/.local/share/renv
docker run -it --rm --entrypoint "/bin/bash" agouy/worldmap:0.0.4
```
