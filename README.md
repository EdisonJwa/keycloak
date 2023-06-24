# Keycloak Docker Image based on Zulu openjdk

If you want to use this docker image, you should use `ghcr.io/edisonjwa/keycloak:<VERSION>` or `ghcr.io/edisonjwa/keycloak:<VERSION>-alpine` as the base image.

For further more information, please see the [Running Keycloak in a container guide](https://www.keycloak.org/server/containers).

### Baking the  cake :)

If you need to build it yourself, you can do it like this

```shell
VERSION=<VERSION> TAG="<YOUR_TAG>:${VERSION}" docker buildx bake  
```
