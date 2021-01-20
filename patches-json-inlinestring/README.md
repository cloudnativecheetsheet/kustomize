# 概要

[patches](https://kubectl.docs.kubernetes.io/references/kustomize/patches/)についてのサンプルコードです。[JSON Patch](https://tools.ietf.org/html/rfc6902)の記述スタイル、且つインライン文字列で記述するサンプルです。
`Deployment`に`livenessProbe`を追加するサンプルにしています。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
