# 概要

[namePrefix](https://kubectl.docs.kubernetes.io/references/kustomize/nameprefix/)、及びに[nameSuffix](https://kubectl.docs.kubernetes.io/references/kustomize/namesuffix/)ついてのサンプルコードです。
各リソースの`name`のプレフィックスに`pre-`、サフィックスに`-post`を追加するサンプルです。。

# 実行方法

カレントディレクトリで下記のコマンドを実行してください。

```sh
kustomize build overlays/prod
```
