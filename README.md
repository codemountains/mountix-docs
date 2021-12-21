# mountix API documents

*mountix API* のドキュメント

## Build command

```shell
docker run --rm -it -v$(pwd):/tmp my-redoc-cli:0.0.1 bash
```

```shell
cd tmp/
redoc-cli bundle openapi.yaml -o target/index.html
```
