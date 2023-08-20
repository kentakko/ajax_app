# テーブル設計

## users テーブル

| Column             | Type   | Options         |
| ------------------ | ------ | ----------------|
| email              | string | NOT NULL, UNIQUE|
| encrypted_password | string | NOT NULL        |
| name               | string | NOT NULL        |
| profile            | text   | NOT NULL        |
| occupation         | text   | NOT NULL        |
| position           | text   | NOT NULL        |

