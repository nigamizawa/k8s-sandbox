# k8s-sandbox


## 📝kindの使い方簡単メモ

マルチノードの起動  
設定ファイルに細い設定は書いてある
```
kind create cluster --config=multinode.yaml
```

## todos

やりたいことのメモ
- ArgoCDを利用したk8sコンポーネントのデプロイ
  - prometheus（必要であればhelmfileも作成）
- ArgoCDをhelmfileで色々設定する
  - 初期ユーザーパスワード
  - 本リポジトリ、components配下を参照先ディレクトリとする
- k8s manifest、helmのlinter色々試す
  - 空白とか、整形とか苦手

## tips
- [tools](./doc/tools.md)
