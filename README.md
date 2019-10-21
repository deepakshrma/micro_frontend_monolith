# micro_frontend_monolith
A scaffold app monolith to demonstrate micro_frontend using docker, kotlin, nginx, golang

### How to work with
`Build all`
```
./gradlew build
```
`Run docker build`
```
./gradlew dockerBuild
```

## Create self sign cert:
```
cd configs
openssl req -nodes -new -x509 -keyout server.key -out server.cert
```