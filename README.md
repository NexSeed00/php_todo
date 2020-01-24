# PHP + MySQLを利用したTODOアプリの作成

## 実施する内容
- TODOアプリの作成(チーム開発)

## 要件
### 機能一覧
- タスクの作成ができる
  - 作成したタスクの担当者を入力できる(任意)
- タスクの一覧表示ができる
  - 表示される順番を登録日が新しい順に表示(任意)
- タスクの編集ができる(任意)
- タスクの削除ができる
- タスクの登録日を記録することができる(任意)
  - 入力欄は不要(投稿した日を自動でDBに保存する)
- タスクの検索ができる(任意)

### テーブル定義
### テーブル名: tasks
| 列名        | データ型    | NOT NULL | デフォルト | 備考                 |
| ----------- | ----------- | -------- | ---------- | -------------------- |
| id          | INT         | YES      |            | PK                   |
| title       | varchar(30) | YES      |            | タスクの題名が入る   |
| contents    | varchar(30) | NO       |            | タスクの詳細が入る   |
| created_at  | TIMESTAMP   | NO       |            | タスクの登録日       |


## その他
- エラー文は必ず読むようにしましょう。
- var_dumpを活用しましょう。
- すべてをまとめてやらずに1つ1つ順番に実施しましょう
- 1つ実装が終わったら必ず動作確認をしましょう。
