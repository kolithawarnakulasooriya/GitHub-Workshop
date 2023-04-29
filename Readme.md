# Github Actions

[Support Materials](https://github.com/kolithawarnakulasooriya/GitHub-Workshop/blob/master/Docker%20Workshop.pdf)

### ISC 629: Computing Ecosystems
### School of Computing
### University of South Alabama
### September 20, 2022

Conducted by Harith Warnakulasooriya

## Developer Run

```
npm start
```

## Production Run + Docker

```
npm run build
docker build . -t "user:latest"
docker run -d -p 80:8080 user:latest
```

