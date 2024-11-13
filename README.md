```bash
docker-compose up
```
```bash
./mvnw verify
```
```bash
./mvnw clean package docker:build
```
```bash
docker run -p 8080:8080 -p 9990:9990 --rm -it practica-dockercompose
```