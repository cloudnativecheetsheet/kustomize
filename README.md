# Kustomizeサンプルコード
[@IT連載「Cloud Nativeチートシート」第二回「「Kustomize」超入門――複数環境の重過ぎKubernetesマニフェスト、どう管理すればいいのか」](https://www.atmarkit.co.jp/ait/articles/2101/21/news004.html)で利用しているサンプルコードです。


Kustomizeの各プラグインのサンプルコード用のプロジェクトです。各サンプルでは、各ディレクトリのoverlays/prodにパッチを定義しています。
ご利用の際は、各ディレクトリに移動してから、連載内容に従いコマンドを実行してください。



## 1.patch機能によるマニフェスト管理の実践

[basic-patch](basic-patch)をご覧ください。


## 2.プラグインを利用したKustomizeの利用

プラグインの使い方の概要については、[basic-plugin](basic-plugin)をご覧ください。
個別のプラグインの使い方については、下記の表を参照してください。

| 機能名                     | ディレクトリ名                           |
|----------------------------|------------------------------------------|
| images                     | [images](images)                         |
| namespace                  | [namespace](namespace)                   |
| replicas                   | [replicas](replicas)                     |
| namePrefix                 | [namePrefixSuffix](namePrefixSuffix)     |
| nameSuffix                 | [namePrefixSuffix](namePrefixSuffix)     |
| commonLabels               | [commonLabels](commonLabels)             |
| commonAnnotations          | [commonAnnotations](commonAnnotations)   |
| configMapGenerator         | [configMapGenerator](configMapGenerator) |
| secretGenerator            | [secretGenerator](secretGenerator)       |
| generatorOptions           | [generatorOptions](generatorOptions)     |
| patches                    | - JSON Patch記述スタイル (パッチファイル) [patches-json-file](patches-json-file) <br> - JSON Patch記述スタイル (インライン文字列) [patches-json-inlinestring](patches-json-inlinestring) <br> - strategic-merge-style Patch記述スタイル (パッチファイル) [patches-strategic-merge-file](patches-strategic-merge-file) <br> - strategic-merge-style Patch記述スタイル (インライン文字列) [patches-strategic-merge-inlinestring](patches-strategic-merge-inlinestring) |
| vars                       | [vars](vars)                             |


## 利用条件
* 本サンプルは、商用・個人利用を問わず自由に利用することができます。
* 本サンプルを利用したことによって生じたあらゆる損害については、一切責任を負いません。
* 本サンプルは、Kustomize v3.9.1で試していますが、他のバージョンでは動作しないことがあります。
* 不具合などがございましたら、GitHubのIssueで頂けると幸いです。

