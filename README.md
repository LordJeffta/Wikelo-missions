#  Wikelo missions

This is made with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)

## Run in dev

```shell
docker build -t squidfunk/mkdocs-material:local .
docker run --rm -it -p 8000:8000 -v ${PWD}:/docs squidfunk/mkdocs-material:local
```