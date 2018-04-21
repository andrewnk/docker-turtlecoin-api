# Docker Turtlecoin Api
This is a Docker build of Turtlecoin-Api-Proxy (https://github.com/turtlecoin/turtlecoin-api-proxy).

___

```docker build -t turtlecoin-api .```

Then start a container:

```docker run -d -p 80:80 turtlecoin-api```

___

You can also run using the prebuilt image from hub.docker.com:

```docker run -d -p 80:80 andrewnk/turtlecoin-api```