# 概要

[patches](https://kubectl.docs.kubernetes.io/references/kustomize/patches/)についてのサンプルコードです。[strategic-merge](https://github.com/kubernetes/community/blob/master/contributors/devel/sig-api-machinery/strategic-merge-patch.md)-style patch (SMP)の記述スタイル、且つパッチファイルで記述するサンプルです。
`Deployment`に`livenessProbe`を追加するサンプルにしています。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
