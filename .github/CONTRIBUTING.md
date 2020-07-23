# このリポジトリへプルリクエストを送るには

1. まず Issue を作る
1. Issue に対応したブランチを作る
1. 作ったブランチからマージしたいブランチへ Pull Request を送る
1. Pull Request をレビューする
1. 修正点があれば修正する
1. マージする
1. 不要になったブランチを適宜削除する

## Issue の作り方

1. プロジェクトの Issue 作成画面から「New Issue」をクリック
1. 使いたい Issue テンプレートを選択
1. Title を入力
1. Issue テンプレートに沿って必要な情報を入力/修正
1. Assignees に担当者を指定
1. Labels で優先度（Low/Middle/High）と該当するものを選択（該当するラベルがなければ「Edit labels」から作成して追加する）
1. その他必要項目を適宜設定
1. 「Submit new issue」で Issue を登録
1. Issue 番号（ `#番号` ）が作成されるので覚えておく

### ブランチの作成例

開発中の機能追加例

```bash
# develop ブランチにいることを確認
$ git branch
* develop

# develop ブランチにいない場合
$ git checkout develop

# ブランチ feature/1 ブランチを作成し、作成したブランチへ移動する
$ git checkout -b feature/1
# ローカルでコミットを行う
# 作成したブランチをリモートリポジトリへ push
$ git push origin feature/1
```

## Pull Request の作り方

1. Pull requests 作成画面から「New pull request」をクリック
1. Title を入力
1. Pull Request テンプレートに沿って必要な情報を入力/修正
1. Assignees に担当者を指定
1. Labels で優先度（Low/Middle/High）と該当するものを選択（該当するラベルがなければ「Edit labels」から作成して追加する）
1. Linked issues を指定
1. 「Create pull request」で Pull Request を作成
