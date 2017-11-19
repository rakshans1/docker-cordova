[![Travis](https://img.shields.io/travis/rakshans1/docker-cordova.svg)](https://travis-ci.org/rakshans1/docker-cordova)
[![Pulls](https://img.shields.io/docker/pulls/rakshans1/cordova.svg)]()
[![Layers](https://img.shields.io/imagelayers/layers/rakshans1/cordova/latest.svg)]()
[![Size](https://img.shields.io/imagelayers/image-size/rakshans1/cordova/latest.svg)]()


![rakshans1/cordova](/icon.png?raw=true)
# Cordova 7.1.0
### based on [Latest Android with Node.js](https://github.com/rakshans1/docker-android-nodejs)
----
### Pull from Docker Hub
```
docker pull rakshans1/cordova:latest
```

### Build from GitHub
```
docker build -t rakshans1/cordova github.com/rakshans1/docker-cordova
```

### Run image
```
docker run -it rakshans1/cordova bash
```

### Use as base image
```Dockerfile
FROM rakshans1/cordova:latest
```