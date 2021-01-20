# 概要

[secretGenerator](https://kubectl.docs.kubernetes.io/references/kustomize/secretgenerator/)についてのサンプルコードです。
TLS証明書を保持するための`Secret`リソースを生成するサンプルです。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
