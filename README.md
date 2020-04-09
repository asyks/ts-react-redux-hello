# ts-hello

A typescript hello world for use as a github template.


### Building for local testing

With docker-compose:
```
docker-compose build
```

### Running the dev server

Running the dev server With docker-compose:
```
docker-compose up --build
```

### Automated Tests

Running tests with docker-compose:
```
> docker-compose run app npm test
```

Running tests with just docker:
```
> docker run ts-hello_app npm test
```
