# mountix API documents

*mountix API* のドキュメント

[https://codemountains.github.io/mountix-docs/](https://codemountains.github.io/mountix-docs/)

## Build command

ローカル環境でindex.htmlを生成する。

```shell
docker run --rm -it -v$(pwd):/tmp my-redoc-cli:0.0.1 bash
```

```shell
cd tmp/
redoc-cli bundle openapi.yaml -o target/index.html
```
