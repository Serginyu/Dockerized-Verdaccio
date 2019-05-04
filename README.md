<img src="https://github.com/verdaccio/verdaccio/raw/master/assets/bitmap/verdaccio%402x.png">

# Dockerized Verdaccio

### Prerequisites
* Docker

### How it works
```
docker-compose up
```

Now you will be able to access the web interface <a href="http://localhost:4873">http://localhost:4873</a>

You can create a new user with the follow command
```
# Add a new user with the follow command
npm adduser --registry http://localhost:4873

# Add the current package to the registry
npm publish --registry http://localhost:4873
```
