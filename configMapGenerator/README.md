# 概要

[configMapGenerator](https://kubectl.docs.kubernetes.io/references/kustomize/configmapgenerator/)についてのサンプルコードです。
各プロパティファイルをインプットに`ConfigMap`リソースを生成するサンプルです。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
