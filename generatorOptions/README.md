# 概要

[generatorOptions](https://kubectl.docs.kubernetes.io/references/kustomize/generatoroptions/)についてのサンプルコードです。
`secretGenerator`で生成される`Secret`リソースに`labels`、`annotations`を付与し、生成されるリソースにハッシュ値を付与しない設定のサンプルです。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
