# 概要

[vars](https://kubectl.docs.kubernetes.io/references/kustomize/vars/)についてのサンプルコードです。
`Deployment`の`env`に定義した変数に`Service`リソースの`name`を代入するサンプルです。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
