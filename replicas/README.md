# 概要

[replicas](https://kubectl.docs.kubernetes.io/references/kustomize/replicas/)についてのサンプルコードです。
`Deployment`の`replicas`を`1`から`3`にパッチするサンプルです。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
