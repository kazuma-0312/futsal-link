# README

## usersテーブル

| Column        | Type            | Options                  |
| ------------- | --------------- | ------------------------ |
| name          | string          | nul:  false              |
| email         | string          | null: false              |
| password      | string          | null: false              |

## postsテーブル

| Column        | Type            | Options                  |
| ------------- | --------------- | ------------------------ |
| content       | text          | nul:  false              |
| uer_id        | reference       | foreign_key              |


## messagesテーブル

| Column        | Type            | Options                  |
| ------------- | --------------- | ------------------------ |
| text          | text            | nul:  false              |
| from_id       | integer         | null: false              |
| to_i          | integer         | null: false              |
| room_id       | integer         | null: false              |

